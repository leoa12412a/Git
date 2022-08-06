# Git教學

### 1.安裝Git
<a href="https://git-scm.com/download/win">Dowload for Windows</a><br />

### 2.Git初始化及加入版本控制

首先先到專案資料夾，按右鍵->git bash here<br />
<img width="726" alt="1" src="https://user-images.githubusercontent.com/22145676/183237303-321a716b-5963-437e-b4aa-d612db0f8d59.png"><br />

在Git bash中輸入指令<br />
1.輸入初始化指令<br />
```
git init
```
2.第一次使用需要輸入mail與姓名<br />
```
git config --global user.name "您的姓名"
git config --global user.email "您的Email"
```
3.將所有檔案加入版本控制中<br />
```
git add .<br />
```
4.進行commit<br />
```
git commit -m "first commit"
```

### 3.開啟gitlab專案
![2](https://user-images.githubusercontent.com/22145676/183237325-84ef305d-cc29-4feb-80d0-c7de5ab16fd0.jpg)<br />
![3](https://user-images.githubusercontent.com/22145676/183237331-300a9da4-8078-4e2a-ac33-36110053a4d9.jpg)<br />
![4](https://user-images.githubusercontent.com/22145676/183237333-9d783fcf-9219-4d9c-aaed-ddec2d39c486.jpg)<br />
將上圖的remote指令複製並輸入於git bash中<br />
![5](https://user-images.githubusercontent.com/22145676/183237338-65e667e5-108e-40a8-b687-258725851096.jpg)<br />
輸入指令上傳<br />
```
git push -u origin master
```
![6](https://user-images.githubusercontent.com/22145676/183237341-9fb827ca-b735-450e-890f-9d2820fa6289.jpg)<br />
![7](https://user-images.githubusercontent.com/22145676/183237344-eaf6616a-6518-453f-8cdd-9719c75e5610.jpg)<br />
上傳完成<br />
![8](https://user-images.githubusercontent.com/22145676/183237352-c9450407-1163-4008-baad-1d4205d6f8c0.jpg)<br />

