<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Stoplicht</title>
<style>
  .container {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
  }

  .light {
    width: 100px;
    height: 300px;
    border: 2px solid black;
    border-radius: 10px;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    align-items: center;
  }

  .light div {
    width: 80px;
    height: 80px;
    border-radius: 50%;
  }

  .red {
    background-color: red;
  }

  .yellow {
    background-color: yellow;
  }

  .green {
    background-color: green;
  }
</style>
</head>
<body>

<div class="container">
  <div class="light">
    <div class="red"></div>
    <div class="yellow"></div>
    <div class="green"></div>
  </div>
</div>

</body>
</html>
