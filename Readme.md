







============================================================================================
#### To install the lite server   
1 - create package file and inside this file type {} then save     
2 - create index html file    
3 - npm i lite-server --save-dev     
4 - add script part in package     
  "scripts": { "start": "lite-server"},    
5 - run the server (npm start) and see if html works fine.   
6 - install web3 library   
> npm i web3 --save-dev   
your web3 library is installed now.   

7 - use  "type": "commonjs" inside package.json   

8. Add in html page following libs   

<script type="text/javascript" src="node_modules/web3/dist/web3.min.js"></script> 

<script type="text/javascript" src="./src/index.js"></script>   
