Clone project locally. Then to install bundler, jquery and bootstrap run:

```
npm i
```

Then start a development server running at http://localhost:1234 (with live reload):

```
npm start
```

Then to build the static files for production deployment:

```
npm run-script build
```

Copy files which are generated into `dist/` to web server.

You will see all JS and CSS have been combined and compressed into single files. Both with hashes for caching. The `dist/` directory should never be checked into version control.
