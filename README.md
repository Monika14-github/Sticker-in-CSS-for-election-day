# Sticker-in-CSS-for-election-day
....html......
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width">
    <title>repl.it</title>
    <link href="style.css" rel="stylesheet" type="text/css" />
    <title> Happy election day!</title>
  </head>
  <body>
    <script src="script.js"></script>
    <div class="sticker">
  <div class="sticker__top">
    <h1>Happy election day!-2021.</h1>
  </div>
  <div class="sticker__bottom">
  </div>
</div>
  </body>
</html>
.....css......
.sticker {
  background-image:url(https://tamil.cdn.zeenews.com/tamil/sites/default/files/2021/04/05/187495-election-2021.jpg);
  border: 20px solid white(255, 247, 247, 0.801);
  border-radius: 100%;
  color: rgb(51, 28, 28);
  display: flex;
  flex-flow: column;
  align-items: center;
  height: 590px;
  width: 590px;
}

/* Base Styles */
body {
  align-items: center;
  background-color: rgba(0, 0, 0, 0);
  display: flex;
  height: 150vh;
  justify-content: center;
}
