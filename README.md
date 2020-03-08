# smooth-touchpad-gestures
combine fusuma with xte


So i wrote some notes for myself (and maybe somebody else) about fusuma gestures and found best solution instead of xdotool


Visit source: https://github.com/iberianpig/fusuma and compare with my stuff below...

1. Grant permission to read the touchpad device
$ sudo gpasswd -a $USER input
3. Install Ruby
$ sudo apt-get install ruby
4. Install Fusuma
$ sudo gem install fusuma
5. Install xautomation
$ sudo apt-get update -y && sudo apt-get install -y xautomation
6. Add fusuma to startup applications
7. You can put my config to ~/.config/fusuma/ but in my case fusuma does not recognize it. And i decided to put it to /var/lib/gems/2.5.0/gems/fusuma-1.5.0/lib/fusuma/
(check your fusuma version)

Reboot and enjoy smooth gestures.


(there may appear explanation why you should use xte instead of xdotool && details of config...)

