# slush-pages-react

> a generator for static react pages using browserify

## Wait, what is this?

This is a project generator for a frontend react project. You can optionally deploy your project to [github pages](https://pages.github.com/) as a set of static files. If you need a backend, that's up to you to sort out.

The template project:

- uses [browserify](browserify.org) to bundle your source.
- allows jsx and es6 syntax which will be transpiled by [babelify](https://www.npmjs.com/package/babelify).
- has a development server, [budo](https://www.npmjs.com/package/budo) which transpiles your code and has live-reloading.
- has a handy script to allow easy publishing to github pages: `npm run deploy`.
- uses [tinify](https://www.npmjs.com/package/tinyify) to make your deployed builds as small as possible.

## Dependency Versions:

From the template package.json:

```json
  "devDependencies": {
    "@babel/core": "^7.4.3",
    "@babel/preset-env": "^7.4.3",
    "@babel/preset-react": "^7.0.0",
    "babelify": "^10.0.0",
    "browserify": "^16.2.3",
    "budo": "^11.6.1",
    "gh-pages": "^0.11.0",
    "react": "^16.8.6",
    "react-dom": "^16.8.6",
    "tap-spec": "^4.1.1",
    "tape": "^4.5.1",
    "tinyify": "^2.5.0",
    "watchify": "^3.7.0"
  }
```

## Getting Started

Install `slush` and `slush-pages-react` globally:

```bash
$ npm install -g slush slush-pages-react
```

### Usage

Create a new folder for your project:

```bash
$ mkdir my-ghpages-react-app
```

Run the generator from within the new folder:

```bash
$ cd my-ghpages-react-app && slush pages-react
```

Woo! Check out the generated README for more usage information.

## Getting To Know Slush

Slush is a tool that uses Gulp for project scaffolding.

Slush does not contain anything "out of the box", except the ability to locate installed slush generators and to run them with liftoff.

To find out more about Slush, check out the [documentation](https://github.com/klei/slush).
