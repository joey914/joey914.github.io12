---
layout: post
title:  "[Java] JOptionPane 예제와 사용법"
date:   2017-03-20 10:30:27 -0800
tags: [Sunrin, JAVA]
author: Jooholee
description: "선린인터넷고 JAVA 시간에 학습한 JOptionpane에 관한 내용입니다."
---

JOptionpane는 이름에서도 알 수 있듯 알림창을 띄워 사용자에게 피드백을 제공하는 판을 다루는 옵션입니다.
사용법은 Joption + ctrl + space 단축키로 Import와 동시에 사용할 수 있고, 이 판의 전체적인 기능은 자바스크립트의 alert와 흡사합니다.
다음 예제를 봅시다.

{% highlight ruby %}
package j;

import javax.swing.JOptionPane;

public class Exa {
  public static void main(String[] args) {
    JOptionPane.showMessageDialog(null,"Hello, world");
    System.exit(0);
  }
}
{% endhighlight %}

실행 결과

![](http://i.imgur.com/BMbwhaj.png)

{% highlight ruby %}
package j;

import javax.swing.JOptionPane;

public class Exa {
  public static void main(String[] args) {
    String name = JOptionPane.showInputDialog("당신의 이름?");
    JOptionPane.showMessageDialog(null, name);
    System.exit(0);
  }
}
{% endhighlight %}

실행 결과

![](http://i.imgur.com/JdOrm01.png)

![](http://i.imgur.com/ydy2fSc.png)



[jekyll-docs]: http://joey914.github.io/home
[jekyll-gh]:   https://github.com/joey914/joey914
[jekyll-talk]: https://talk.joey914.com/
