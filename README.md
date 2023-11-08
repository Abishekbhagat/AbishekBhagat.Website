![john01](https://github.com/Abishekbhagat/AbishekBhagat.Website/assets/149918431/da792cec-8cc2-4311-89cd-9ad8dd88ccc1)
![h](https://github.com/Abishekbhagat/AbishekBhagat.Website/assets/149918431/f9423479-ea40-45e2-a091-83785c948297)
<!DOCTYPE html>
<html lang="en">
<head>
   <meta charset="UTF-8">
   <meta http-equiv="X-UA-Compatible" content="IE=edge">
   <meta name="viewport" content="width=device-width, initial-scale=1.0">
   <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.2.0/css/all.min.css">
   <link rel="stylesheet" href="style.css">
   <title>Login Form</title>
</head>
<body>
   <div class="movie-container">
      <div class="title">John Wick</div>
      <h3>Chapter 4</h3>
      <div class="dis">
         <p>John Wick: Chapter 4 is fast approaching. Well only need to wait <br> until 24th March 2023, to see Baba Yaga back in action.
            So what better time to start <br> looking at what the new movie could bring. Heres everything we know so far.Oh, <br>
             and for those yet to the see the series, there are some spoilers,<br>
             so please dont read on if you dont want to know!</p>
             <br>
             <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit.<br>
               Officia quae dolores veritatis dignissimos earum perspiciatis.<br> eveniet, nihil nemo voluptatem ratione.</p>
      </div>
      <button>Watch Now</button>
      <img src="images/john01.jpg" alt="">
   </div>
</body>
</html>

*{
   margin: 0;
   padding: 0;
   box-sizing: border-box;
}
body{
   display: flex;
   justify-content: center;
   align-items: center;
   height: 100vh;
   background-image: url(images/h.jpeg);
   background-size: cover;
}

.movie-container{
   width: 80%;
   height: auto;
   border: 5px solid rgba(255, 255, 255, 0.4);
   position: relative;
   overflow: hidden;
   background: transparent;
   backdrop-filter: blur(50px);
   box-shadow: 0 50px 55px -10px #000;
}
img{
   float: right;
}
.title{
   position: absolute;
   color: #fff;
   padding: 50px 80px;
   font-size: 125px;
   font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
   text-transform: uppercase;
   letter-spacing: 10px;
}
h3{
   position: absolute;
   font-size: 40px;
   font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
   text-transform: uppercase;
   letter-spacing: 56px;
   color:#fff;
   top: 180px;
   left: 100px;
}
.dis{
   position: absolute;
   color: #fff;
   top: 220px;
   padding: 80px 80px;
   font-size: 18px;
}
button{
   position: absolute;
   top: 70%;
   left: 5%;
   padding: 20px 70px;
   font-size: 30px;
   border-radius: 0px;
   border: 2px solid #fff;
   background: none;
   background-size: 100% 100%;
   color: #f1f1f1;
   text-transform: uppercase;
   letter-spacing: 5px;
   font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
}
button:hover{
   color: #000;
   background:#fff;
}

