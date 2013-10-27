---
layout: post
title:  "Installing rails on Ubuntu"
date:   2013-10-27 15:14:36 +0530
categories: rails
---

Install the pre-requisites

{% highlight bash %}
$ sudo apt-get install build-essential openssl libreadline6 libreadline6-dev curl git-core zlib1g zlib1g-dev libssl-dev libyaml-dev libsqlite3-0 libsqlite3-dev sqlite3 libxml2-dev libxslt-dev autoconf libc6-dev ncurses-dev automake libtool bison subversion
{% endhighlight %}


Download and install [Ruby][ruby]

{% highlight bash%}
$ wget http://cache.ruby-lang.org/pub/ruby/2.0/ruby-2.0.0-p247.tar.gz
$ tar -xvzf ruby-2.0.0-p247.tar.gz
$ cd ruby-2.0.0-p247
$ ./configure
$ make
$ make install
{% endhighlight %}

Check the installation
{% highlight bash%}
$ ruby -v
ruby 2.0.0p247 (2013-06-27 revision 41674) [i686-linux]
{% endhighlight %}


Install [Rails][rails]

{% highlight bash%}
$ sudo gem install rails
{% endhighlight %}


[ruby]:    https://www.ruby-lang.org/en/downloads/
[rails]:   http://rubyonrails.org/

