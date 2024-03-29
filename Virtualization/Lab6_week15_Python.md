<a name="111"/>

# Lab6：Ubuntu VM _ Python虛擬環境介紹與應用

## 為什麼需要虛擬環境 (Virtual Environment) ?
**Python 自 3.3 版開始提供虛擬環境 (PEP405, virtual environments in core, Sept. 29, 2012).主要是為了清理出一個乾淨開發環境, 以便將來布署時不會多出一些有的沒的 package; 使用虛擬環境可以讓我們在構建專案時把環境先弄好, 並鎖定為專案的專用環境, 不必擔心因為別的專案的需求而弄壞了這個專案的環境; 常見的需求如下：**

- **別的專案用的, 而且這個專案用不到的.**
- **正在測試學習的.或者猜想著這個 package 到底是有沒有用到 (不曾記得安裝過, 但實際上是因為和另一個 package 相依而自動安裝進來了).**
- **避免 package 和 python 本身 (以及其他 package) 不相容的問題. 同時也可以避免這些多出來 package 引發不相容的問題。**


[1. 安裝一個方便開發的 Python 虛擬環境：使用 Pyenv 管理 Python 版本](#222)

---

``` ## Install Python packages (About 10 minutes)
eliva@eliva:~$ python3 --version
Python 3.8.2

eliva@eliva:~$ sudo apt-get update
eliva@eliva:~$ sudo apt-get install -y make build-essential libssl-dev zlib1g-dev libbz2-dev libreadline-dev libsqlite3-dev wget curl llvm libncurses5-dev libncursesw5-dev xz-utils tk-dev libffi-dev liblzma-dev python-openssl python-dev

eliva@eliva:~$ sudo apt-get install python3-pip

## --- install pyenv
eliva@eliva:~$ sudo apt install curl 
[sudo] eliva 的密碼： 

eliva@eliva:~$ curl -L https://raw.githubusercontent.com/yyuu/pyenv-installer/master/bin/pyenv-installer | bash

eliva@eliva:~$ gedit ~/.bashrc

--- 將以下 4 行添加到 .bashrc 的底部

export PYENV_ROOT="$HOME/.pyenv"
export PATH="$PYENV_ROOT/bin:$PATH"
eval "$(pyenv init --path)"
eval "$(pyenv virtualenv-init -)"

--- 完成後, 記得儲存後, 關閉終端並再次打開一個新的Terminal
```

<a name="222"/>
1. 開啟你的Ubuntu → 桌面點擊右鍵 → 開啟Open in Terminal
輸入：

`python3 --version`

`sudo apt-get update`

![image](https://github.com/ElivaSong/ES-Fall2023/assets/126373882/d3e4273e-4f38-47eb-a78b-09fe18fcbb37)







[TOP](#111)
