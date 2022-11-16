# POST-PROJECTS-ON-GITHUB ( 6 steps)


1.git init

2. Đăng nhập vào git bash.

git config --global user.name “username”

Thay "username"  = tên ở tài khoản github

VD: git config --global user.name DangQuangThinh1999

git config --global user.email “email@gmail.com”

Thay "email@gmail.com"  = gmail ở tài khoản github

VD: git config --global user.email quangthinh123qb@gmail.com

git remote -v      

3. thay đoạn mã vào 

"đoạn mã" : Lấy ở phần lưu ý 

git remote add origin http://"đoạn mã"@github.com/DangQuangThinh1999/ReactJS-Fontend.git

4. git add .

5. git commit -m "init"

6. git push origin master 

------------------------------------------------
EEROR: remote: Permission to samrao2/manager-4.git denied to samrao1.

fatal: unable to access 'https://github.com/samrao2/manager-4.git/': The requested URL returned error: 403

Fix: delete token ở phần Lưu ý , rồi bấm vào gregenerate new token classic , bấm dấu tích hết trừ cái mục đầu , xong chọn expiration date, bấm lưu  


GOOD LUCK !!! 
--------------------------------------------------------------------------------------------------------------------


LƯU Ý: MÃ LẤY Ở settings -> developer settings -> Personal access tokens -> Tokens(classic) , xong bấm vào This token has no expiration date. (biểu tượng tam giác chấm than) -> chọn 30days -> rồi bấm regenerate token 
