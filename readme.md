# Image zoom on hover
##### Zoom images when hovering without the need of a higher resolution

### Demo

You can see a demo into a demo/index.html

### Usage
Just put the image into a container with the `image-hover-zoom` class and if you want you can add attribute scale to that div.

For example:
```
        <div class='image-hover-zoom' scale="2.0">
            <img src='https://dummyimage.com/600x400/000/fff'>
        </div>
```

Full example:

```
<!DOCTYPE html>
<html lang='en'>
<head>
    <meta charset='UTF-8'>
    <meta name='viewport' content='width=device-width, initial-scale=1.0'>
    <title>Document</title>
</head>
<body>
    <div style="display: flex; justify-content: center; align-items: center; width: 100%; height: 100vh;">
        <div class='image-hover-zoom' scale="2.0">
            <img src='https://dummyimage.com/600x400/000/fff'>
        </div>
    </div>
    <script src='/index.js'></script>
</body>
</html>
```

In this case index.js is our zoom plugin