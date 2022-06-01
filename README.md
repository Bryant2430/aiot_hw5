# Bryant Zhan's Homework #5(to Bryant2430/aiot_hw5)

## Lecture 14: IoT Flask Web (github, vs code)

### Step 1 : Development Environment Setup in aiot_hw5
1. Please install vs code, register github, install git for windows
2. (check-point 1) github create a new repository (aiot0524)
3. go to vs code clone this repository (choose new branch)
4. vs code 安裝 python extension
5. pip install flask, pandas, sklearn
    * 快捷鍵 ctrl+shift+p ===> package manager 叫出 (git clone....)
    * 快捷鍵 ctrl+' ==> 叫出終端機
6. (check-point 2) 為了要upload local file to github from local要終端機 C:> 設定下面 (不設定 branch default ='main')
    * C:> git config --global user.name "Bryant Zhan"
    * C:> git config --global user.email tony10613@gmail.com
    * C:> git commit -m "first commit"
    * C:> git remote add origin https://github.com/Bryant2430/aiot_hw5.git
    * C:> git branch -M main
    * C:> git push -u origin main

7. Remeber to turn on xampp/MySQL (Apache is not necessary)
add user/password: test123/test123

### step2 develop log(作業五(flask,github,database))
* 步驟一:建立一個新的repository
    <br/><img src="https://github.com/Bryant2430/aiot_hw5/blob/step5/hw05_img/1.jpg" width="500px"/>
* 步驟二:打開建立的新資料夾
    <br/><img src="https://github.com/Bryant2430/aiot_hw5/blob/step5/hw05_img/2.jpg" width="500px"/>
* 步驟三:擴增python套件
    <br/><img src="https://github.com/Bryant2430/aiot_hw5/blob/step5/hw05_img/3.jpg" width="500px"/>
* 步驟四:使用git clone將github上的aiot_hw5給複製到指定的資料夾
    <br/><img src="https://github.com/Bryant2430/aiot_hw5/blob/step5/hw05_img/4.jpg" width="500px"/>
* 步驟五:將github上的檔案指定到aiot_hw5中
    <br/><img src="https://github.com/Bryant2430/aiot_hw5/blob/step5/hw05_img/5.jpg" width="500px"/>
* 步驟六:將檔案開啟至vs code
    <br/><img src="https://github.com/Bryant2430/aiot_hw5/blob/step5/hw05_img/6.jpg" width="500px"/>
* 步驟七: 在readme.md上添增文字
    <br/><img src="https://github.com/Bryant2430/aiot_hw5/blob/step5/hw05_img/7.jpg" width="500px"/>
* 步驟八:將檔案存檔並傳至github
    <br/><img src="https://github.com/Bryant2430/aiot_hw5/blob/step5/hw05_img/8.jpg" width="500px"/>
* 步驟九:確認檔案並上傳
    <br/><img src="https://github.com/Bryant2430/aiot_hw5/blob/step5/hw05_img/9.jpg" width="500px"/>
* 步驟十:點選「重新命名分支」
    <br/><img src="https://github.com/Bryant2430/aiot_hw5/blob/step5/hw05_img/10.jpg" width="500px"/>
* 步驟十一:將分支改名為step1
    <br/><img src="https://github.com/Bryant2430/aiot_hw5/blob/step5/hw05_img/11.jpg" width="500px"/>
    <br/><img src="https://github.com/Bryant2430/aiot_hw5/blob/step5/hw05_img/12.jpg" width="500px"/>
* 步驟十二:完成上傳並在github中顯示
    <br/><img src="https://github.com/Bryant2430/aiot_hw5/blob/step5/hw05_img/13.jpg" width="500px"/>
* 步驟十三:點選「簽出至」並切換至step5分支
    <br/><img src="https://github.com/Bryant2430/aiot_hw5/blob/step5/hw05_img/14.jpg" width="500px"/>
* 步驟十四:安裝需要套件(flask,pandas,sklearn,pymysql)
    <br/><img src="https://github.com/Bryant2430/aiot_hw5/blob/step5/hw05_img/15.jpg" width="500px"/>
    <br/><img src="https://github.com/Bryant2430/aiot_hw5/blob/step5/hw05_img/16.jpg" width="500px"/>
    <br/><img src="https://github.com/Bryant2430/aiot_hw5/blob/step5/hw05_img/17.jpg" width="500px"/>
* 步驟十五:打開xampp並建立使用者test123與匯入資料庫到aiotdb中
    <br/><img src="https://github.com/Bryant2430/aiot_hw5/blob/step5/hw05_img/18.jpg" width="500px"/>
    <br/><img src="https://github.com/Bryant2430/aiot_hw5/blob/step5/hw05_img/19.jpg" width="500px"/>
    <br/><img src="https://github.com/Bryant2430/aiot_hw5/blob/step5/hw05_img/20.jpg" width="500px"/>
* 步驟十六:執行app.py並點選http://127.0.0.1:5000/
    <br/><img src="https://github.com/Bryant2430/aiot_hw5/blob/step5/hw05_img/21.jpg" width="500px"/>

* 步驟十七:進入網站後即可點選set random來隨機亂數data
    <br/><img src="https://github.com/Bryant2430/aiot_hw5/blob/step5/hw05_img/22.jpg" width="500px"/>
* 步驟十八:點選call AI來進行分類將高於300為1(綠色)，反之為0(紅色)
    <br/><img src="https://github.com/Bryant2430/aiot_hw5/blob/step5/hw05_img/23.jpg" width="500px"/>
    <br/><img src="https://github.com/Bryant2430/aiot_hw5/blob/step5/hw05_img/24.jpg" width="500px"/>
* 步驟十九:在vs code中建立新分支step5並上傳至github即完成。
    <br/><img src="https://github.com/Bryant2430/aiot_hw5/blob/step5/hw05_img/25.jpg" width="500px"/>
    <br/><img src="https://github.com/Bryant2430/aiot_hw5/blob/step5/hw05_img/26.jpg" width="500px"/>

