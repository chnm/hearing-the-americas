# Homepage

Here's what goes in the home page for HtA

Title: Welcome

URL slug: welcome

HOMEPAGE LAYOUT

==================
HTML block - INTRO
```
<div class="intro">
<div id="left-intro">
<h1 style="line-height:0em;">Hearing the Americas</h1>

<p>explores the early decades of the recording industry (1898-1925), posing new questions about the origins of popular music.</p>
<a class="button" href="#get-started-here" style="padding-top: 3px; padding-bottom: 3px; padding-left: 12px; padding-right: 12px; background-color: #b13a1a; color: #fff; border-radius: 4px; display: inline-block; border: 0; cursor: pointer; font-size: 15px;">Get Started</a>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a class="button" href="#" style="border: 2px solid #B13A1A; padding-top: 2px; padding-bottom: 2px; padding-left: 15px; padding-right: 15px; background-color: #F6F1E9; color: #B13A1A; border-radius: 4px; display: inline-block; cursor: pointer; font-size: 15px; font-weight: 600;">About</a></div>

<div id="right-intro"><img alt="" src="<RELATIVE PATH to /asset/img/HtA-Vinyl-icon.png>" style="width: 450px; padding-top: 30px; padding-right: 100px;" /></div>
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
==================

==================
Asset Block - HERO IMAGE
![hero-img1](https://user-images.githubusercontent.com/59841908/165409966-da16698f-d1a7-4ab3-8dce-14f07fd3494a.png)
Class: hero-image, Alignment: default

End Asset Block
==================

==================
HTML Block - GET STARTED
```
<div class="intro2">
    <div id="get-started-here">
        <!-- get started -->
        <h1>Get Started</h1>
        <p>The music of the early recorded industry predates most of the familiar commercial genres we know today. Terms
            like &ldquo;country,&rdquo; blues&rdquo; or &ldquo;folk,&rdquo; didn&rsquo;t have the same meaning, and the
            site offers startling insights into how those genres came to be.</p>
        <p>It reflects the transnational circulation of themes and styles, but also the circulation of ethnic and racial
            stereotypes, many of which will be extremely offensive to modern audiences.</p>
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
                <!-- start scenes -->
                <h2 style="font-size: 18px; margin-bottom: 0px;">Scenes</h2>
                <p style="margin-block-start: 0px;">Finding digital primary sources of local history, determining if you
                    can use material you find, and creating metadata to describe your sources.</p>
                <p><a class="button" href="#"
                        style="padding-top: 3px; padding-bottom: 3px; padding-left: 12px; padding-right: 12px; background-color: #b13a1a; color: #fff; border-radius: 4px; display: inline-block; border: 0; cursor: pointer; font-size: 15px;">View
                        all scenes</a></p>
            </div> <!-- end scenes -->

            <div id="explore-cards">
                <!-- start artists -->
                <h2 style="font-size: 18px; margin-bottom: 0px;">Artists</h2>
                <p style="margin-block-start: 0px;">Finding digital primary sources of local history, determining if you
                    can use material you find, and creating metadata to describe your sources.</p>
                <p><a class="button" href="#"
                        style="padding-top: 3px; padding-bottom: 3px; padding-left: 12px; padding-right: 12px; background-color: #b13a1a; color: #fff; border-radius: 4px; display: inline-block; border: 0; cursor: pointer; font-size: 15px;">View
                        all artists</a></p>
            </div> <!-- end artists -->
        </div> <!-- end container cards -->

        <div class="container-cards">
            <!-- start container cards -->
            <div id="explore-cards">
                <!-- start spins -->
                <h2 style="font-size: 18px; margin-bottom: 0px;">Spins</h2>
                <p style="margin-block-start: 0px;">Finding digital primary sources of local history, determining if you
                    can use material you find, and creating metadata to describe your sources.</p>
                <p><a class="button" href="#"
                        style="padding-top: 3px; padding-bottom: 3px; padding-left: 12px; padding-right: 12px; background-color: #b13a1a; color: #fff; border-radius: 4px; display: inline-block; border: 0; cursor: pointer; font-size: 15px;">View
                        all spins</a></p>
            </div> <!-- end spins -->

            <div id="explore-cards">
                <!-- start notes -->
                <h2 style="font-size: 18px; margin-bottom: 0px;">Notes</h2>
                <p style="margin-block-start: 0px;">Finding digital primary sources of local history, determining if you
                    can use material you find, and creating metadata to describe your sources.</p>
                <p><a class="button" href="#"
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
==================

==================
HTML Block - SPIN BANNER
```
<div class="div-banner">
    <div class="spin-icon">
        <img src="http://localhost:8888/omeka-s/files/asset/d94d039e270a7f6a6e550df94db159ec32e919a8.png" />
    </div>

    <div class="spin-banner">
        <h2>Spins</h2>
        <p>The music of the early recorded industry predates most of the familiar commercial genres we know today Terms
            like &ldquo;country,&rdquo; blues&rdquo; or &ldquo;folk,&rdquo; didn&rsquo;t have the same meaning, and the
            site offers startling insights into how those genres came to be. </p>
    </div>
</div>
```
END HTML Block
==================

==================
HTML Block - RECORDS
```
<div class="records">
    <div class="flip-card">
        <div class="flip-card-inner">
            <div class="flip-card-front">
                <a href="https://hearingtheamericas.org/s/the-americas/page/q-dancecraze">
                    <img alt="Avatar"
                        src="http://localhost:8888/omeka-s/files/asset/1dc333f6bd40108f971cf9d3369e02da589efe9d.png"
                        style="border-radius: 50%;z-index: -1;" />
                </a>
            </div>

            <div class="flip-card-back">
                <a href="https://hearingtheamericas.org/s/the-americas/page/q-dancecraze">
                    <img alt="Avatar"
                        src="http://localhost:8888/omeka-s/files/asset/135a756bdd8c9b8453c42a9381def196f08acca4.png"
                        style="border-radius: 50%;z-index: -1;" />
                </a>
            </div>
        </div>
    </div>

    <div class="flip-card">
        <div class="flip-card-inner">
            <div class="flip-card-front">
                <a href="https://hearingtheamericas.org/s/the-americas/page/q-dancecraze">
                    <img alt="Avatar"
                        src="http://localhost:8888/omeka-s/files/asset/343051b2c493656a3dc1ef70f89c4e1762f27f25.png"
                        style="border-radius: 50%;z-index: -1;" />
                </a>
            </div>

            <div class="flip-card-back">
                <a href="https://hearingtheamericas.org/s/the-americas/page/q-dancecraze">
                    <img alt="Avatar"
                        src="http://localhost:8888/omeka-s/files/asset/5b52009ff3a53e4ec8bdd7983aa791aee5ec161f.png"
                        style="border-radius: 50%;z-index: -1;" />
                </a>
            </div>
        </div>
    </div>

    <div class="flip-card">
        <div class="flip-card-inner">
            <div class="flip-card-front">
                <a href="https://hearingtheamericas.org/s/the-americas/page/q-dancecraze">
                    <img alt="Avatar"
                        src="http://localhost:8888/omeka-s/files/asset/4474a1c9b38759bf2b16a0f2980ff020a143d45b.png"
                        style="border-radius: 50%;z-index: -1;" />
                </a>
            </div>

            <div class="flip-card-back">
                <a href="https://hearingtheamericas.org/s/the-americas/page/q-dancecraze">
                    <img alt="Avatar"
                        src="http://localhost:8888/omeka-s/files/asset/7e8859ff2598274069483dd54e2971296cf12aa8.png"
                        style="border-radius: 50%;z-index: -1;" />
                </a>
            </div>
        </div>
    </div>

    <div class="flip-card">
        <div class="flip-card-inner">
            <div class="flip-card-front">
                <a href="https://hearingtheamericas.org/s/the-americas/page/q-dancecraze">
                    <img alt="Avatar"
                        src="http://localhost:8888/omeka-s/files/asset/f309295df76b817361f70d7ab030426bc2caf96d.png"
                        style="border-radius: 50%;z-index: -1;" />
                </a>
            </div>

            <div class="flip-card-back">
                <a href="https://hearingtheamericas.org/s/the-americas/page/q-dancecraze">
                    <img alt="Avatar"
                        src="http://localhost:8888/omeka-s/files/asset/c9a50d284acbf88e0e0382e918ea88d559ca7b5d.png"
                        style="border-radius: 50%;z-index: -1;" />
                </a>
            </div>
        </div>
    </div>
</div>
```
END HTML Block


HTML Block
```
<p><a class="button" href="http://localhost:8888/omeka-s/s/hearing-the-americas-preprod/page/spins" style="padding-top: 3px; padding-bottom: 3px; padding-left: 12px; padding-right: 12px; background-color: #b13a1a; color: #fff; border-radius: 4px; display: inline-block; border: 0; cursor: pointer; font-size: 15px; margin-left: 45%; margin-top: 30px; margin-bottom: 40px;">More Spins</a></p>
```
END HTML Block
==================



