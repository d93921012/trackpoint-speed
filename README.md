# trackpoint-speed
Set Trackpoint Speed for Thinkpad USB Keyboard

在 Linux 的 X window 下，用來設定外接 USB Thinkpad 鍵盤的小紅點的速度。只適用於型號 SK-8855。需求 pyusb 的程式庫。

### 使用
sudo sh set-trackpoint

會先將裝置 unbind，再透過 pyusb 送出指令給鍵盤，再重新 bind 裝置。

參考: https://github.com/bseibold/tpkbdctl
