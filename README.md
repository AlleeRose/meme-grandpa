# meme-grandpa
<!DOCTYPE html>
<html>
<div id="meme">
  
      <img src="https://data.whicdn.com/images/59078898/original.jpg">

      <h1>Learn to code,</h1>       

      <h2>We've had enough, grandpa!</h2>

</div>
</html>
<head>
<link rel="stylesheet" type="text/css" href="mystyle.css">
  #meme {
        position: relative;
        margin: 50px auto;
        width: 600px;
      }

      h1, h2 {
        position:absolute;
        font-family: Impact;
        color: white;
        text-align: center;
        margin: 0 auto;
        width: 100%;
        text-shadow:
          -3px -3px 1px black, 3px -3px 1px black, -3px 3px 1px black, 3px 3px 1px black;
      }

      h1 {
        font-size: 48px;
        top: 245px;
      }

      h2 {
        font-size: 45px;
        bottom: 20px;
      }
      
      img {
        border: 10px solid white;
        box-shadow: 0px 3px 10px rgba(0,0,0,.8);
        margin: 0 auto;
        width: 100%;
      }
</head>
<script>
document.getElementById("demo").innerHTML = "My First JavaScript";
  var meme = $('#meme');

meme.on('click', function(){
  meme.fadeOut(2000);
  meme.fadeIn(2000);
                           })
</script>
