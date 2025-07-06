# my_test
**ถ้าคุณแก้บน GitHub (เว็บ) แล้วอยากให้ VSCode อัปเดต ต้องทำ: # git pull คำสั่งนี้จะดึง (download) โค้ดเวอร์ชันล่าสุดจาก GitHub ลงมาเครื่องคุณ ทำให้ VSCode ที่เปิดอยู่เห็นโค้ดใหม่ล่าสุด**

**แก้โค้ดใน VSCode	# git add → git commit → git push (ส่งขึ้น GitHub)**
***แต่ต้องส่งโค้ดที่อัพเดทแล้วเข้าไปด้วย -> git commit -m "โค้ดที่แก้" (ใส่อันที่แก้เข้าไปเลย)**

ขั้นตอนการโหลดงานใหม่เข้า github
1. open the terminal
2.  git config --global user.name "ชื่อของคุณ"
    git config --global user.email "อีเมลของคุณ" (only first time)
3. git init (only first time)
4. git remote add origin https://github.com/username/repo-name.git (use our url)
5. git add .
6. git commit -m "อัปโหลดโปรเจกต์ครั้งแรก" use commit
7.  git branch -M main
    git push -u origin main
8. done !!
eiei
