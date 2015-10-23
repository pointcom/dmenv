# dmenv

It aims to use the right docker machine for the right project.

## Getting started

### Setup dmenv
1) Clone the `dmenv` project :

```shell
$ git clone https://github.com/pointcom/dmenv.git ~/.dmenv
```

2) Add `dmenv` path to your shell :

```shell
$ echo 'export PATH="~/.dmenv/:$PATH"' >> ~/.bash_profile
```

### Setup your project

1) add a `.dmenv` in the root of your project with his name :

```
myawesomeproject
```

Now every docker commands you will run on this directory will automatically use the docker machine `myawesomeproject`.



## Credits

This project is inspired by the Rbenv project from "Sam Stephenson" :
https://github.com/sstephenson/rbenv
