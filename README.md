<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>Đăng ký</title>
</head>
<body>
<h1>Đăng ký Thành viên</h1> 
<form action="google.com"> <!-- để nút đk và reset hđ -->
<table border="1">

<tbody>
<tr> <td colspan="2"><b>THÔNG TIN ĐĂNG NHẬP</b></td>  </tr> <!--thẻ tr hang ngang thẻ b in đậm kiểm tra không phải @ ko gửi thư password che mk -->
<tr> <td>Email:</td>  <td> <input type="email" name="email" id="idEmail"  > </td>  </tr>
<tr> <td>Mật Khẩu:</td>  <td> <input type="password" name="password" id="idpassword"  > </td>  </tr>
<!--type email kt email có @ không, name kt name đặt tên form email=haxuanphubc96@gmail.com, gửi đi id là chuyên thanh Api  -->
<tr> <td>Nhập Lại Mật Khẩu:></td>  <td> <input type="password" name="re_password" id="id_repassword"  > </td>  </tr>
<tr> <td colspan="2"> <strong> Thông Tin Cá Nhân</strong>  </td>   </tr>
<tr> <td>Họ Và Tên:</td>  <td> <input type="text" name="hoVaTen" id="idHoVaTen"  > </td>  </tr>
<tr> <td>Giới Tính:</td>  <td> <!-- F và M là nó lưu và value rồi gửi đi , id gửi riêng ko có value thì nó gửi rỗng-->
     <input type="radio" name="gioiTinh" id="idGioiTinhM" value="M" ><label for="M"> Nam </label>
     <input type="radio" name="gioiTinh" id="idGioiTinhF" value="F" ><label for="F"> Nữ </label> </td>  </tr>
<tr> <td>Ngày Sinh:</td>  <td> <input type="date" name="ngaySinh" id="idNgaySinh"  > </td>  </tr> 
<tr> <td>Số Điện Thoại:</td>  <td> <input type="tel" name="soDienThoai" id="idsoDienThoai"  > </td>  </tr> 
<tr> <td>Số Di Động:</td>  <td> <input type="tel" name="soDiDong" id="idsoDiDong"  > </td>  </tr> 
<tr> <td colspan="2"><b>Địa Chỉ:</b></td>  </tr> 
<tr> <td>Quốc Gia:</td>  <td> <select name="quocGia" id ="idQuocGia"> <option value="VN">Việt Nam </option> 
     <option value="PL">Ba Lan 
     </option><option value="USA"> Mỹ </option> </select> </td>  </tr> 
<tr> <td>Tỉnh Thành:</td>  <td> <select name="tinhThanh" id ="idTinhThanh"> <option value="TPHCM">Thành Phố HCM  </option> 
     <option value="AG">An Giang 
     </option><option value="KG">Kiên Giang </option> </select> </td>  </tr> 
<tr> <td>Quận Huyện:</td>  <td> <select name="quanHuyen" id ="idquanHuyen"> <option value="NB">Nhà Bè </option> 
     <option value="LA">Long An
     </option><option value="Q1">Quận 1</option> </select> </td>  </tr> 
<tr> <td >Địa Chỉ Nhà </td> <td> <textarea rows="5" cols="" name="diaChi" id="idDiaChi"></textarea> </td> </tr>
<tr> <td colspan="2"><b>Bổ Sung:</b></td>  </tr> 
<tr> <td >Sở Thích </td> <td><input type="checkbox" name="soThich" id="idSoThichDocSach"> <label for="soThichDocSach">Đọc Sách</label> 
                             <input type="checkbox" name="soThich" id="idSoThichXemPhim"> 
                             <label for="soThichXemPhim">Xem Phim</label>  </td> </tr>  
<tr> <td >Hình Ảnh </td> <td><input type="file" name="hinhAnh" id="idHinhAnh"> </td> </tr>    
<tr> <td >Tuổi </td> <td><input type="number" name="tuoi" id="idTuoi" min="0"> </td> </tr> <!-- ít nhất 0 tuổi -->                          
<tr> <td colspan="2"><input type="submit" value="Đăng Ký" />
                     <input type="reset" value="reset" /></td> </tr>


</tbody>


</table>
</form>
<!-- <tr> <td><b>Giới Tính:</b></td>  <td>
     <input type="radio" name="gioiTinh" id="idGioiTinhM"  >Nam
     <input type="radio" name="gioiTinh" id="idGioiTinhF">Nư</td>  </tr>
 cũng chạy , value="VN" chuyển việt nam thành vn gửi đi thôi ,rows="5" 5 dong--> 


<!-- <input type="checkbox" name="soThich" id="idSoThichDocSach" value="doc_sach"> 
        <label for="soThichDocSach">Đọc Sách</label> ,value docsach nó lưu của soThichDocSach , ko có value thì nó ko lưu -->

































</body>
</html>
