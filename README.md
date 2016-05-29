### Grunt support

####Tasks

**Development**

```
grunt serve
```

- activates livereload
- opens site in browser (http://localhost:9000)
- watches files for changes

```
grunt watch
```

- watches for changes on all html files and assets (sass & js)

**Production**

```
grunt build
```

- Generates minified site stylesheet
- Optimises images
- Concatinates and minifies js
- Places all build assets (css, js & imgs) in dist directory
- Copies all other build files (.ico, html & web fonts) to dist directory
