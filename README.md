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
    document.write ("<p>Mã sinh viên</p>");
    document.write ("<p>Họ và tên</p>");
    document.write ("<p>Ngày tháng năm sinh</p>");
    document.write ("<p>Lớp học</p>");
    document.write ("<p>Điểm GPA</p>");
    y++;
}
}
</script>

</body>
</html>
