# automation-repo



## Initialize project
`npm install`

### Run all tests
`npx wdio run ./wdio.conf.js`

### Run Authentication tests
`npx wdio run ./wdio.conf.js --spec .\test\specs\authentication\authentication.spec.js`

### Run Add to cart tests
`npx wdio run ./wdio.conf.js --spec .\test\specs\addToCart\*`

### Change the environment
change environment to deb or prod in `.env` file 

### Create Reports
`npx marge  .\report\wdio-ma-merged.json`



