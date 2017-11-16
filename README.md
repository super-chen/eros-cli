# eros-cli
A simple CLI for scaffolding [weex](http://weex.apache.org/cn/) projects, we provide [eros-template](https://github.com/bmfe/eros-template) to quickly build small and medium sized app.

## Installation
Prerequisites: Node.js (>=4.x, 6.x preferred), npm version 3+ and Git.

```
$ npm install -g eros-cli
```

If you were in China, we recommand you install [cnpm](https://npm.taobao.org/) before.

```
$ cnpm install -g eros-cli
```

## Usage
You can code `eros -h` to show a profile.
```
eros-cli:
The following instructions are provided to help you build app !

 build      | build for eros project.
 dev        | start dev server.
 init       | generate eros template.
 install    | install eros platform and components' librarys.
 mock       | start a mock server.
 pack       | pack full dose zip and send to eros platform project.
 update     | update eros-template file by path.
```

## Command
**build**: 

eros cli build prod's zip, contain js bundle, assets/images and iconfont. 
```
$ eros build
```
**dev**:

start dev server, eros' app can refresh current view when your local code is changed and saved, **You can debug by forward agent software in real machine.**

forward agent software recommand:

* windows: fidder
* ios: charles

```
$ eros dev
```
**init**:

generate [eros-template](https://github.com/bmfe/eros-template) in current execution directory, you can quickly build your app through
 it.
```
$ eros init
```
**install**

eros developed many functions based on weex (self-module), you don't have to worry about the version of the weex update, we will update weex in time, every time we have a change ( new module / bugfix / weex update and so on), you can install them to use it.
```
$ eros install
```
**mock**
```
$ eros mock
```
**pack**
```
$ eros pack
```
**update**
```
$ eros update
```

