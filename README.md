### React - 'Hello World'

`npm install -g create-react-app`

`create-react-app first-app`

It will take sometime to load all dependencies (node modules, etc.,)

If you face any issues while doing this please check your proxy info.

 Go to your user directory and find .npmrc file and check your proxy deatails

![image](https://user-images.githubusercontent.com/6780840/37506713-2299bc68-2911-11e8-889e-552bb7502f9b.png)

Open the .npmrc file and edit the below information

``` proxy=http://username:password@proxy-address/ ```

``` https-proxy=http://username:password@proxy-address/ ```

using this you can find a proxy information (It will differ when you connect different networks)

`chrome://net-internals/#http2` `chrome://net-internals/#proxy`

Even if still not working or getting any error like admin rights / proxy settings then follow this

` npm cache clear ` and then execute this command `npm i -g npm@latest`

Once everything is fine then below folder structure will create.

```
first-app
├── README.md
├── node_modules
├── package.json
├── .gitignore
├── public
│   └── favicon.ico
│   └── index.html
│   └── manifest.json
└── src
    └── App.css
    └── App.js
    └── App.test.js
    └── index.css
    └── index.js
    └── logo.svg
    └── registerServiceWorker.js
```

Once you have done all these setup go into your project folder.

> cd first-app

To see the result in the browser enter the below command.

> npm start

It will start execute and open the browser by default in port 3000. 

![image](https://user-images.githubusercontent.com/6780840/37518548-9522d54c-293b-11e8-96cb-247396695d4f.png)

And finally this is the output you can see in the browser.

happy coding :smile:
