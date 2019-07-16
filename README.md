# Avant-Garde

Medical AIDS/HIV data visualization process for Dr. Ali Sarvghad and Prof. Nadir Weibel.

## Links 
* Link to Current Release:  [http://avantgarde.zifengxie.com](http://avantgarde.zifengxie.com)
* Link to Prototype:  [http://rezzwc.axshare.com](http://rezzwc.axshare.com)
## Usage

### Environment
Make sure that packages and libraries listed below are installed before running the project
* [ mongoDB ](https://docs.mongodb.com/manual/administration/install-community/)
* [ Node.js ](https://nodejs.org/en/)
* [ yarn ](https://yarnpkg.com/en/docs/install#mac-stable)

and set up the environment:
* run mongoDB on backend.
```bash
$ mongod
```

### Installation
* Clone the project from github to local
```bash
$ git clone https://github.com/TreeNewBeeing/avantgarde-dashboard.git
```

### To Start 
Enter the main directory of the project, run `yarn` and
* To run the current release version, run
```bash
$ yarn start
```
* To run a development version, run
```bash
$ yarn start:dev
```
And then the project will run on http://locahost:3000

## Link to other things
* [Javascript style guide](https://github.com/airbnb/javascript)
* [SASS style guide](https://github.com/airbnb/css)

## Development

* `yarn start:dev` - to start local development server with nodemon and hot reloading.
* `yarn test` - to run unit tests.
* `yarn lint` - to run linter.
* `yarn build` - to build production files
* `yarn start:prod` - to start the server in production mode
* `yarn bs` - to build production files and start server in production mode (combination of above two steps).

## License
TBD
