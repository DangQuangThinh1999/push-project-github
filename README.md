# push-project-github


git init

1. Đăng nhập vào git bash.
git config --global user.name “username”     
git config --global user.name DangQuangThinh1999

Thay "username"  = tên ở tài khoản github

git config --global user.email “email@gmail.com”
Thay "email@gmail.com"  = gmail ở tài khoản github

git config --global user.email quangthinh123qb@gmail.com

git remove -v : xóa tất cả nhánh cũ
2. thay đoạn mã vào 

git remote add origin http://"đoạn mã"@github.com/DangQuangThinh1999/ReactJS-Fontend.git


đoạn mã : Lấy ở phần lưu ý 

3. git add .

4. git commit -m "init"

5. git push origin master 




LƯU Ý: MÃ LẤY Ở settings -> developer settings -> Personal access tokens -> Tokens(classic) , xong bấm vào This token has no expiration date. (biểu tượng tam giác chấm than) -> chọn 30days -> rồi bấm regenerate token
