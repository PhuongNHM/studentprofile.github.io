<!DOCTYPE html>
<html>
<head>
<h1> Danh sách sinh viên </h1>
</head>

  
<body>
<p>Nhập số sinh viên</p>
Số lượng: <input type="text" id="myText" value="">
<button onclick="myFunction()"> Nhập </button>
<p id="demo"></p>
<script>
function myFunction() {
var x = document.getElementById("myText").value;
var y = 1;
  while(y <= x){
    document.write(mã sinh viên);
    document.Write(họ và tên);
    document.write(ngày tháng năm sinh);
    document.write(lớp học);
    document.write(điểm GPA);
    y++
}
</script>

</body>
</html>
