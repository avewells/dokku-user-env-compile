dokku-user-env-compile
=====================

dokku-user-env-compile is to dokku what [user-env-compile](https://devcenter.heroku.com/articles/labs-user-env-compile) is to heroku. It essentially makes a applications ENV file available to the build container. This allows the build process to to run in an environment that more closely resembles the runtime environment.

## Installation

```sh
sudo dokku plugin:install https://github.com/avewells/dokku-user-env-compile.git
```
