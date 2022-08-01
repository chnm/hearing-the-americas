# Homepage

Here's what goes in the home page for HtA

Title: Welcome

URL slug: welcome

==== HOMEPAGE LAYOUT ===

HTML block - INTRO
```
<div class="intro">
<div id="left-intro">
<h1 style="line-height:0em;">Hearing the Americas</h1>

<p>explores the early decades of the recording industry (1898-1925), posing new questions about the origins of popular music.</p>
<a class="button" href="#get-started-here" style="padding-top: 3px; padding-bottom: 3px; padding-left: 12px; padding-right: 12px; background-color: #b13a1a; color: #fff; border-radius: 4px; display: inline-block; border: 0; cursor: pointer; font-size: 15px;">Get Started</a>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a class="button" href="#" style="border: 2px solid #B13A1A; padding-top: 2px; padding-bottom: 2px; padding-left: 15px; padding-right: 15px; background-color: #F6F1E9; color: #B13A1A; border-radius: 4px; display: inline-block; cursor: pointer; font-size: 15px; font-weight: 600;">About</a></div>

<div id="right-intro"><img alt="" src="</themes/[THEMEFOLDER]/asset/img/HtA-Vinyl-icon.png>" style="width: 450px; padding-top: 30px; padding-right: 100px;" /></div>
</div>
<script> 
document.querySelectorAll('a[href^="#"]').forEach(anchor => {
    anchor.addEventListener('click', function (e) {
        e.preventDefault();
        document.querySelector(this.getAttribute('href')).scrollIntoView({
            behavior: 'smooth'
        });
    });
});
</script>
```
End HTML Block

Asset Block - HERO IMAGE
![hero-img1](https://user-images.githubusercontent.com/59841908/165409966-da16698f-d1a7-4ab3-8dce-14f07fd3494a.png)
Class: hero-image, Alignment: default
End Asset Block

HTML Block - GET STARTED
```
<div class="intro2">
    <div id="get-started-here">
        <!-- get started -->
        <h1>Get Started</h1>
        <p>The emergence of the record industry in the early decades of the twentieth century had a powerful impact on popular music, carrying songs and styles across national borders and pushing innovation in unexpected directions. These early recordings can sound very strange to modern ears, since the technology was limited, and most of the genres we are used to did not yet exist. This website provides multiple paths into this sonic world, revealing new perspectives on the history of this period.</p>
        <div class="alert alert-warning">
            <h2>Disclaimer</h2>
            <p>This site contains historical content which may be upsetting or offensive to some visitors. Please see
                the content warning for a full statement.</p>
        </div>
    </div> <!-- end get started -->

    <div class="explore-spacing">
        <!-- start explore -->
        <h1>Explore</h1>
        <div class="container-cards">
            <!-- start container cards -->
            <div id="explore-cards">
                <!-- start styles -->
                <h2 style="font-size: 18px; margin-bottom: 0px;">Styles</h2>
                <p style="margin-block-start: 0px;">Check out the musical categories that accounted for many of the recordings sold in this period.</p>
                <p><a class="button" href="/s/the-americas/page/genres"
                        style="padding-top: 3px; padding-bottom: 3px; padding-left: 12px; padding-right: 12px; background-color: #b13a1a; color: #fff; border-radius: 4px; display: inline-block; border: 0; cursor: pointer; font-size: 15px;">View
                        all Styles</a></p>
            </div> <!-- end styles -->

            <div id="explore-cards">
                <!-- start artists -->
                <h2 style="font-size: 18px; margin-bottom: 0px;">Artists</h2>
                <p style="margin-block-start: 0px;">Some of these performers are still famous today. Many more you’ve never heard of, though they sold hundreds of thousands of records.</p>
                <p><a class="button" href="/s/the-americas/page/artists"
                        style="padding-top: 3px; padding-bottom: 3px; padding-left: 12px; padding-right: 12px; background-color: #b13a1a; color: #fff; border-radius: 4px; display: inline-block; border: 0; cursor: pointer; font-size: 15px;">View
                        all artists</a></p>
            </div> <!-- end artists -->
        </div> <!-- end container cards -->

        <div class="container-cards">
            <!-- start container cards -->
            <div id="explore-cards">
                <!-- start spins -->
                <h2 style="font-size: 18px; margin-bottom: 0px;">Spins</h2>
                <p style="margin-block-start: 0px;">Test your knowledge with these questions about music at the dawn of the recording era. You may be surprised by what you find.</p>
                <p><a class="button" href="/s/the-americas/page/spins"
                        style="padding-top: 3px; padding-bottom: 3px; padding-left: 12px; padding-right: 12px; background-color: #b13a1a; color: #fff; border-radius: 4px; display: inline-block; border: 0; cursor: pointer; font-size: 15px;">View
                        all spins</a></p>
            </div> <!-- end spins -->

            <div id="explore-cards">
                <!-- start notes -->
                <h2 style="font-size: 18px; margin-bottom: 0px;">Notes</h2>
                <p style="margin-block-start: 0px;">Explore the technical, commercial, and musicological aspects of the early record business.</p>
                <p><a class="button" href="/s/the-americas/page/notes"
                        style="padding-top: 3px; padding-bottom: 3px; padding-left: 12px; padding-right: 12px; background-color: #b13a1a; color: #fff; border-radius: 4px; display: inline-block; border: 0; cursor: pointer; font-size: 15px;">View
                        all notes</a></p>
            </div> <!-- end notes -->
        </div> <!-- end container cards -->
    </div> <!-- end explore -->
</div>
```
END HTML Block

HTML Block - TIMELINE
```
<div class="iframe-div">
    <p style="margin-top: 0; padding-top: 0; line-height: 0px;"><iframe allowfullscreen="" frameborder="0" height="650"
            mozallowfullscreen=""
            src="https://cdn.knightlab.com/libs/timeline3/latest/embed/index.html?source=1QA4375O8BUp5pUas5Yr0duph-Pg5fRYmHJ0ZcKLLuDE&amp;font=Default&amp;lang=en&amp;initial_zoom=2&amp;height=650"
            style="overflow-x: hidden;overflow-y: hidden;" webkitallowfullscreen="" width="100%"></iframe></p>
</div>
```
END HTML Block

HTML Block - SPIN BANNER
```
<div class="div-banner">
    <div class="spin-icon">
        <img src="/themes/hearing/asset/img/spins-banner-icon.png"/>
    </div>

    <div class="spin-banner">
        <h2>Spins</h2>
        <p>Test your knowledge with these questions about music at the dawn of the recording era. </p>
    </div>
</div>
```
END HTML Block

HTML Block - RECORDS
```
<div class="records-welcome">
    <div class="flip-card">
        <div class="flip-card-inner">
            <div class="flip-card-front disc-yellow">
                <h3 style="font-size: 14px; margin-left: 20px; margin-right: 20px; line-height: 20px;">What was the
                    dance craze that inspired W.C. Handy&rsquo;s legendary &ldquo;St. Louis Blues&rdquo; (1914)?</h3>
            </div>

            <div class="flip-card-back disc-1-back">
                <h3 style="line-height: 10px;">A: The tango</h3>
                <a class="button" draggable="false"
                    href="https://hearingtheamericas.org/s/the-americas/page/q-dancecraze"
                    style="padding-top: 3px; padding-bottom: 3px; padding-left: 12px; padding-right: 12px; color: #fff; border-radius: 30px; display: inline-block; border: 2px solid #fff; background-color: transparent; cursor: pointer; font-size: 15px;"><b>learn
                        more</b></a>
            </div>
        </div>
    </div>

    <div class="flip-card">
        <div class="flip-card-inner">
            <div class="flip-card-front disc-blue">
                <h3 style="font-size: 14px; margin-left: 20px; margin-right: 20px; line-height: 20px;">What was the most
                    popular kind of band in America and worldwide in 1900?</h3>
            </div>

            <div class="flip-card-back disc-2-back">
                <h3 style="line-height: 9.5px;">A: The brass band</h3>
                <a class="button" draggable="false"
                    href="https://hearingtheamericas.org/s/the-americas/page/q-popular-band"
                    style="padding-top: 3px; padding-bottom: 3px; padding-left: 12px; padding-right: 12px; color: #fff; border-radius: 30px; display: inline-block; border: 2px solid #fff; background-color: transparent; cursor: pointer; font-size: 15px;"><b>learn
                        more</b></a>
            </div>
        </div>
    </div>

    <div class="flip-card">
        <div class="flip-card-inner">
            <div class="flip-card-front disc-green">
                <h3 style="font-size: 14px; margin-left: 20px; margin-right: 20px; line-height: 20px;">How did recording
                    transform music listening?</h3>
            </div>

            <div class="flip-card-back disc-3-back">
                <h3 style="line-height: 11px; font-size: 10px; padding-left: 20px; padding-right: 20px;">A: It allowed
                    for repeated listening, provided public access to types of music that were previously restricted to
                    the elite, and brought professionally performed music into the home.</h3>
                <a class="button" draggable="false"
                    href="https://hearingtheamericas.org/s/the-americas/page/recording-transform"
                    style="padding-top: 3px; padding-bottom: 3px; padding-left: 12px; padding-right: 12px; color: #fff; border-radius: 30px; display: inline-block; border: 2px solid #fff; background-color: transparent; cursor: pointer; font-size: 15px;"><b>learn
                        more</b></a>
            </div>
        </div>
    </div>

    <div class="flip-card">
        <div class="flip-card-inner">
            <div class="flip-card-front disc-red">
                <h3 style="font-size: 14px; margin-left: 20px; margin-right: 20px; line-height: 20px;">What role did
                    Black people from the British Caribbean play in the Jazz Age?</h3>
            </div>

            <div class="flip-card-back disc-4-back">
                <h3 style="font-size: 14px; margin-left: 20px; margin-right: 20px; line-height: 20px;">A: Migration
                    patterns and the record business made them central.</h3>
                <a class="button" draggable="false"
                    href="https://hearingtheamericas.org/s/the-americas/page/british-caribbean"
                    style="padding-top: 3px; padding-bottom: 3px; padding-left: 12px; padding-right: 12px; color: #fff; border-radius: 30px; display: inline-block; border: 2px solid #fff; background-color: transparent; cursor: pointer; font-size: 15px;"><b>learn
                        more</b></a>
            </div>
        </div>
    </div>
</div>
```
END HTML Block


HTML Block
```
<p><a class="button" href="/s/the-americas/page/spins" style="padding-top: 3px; padding-bottom: 3px; padding-left: 12px; padding-right: 12px; background-color: #131B1B; color: #fff; border-radius: 4px; display: inline-block; border: 0; cursor: pointer; font-size: 15px; margin-left: 45%; margin-top: 30px; margin-bottom: 40px;">More Spins</a></p>
```
END HTML Block
