Massively by HTML5 UP
html5up.net | @ajlkn
Free for personal and commercial use under the CCA 3.0 license (html5up.net/license)

This is Massively, a text-heavy, article-oriented design built around a huge background
image (with a new parallax implementation I'm testing) and scroll effects (powered by
Scrollex). A *slight* departure from all the one-pagers I've been doing lately, but one
that fulfills a few user requests and makes use of some new techniques I've been wanting
to try out. Enjoy it :)

Demo images* courtesy of Unsplash, a radtastic collection of CC0 (public domain) images
you can use for pretty much whatever.

(* = not included)

AJ
<aj@lkn.io> | @ajlkn

Credits:

 Demo Images:
  Unsplash (unsplash.com)

 Icons:
  Font Awesome (fontawesome.io)

 Other:
  jQuery (jquery.com)
  Scrollex (github.com/ajlkn/jquery.scrollex)
  Responsive Tools (github.com/ajlkn/responsive-tools)zz

---

###### Dito isso

# Olhe que bacana

* O uso do header não só em um cabeçalho no topo do site.
* O conteúdo que esrá no main.css
* mixins???

```css
 .row {
  display: flex;
  flex-wrap: wrap;
  box-sizing: border-box;
  align-items: stretch;
 }

  .row > * {
   box-sizing: border-box;
  }

  .row.gtr-uniform > * > :last-child {
   margin-bottom: 0;
  }

  .row.aln-left {
   justify-content: flex-start;
  }

  .row.aln-center {
   justify-content: center;
  }

  .row.aln-right {
   justify-content: flex-end;
  }

  .row.aln-top {
   align-items: flex-start;
  }

  .row.aln-middle {
   align-items: center;
  }

  .row.aln-bottom {
   align-items: flex-end;
  }

  .row > .imp {
   order: -1;
  }

  .row > .col-1 {
   width: 8.33333%;
  }

  .row > .off-1 {
   margin-left: 8.33333%;
  }

  .row > .col-2 {
   width: 16.66667%;
  }

  .row > .off-2 {
   margin-left: 16.66667%;
  }

  .row > .col-3 {
   width: 25%;
  }

  .row > .off-3 {
   margin-left: 25%;
  }

  .row > .col-4 {
   width: 33.33333%;
  }

  .row > .off-4 {
   margin-left: 33.33333%;
  }

  .row > .col-5 {
   width: 41.66667%;
  }

  .row > .off-5 {
   margin-left: 41.66667%;
  }

  .row > .col-6 {
   width: 50%;
  }

  .row > .off-6 {
   margin-left: 50%;
  }

  .row > .col-7 {
   width: 58.33333%;
  }

  .row > .off-7 {
   margin-left: 58.33333%;
  }

  .row > .col-8 {
   width: 66.66667%;
  }

  .row > .off-8 {
   margin-left: 66.66667%;
  }

  .row > .col-9 {
   width: 75%;
  }

  .row > .off-9 {
   margin-left: 75%;
  }

  .row > .col-10 {
   width: 83.33333%;
  }
```

* Exemplos de variáveis, mas aqui com scss

```scss
// Misc.
 $misc: (
  z-index-base:  10000
 );

// Duration.
 $duration: (
  menu:    0.5s,
  transition:   0.2s
 );

// Size.
 $size: (
  element-height:  3rem,
  element-margin:  2rem,
  padding:   2rem,
  wrapper:   72rem
 );

// Font.
 $font: (
  family:    ('Merriweather', Georgia, serif),
  family-heading:  ('Source Sans Pro', Helvetica, sans-serif),
  family-fixed:  ('Courier New', monospace),
  weight:    300,
  weight-bold:  600,
  weight-heading:  900
 );

// Palette.
 $palette: (
  wrapper-bg:   #212931,

  bg:     #ffffff,
  fg:     #212931,
  fg-bold:   #212931,
  fg-light:   mix(#212931, #ffffff, 50%),
  border:    mix(#dcdcdc, #ffffff, 50%),
  border-bg:   rgba(#dcdcdc, 0.25),
  accent:    #18bfef,

  alt: (
   bg:    #f5f5f5,
   fg:    #717981,
   fg-bold:  #717981,
   fg-light:  mix(#717981, #f5f5f5, 50%),
   border:   mix(#dcdcdc, #f5f5f5, 75%),
   border-bg:  rgba(#dcdcdc, 0.5),
   accent:   #18bfef,
  ),

  invert: (
   bg:    #1e252d,
   bg-alt:   #1e252d,
   fg:    #ffffff,
   fg-bold:  #ffffff,
   fg-light:  rgba(#ffffff, 0.5),
   border:   #ffffff,
   border-bg:  rgba(#ffffff,0.075),
   accent:   #18bfef,
  ),
 );
```
