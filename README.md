
# HTML Comic Book Template

This is a simple (beta) HTML/CSS template for comic books. It includes a 12x12 grid, as well as classes for speech bubbles, text-box and a dedicated font. It is still in development. The (badly drawn) example is visible at <a href="http://mdaquin.me/hcbt/">mdaquin.me/hcbt/</a>.

## Basics

```HTML
<!DOCTYPE html>
<head>
  <meta charset="utf-8" />
  ... 
  <!-- include css -->
  <link rel="stylesheet" href="hcbt.css"> 
</head>

<body class="comic_book">

  <!-- page -->
  <div class="page">
    <!-- panel - page width, third of of height -->
    <div class="panel l12 h4">
      <!-- background image -->
      <img class="background_image" src="imgs/bookshelf.png">
      <!-- character -->
      <img class="object" style="bottom: 0%; left: 0%; height: 95%;" src="imgs/mathieu_c.png">
      <!-- speech buble, pointer bottom left -->
      <div class="bubble southwestwest" style="top: 10%; left: 30%; width: 30%;">Hi, I'm Mathieu, and I would like to tell you about HTML Comic Book Template.</div>      
      <!-- text-box -->
      <div class="text_box" style="right: 5%; bottom: 5%;">Galway, Ireland, 2020</div>
    </div>
    <div class="panel l6 h4">
    ...
```