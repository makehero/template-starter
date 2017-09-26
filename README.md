# Template Starter

To hit the ground running feel free to use our simple template starter. You can clone in from GitHub and get started in a few easy steps:

Clone the repository:

```bash
$ git clone git@github.com:makehero/template-starter.git template_name
```

Use [yarn](https://yarnpkg.com) to install project dependencies:

```bash
$ cd template_name/
$ yarn install
```

Start a local development server:

```bash
$ yarn dev
```

This will launch a comfortable development environment for implementing a template design. Whatever can be done with `yarn` can also be done with `npm` so use whichever feels right for you.

Check out [Yarn Usage](https://yarnpkg.com/en/docs/usage) and [Yarn Documentation](https://yarnpkg.com/en/docs/cli).


### Use Yarn or Node Packaga Manager

- `yarn add [package] --dev` or `npm install [package] --save`


### Neat Bourbon & Bitters

This project comes with a few SASS libraries:

- [Bourbon](http://bourbon.io/) - A lightweight mixin library for SASS
- [Neat](http://neat.bourbon.io/) - A flexible SASS responsive grid
- [Bitters](http://bitters.bourbon.io/) - A basic structure for your SASS files

All of these can be found inside your `assets/sass` directory. You can safely delete everything and start from scratch.


## Build

When you are done implementing the template you can build a Lndr compatible version by running the build command.

```bash
$ yarn build
```

### Using Boilerplate

- Use `styles.scss` to import all style files.
- Use `assets/sass` directory for your own templates sass code