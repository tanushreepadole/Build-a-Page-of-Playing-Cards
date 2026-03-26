# Build-a-Page-of-Playing-Cards

#playing-cards{
  display:flex;
 justify-content: center; 
  flex-wrap: wrap;         
  gap: 20px;    
  
}

.card{
   justify-content:space-between;
   display:flex;
   border:50px;
   margin:10px;
   padding:10px;
   border: 2px solid black;
   height:180px;
   width:100px;
    box-shadow: 2px 2px 10px gray;
   border-radius:5px;

   

.left{
  align-self: flex-start;

}

.right{
  align-self: flex-end;
}

.middle{
  align-self: center;
  display: flex;
  flex-direction: column;
}


<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Playing Cards</title>
<link rel="stylesheet" href="styles.css">
</head>

<body>
<main id="playing-cards">
  <div class="card">
    <div class="left">♠</div>
    <div class="middle">A</div>
    <div class="right">♠</div>
  </div>

  <div class="card">
    <div class="left">♥</div>
    <div class="middle">K</div>
    <div class="right">♥</div>
  </div>

  <div class="card">
    <div class="left">♦</div>
    <div class="middle">Q</div>
    <div class="right">♦</div>
  </div>

 
  </main>
</body>

</html>
