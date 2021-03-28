---
layout: page
title: Gallery
permalink: /gallery/
---


  <meta name="viewport" content="width=device-width, initial-scale=1"><link rel="stylesheet" href="../assets/css/gallery.css">

</head>
<body>
<!-- partial:index.partial.html -->
<h1>Pure CSS Gallery</h1>
    <section class="gallery">
        <div class="carousel">

            <input type="radio" id="image1" name="gallery-control" checked>
            <input type="radio" id="image2" name="gallery-control">
            <input type="radio" id="image3" name="gallery-control">
            <input type="radio" id="image4" name="gallery-control">


            <input type="checkbox" id="fullscreen" name="gallery-fullscreen-control"/>

            <div class="wrap">

                <figure>
                    <label for="fullscreen">
                        <img src="https://unsplash.it/1000/700/?random" alt="image3"/>
                    </label>
                </figure>

                <figure>
                    <label for="fullscreen">
                        <img src="https://unsplash.it/1200/980/?random" alt="image2"/>
                    </label>
                </figure>

                <figure>
                    <label for="fullscreen">
                        <img src="https://unsplash.it/1600/880/?random" alt="image3" />
                    </label>
                </figure>

                <figure>
                    <label for="fullscreen">
                        <img src="https://unsplash.it/2000/1400/?random" alt="image4"/>
                    </label>
                </figure>
            </div>

            <div class="thumbnails">

                <div class="slider"><div class="indicator"></div></div>

                <label for="image1" class="thumb" style="background-image: url('https://unsplash.it/700/480/?random')"></label>

                <label for="image2" class="thumb" style="background-image: url('https://unsplash.it/700/400/?random')"></label>

                <label for="image3" class="thumb" style="background-image: url('https://unsplash.it/700/410/?random')"></label>

                <label for="image4" class="thumb" style="background-image: url('https://unsplash.it/700/450/?random')"></label>
            </div>
        </div>
    </section>
<!-- partial -->
  
</body>
</html>