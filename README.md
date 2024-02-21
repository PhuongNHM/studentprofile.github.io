<!DOCTYPE html>
<html>
<head>
<h1> Danh sách sinh viên </h1>
</head>

  
<body>
<p>Nhập số sinh viên</p>
Số lượng: <input type="text" id="myText" value="">
<button onclick="myFunction()"> </button>
<p id="demo"></p>
<script>
function myFunction() {
var x = document.getElementById("myText").value;
document.getElementById("demo").innerHTML = x;
}
</script>

</body>
</html>
