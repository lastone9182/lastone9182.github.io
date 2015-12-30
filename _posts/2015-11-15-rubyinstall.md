---
layout: post
title: Ruby install
---

### 루비2.2 패키지 설치
* apt-add-repository ppa:brightbox/ruby-ng
* apt-get update
* apt-get install ruby2.2

### jekyll install
* gem install jekyll

### 헤더 파일 오류 발생시
	ERROR:  Error installing jekyll:
	ERROR: Failed to build gem native extension.

	current directory: /var/lib/gems/2.2.0/gems/ffi-1.9.10/ext/ffi_c
	/usr/bin/ruby2.2 -r ./siteconf20151116-11572-aizd4o.rb extconf.rb
	mkmf.rb can't find header files for ruby at /usr/lib/ruby/include/ruby.h

* apt-get install ruby-dev
* apt-get install ruby2.2-dev

###	Markdown utility
* GitBook	: Markdown으로 ebook을 만들 수 있다고 한다.
* Swipe		: Makrdown으로 multimedia presentation을 만들 수 있다.