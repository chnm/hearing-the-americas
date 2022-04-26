# Homepage

Here's what goes in the home page for HtA

Title: Welcome
URL slug: welcome

=== HOMEPAGE LAYOUT ===

HTML block
```
<div class="intro">
<div id="left-intro">
<h1 style="line-height:0em;">Hearing the Americas</h1>

<p>explores the early decades of the recording industry (1898-1925), posing new questions about the origins of popular music.</p>
<a class="button" href="#get-started-here" style="padding-top: 3px; padding-bottom: 3px; padding-left: 12px; padding-right: 12px; background-color: #b13a1a; color: #fff; border-radius: 4px; display: inline-block; border: 0; cursor: pointer; font-size: 15px;">Get Started</a>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a class="button" href="#" style="border: 2px solid #B13A1A; padding-top: 2px; padding-bottom: 2px; padding-left: 15px; padding-right: 15px; background-color: #F6F1E9; color: #B13A1A; border-radius: 4px; display: inline-block; cursor: pointer; font-size: 15px; font-weight: 600;">About</a></div>

<div id="right-intro"><img alt="" src="http://localhost:8888/omeka-s/files/asset/ddac41ce1cbcc6c315ec8523606ec4bcad85f2d6.png" style="width: 450px; padding-top: 30px; padding-right: 100px;" /></div>
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

Asset

![hero-img1](https://user-images.githubusercontent.com/59841908/165409966-da16698f-d1a7-4ab3-8dce-14f07fd3494a.png)


