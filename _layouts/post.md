<!DOCTYPE html>
<html itemscope itemtype="http://schema.org/Organization">
<head>
{% include head.html %}
</head>
<body>
{% include header2.html %}


<body class="blog single">

<article>
    <section id="main">
            <div class="container">
                <div id="post-cont">
                 <h1>{{ page.title }}</h1>
                 {{ content }}
                </div> <!--post-cont-->
            </div><!--container-->
    </section><!--main-->   
</article>


 
<!-- Place this tag right after the last button or just before your close body tag. -->
<script async defer id="github-bjs" src="https://buttons.github.io/buttons.js"></script>

</body>
</html>



