# Sass placeholder extend reproduction

Minimal test case showing the “target selector not found” error when extending a placeholder from another module.

## Run the test

```
npm install
npm run build
```

### Error

```
Error: The target selector was not found.
Use "@extend %block_input !optional" to avoid this error.
  ╷
4 │     @extend %block_input;
  │     ^^^^^^^^^^^^^^^^^^^^
  ╵
  src/select.scss 4:2  root stylesheet
```
