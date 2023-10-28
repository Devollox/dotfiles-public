<div align="center">
   <h1>
      <a>Day</a>
      <a href="-" target="_blank">4</a>
   </h1>
   <h3>
      <a>I will dedicate this <a href="">day</a> to creating a <a href="">roadmap</a>.</a>
   </h3>
   <div>
      <h3>
         <a href="-" target="_blank">Site</a> - Here you can see
      </h3>
   </div>
</div>


<div align="center">
   <h1>
      <a>Day</a>
      <a href="-" target="_blank">3</a>
   </h1>
</div>

```sass
$primary-color: #933

@mixin font-settings
  color: $primary-color
  font-weight: bold 900

.font
  @include font-settings

```

<div align="center">
   <h3>
      <a><a href="">@mixin</a> - one of the coolest tools I've learned from <a href="">styles</a>.</a>
   </h3>
</div>

```sass
// _reset.sass
html,
body,
ul,
ol
  margin:  0
  padding: 0

// base.sass
@import reset
body
  font: 100% Helvetica, sans-serif
  background-color: #efefef

```

<div align="center">
   <h3>
      <a><a href="">@import</a> - also a very interesting thing, it's a pity that I haven't found the application <a href="">yet</a>.</a>
   </h3>
</div>

<h5>scss</h5>

```scss
@mixin transform($property) {
  -webkit-transform: $property;
  -ms-transform: $property;
  transform: $property;
}
.box { @include transform(rotate(30deg)); }
```

<h5>sass</h5>

```sass
=transform($property)
  -webkit-transform: $property
  -ms-transform: $property
  transform: $property
.box
  +transform(rotate(30deg))
```

<div align="center">
   <h1>
     ↓
   </h1>
</div>

```css
.box {
  -webkit-transform: rotate(30deg);
  -ms-transform: rotate(30deg);
  transform: rotate(30deg);
}

```

<h5>sass/scss</h5>

```sass
/* This CSS will print because %message-shared is extended. */
%message-shared
  border: 1px solid #ccc
  padding: 10px
  color: #333


// This CSS won't print because %equal-heights is never extended.
%equal-heights
  display: flex
  flex-wrap: wrap


.message
  @extend %message-shared
```

<div align="center">
   <h1>
    <a>Day</a>
    <a href="-" target="_blank">2</a>
   </h1>
   <h3>
     <div>
       <a href="">Starting</a> to study, I thought and decided that everyday I would devote <a href="">1-2 hours</a> to studying.
     </div>
   </h3>
   <h3 align="left">      ⠀⠀⠀⠀⠀⠀⠀⠀⠀
      <a href="-" target="_blank">-</a> Studied
   </h3>
   <h4 align="left">
      <div>            ⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
         <a href="-" target="_blank">SCSS</a>
      </div>
      <div>            ⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
         <p>            ⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
            I have studied scss so far, essentially the same css, but with improved application.
            <div>            ⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
               Tomorrow I will start studying a full-fledged sas, as I know a lot of useful chips open in sass.
            </div>
         </p>
      </h4>
   </div>

<h1 align="center">scss</h1>

<h5>scss</h5>

```scss
$font-stack: Helvetica, sans-serif;
$primary-color: #333;
$link: #15157d;
$link_bottom: $link;
$input_font_size: 13px;
$content_bg: #F1F1F1;
$input_color: #4E4D4D;
$input_color_placeholder: #959595;
$text_color: black;

body {
	font: 100% $font-stack;
	color: $primary-color;
}

a { color: $link; }
span.link {
  color: $link;
  text-decoration: underline; 
}

/* Nesting, as much as possible something new and unclear, but I will look and put it into practice. */

#some {
  border: 1px solid red;
  .some { background: white; }
}

/* => */

#some { border: 1px solid red; }
#some .some { background: white; }
```

<h3 align="center">The biggest <a href="-" target="_blank">difference</a> is that you don't have to put <a href="-" target="_blank">brackets</a>. <a href="-" target="_blank">I don't know</a> how it wzill <ahref="-" target="_blank">affect me</a>.</h3>

<h5>sass</h5>

```sass
body 
	font: 100% $font-stack
	color: $primary-color

```

<h3 align="center"><a href="-" target="_blank">Error</a></h3>

<h5>sass</h5>

```sass
body
	font: 100% $font-stack;
	color: $primary-color;
```

   <h3 align="center">
     <div>
       <a>I think I can still learn <a href="">gridbox</a>, I know <a href="">flexbox</a>.
     </div>
   </h3>


<div align="center">
      <h1>
         <a>Day</a>
         <a href="-" target="_blank">1</a>
      </h1>
      <h3>
       <div>
          Oddly enough, I'm <a href="-" target="_blank">studying</a> in college and now I'm going there
        </div>
        <div>
          I think <a href="-" target="_blank">today</a> I will make a plan and tell you what I want to achieve
        </div>
       </h3>
      <h3 align="left">      ⠀⠀⠀⠀⠀⠀⠀⠀⠀
         <a href="-" target="_blank">-</a> Skills I want to <a href="-" target="_blank">learn</a>
      </h3>
      <h4 align="left">
         <div>            ⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
            <a href="-" target="_blank">SASS</a>
         </div>
         <div>            ⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
            <a href="-" target="_blank">Git</a>
         </div>
         <div>            ⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
            Java<a href="-" target="_blank">Script</a>
         </div>
         <div>            ⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
            Type<a href="-" target="_blank">Script</a>
         </div>
         <div>            ⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
            <a href="-" target="_blank">React</a>
         </div>
      </h4>
      <h4>
         <a>
            I'm <a href="-" target="_blank">starting</a> not only to learn <a href="-" target="_blank">programming</a>, 
            but also <a href="-" target="_blank">physics</a>, so there will be thoughts not only about the <a href="-" target="_blank">code</a>
         </a>
         <div>
            I have a blank about the <a href="-" target="_blank">roadmap</a>, so <a href="-" target="_blank">
            I'm</a> thinking of making it and uploading it to my <a href="-" target="_blank">site</a>, there to make <a href="-" target="_blank">modal windows</a>
         </div>
      </h4>
      <h3>
         <a href="-" target="_blank">Site</a> - Here you can see
      </h3>
</div>
