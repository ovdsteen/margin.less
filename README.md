#Margin.less (beta)
*Top and bottom margin library for twitter bootstrap*

A libary to add margin between rows

*Note: Still in beta version*

##Usage

####Determine margins:
```css
@margin-xs: 25px;
@margin-sm: 50px;
@margin-md: 75px;
@margin-lg: 100px;
```

####Determine responsive factor:
```css
@margin-md-factor: 80;
@margin-sm-factor: 60;
@margin-xs-factor: 30;
```

####Use for debug:
```css
@debug:0;
```

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



##Cheat Sheet

####Margin-xs:
- `margin-xs`
- `margin-xs-top`
- `margin-xs-bottom`
- `margin-xs-noresize`
- `margin-xs-top-noresize`
- `margin-xs-bottom-noresize`

####Margin-sm:
- `margin-sm`
- `margin-sm-top`
- `margin-sm-bottom`
- `margin-sm-noresize`
- `margin-sm-top-noresize`
- `margin-sm-bottom-noresize`

####Margin-md:
- `margin-md`
- `margin-md-top`
- `margin-md-bottom`
- `margin-md-noresize`
- `margin-md-top-noresize`
- `margin-md-bottom-noresize`

####Margin-lg:
- `margin-lg`
- `margin-lg-top`
- `margin-lg-bottom`
- `margin-lg-noresize`
- `margin-lg-top-noresize`
- `margin-lg-bottom-noresize`
