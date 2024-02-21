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
    document.write ("Mã sinh viên");
    document.write ("Họ và tên");
    document.write ("Ngày tháng năm sinh");
    document.write ("Lớp học");
    document.write ("Điểm GPA");
    y++;
}
}
</script>

</body>
</html>
