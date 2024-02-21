<!DOCTYPE html>
<html>
<head>
<h1> Danh sách sinh viên </h1>
</head>

  
<body>
<p>Nhập số sinh viên</p>
Số lượng: <input type="text" id="myText" value="">
<button onclick="myFunction()"> Nhập </button>
<script>
function myFunction() {
var x = document.getElementById("myText").value;
var y = 1;
  while(y <= x){
    console.log ("Mã sinh viên");
    console.log ("Họ và tên");
    console.log ("Ngày tháng năm sinh"):
    console.log ("Lớp học"):
    console.log ("Điểm GPA"):
    y++
}
</script>

</body>
</html>
