---
layout: post
title:  "Installation and uninstallation of MATLAB on linux"
date:   2017-10-30 17:20:34 +0700
categories: MATLAB linux
---

### Installation

1. Extract files from the archive file
2. Open Terminal.
3. Type these following command(s) and then folow the instruction of the installer:
{% highlight ruby%}
./install
{% endhighlight %}


For more detail: [Install Products Using a MathWorks Account](https://www.mathworks.com/help/install/ug/install-mathworks-software.html)


### Uninstallation

1. Open Terminal.
2. Type these following command(s).:

{% highlight ruby%}
cd / 
rm -rf /usr/local/MATLAB/R2017b
{% endhighlight %}