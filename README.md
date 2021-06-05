# TG-Project

## วิธีการสร้าง project
#### 1. ทำการ clone project
```
git clone https://github.com/tatazakup/TG-Project.git
```
#### 2. จากนั้นลองเข้าไปยัง sub-project directory จะพบว่ายังไม่มี source code ดังนั้นจึงต้องทำการ init submodule
```
cd TG-Project/
```
```
git submodule init
```
#### 3. ทำการ update submodule
```
git submodule update
```
#### 4. install package ในทุก submodule ด้วยคำสั่งเดียว
```
npm run install-package
```

## วิธีการ run project
#### 1. ไปที่ root directory แล้ว run คำสั่ง
```
npm run dev
```

## เมื่อมีการ update จาก parent module ให้ใช้คำสั่ง
```
git submodule foreach git pull origin master
```
