# webpack devServer

## webpack --watch

## devServer

```javascript
devServer: {
  contentBase: './dist',
  open: true,
  proxy: {
    '/api': 'localhost:3000'
  }
}
```
