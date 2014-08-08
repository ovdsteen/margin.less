#Margin.less (beta)
*Top and bottom margin library for twitter bootstrap*

A libary to add margin between rows

*Note: Still in beta version*

##Usage

Determine margins:
`@margin-xs: 25px;`
`@margin-sm: 50px;`
`@margin-md: 60px;`
`@margin-lg: 100px;`

Determine responsive factor:
`@margin-md-factor: 80;`
`@margin-sm-factor: 60;`
`@margin-xs-factor: 30;`

Use for debug:
`@debug:0;`


###Bootstrap
To use margin.less in your Bootstrap project, simply add the line below into `bootstrap.less`:

```css
@import "margin.less";
```

###Inside your HTML
Add for example the class `margin-md` to your HTML

For example:

```html
<div class="row margin-md">...</div>
<div class="row margin-md-top">...</div>
<div class="row margin-md-bottom">...</div>
<div class="row margin-md-noresize">...</div>
<div class="row margin-md-top-noresize">...</div>
<div class="row margin-md-bottom-noresize">...</div>
```

*Note: if you're having issues, try re-compiling `bootstrap.less` for changes to take effect.*

###Extending with jQuery
You can add more functionality to your animations with jQuery such as below:

```javascript
$("#logo").addClass('animated bounceOutLeft');
```

We can also bind these classes with events or triggers like below:

```javascript
$(document).ready(function(){
    $("#logo").click(function() {
        $("this").addClass("animated bounceOutLeft");
    });
});
```
###Editing an animation effect
You can 1) change the duration of your animations, 2) extend the delay, or 3) change the number of times that it plays. If you do edit an animation effect, make sure you change them cross-browser.

```css
#logo {
    -vendor-animation-duration: 3s; // Change to Webkit, Mozilla, Opera, etc.
    -vendor-animation-delay: 2s;
    -vendor-animation-iteration-count: infinite;
    animation-duration 3s; // Default
    animation-delay: 2s; // Default
    animation-iteration-count: infinite; // Default
}
```



##Cheat Sheet

####Margin-xs:
margin-xs
margin-xs-top
margin-xs-bottom
margin-xs-noresize
margin-xs-top-noresize
margin-xs-bottom-noresize

####Margin-sm:
margin-sm
margin-sm-top
margin-sm-bottom
margin-sm-noresize
margin-sm-top-noresize
margin-sm-bottom-noresize

####Margin-md:
margin-md
margin-md-top
margin-md-bottom
margin-md-noresize
margin-md-top-noresize
margin-md-bottom-noresize

####Margin-lg:
margin-lg
margin-lg-top
margin-lg-bottom
margin-lg-noresize
margin-lg-top-noresize
margin-lg-bottom-noresize
