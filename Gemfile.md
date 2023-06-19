


gem sources -l
gem sources --add https://rubygems.org/ --remove  https://gems.ruby-china.com/
gem update --system

bundle install

rvm install 3.0.0
rvm use 3.0.0

清空错误的replace
~/.bundle/config

❯ gem sources -r https://gems.ruby-china.org
source https://gems.ruby-china.org not present in cache
❯ gem sources -a https://gems.ruby-china.com
参考资料
https://www.jianshu.com/p/46dfd66f8861