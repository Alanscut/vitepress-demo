# Hello VitePress

The plugin will be used by default. For production, you will need [DefinePlugin](https://webpack.js.org/plugins/define-plugin/) for webpack or [envify](https://github.com/hughsk/envify) for Browserify to convert the value of `process.env.NODE_ENV !== 'production'` to `false` for the final build.
