# no_framework
This is a working repo for UI samples and design patterns which I use in projects. I'm getting out of css frameworks. everything is a component now. why, even you are a component. 

<strike>TODO: settle on a selector methodology. </strike>. 
It's BEM I guess, b/c of specificity. I like the idea of flat. except the earth. lets keep that round amirite.

TODO: replacement for css framework grids?  
I like libraries such as bootstrap/tailwindcss for the (imho) intuitive naming conventions, the documentation & adoption within community, which is important because w/ a large community project bugs are fixed, issues are resolved.  but css grid has more flexibility, and  so bootstrap grid can be replaced. The naming convention and markup structure however, that is the thing.  
I would prefer using:

```
# ex.1

<nav>
  <div class="row">
    <div class="col-6"><a href="/">Brand</a></div>
  </div>
</nav>
```
than:
```
# ex.2

<div class="nav-container--grey">
  <a href="/">Brand</a>
</div>`
```
In ex.1 the layout is recognizable, it's a row with a 50% width column containing an anchor. css grid uses rows and columns, but it's not apparent from the markup (ex.2) what the layout is. which I'm sure is by design, but I'm not sold on the methodology. anyways.


