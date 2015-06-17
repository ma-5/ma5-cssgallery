# ma5-cssgallery


### MA5-CSSgallery ###
Responsive CSS Gallery without javascripts.
>v.1.0 Initial


###Features:
* Responsive
* Html5
* CSS3
* No javascripts

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
    <input type="radio" name="slides" id="gallery-01" checked="checked">
    <div class="ma5-gallery-content">
        <!-- thumbnails -->
        <figure>
            <label for="slide_1">Slide 1</label>
            <img src="./path/to/thumbnail.jpg" alt="">
        </figure>
        <figure>
            <label for="slide_2">Slide 2</label>
            <img src="./path/to/thumbnail.jpg" alt="">
        </figure>
        <figure>
            <label for="slide_3">Slide 3</label>
            <img src="./path/to/thumbnail.jpg" alt="">
        </figure>
        <!-- slider -->
        <div class="ma5-container">
            <div class="ma5-cssslider">
                <label class="ma5-close" for="gallery-01">Close</label>
                <div class="ma5-slides">
                    <!-- slide 1 -->
                    <div class="ma5-slide">
                        <input type="radio" name="slides" id="slide_1">
                        <figure class="ma5-has-figcaption">
                            <img src="./path/to/full-image.jpg" alt="">
                            <figcaption>Title of slide 1</figcaption>
                        </figure>
                        <label for="slide_1"><img src="./path/to/navigator-icon.jpg" alt=""></label>
                    </div>
                     <!-- slide 2 -->
                    <div class="ma5-slide">
                        <input type="radio" name="slides" id="slide_2">
                        <figure class="ma5-has-figcaption">
                            <img src="./path/to/full-image.jpg" alt="">
                            <figcaption>Title of slide 2</figcaption>
                        </figure>
                        <label for="slide_2"><img src="./path/to/navigator-icon.jpg" alt=""></label>
                    </div>
                     <!-- slide 3 -->
                    <div class="ma5-slide">
                        <input type="radio" name="slides" id="slide_3">
                        <figure class="ma5-has-figcaption">
                            <img src="./path/to/full-image.jpg" alt="">
                            <figcaption>Title of slide 3</figcaption>
                        </figure>
                        <label for="slide_3"><img src="./path/to/navigator-icon.jpg" alt=""></label>
                    </div>
                </div>
            </div>
        </div> 
    </div>       
</div>
```

License
------------
The MIT License (MIT)
