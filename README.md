<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Box model</title>
  <style>
    *{
      background-color: hot pink ;
      margin: 0px;
      padding: 0px;
      width: fit-content;
      height: fit-content;
    }
    .container{
      margin:10px;
      border: 5px solid red;
    }
    .multibox{
      margin: 40px;
      width: auto;
      display: flex;
      flex-direction: row;
      justify-content: space-around;
      flex-flow: wrap;
    }

    .box1{
      padding: 10px;
      text-align: center;
      border: 5px solid rgb(0, 255, 170);
      width: 85%;
      height: 300px;
      background: yellowgreen;
      margin: 20px;
      box-sizing: border-box;
      font-size: 50px;
    }
    .box2{
      padding: 10px;
      text-align: center;
      border: 5px solid yellowgreen;
      width: 85%;
      height: 300px;
      background: bpg(16, 237, 163);  
      margin: 20px;
      box-sizing: border-box;
      font-size: 50px;
    }
    .box3{
      padding: 10px;
      text-align: center;
      border: 5px solid rgb(248, 25, 25);
      width: 85%;
      height: 300px;
      background: rgb(49, 132, 234);
      margin: 20px;
      box-sizing: border-box;
      font-size: 50px;
    }
    .box4{
      padding: 10px;
      text-align: center;
      border: 5px solid rgb(49, 132, 234);
      width: 85%;
      height: 300px;
      background: rgg(248, 25, 25);
      margin: 20px;
      box-sizing: border-box;
      font-size: 50px;
    }
    .main{
      border: 5px solid aqua;
      text-align: justify;
      padding: 20px;
      width: auto;
      height: auto;
      background: skyblue ;
      margin: 50px;
      box-sizing: border-box;
      font-size: 40px;
    }
  </style>
</head>
<body>
  <div class="container">
  <div class="main">Hi Myself MOHAMMAD Ali . I’m a Web Developer & Designer
    Lorem ipsum dolor sit amet, consectetur adipisicing elit. Expedita natus ad sed harum itaque ullam enim quas, veniam accusantium, quia animi id eos adipisci iusto molestias asperiores explicabo cum vero atque amet corporis! Soluta illum facere consequuntur magni. Ullam dolorem repudiandae cumque voluptate consequatur consectetur, eos provident necessitatibus reiciendis corrupti!</div>
    <div class="multibox">
    <div class="box1">MOHAMMAD Ali </div>
    <div class="box2">MOHAMMAD Ali</div>
    <div class="box3">MOHAMMAD ALI </div>
    <div class="box4">MOHAMMAD Ali
  </div>
  </div>
</div>
</body>
</html>
