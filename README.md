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
    document.write ("<p>Mã sinh viên/n</p>");
    document.write ("<p>Họ và tên/n</p>");
    document.write ("<p>Ngày tháng năm sinh/n</p>");
    document.write ("<p>Lớp học/n</p>");
    document.write ("<p>Điểm GPA/n</p>");
    y++;
}
}
</script>

</body>
</html>
