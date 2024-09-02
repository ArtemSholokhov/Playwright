## This project is a basic example of how to run your Playwright tests from GitLab CI/CD repositoty to TestIT TMS and in reverse order.

## Project structure

* **tests/** – test files
    * **annotations.test.ts** – simple test examples with [annotations testit-adapter-playwright](https://github.com/testit-tms/adapters-js/tree/main/testit-adapter-playwright#methods)
    * **methods.test.ts** – simple test examples with [methods testit-adapter-playwright](https://github.com/testit-tms/adapters-js/tree/main/testit-adapter-playwright#methods)
    * **steps.test.ts** – simple test examples with [steps testit-adapter-playwright](https://github.com/testit-tms/adapters-js/tree/main/testit-adapter-playwright#methods)
* **playwright.config.ts** - [configuration file of Playwright](https://playwright.dev/docs/test-configuration)
* **package.json** - [JSON representation](https://docs.npmjs.com/cli/v9/configuring-npm/package-json?v=true) of a NPM project
* **tms.config.json** - configuration file where specified base options for tests
* **.gitlab-ci.yml** - the default configuration of .gitlab-ci.yml, which is main file to run GitLab Pipelines
