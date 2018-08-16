<!DOCTYPE html>
<html>
<head>
  <title>1001</title>
  <link rel="stylesheet" type="text/css" href="rd.css">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <script type="javascript" src="rd.js"></script>
</head>
<body>

  <nav class="navbar navbar-expand-lg navbar-dark bg-primary">
    <a href="#"><img src="012.png" width="50px" height="90px"></a>&nbsp;&nbsp;&nbsp;
  <a  class="navbar-brand" href="#">1001</a>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarColor01" aria-controls="navbarColor01" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>

  <div class="collapse navbar-collapse" id="navbarColor01">
    <ul class="navbar-nav mr-auto">
      <li class="nav-item active">
        <a class="nav-link" href="#">Home <span class="sr-only">(current)</span></a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">Features</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">Pricing</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">About</a>
      </li>
    </ul>
    <form class="form-inline my-2 my-lg-0">
      <input class="form-control mr-sm-2" type="text" placeholder="Search">
      <button class="btn btn-secondary my-2 my-sm-0" type="submit">Search</button>
    </form>
  </div>
</nav>



<img id="img1" src="010.jpg">

<ul id="r1">
  <br>
  <li>1001 account</li><br>
  <li>1001 games</li><br>
  <li>1001 info</li><br>
  <li>1001 phone</li><br>
  <li>1001 aflam</li><br>


</ul>
<ul id="r2">
  <br>
  <li>Facebook</li><br>
  <li>instagram</li><br>
  <li>twitter</li><br>
  <li>...</li><br>
  <li>...</li><br>


</ul>



  <script type = "text/javascript">
            var image = document.getElementById("img1");
            var currentPos = 0;
            var images = ["010.jpg", "011.jpg", "010.jpg"]

            function volgendefoto() {
                if (++currentPos >= images.length)
                    currentPos = 0;

                image.src = images[currentPos];
            }

            setInterval(volgendefoto, 2000);
        </script>


</body>
</html>
