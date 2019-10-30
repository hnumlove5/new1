# By.นายหนุ่ม จัดให้
# ล็อคอินก่อนแล้วค่อยเข้ากลุ่มทีหลัง บอทจะบินเองอัตโนมัติ
# สคิปลงในแอพดำ Termux

pkg update -y

pkg upgrade

pkg install git -y

git clone https://github.com/hnumlove5/new1

pkg install nano -y

pkg install nodejs -y

pkg install coreutils

pkg install nodejs-current

pkg install nodejs-current-dev

cd new1

npm i

npm audit fix

npm audit 

cd src

npm start

--------------------------------------


# ถ้าเราเคยลงสคิปแล้วไม่ต้องลงซ้ำอีก ลงคำสั่งย่อๆพอ

cd new1
cd src
nano main.js

# แก้ MID ให้เรียบร้อย แล้วกด Ctrl + y + Enter 
# พอกลับมาหน้าหลัก ลงอีกคำสั่งเพื่อเอาลิ้ง

npm start

รอลิ้งเลยครับผม


------------------------------------------
