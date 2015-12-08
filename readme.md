
This little App is written within the Qt-Framework, uses qml for ui-creation and speaks to ipfs through http localhost.

INSTALL:<br><br>

  -git clone https://github.com/crazysoldier/ipfs-browser & cd /ipfs-browser<br>
  -There is a ubuntu-linux binary but better compile it yourself. <br>
  -If you have QtCreator installed, just open/build/run.<br>
  -Or use qmake like: qmake minibrowser.pro -r -spec linux-g++<br>
  -launch it like: ./ipfs-browser<br><br>

FIRST STEPS:<br><br>

Add a folder with index.html in ipfs like: <br>
  -click on 'Home-Button', <br>
  -change to 'Files', <br>
  -add file/folder here,<br>
  -copy the resulting 'hash' from the folder.<br><br>
  
Open ipfs-Browser on any computer to view it with the 'hash'. You can paste in any ipfs-address which is saved and accessible. <br>

Here you see where to add files:<br>
![screenshot-1](https://cloud.githubusercontent.com/assets/3826169/11655408/e5d824c2-9dad-11e5-8179-e85b5c87b6c1.png)<br>
Here you see howto open files with 'hash'<br>
![screenshot](https://cloud.githubusercontent.com/assets/3826169/11655411/e5e1568c-9dad-11e5-8ebf-48d4efb0150a.png)<br>
This shows the peers from ipfs:<br>
![ipfs-gui-home](https://cloud.githubusercontent.com/assets/3826169/11655409/e5dc612c-9dad-11e5-871c-4eca4be06319.png)<br>
This is the current start-page: <br>
![screenshot-qt - home qtwebview example](https://cloud.githubusercontent.com/assets/3826169/11655410/e5e079e2-9dad-11e5-8293-1a2e39d0fd06.png)
<br>
