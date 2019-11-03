<!DOCTYPE html>
<html lang="pl">
  <head> 
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">
    <link rel="stylesheet" href="stylew.css" type="text/css"/>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <link href="https://fonts.googleapis.com/css?family=Pacifico|Satisfy&display=swap" rel="stylesheet">
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
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js" integrity="sha384-JjSmVgyd0p3pXB1rRibZUAYoIIy6OrQ6VrjIEaFf/nJGzIxFDsf4x0xIM+B07jRM" crossorigin="anonymous"></script>
</body>


</html>

