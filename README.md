# learning_npm_istanbul

## Advanced Reports

```
    "cover": "nyc mocha src --recursive",
```

Runs all test with simple reporting

```
"cover:reports": "nyc --reporter=html --reporter=text mocha src --recursive"
```

Runs all test with both `text` and `html` reporting



### Sources

[Istanbul with Mocha](https://istanbul.js.org/docs/tutorials/mocha/)