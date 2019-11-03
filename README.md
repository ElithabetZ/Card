
<html lang="pl">
  <head> 
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    <link rel="stylesheet" href="stylew.css" type="text/css"/>
    <link rel="stylesheet" href="css/bootstrap.min.css"/>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <link href="https://fonts.googleapis.com/css?family=Pacifico|Satisfy&display=swap" rel="stylesheet">
    <style>.container{
    display: grid;
    grid-template-columns: repeat(12, 1ft);
    grid-template-rows: 30px 800px 60px 350px 60px auto 60px auto;
  }
  
  header{
    grid-column: span 12;
  }
  .pic{
    grid-column: span 12;
  }
  .me{
    grid-column: span 12; 
  }
  aside{
    grid-column: span 5;
  }
  main{
    grid-column: span 7;
  }
  .portfolio{
    grid-column: span 12;    
  }
  .port{
    grid-column: span 12;
  }
  .ankieta{
    grid-column: span 12;
  }
  .ank{
    grid-column: span 12;
  }
  
  header{
    
    font-family: 'Pacifico', cursive;
    color: rgb(128, 85, 156);
    font-size: 20px;
  }
 
  body{
    background-image: linear-gradient(rgb(235, 217, 217) 100px,rgb(93, 93, 199) 2000px);
  }
  .fa-facebook{
    transition: all 0.2s ease-in-out;
  }
  .fa-facebook:hover {
    opacity: 0.7;
    color: rgb(70, 36, 92);
    text-decoration: none;
  }
  .fa-twitter{
    transition: all 0.2s ease-in-out;
  }
  .fa-twitter:hover {
    opacity: 0.7;
    color: rgb(70, 36, 92);
    text-decoration: none;
  }
  .fa-instagram{
    transition: all 0.2s ease-in-out;
  }
  .fa-instagram:hover {
    opacity: 0.7;
    color: rgb(70, 36, 92);
    text-decoration: none;
  }
  .fa-pinterest{
    transition: all 0.2s ease-in-out;
  }
  .fa-pinterest:hover {
    opacity: 0.7;
    color: rgb(70, 36, 92);
    text-decoration: none;
  }
  .fa{
    text-decoration: none;
    width: 17%;
    color:rgb(70, 36, 92)
  
  }
  
  .pic{
    background: url(2back.jpg) no-repeat 0% 30%/ cover padding-box border-box;
    font-family: 'Pacifico', cursive;
    display: flex;
    justify-content: center;
    align-items: center;
    font-size: 50px;
    color: rgb(153, 97, 190);
    text-align: center;
  }
  figure{
      display: flex;
  }
 #cv{
     border-radius: 79%;
     position: relative;
     height: 280px;
     top: 15px;
     left: 90px;
     border-left: 5px solid rgb(137, 100, 146);
 }
 .me{
    font-family: 'Pacifico', cursive;
    color: rgb(128, 85, 156);
    font-size: 40px;
    text-align: center;
    
 }
 aside{
    position: relative;
     border-right: 8px solid rgb(71, 29, 95); 
     border-left: 0px;
     border-top: 0px;
     border-bottom: 0px;
     border-style: dotted;
 }
 .portfolio{
    font-family: 'Pacifico', cursive;
    color: rgb(128, 85, 156);
    font-size: 40px;
    text-align: center;
 }
.ankieta{
    font-family: 'Pacifico', cursive;
    color: rgb(65, 30, 88);
    font-size: 40px;
    text-align: center;
}
.img-fluid{
  transition: all 0.2s ease-in-out;
}
.img-fluid:hover{
transform: scale(1.1);  
opacity: 0.9;
}
label{
  font-family: 'Pacifico', cursive;
  color: rgb(65, 30, 88);
}
.ank{
  display: flex;
  justify-content: center;
}
input{
  background-color: rgb(205, 183, 226);
}
textarea{
  background-color: rgb(205, 183, 226);
}
p{ font-family: 'Pacifico', cursive;
  color: rgb(65, 30, 88);
  text-align: center;

}
main{
  font-family: 'Pacifico', cursive;

} </style>
    <script type="text/javascript" src="clock.js"></script>
    <script type="text/javascript" src="data.js"></script>
</head>

<body  onload="obliczanie(); obliczanie2();">
  <div class="container">
<Header class="row">
  <div class="col-4">
    <div id="data">
      <script type="text/javascript"></script>
      </div>
  </div>
  <div class="col-4">
    <div id="clock"> 
  <script type="text/javascript"></script>
</div>
 </div>
  <div class="col-4">
    <p class="media">My media:</p> 
    <a href="https://www.instagram.com/elithabetz/" class="fa fa-instagram" target="_blank" ></a>
    <a href="https://www.facebook.com/elithabet.zyshchuk" class="fa fa-facebook" target="_blank" ></a>
    <a href="https://twitter.com/" class="fa fa-twitter" target="_blank" ></a>
    <a href="https://www.pinterest.com/" class="fa fa-pinterest" target="_blank" ></a>
  </div>
</Header>
<div class="pic">Hello <br> My name is Eli </div>

<div class="me">About myself</div>
<aside > <img id="cv" class="img-fluid" src="CV.jpg"  /> </aside>
<main >Let me introduce myself. My full name is Elithabet Zyshchuk. I was born on November, 23, 1999 in Brest.<br><br>
   I’m interested in computer science, music, sport and crime fiction.<br><br>
   I have always been good at sports. I like playing volleyball, basketball and many more. <br><br>
  I love crime fiction. I read criminal books and magazines, watch criminal films and play role playing games such as "Mafia". <br><br>
  My dream is to study computer science and to go to Japan. I love everything associated with this country. I hope that in the future, I will learn Japanise. I want to go to Japan and stay there for a long time. I want to get a job there as a computer scientist. </main>

<div class="portfolio">Portfolio</div>
<div class="port">
<div class="row">
 <div class="col-sm-6 col-xl-4"> 
  <figure>
    <img src="port1.jpg" class="img-fluid"/>
  </figure>   
  <p>New Year in Wrocław</p>  
 </div>
 <div class="col-sm-6 col-xl-4"> 
    <figure>
        <img src="port2.jpg" class="img-fluid" />
    </figure>   
    <p>Beautiful flowers near my house</p>  
 </div>
 <div class="col-sm-6 col-xl-4"> 
    <figure>
         <img src="port3.jpg" class="img-fluid"/>
    </figure> 
    <p>Winter in Globin</p>    
 </div>
 <div class="col-sm-6 col-xl-4"> 
    <figure>
         <img src="port4.jpg" class="img-fluid"/>
    </figure>    
    <p>Magnificent sunset in Mietków</p> 
 </div>                
 <div class="col-sm-6 col-xl-4"> 
    <figure>
        <img src="port5.jpg" class="img-fluid"/>
    </figure>     
    <p>Chamomile after rain</p>
 </div>
 <div class="col-sm-6 col-xl-4"> 
    <figure>
        <img src="port6.jpg" class="img-fluid"/>
    </figure>   
    <p>Summer in Lloret de Mar</p>  
 </div>
 

 </div>
 </div>

<div class="ankieta">Ask me<br> </div>

<div class="ank">
<div class="row">
  <form action="Wizetowka.html" method="POST">
    <div class="col-6">
    <label>Name and Surname</label> 
 <input name="nazwisko" id="nazwisko">
</div>
<div class="col-6">
 <label>E-mail</label>
 <input name="email" type="email" id="email">
</div>
<div class="col-6">
 <label>Message</label>
 <textarea name="wiadomosc" placeholder="Ask your questions" cols="50" rows="3"></textarea>
</div>
<div class="col-6">
 <input type="submit" name="wyslij" id="submit" value="Sent">  
</div>
 </form>
</div>
</div>

</div>
<script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js" integrity="sha384-UO2eT0CpHqdSJQ6hJty5KVphtPhzWj9WO1clHTMGa3JDZwrnQq4sF86dIHNDz0W1" crossorigin="anonymous"></script>
<script src="js/bootstrap.min.js"></script>
</body>


</html>
