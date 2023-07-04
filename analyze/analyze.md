# eject

## script

이전

```
"start": "react-scripts start",
"build": "react-scripts build",
"test": "react-scripts test",
"eject": "react-scripts eject"
```

이후

```
"start": "node scripts/start.js",
"build": "node scripts/build.js",
"test": "node scripts/test.js"
```

- [react scripts](https://www.npmjs.com/package/react-scripts) dependency 삭제
- https://github.com/facebook/create-react-app#readme
