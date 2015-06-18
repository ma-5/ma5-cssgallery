# ma5-cssgallery


### MA5-CSSgallery ###
Responsive CSS Gallery without javascripts.
>v.1.0 Initial


###Features:
* Responsive
* Html5
* CSS3
* No javascripts
* The number of images is not dependent on the CSS

### Example
* [See example](http://galeriacss.ma5.pl)


### 1.Getting Started
```html
<!-- html head -->
<meta name="viewport" content="width=device-width, initial-scale=1, minimal-ui, user-scalable=no">
<link href="./stylesheets/ma5-cssgallery.css" media="screen, projection" rel="stylesheet" type="text/css">
<!--[if lte IE 9]>
<link href="./stylesheets/ma5-cssgallery-ie9.css" media="screen, projection" rel="stylesheet" type="text/css">
<![endif]-->

<!-- html body -->
<div class="ma5-css-gallery">
    <input type="radio" name="gallery-1" id="gallery-1" checked="checked">
    <div class="ma5-gallery-content">
        <!-- thumbnails -->
        <figure>
            <label for="gallery-1-slide-1">Slide 1</label>
            <img src="./images/ptaki/DSC_1769-thumbnail.jpg" alt="">
        </figure>
        <figure>
            <label for="gallery-1-slide-2">Slide 2</label>
            <img src="./images/ptaki/DSC_1641-thumbnail.jpg" alt="">
        </figure>
        <figure>
            <label for="gallery-1-slide-3">slide3</label>
            <img src="./images/ptaki/DSC_1604-thumbnail.jpg" alt="">
        </figure>
        <!-- slider -->
        <div class="ma5-container">
            <div class="ma5-cssslider">
                <label class="ma5-close" for="gallery-1">close</label>
                <div class="ma5-slides">
                    <!-- slide 1 -->
                    <div class="ma5-slide">
                        <input type="radio" name="gallery-1" id="gallery-1-slide-1">
                        <figure class="ma5-has-figcaption">
                            <img src="./images/ptaki/DSC_1769.jpg" alt="">
                            <figcaption>Title of slide 1</figcaption>
                        </figure>
                        <label for="gallery-1-slide-1"><img src="./images/ptaki/DSC_1769-navigator.jpg" alt=""></label>
                    </div>
                    <!-- slide 2 -->
                    <div class="ma5-slide">
                        <input type="radio" name="gallery-1" id="gallery-1-slide-2">
                        <figure class="ma5-has-figcaption">
                            <img src="./images/ptaki/DSC_1641.jpg" alt="">
                            <figcaption>Title of slide 2</figcaption>
                        </figure>
                        <label for="gallery-1-slide-2"><img src="./images/ptaki/DSC_1641-navigator.jpg" alt=""></label>
                    </div>
                    <!-- slide 3 -->
                    <div class="ma5-slide">
                        <input type="radio" name="gallery-1" id="gallery-1-slide-3">
                        <figure class="ma5-has-figcaption">
                            <img src="./images/ptaki/DSC_1604.jpg" alt="">
                            <figcaption>Title of slide 3</figcaption>
                        </figure>
                        <label for="gallery-1-slide-3"><img src="./images/ptaki/DSC_1604-navigator.jpg" alt=""></label>
                    </div>
                </div>
            </div>
        </div> 
    </div>       
</div>
```
When the picture nasn't figcaption:

```html
<!-- slide without figcaption -->
<div class="ma5-slide">
    <input type="radio" name="slides" id="slide_1">
    <figure>
        <img src="./path/to/full-image.jpg" alt="">
    </figure>
    <label for="slide_1"><img src="./path/to/navigator-icon.jpg" alt=""></label>
</div>
```

License
------------
The MIT License (MIT)
