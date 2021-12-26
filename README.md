# html-food-web-site
using basic html , I have created Restaurant website a front design
<!DOCTYPE html>
<html>
<head>
<style>
.item1 {
  grid-area: myArea;
}

.grid-container {
  display: grid;
  grid-template-areas: 'myArea myArea myArea myArea myArea';
  grid-gap: 10px;
  background-color:wheat;
  padding: 10px;
}

.grid-container > div {
  background-color: rgba(255, 255, 255, 0.8);
  text-align: center;
  padding: 20px 0;
  font-size: 30px;
}    
* {
  box-sizing: border-box;
}

body {
  font-family: Arial;
  padding: 10px;
  background: rgb(54, 37, 41);
}

/* Header/Blog Title */
.header {
  padding: 30px;
  text-align: center;
  background: tomato;
  

}
.header h1 {
  font-size: 75px;
  font-family: Georgia, 'Times New Roman', Times, serif;
}
.header p {
  font-size: 30px;
  font-family:Gabriola;
}

/* Style the top navigation bar */
.topnav {
  overflow: hidden;
  background-color: #333;
}

/* Style the topnav links */
.topnav a {
  float: left;
  display: block;
  color: #f2f2f2;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
}

/* Change color on hover */
.topnav a:hover {
  background-color:steelblue;
  color: black;
}

/* Create two unequal columns that floats next to each other */
/* Left column */
.leftcolumn {   
  float: left;
  width: 75%;
}

/* Right column */
.rightcolumn {
  float: left;
  width: 25%;
  background-color: #f1f1f1;
  padding-left: 20px;
}

/* Fake image */
.fakeimg {
  background-color: #aaa;
  width: 100%;
  padding: 20px;
}

/* Add a card effect for articles */
.card {
  background-color:wheat;
  padding: 20px;
  margin-top: 20px;
}

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}

/* Footer */
.footer {
  padding: 20px;
  text-align: center;
  background: #ddd;
  margin-top: 20px;
}

/* Responsive layout - when the screen is less than 800px wide, make the two columns stack on top of each other instead of next to each other */
@media screen and (max-width: 800px) {
  .leftcolumn, .rightcolumn {   
    width: 100%;
    padding: 0;
  }
}

/* Responsive layout - when the screen is less than 400px wide, make the navigation links stack on top of each other instead of next to each other */
@media screen and (max-width: 400px) {
  .topnav a {
    float: none;
    width: 100%;
  }
}
</style>
</head>
<body>

<style>
  .city {
    background-color: rgb(189, 152, 143);
    color: white;
    border: 2px solid black;
    margin: 20px;
    padding: 20px;
  }
</style>

<body>

<div class="city">
<center><h1>yakesh coffee</h1></center>
</div>
<div class="topnav">
  <a href="#1">Home</a>
  <a href="#2">Menu</a>
  <a href="#3">Online orders</a>
  <a href="#5">Contact us</a>
  <a href="#" style="float:right"></a>
</div>

<img src="https://imagesvc.meredithcorp.io/v3/mm/image?q=85&c=sc&poi=face&w=960&h=480&url=https%3A%2F%2Fstatic.onecms.io%2Fwp-content%2Fuploads%2Fsites%2F44%2F2019%2F03%2F27113256%2Fcoffee_960.jpg" alt="https://www.eatingwell.com/article/41595/9-rules-for-how-to-make-a-perfect-cup-of-coffee/" style="width:100%">


<div class="row">
  <div class="leftcolumn">
    <div class="card" id="1">
      <center> <h1 style="font-family:Georgia, 'Times New Roman', Times, serif ; color: navy;">The Land of Spices</h1></center>
      <h5 style="font-family: 'Times New Roman', Times, serif; color: violet; font-size: large;">The Essence of Delicious India</h5>
      <div> <img src="https://3.imimg.com/data3/RX/TS/GLADMIN-3907/coffee-500x500.jpg" height="200" width="400"> <img src="https://upload.wikimedia.org/wikipedia/commons/4/45/A_small_cup_of_coffee.JPG" height="200" width="500"> <img src="https://post.healthline.com/wp-content/uploads/2020/08/ways-to-make-coffee-super-healthy-1200x628-facebook-1200x628.jpg" height="200" width="400"> <img src="https://www.liquor.com/thmb/Ce0SvKbrZKRlM7M9EAy-LkorTxE=/735x0/__opt__aboutcom__coeus__resources__content_migration__liquor__2017__02__22140200__irish-coffee-720x720-recipe1-b1ddbe38da014bdb9c21cb2b6fcc629f.jpg" height="200" width="500"></div>
      <p style="font-family: Georgia, 'Times New Roman', Times, serif; color: red;">Nothing is better than going home to family and eating good food and relaxing.<br> WE make you feel like HOME !!!</p>
    </div>
    <div class="card">
        <center> <h1 style="font-family:Georgia, 'Times New Roman', Times, serif ; color:orangered" i="2">The house of spices</h1></center> 
        <h5 style="font-family: 'Times New Roman', Times, serif; color:seagreen; font-size: large;">The pleasure of variety on your plate</h5>
        <div> <img src="https://www.worldtopupdates.com/wp-content/uploads/2017/06/imagea.jpg" height="200" width="400"> <img src="https://res.cloudinary.com/purnesh/image/upload/w_1080,f_auto/unlimited-south-indian-meals.jpg" height="200" width="=500"> <img src="https://media.timeout.com/images/105444023/630/472/image.jpg" height="200" width="400"> </div>
        <p style="font-family: Georgia, 'Times New Roman', Times, serif; color: red;">If you’re in a hurry, eat our curry.<br> WE make you feel like HOME !!!</p>
      </div>
    <div class="card">
        <center> <h2>One thousand flavors in one place.</h2></center> 
      <h5></h5>
      <div><img src="https://previews.123rf.com/images/dash/dash1903/dash190300223/119332960-assorted-indian-various-food-with-spices-rice-and-fresh-vegetables-on-white-wooden-table-flat-lay-to.jpg" height="500" width="600"> <img src="https://www.youngisthan.in/wp-content/uploads/2021/03/5cbc5ded512c0c3e8b6c782d_1555848685957-970x1213.jpg" height="500" width="600"> </div>
      <p>The Essence of Delicious India.</p></div>
  </div>
  <div class="rightcolumn">
    <div class="card">
      <h2>Our special </h2>
      <div><img src="https://i.ytimg.com/vi/b4pjSmwAdTw/maxresdefault.jpg" height="220" width="400"></div>
    
    </div>
    <div class="card">
      <h3>Most popular dessert's</h3>
      <div><img src="https://akm-img-a-in.tosshub.com/indiatoday/images/story/201610/sweets_story_647_102416112934.jpg" height="150" width="170"></div>
      <div><img src="https://hirasweets.com/wp-content/uploads/2019/07/History_of_Iconic_Indian_Sweets-1.jpg" height="150" width="170"></div>
      <div><img src="https://escapingsoul.in/wp-content/uploads/2020/09/Potharekulu.jpg" height="150" width="170"></div>
      <div><img src="https://1.bp.blogspot.com/-6jxCZV-NhXA/X5bsXbgBsaI/AAAAAAAAY8o/IrKygNbvCOIh5i6ArUImO9CJcMplxj98gCLcBGAsYHQ/s2048/pineapple%2Bhalwa%2B7.JPG" height="150" width="170"></div>
      <div><img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT6kZbohHw3YH7h7LfphwA7C3IaCC7r97OI8zFrTCzfRS3yl-HnoBc3MZtvkvKrlulOglw&usqp=CAU" height="150" width="170"></div>
    </div>
    <div class="card">
      <h3 id="5">contact us </h3>
      <p>Yakesh Restaurant<br>Sathy - Bhavani State Highway<br>Alathukombai Post<br> Sathyamangalam<br> Tamil Nadu 638401<br> landmark: <br>opposite to Bannari Amman Institute of Technology</p>
    </div>
  </div>
  
</div>

<div class="grid-container">
    <div class="item1" id="2">Menu</div>
    <div class="item2">All Time Favourite<br><br> 
        French Fries	106/-<br>
        Chilli Cheese Toast 	115/-<br>
        Chilli Cheese Gralic Toast 	115/-<br>
        Garlic Bread	98/-<br>
        Garlic Bread with Cheese	119/-<br></div>
    <div class="item3">Rice / Pulao / Biryanis / Raitas<br><br>
        Steam Rice	161/-<br>
        Soya Dum Biryani 	220/-<br>
        Veg. Pulao	161/-<br>
        Mix Veg. Pulao	161/-<br>
        Jeera Pulao	161/-<br>
        Matka Biryani With Raita 	220/-<br>
        Hyderabadi Biryani 	220/-<br>
        Plain Raita	102/-<br>
        Boondi Raita	102/-<br>
        Mix. Veg. Raita	102/-<br>
        Jeera Raita	102/-<br>
        Pineapple Raita	102/-<br></div>  
    <div class="item4">Tea & Coffee	 <br><br>
        Tea	40/-<br>
        Coffee Mocachino	51/-<br>
        Coffee Americano (Black)	55/-<br>
        Coffee Espresso	60/-<br>
        Ice Tea (Lemon)	51/-<br>
        Coffee Cappuccino	51/-<br>
        Espresso (Black)	55/-<br>
        Cold-Coffee (Frappe)	70/-<br></div>
    <div class="item5">Chats<br><br>	 
        Dahi Bhalla / Dahi Papri	90/-<br>
        Dahi Bhalla Papri	90/-<br>
        Gol Gappa (6 pcs.)	68/-<br>
        Gol Gappa Water Extra For Packing 25/-<br></div>
  </div>
  <details style="text-align: center;" id="3">
    <summary><b>Online order</b></summary>
    <p>Online order is available 24/7<a href="https://www.zomato.com/kingman-ks">View details</a></p>
  </details>
  

<div class="footer">
  <h2><footer class="py-4 bg-light mt-auto">
    <div class="container-fluid px-4">
        <div class="d-flex align-items-center justify-content-between small">
            <div class="text-muted">Copyright &copy; Your Website 2021</div>
            <div>
                <a href="https://tripadvisor.mediaroom.com/in-privacy-policy">Privacy Policy</a>
                
            </div>
        </div>
    </div>
</footer></h2>
</div>

</body>
</html>
