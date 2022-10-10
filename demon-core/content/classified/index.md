+++
title = "Classified Documents"
description = "About the website"
date = "2022-09-30"
aliases = ["about-us", "contact"]
author = "June"
+++
<style>input[type='checkbox'] {
    display: none;
}

.wrap-collapsible {
    margin: 1.2rem 0;
}

.lbl-toggle {
    display: block;
    font-weight: bold;
    font-size: 1.2rem;
    text-transform: uppercase;
    text-align: center;
    padding: 1rem;
    color: #DDD;
    background: #696969;
    cursor: pointer;
    border-radius: 7px;
    transition: all 0.25s ease-out;
}

.lbl-toggle:hover {
    color: #FFF;
}

.lbl-toggle::before {
    content: ' ';
    display: inline-block;
    border-top: 5px solid transparent;
    border-bottom: 5px solid transparent;
    border-left: 5px solid currentColor;
    vertical-align: middle;
    margin-right: .7rem;
    transform: translateY(-2px);
    transition: transform .2s ease-out;
}

.toggle:checked+.lbl-toggle::before {
    transform: rotate(90deg) translateX(-3px);
}

.collapsible-content {
    max-height: 0px;
    overflow: hidden;
    transition: max-height .25s ease-in-out;
}

.toggle:checked+.lbl-toggle+.collapsible-content {
    max-height: 2000px;
}

.toggle:checked+.lbl-toggle {
    border-bottom-right-radius: 0;
    border-bottom-left-radius: 0;
}

.collapsible-content .content-inner {
    background: rgba(200, 200, 200, .2);
    border-bottom: 1px solid rgba(0, 0, 0, .45);
    border-bottom-left-radius: 7px;
    border-bottom-right-radius: 7px;
    padding: .5rem 1rem;
}

.collapsible-content p {
    margin-bottom: 0;
}</style>

<br>

<div align="center">
<img src="./images/los_alamos.png" alt="Los Alamos Header" width="600"/>
<img src="./images/warning.png" alt="Warning" width="600"/>
</div>

## THE FOLLOWING CONTENT HAS BEEN DEEMED CLASSIFIED MATERIAL
# ...
# ...
# ...
<div class="wrap-collapsible"> 
<input id="collapsible" class="toggle" type="checkbox"> 
<label for="collapsible" class="lbl-toggle">I UNDERSTAND THE RISKS INVOLVED IN VIEWING THIS SECTION</label>
<div class="collapsible-content">
<div class="content-inner">
<p> 
<div align="center">
<h2>DISCLAIMER: THIS CONTENT IS NOT RELATED TO THE REST OF THE SITE, IT IS HERE FOR TESTING THE CODE</h2>
<img src="./images/beloved.gif" alt="Demon Core My Beloved" width="600"/>
<img src="./images/producer.png" alt="Demon Core My Beloved" width="600"/>
<iframe width="560" height="315" src="https://www.youtube.com/embed/6ZIjbX1gj88" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>
</p>
</div>
</div>
</div>