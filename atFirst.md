### npx create-react-app .
### npm start

### publicフォルダの下記のファイルを削除
#### index.html以外全部

### srcフォルダの下記のファイルを削除
#### App.test.js
#### logo.svg
#### reportWebVitals.js
#### setupTest.js

### index.htmlの下記の部分を削除
    <link rel="icon" href="%PUBLIC_URL%/favicon.ico" />


<!--
<meta
      name="description"
      content="Web site created using create-react-app"
    />
    <link rel="apple-touch-icon" href="%PUBLIC_URL%/logo192.png" />
    <!--
      manifest.json provides metadata used when your web app is installed on a
      user's mobile device or desktop. See https://developers.google.com/web/fundamentals/web-app-manifest/
    <link rel="manifest" href="%PUBLIC_URL%/manifest.json" />
    <!--
      Notice the use of %PUBLIC_URL% in the tags above.
      It will be replaced with the URL of the `public` folder during the build.
      Only files inside the `public` folder can be referenced from the HTML.

      Unlike "/favicon.ico" or "favicon.ico", "%PUBLIC_URL%/favicon.ico" will
      work correctly both with client-side routing and a non-root public URL.
      Learn how to configure a non-root public URL by running `npm run build`.
    -->
#### body内

    <noscript>You need to enable JavaScript to run this app.</noscript>


<!--
      This HTML file is a template.
      If you open it directly in the browser, you will see an empty page.

      You can add webfonts, meta tags, or analytics to this file.
      The build step will place the bundled scripts into the <body> tag.

      To begin the development, run `npm start` or `yarn start`.
      To create a production bundle, use `npm run build` or `yarn build`.
    -->

#### 適宜title変更

### App.jsの下記の部分を削除
import logo from './logo.svg';

<!--
<header className="App-header">
        <img src={logo} className="App-logo" alt="logo" />
        <p>
          Edit <code>src/App.js</code> and save to reload.
        </p>
        <a
          className="App-link"
          href="https://reactjs.org"
          target="_blank"
          rel="noopener noreferrer"
        >
          Learn React
        </a>
</header>
      -->

### index.jsの下記の部分を削除
import reportWebVitals from './reportWebVitals';

<!--
// If you want to start measuring performance in your app, pass a function
// to log results (for example: reportWebVitals(console.log))
// or send to an analytics endpoint. Learn more: https://bit.ly/CRA-vitals
 -->
reportWebVitals();


### App.css全削除




