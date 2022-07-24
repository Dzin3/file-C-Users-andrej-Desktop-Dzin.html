<!DOCTYPE html>
<html>
  <head>

  </head>
  <body>
    <h1>JavaScript function()</h1>
    <p>U ovom primeru je fullName metod od osobe primenjen na person1 </p>
    <p id="demo"></p>
    <script> 
    function myDisplayer(some) {
      document.getElementById("demo").innerHTML = some;
    }
    function myCalculator(num1, num2) {
      let sum = num1 + num2;
      return sum;
    }
    let result = myCalculator(3,44);
    myDisplayer(result);
    </script>
  </body>
</html>
