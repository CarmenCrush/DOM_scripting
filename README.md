# DOM_scripting
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8" />
    <title>Image Gallery</title>
  </head>
  <body>
    <h1>Snapshots</h1>
    <ul>
      <li>
        <a href="https://pbs.twimg.com/media/DtD7PBaXcAA60zj.jpg" onclick="showPic(this);
      return false;" title="Carmen's Feet Make YOU Lose Your Paycheck"> Pay To See These Sweet Feets!</a>
      </li>
      <li>
        <a href="https://pbs.twimg.com/media/DsO7ctWVYAAdFgg.jpg" onclick="showPic(this);
      return false;" title="Carmen's Juicy Booty."> A Real Georgia Peach.</a>
      </li>
      <li>
        <a href="https://pbs.twimg.com/media/DoO8T3AU4AArOye.jpg" onclick="showPic(this);
      return false;" title="Carmen's Sweet, Sweet Face."> The Means to My Brain.</a>
      </li>
    </ul>
    <img id="placeholder" src="https://tinyurl.com/yb9rwvqn" alt="my image gallery" />
    </h1>
  </body>
</html>
// JavaScript code

function showPic(whichpic) {
var source = whichpic.getAttribute("href");
var placeholder = document.getElementByID("placeholder");
placeholder.setAttribute("src", source);
}
var text = whichpic.getAttribute("title");
var body_element = document.getElementsByTagName("body")[0];
body_element.childNodes.length;

function countBodyChildren() {
var body_element = document.getElementsByTagName("body")[0];
alert (body_element.childNodes.length);
}
window.onload = countBodyChildren;
