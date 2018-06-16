# Promo 2018 - first cohort

Websites and final projects created by Codi 2018

### Additional websites not listed in this repo:

- [Codi Talents](http://coditalent.tk)

## INSTALL

run the local included `install` script:

```sh
$ npm git:init
```

then

```sh
$ npm install
```

This will:

- download every project from git
- enter each directory
- run `npm install` in each directory

*note*: on Windows 10, you need to install a specific Meteor version. Use `meteor update --release 1.6.1.2-rc.0`. You will also likely need `node-gyp`, which you can setup in one command from an admin shell `npm install --global --production windows-build-tools`

## RUN

Check all the required dependencies are available

```sh
$ npm run requirements
```

Install whatever is missing, then

Use the included `start` script:

```sh
$ npm run <NAME>
```

Where `<NAME>` is the name of a student project (directory), e.g, `npm run amr_gharz`

or

```sh
$ npm start
```

to run all projects

## OTHER USEFUL SCRIPTS

run `npm install` in each subdirectory
```sh
$ npm install 
```

Update each submodule to its latest version
```sh
$ npm run git:update
```

Install a specific project
```sh
$ npm run install:<NAME>
```

Build all projects
```sh
$ npm run build:all
```

Build a specific project
```sh
$ npm run build:<NAME>
```

## LICENSE

MIT