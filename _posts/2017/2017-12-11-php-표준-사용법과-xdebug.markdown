---
layout: "post"
title: "PHP 표준 사용법과 xdebug"
date: "2017-12-11 17:42"
categories: [php]
---

PHP 표준 사용법

**PHP The Right Way:** [http://modernpug.github.io/php-the-right-way](http://modernpug.github.io/php-the-right-way)

**PHP document:** [http://php.net/manual/kr/index.php](http://php.net/manual/kr/index.php)

PHP 디버깅을 도와주는 디버거

**xdebug:** [http://xdebug.org](http://xdebug.org)

**Easy PHP Debugging in Ubuntu:** [http://www.apaddedcell.com/easy-php-debugging-ubuntu-using-xdebug-and-vim](http://www.apaddedcell.com/easy-php-debugging-ubuntu-using-xdebug-and-vim)

리모트 디버깅

vim을 최신 버전으로 업데이트

{% highlight linux %}
sudo apt-get update;
sudo apt-get install vim;
{% endhighlight %}

vim의 xdebug용 플러그인 다운로드

**vim xdebug plugin:** [http://www.vim.org/scripts/script.php?script_id=1929](http://www.vim.org/scripts/script.php?script_id=1929)

{% highlight linux %}
sudo wget http://www.vim.org/scripts/download_script.php?src_id=7285 -O debugger.zip;
sudo unzip debugger.zip -d temp_debugger;
mkdir ~/.vim;
mv temp_debugger/plugin .vim/;
{% endhighlight %}

파이어폭스에 xdebug helper를 설치

**파이어폭스 xdebug helper:** [https://addons.mozilla.org/en-US/firefox/addon/easy-xdebug](https://addons.mozilla.org/en-US/firefox/addon/easy-xdebug)
