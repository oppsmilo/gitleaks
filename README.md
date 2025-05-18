# gitleaks

gitleaks指令及安裝過程


先APT-UPDATE及APT-UPGRADE 下載go 

下載完成GO VERSION確認是否安裝好

如果是用apt下載go就不用配置go路徑

但建議設定 GOPATH 和把 $GOPATH/bin 加入 $PATH，這樣你才能使用 go install 安裝的工具

用uname看電腦是甚麼架構(uname -m) 然後看自己是甚麼shell(echo $SHELL)

然後把
export GOPATH=$HOME/go
export PATH=$PATH:$GOPATH/bin
加進檔案最後兩行

GOPATH是GO語言檔案存放的地方

GOPATH/BIN則是放用GO語言下載的程式

用GO INSTALL下載的地方都該放在那邊
