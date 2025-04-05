<!DOCTYPE html>
<html>
<head>
<title>時間経過の視覚化</title>
<style>
  .circle {
    width: 100px;
    height: 100px;
    border-radius: 50%;
    margin: 20px;
    transition: background-color 1s linear;
  }
  #circle1 { background-color: lightblue; }
  #circle2 { background-color: lightgreen; }
  #circle3 { background-color: lightcoral; }
</style>
</head>
<body>

<div id="circle1" class="circle"></div>
<div id="circle2" class="circle"></div>
<div id="circle3" class="circle"></div>

<script>
  const circle1 = document.getElementById('circle1');
  const circle2 = document.getElementById('circle2');
  const circle3 = document.getElementById('circle3');

  setTimeout(() => {
    circle1.style.backgroundColor = 'blue';
  }, 4000); // 4秒後

  setTimeout(() => {
    circle2.style.backgroundColor = 'green';
  }, 7000); // 7秒後

    setTimeout(() => {
    circle3.style.backgroundColor = 'red';
  }, 8000); // 8秒後

</script>

</body>
</html># kokyuuhou
