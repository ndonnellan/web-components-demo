# Web Components Demo

## Usage
To use this web component in your page, you should:

### 1. Install this repo as an npm package:
```
npm install git@github.com:qdonnellan/web-components-demo.git
```

### 2. Add the output .js to your head:

```
<!DOCTYPE html>

<html lang="en">
    <head>
        <meta charset="utf-8"/>
        <script type="text/javascript" src="node_modules/web-components-demo/dist/web-components-demo.js"></script>
    </head>
    ...
</html>
```

### 3. Add the web component where desired in the body of your HTML page:

```
<body>
    <hello-world></hello-world>
</body>
```

Thus, a simplified, complete page that consumes this web component would look like:

```
<!DOCTYPE html>

<html lang="en">
    <head>
        <meta charset="utf-8"/>
        <script type="text/javascript" src="node_modules/web-components-demo/dist/web-components-demo.js"></script>
    </head>
    <body>
        <hello-world></hello-world>
    </body>
</html>
```
