# React Employee Manager App
This project was initialized using [Create React App](https://github.com/facebook/create-react-app) and deployed using [Firebase](https://firebase.google.com/).

See the deployed site [here](https://react-employee-manager-8a4b8.firebaseapp.com/)

##  Includes The Following Modules
styled-components
svgo
@svgr/cli
node-sass
firebase
react-router-dom


##  Available Scripts

In the project directory, you can run: `npm start` to test project in dev environment.

To create a production bundle of your app run: `npm run build`


## Setting Up Absolute Paths With Create React App
To use absolute paths create a jsconfig.json file. If you get tierd of writting relative paths you can instruct CRA to use absolute paths for your imports. In the jsconfig.json file copy and paste the following code. If your Dev Server is running after you create and save the file restart the dev server to make the changes take effect.
```json
{
  "compilerOptions": {
    "baseUrl": "src"
  },
  "include": ["src"]
}
```

 




 



