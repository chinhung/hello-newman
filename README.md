## About
Postman is an api testing tool and Newman is a command-line collection runner for Postman. In this repository, Newman is used as a Node.js module.

## Setup
1. Install npm modules:
    ```sh
    cd /path/of/this/repo
    npm install
    ```

2. Install Postman to edit collection file(*.postman_collection.json) with GUI. In macOS, use Homebrew:
    ```sh
    brew cask install postman
    ```



## Run Test
```sh
npm test
```

## Future Work
- Dockerize this application.
- Integrate with CI system.
- Integrate with [Swagger](https://swagger.io/).
- Survey alternatives because collection file is too difficult to read by human.

## Reference
- https://www.npmjs.com/package/newman#getting-started
- https://medium.com/cubemail88/newman-%E4%B8%80%E5%80%8B%E8%AE%93-postman-api-testing-%E8%87%AA%E5%8B%95%E5%8C%96%E7%9A%84%E5%A5%BD%E5%B9%AB%E6%89%8B-8e12a6956a25
- https://dotblogs.com.tw/tingi/2018/10/14/001620