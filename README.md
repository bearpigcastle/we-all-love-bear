<html>
<head>
  <title>bear castle</title>
  <link href='bootstrap-3.3.7-dist/css/bootstrap.css' rel='stylesheet'> 

<meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1, user-scalable=no">
<style>
body {font-family: "Lato", sans-serif;}

/* Style the tab */
div.tab {
    overflow: hidden;
    border: 1px solid #ccc;
    background-color: #f1f1f1;
}

/* Style the buttons inside the tab */
div.tab button {
    background-color: inherit;
    float: left;
    border: none;
    outline: none;
    cursor: pointer;
    padding: 14px 16px;
    transition: 0.3s;
    font-size: 17px;
}

/* Change background color of buttons on hover */
div.tab button:hover {
    background-color: #ddd;
}

/* Create an active/current tablink class */
div.tab button.active {
    background-color: #ccc;
}

/* Style the tab content */
.tabcontent {
    display: none;
    padding: 6px 12px;
    border: 1px solid #ccc;
    border-top: none;
}
</style>

</head>


<body>

<div class='container'>
  
  <div class='jumbotron'>

    <h1>Welcome to bear castle</h1>



    <img src='images/polarb.jpg'>

    <div class="tab">
  <button class="tablinks" onclick="openCity(event, 'London')">London</button>
  <button class="tablinks" onclick="openCity(event, 'Paris')">Paris</button>
  <button class="tablinks" onclick="openCity(event, 'Tokyo')">Tokyo</button>
 </div>

 <div id="London" class="tabcontent">
  <h3>London</h3>
  <p>London is the capital city of England.</p>
 </div>

 <div id="Paris" class="tabcontent">
  <h3>Paris</h3>
  <p>Paris is the capital of France.</p> 
 </div>

 <div id="Tokyo" class="tabcontent">
  <h3>Tokyo</h3>
  <p>Tokyo is the capital of Japan.</p>
 </div>
</div> 
<script>
function openCity(evt, cityName) {
    var i, tabcontent, tablinks;
    tabcontent = document.getElementsByClassName("tabcontent");
    for (i = 0; i < tabcontent.length; i++) {
        tabcontent[i].style.display = "none";
    }
    tablinks = document.getElementsByClassName("tablinks");
    for (i = 0; i < tablinks.length; i++) {
        tablinks[i].className = tablinks[i].className.replace(" active", "");
    }
    document.getElementById(cityName).style.display = "block";
    evt.currentTarget.className += " active";
}
</script>





  <div id="buzz">
    <h2><small>The Buzz</small><br />What are people saying?</h2>
    
  <div class='row'>
    <div class='text-center col-lg-4'>
    <img class='img-circle' src='images/waddle.png' width="200" height="200">
      <p>Polar bears are so cute!</p>
      <small> --piggy</small>
    </div>
    
    <div class='row'>
  <div class='text-center col-lg-4'>
      <img class='img-circle' src='images/song.JPG' width="200" height="200">
      <p>we all love bear!</p>
      <small> `--little song</small>
    </div>
   
    <div class='row'>
  <div class='text-center col-lg-4'>
      <img class='img-circle' src='images/tu.JPG' width="200" height="200">
      <p>let's play together!</p>
      <small> --little Ground</small>
    </div> 
   </div>




  <div id="mission">
    <h2><small>Our mission</small><br />Join us in helping bears</h2>

    <p>we believe people loving bears are good people!</p>
    <p>let's do it together!</p>

    <div id='social-buttons'>
    <a class="btn-twitter" href="http://twitter.com">
      <button class="btn-twitter">Twitter</button>
      </a>
    <a class="btn-facebook" href="http://facebook.com">
      <button class="btn-facebook">Facebook</button>
      </a>
    <a class="btn-pinterest" href="https://uk.pinterest.com/">
      <button class="btn-pinterest">Pinterest</button>
      </a>
    </div>
  </div>
</div>



<!-- Sandwich from: © Kosoff | <a href="http://www.dreamstime.com/">Dreamstime Stock Photos</a> & <a href="http://www.stockfreeimages.com/">Stock Free Images</a> -->

