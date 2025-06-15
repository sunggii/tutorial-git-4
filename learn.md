# What I learned
ref: [doc พี่ไมค์](https://docs.mikelopster.dev/c/basic/git/intro)

## Git Graph
* เป็น extention โหลดมาดู Graph แทน sourcetree
* วิธีดู Graph 
    1.  ```Ctrl + shift + p```
    2. เลือก

    ![alt text](./img/git-graph.png)

## คำสั่งพื้นฐาน
* ```git init```
* ```git add ``` and ```git commit``` ทำผ่าน UI

## คำสั่ง Branch
* ```git branch``` ใช้เช็ค branch ที่ทำงานอยู่
* ```git branch -m <ชื่อใหม่>```
* ```git merge <deverlop>``` คือ merge develop เข้า main
    * หลัง merge ให้พิม ```:wq``` ที่ terminal เพื่อออก
* ```feature/<ชื่อfeature>``` นิยมใช่ / ตอนทำ feature ใหม่

## Git server และคำสั่ง remote
* หลังจาก cop remote ให้ใช้ ```git push --all  origin``` เพื่ออัพทุก branch ขึ้น github
* ```git push <ตัวแปร> <branch>``` **ตัวอย่าง** ```git push origin main```