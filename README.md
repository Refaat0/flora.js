# Flora.js
![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![Mocha](https://img.shields.io/badge/-mocha-%238D6748?style=for-the-badge&logo=mocha&logoColor=white)  

Flora.js is a toy command line utility for flower nerds!

## Getting Started
These instructions will get you a copy of the project up and running on your local machine! 

### Prerequisites
you **must** have <a href="https://nodejs.org/en/">node.js</a> installed on your local machine.

### Installing
Clone the repository into a directory
```
C:\Users\Refaat\Desktop\flower.js> git clone https://github.com/Refaat0/flora.js .
```

Install the required NPM packages:
```
C:\Users\Refaat\Desktop\flora.js> npm install
```

Install flora.js globally on your machine:
```
C:\Users\Refaat\Desktop\flora.js> npm install -g .
```

Ensure that the application is working correctly by running the following command:
```
C:\Users\Refaat> flora random
```

Your terminal should display a result similar to the following:
```
Plant {
    commonName: "Congdon's woolly sunflower",
    familyName: 'Asteraceae'
}
```

## Creating An Executable
You can create a windows, linux, and macos executable by running the following command:
```
C:\Users\Refaat\flower.js> npm run package
```

A new directory named ``bin`` will be created and it will contain the executables.

Ensure that the application is working by running the following command:
```
C:\Users\Refaat\flower.js\bin> flora.exe random
```

## Running the tests
You can run the included unit tests by runing the following command:
```
C:\Users\Refaat\flower.js> npm test
```
