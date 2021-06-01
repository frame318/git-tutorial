สัญญาลัก U ยังไม่  add
	A  add แล้วรอ commit
	M มีการเปลี่ยนแปลงไฟล์
___________________________________________
git config --global user.name "your_name"

git config --global user.email "your@email.com"
_____________________________________________
git clone <remote_url>
__________________________________________
git init    / สร้างgit

git add .             / add ไฟล์ทั้งหมด

git add src/*.txt    / add ไฟล์ที่เลือก

git status / ดูการเปลียนแปลงต่างๆ

git reset .  / ยกเลิก add

gir rm -rf --cached /ล้างทุกอย่าง

git commit -m "xxx"   / commit

git reflog  / ดูประวัติ commit ทั้งหมด

git log / ดูประวัติ commit ทั้งหมด

git checkout 218e3f7a   / ย้ายไปยัง commit ที่ต้องการด้วย รหัส 7 หลักแรก

git reset --hard 5aecfd2 / ลบ commit  ที่ต้องการด้วย รหัส 7 หลักแรก

git reflog / ใช้แสดง Log ของการเปลี่ยนแปลงใน HEAD ของ Local Repository มันเหมาะสำหรับการค้นหางานที่สูญหายไป

git blame xxx / ดูว่าใครทำการเปลี่ยนแปลงอะไรในไฟล์

git update-ref -d HEAD / ลบ commit ทั้งหมด

ไฟล์ .gitignore สำหรับใส่ชื่อไฟล์ หรือ โฟลเดอ ที่ไม่ต้องการอัพเข้า commit

______________________________________________________________

git remote add origin https://.....

git remote show origin

git branch 

git branch xxx / สร้าง branch 

git checkout xxx / ย้ายไป branch ที่ต้องการ

git merge xxx / ร่วม branch

git branch --delete xxx  / ลบ branch 

git push -u origin xxx   / push ขึ้นตามชื่อ branch

git pull --rebase

git push

https://ohshitgit.com/th
