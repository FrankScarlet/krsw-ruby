# ruby

> 上次看这个[教程](https://guides.rubyonrails.org/getting_started.html)应该是高中...然后是大二左右吧

## start

```bash
ruby --version
sqlite3 --version
node --version
rails --version
```

教程居然还有这种提示

If you're using Windows Subsystem for Linux then there are currently some limitations on file system notifications that mean you should disable the spring and listen gems which you can do by running ```rails new blog --skip-spring --skip-listen``` instead.

`rails`项目要调整`bundler`源

```bash
$ gem sources --add https://gems.ruby-china.com/ --remove https://rubygems.org/
$ gem sources -l
$ bundle config mirror.https://rubygems.org https://gems.ruby-china.com
```
