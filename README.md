# 玩了會懷疑人生系列-1-貪食蛇(Linux版)
COMPILED WITH g++ RUN IN DEBAIN

1. 執行下列指令
```
 sudo apt-get install git libncurses5-dev g++ -y
 git clone https://github.com/chenlicpp/fen-game-1-linux.git
 cd fen-game-1-linux
 g++ -lcurses -o snake main.cpp fn.cpp
 ./snake
```
2.enjoy!
![](https://github.com/chenlicpp/fen-game-1-linux/raw/master/snake.png)
用WASD控制上下左右(遊玩時記得換成(小寫)英文輸入法) W:上 S:下 A:左 D:右
