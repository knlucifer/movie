<!DOCTYPE html>
<html xmlns="http://www.w3.org/1999/xhtml">
<head>
<meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/css/bootstrap.min.css">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/js/bootstrap.min.js"></script>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
  <link rel="stylesheet" href="C:\Users\Karthikn\Downloads\moviehunter\css/style.css" type="text/css" media="all" />
<script type="text/javascript" src="C:\Users\Karthikn\Downloads\moviehunter\js/jquery-1.4.2.min.js"></script>
<script type="text/javascript" src="C:\Users\Karthikn\Downloads\moviehunter\js/jquery-func.js"></script>
<style >
  
.fa {
  padding: 20px;
  font-size: 30px;
  width: 70px;
  text-align: center;
  text-decoration: none;
  margin: 2px 55px;
  border-radius: 50%;
}
.fa-facebook {
  background: #3B5998;
  color: white;
}
.fa-google {
  background: #dd4b39;
  color: white;
}

.fa-twitter {
  background: #55ACEE;
  color: white;
}
.single-img img{
  width: 100%;
  height: 100%;

  transition: 1.5s;
}
.single-img:hover{
  transform: scale(1.1);
  z-index: 2;
  box-shadow: 0px 30px 100px #fff;
}
.single-img:hover img{
  opacity: 1s;
}


</style>



</head>
<body>


<nav class="navbar navbar-inverse">
  <div class="container-fluid">
    <div class="navbar-header">
      <a class="navbar-brand" href="#">KnFavors</a>
    </div>
    <ul class="nav navbar-nav">
      <li ><a href="https://www.netflix.com">Home</a></li>
      <li><a href="aboutus.html">about us</a></li>
      <li><a href="service.html">Services</a></li>
    </ul>
    <form class="navbar-form navbar-left" action="/action_page.php">
      <div class="input-group">
        <input type="text" class="form-control" placeholder="Search" name="search">
        <div class="input-group-btn">
          <button class="btn btn-default" type="submit">
            <i class="glyphicon glyphicon-search"></i>
          </button>
        </div>
      </div>
    </form>
     <ul class="nav navbar-nav navbar-right">
      <li><a href="#"data-toggle="modal" data-target="#myModal"><span class="glyphicon glyphicon-user"></span> Sign Up</a></li>
      <li><a href="index1.html"><span class="glyphicon glyphicon-log-in"></span> Login</a></li>
    </ul>
  </div>
</nav>

<!--slide starts here-->
<div class="container-fluid">

  <div id="myCarousel" class="carousel slide" data-ride="carousel">
    <!-- Indicators -->
    <ol class="carousel-indicators">
      <li data-target="#myCarousel" data-slide-to="0" class="active"></li>
      <li data-target="#myCarousel" data-slide-to="1"></li>
      <li data-target="#myCarousel" data-slide-to="2"></li>
    </ol>

    <!-- Wrapper for slides -->
    <div class="carousel-inner">
      <div class="item active">
        <img src="got.jpg" alt="Los Angeles" style="width:100%;">
      </div>

      <div class="item">
        <img src="luci.jpg" alt="Chicago" style="width:100%;">
      </div>

      <div class="item">
        <img src="st.jpg" alt="New york" style="width:100%;">
      </div>
    </div>

    <!-- Left and right controls -->
    <a class="left carousel-control" href="#myCarousel" data-slide="prev">
      <span class="glyphicon glyphicon-chevron-left"></span>
      <span class="sr-only">Previous</span>
    </a>
    <a class="right carousel-control" href="#myCarousel" data-slide="next">
      <span class="glyphicon glyphicon-chevron-right"></span>
      <span class="sr-only">Next</span>
    </a>
  </div>
</div>

<!--slide ends here-->

<!--movie start here-->
<center>
<div class="container">
 <div id="main">
    <div id="content">
      <div class="box">
        <div class="head">
          <h1>Most Popular</h1>
          <p class="text-right"><a href="https://www.imdb.com/list/ls095964455/">See all</a></p>
        </div>
        <div class="movie">
       
          <div class="movie-image"> 
          
            <div class="single-img">
           <a href="https://www.youtube.com/watch?v=X4bF_quwNtw"><img src="lucifer.jpg" /></a> 

         </div></div>
          <div class="rating">
            <p>RATING</p>
            <div class="stars">
              <div class="stars-in"> </div>
            </div>
            <span class="comments">12</span> </div>
        </div>
        <div class="movie">
          <div class="movie-image"> 

            <div class="single-img">
           <a href="https://www.youtube.com/watch?v=gcTkNV5Vg1E"><img src="got1.jpg" alt="" /></a> </div></div>
          <div class="rating">
            <p>RATING</p>
            <div class="stars">
              <div class="stars-in"> </div>
            </div>
            <span class="comments">18</span> </div>
        </div>
        <div class="movie">
          <div class="movie-image"> 
            <div class="single-img">
           <a href="https://www.youtube.com/watch?v=HhesaQXLuRY"><img src="bb.jpg" alt="" /></a> </div></div>
          <div class="rating">
            <p>RATING</p>
            <div class="stars">
              <div class="stars-in"> </div>
            </div>
            <span class="comments">5</span> </div>
        </div>
        <div class="movie">
          <div class="movie-image"> <div class="single-img"> <a href="https://www.youtube.com/watch?v=mnd7sFt5c3A"><img src="stranger things.png" alt="" /></a> </div></div>
          <div class="rating">
            <p>RATING</p>
            <div class="stars">
              <div class="stars-in"> </div>
            </div>
            <span class="comments">8</span> </div>
        </div>
        <div class="movie">
          <div class="movie-image"> <div class="single-img"> <a href="https://www.youtube.com/watch?v=BmVmhjjkN4E"><img src="tvd.jpg" alt="" /></a> </div></div>
          <div class="rating">
            <p>RATING</p>
            <div class="stars">
              <div class="stars-in"> </div>
            </div>
            <span class="comments">11</span> </div>
        </div>
        <div class="movie last">
          <div class="movie-image"> <div class="single-img"> <a href="https://www.youtube.com/watch?v=toj3CyMhBOs"><img src="13.jpg" alt="" /></a> </div></div>
          <div class="rating">
            <p>RATING</p>
            <div class="stars">
              <div class="stars-in"> </div>
            </div>
            <span class="comments">20</span> </div>
        </div>
        <div class="cl">&nbsp;</div>
      </div>
      <div class="box">
        <div class="head">
          <h1>Trending Now</h1>
          <p class="text-right"><a href="https://www.imdb.com/search/title/?title_type=tv_series">See all</a></p>
        </div>
        <div class="movie">
          <div class="movie-image"> <div class="single-img"> <a href="https://www.youtube.com/watch?v=T8rZHWgYpyA"><img src="19.jpg" alt="" /></a> </div></div>
          <div class="rating">
            <p>RATING</p>
            <div class="stars">
              <div class="stars-in"> </div>
            </div>
            <span class="comments">15</span> </div>
        </div>
        <div class="movie">
          <div class="movie-image"> <div class="single-img"> <a href="https://www.youtube.com/watch?v=4FC8krII948"><img src="ga.jfif" alt="" /></a> </div></div>
          <div class="rating">
            <p>RATING</p>
            <div class="stars">
              <div class="stars-in"> </div>
            </div>
            <span class="comments">4</span> </div>
        </div>
        <div class="movie">
          <div class="movie-image"> <div class="single-img"> <a href="https://www.youtube.com/watch?v=JWtnJjn6ng0"><img src="crown.jpg" alt="" /></a> </div></div>
          <div class="rating">
            <p>RATING</p>
            <div class="stars">
              <div class="stars-in"> </div>
            </div>
            <span class="comments">7</span> </div>
        </div>
        <div class="movie">
          <div class="movie-image"> <div class="single-img"> <a href="https://www.youtube.com/watch?v=xZCiyw1ZfB0"><img src="fargo.jpg" alt="" /></a> </div></div>
          <div class="rating">
            <p>RATING</p>
            <div class="stars">
              <div class="stars-in"> </div>
            </div>
            <span class="comments">9</span> </div>
        </div>
        <div class="movie">
          <div class="movie-image"> <div class="single-img"> <a href="https://www.youtube.com/watch?v=oVzVdvGIC7U"><img src="pb.jpg" alt="" /></a> </div></div>
          <div class="rating">
            <p>RATING</p>
            <div class="stars">
              <div class="stars-in"> </div>
            </div>
            <span class="comments">17</span> </div>
        </div>
        <div class="movie last">
          <div class="movie-image"><div class="single-img"> <a href="https://www.youtube.com/watch?v=0DAmWHxeoKw"><img src="ua.jpg" alt="" /></a> </div></div>
          <div class="rating">
            <p>RATING</p>
            <div class="stars">
              <div class="stars-in"> </div>
            </div>
            <span class="comments">13</span> </div>
        </div>
        <div class="cl">&nbsp;</div>
      </div>
      <div class="box">
        <div class="head">
          <h1>Returing this week</h1>
          <p class="text-right"><a href="https://editorial.rottentomatoes.com/article/tv-premiere-dates-2020/">See all</a></p>
        </div>
        <div class="movie">
          <div class="movie-image"> <div class="single-img"> <a href="https://www.youtube.com/watch?v=c0Aj6gG9lJM"><img src="all.jfif" alt="" /></a> </div></div>
          <div class="rating">
            <p>RATING</p>
            <div class="stars">
              <div class="stars-in"> </div>
            </div>
            <span class="comments">16</span> </div>
        </div>
        <div class="movie">
          <div class="movie-image"> <div class="single-img"> <a href="https://www.youtube.com/watch?v=_h3NFrBsJAM"><img src="fbi.jpg" alt="" /></a> </div></div>
          <div class="rating">
            <p>RATING</p>
            <div class="stars">
              <div class="stars-in"> </div>
            </div>
            <span class="comments">11</span> </div>
        </div>
        <div class="movie">
          <div class="movie-image"> <div class="single-img"> <a href="https://www.youtube.com/watch?v=ew5QcUf5mZE"><img src="fif.jpg" alt="" /></a> </div></div>
          <div class="rating">
            <p>RATING</p>
            <div class="stars">
              <div class="stars-in"> </div>
            </div>
            <span class="comments">12</span> </div>
        </div>
        <div class="movie">
          <div class="movie-image"> <div class="single-img"> <a href="https://www.youtube.com/watch?v=x0aB4nA5MOQ"><img src="million.jfif" alt="" /></a> </div></div>
          <div class="rating">
            <p>RATING</p>
            <div class="stars">
              <div class="stars-in"> </div>
            </div>
            <span class="comments">6</span> </div>
        </div>
        <div class="movie">
          <div class="movie-image"> <div class="single-img"> <a href="https://www.youtube.com/watch?v=a2rH5MhmyYA"><img src="ncis.jpg" alt="" /></a> </div></div>
          <div class="rating">
            <p>RATING</p>
            <div class="stars">
              <div class="stars-in"> </div>
            </div>
            <span class="comments">16</span> </div>
        </div>
        <div class="movie last">
          <div class="movie-image"> <div class="single-img"> <a href="#"><img src="sos.jpg" alt="" /></a> </div></div>
          <div class="rating">
            <p>RATING</p>
            <div class="stars">
              <div class="stars-in"> </div>
            </div>
            <span class="comments">8</span> </div>
        </div>
        <div class="cl">&nbsp;</div>
      </div>

    <div id="news">
      <div class="head">
        <h3>NEWS</h3>
        <p class="text-right"><a href="https://www.independent.co.uk/topic/netflix">See all</a></p>
      </div>
      <div class="content">
        <h4>The Crown</h4>
        <p>Season four of Netflix’s hit show The Crown launches on Sunday (15 November), and will introduce a host of new characters, including Gillian Anderson’s hugely anticipated turn as Margaret Thatcher. </p>
        <a href="https://www.independent.co.uk/arts-entertainment/netflix/the-crown/prince-philip-the-crown-queen-elizabeth-b1760470.html">Read more</a> </div>
      <div class="content">
        
        <h4>Where the Wild Things Are</h4>
        <p>Innovative director Spike Jonze collaborates with celebrated author Maurice Sendak to bring one of the most beloved books of all time to the big screen in &quot;Where the Wild Things Are,&quot;...</p>
        <a href="#">Read more</a> </div>
      <div class="content">
        
        <h4>The Box</h4>
        <p>Norma and Arthur Lewis are a suburban couple with a young child who receive an anonymous gift bearing fatal and irrevocable consequences.</p>
        <a href="#">Read more</a> </div>
    </div>
    <div id="coming">
      <div class="head">
        <h3>COMING SOON<strong>!</strong></h3>
        <p class="text-right"><a href="#">See all</a></p>
      </div>
      <div class="content">
        <h4>The Uncanny Counter </h4>
        <a href="https://www.netflix.com/in/title/81323551"><img src="uc.jpg" alt="" /></a>
        <p>Demon hunters pose as workers in a noodle shop in an effort to catch evil spirits hoping to find eternal life.</p>
        <a href="https://www.google.com/search?q=the+uncanny+counter&source=lmns&bih=530&biw=1280&rlz=1C1CHBF_enIN919IN919&hl=en&sa=X&ved=2ahUKEwiq3dP0sJrtAhWY_3MBHXZzDXUQ_AUoAHoECAEQAA">Read more</a> </div>
      <div class="cl">&nbsp;</div>
      <div class="content">
        <h4>Great Pretender, Season 2 </h4>
        <a href="https://www.thrillist.com/entertainment/nation/great-pretender-review-netflix-anime-series"><img src="gp.jpg" alt="" /></a>
        <p>In the second season of this con-man anime, even as Makoto tries to leave Laurent's nefarious team, he finds they're still connected in unexpected ways and keeps getting pulled back in for bold heist jobs..</p>
        <a href="#">Read more</a> </div>
    </div>
    <div class="cl">&nbsp;</div>
  </div>
  <div id="footer">
    <p class="lf">Copyright &copy; 2020 <a href="#">SiteName</a> - All Rights Reserved</p>
    <p class="rf">Design by <a href="#">Karthikeyan S</a></p>
    <div style="clear:both;"></div>
  </div>
</div>
 </center>
<!-- movie ends here-->



 <!--model starts here-->
 <div class="container">


  <!-- Modal -->
  <div class="modal fade" id="myModal" role="dialog" >
    <div class="modal-dialog modal-dialog-centered" >

      <!-- Modal content-->
      <div class="modal-content" >
        <div class="modal-header">
          <button type="button" class="close" data-dismiss="modal">&times;</button>
          <h4 class="modal-title">Sign up</h4>
        </div>
        <div class="modal-body">
          <div class="form-group" >
   <label for="usr">Username:</label>
    <input type="text" class="form-control" placeholder="Enter Username" id="usr">
   
  </div>
  <div class="form-group">
  <label for="pwd">Password:</label>
  <input type="password" class="form-control" placeholder="Enter password" id="pwd">
     </div>

  <div class="form-group">
   <label for="pwd">Repeat Password:</label>
   <input type="password" class="form-control" placeholder="Enter password" id="pwd">
  </div>
    <div class="form-group">
  <label for="pwd">Email</label>
  <input type="Email ID" class="form-control" placeholder="Enter Email" id="pwd">
      </div>
       <div class="form-group">
  
      <input type="submit"value="create account" class="btn btn-success btn-block"/></br>
        <center>
          <h4>Or</h4>
        </center>  
        <a href="https://www.facebook.com" class="fa fa-facebook"></a>
        <a href="https://www.google.com" class="fa fa-google"></a>     
         <a href="https://www.twitter.com" class="fa fa-twitter"></a>             
      </div>
        </div>
      </div>
    </div>
  </div>
</div>
</div>
<!--model ends here-->
</body>
</html>

