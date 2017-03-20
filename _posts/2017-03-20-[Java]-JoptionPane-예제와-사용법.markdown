---
layout: post
title:  "[Java] JOptionPane 예제와 사용법"
date:   2017-03-21 10:30:27 -0800
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

![](https://scontent-hkg3-1.xx.fbcdn.net/v/t34.0-12/17409826_659613600902281_1673877171_n.png?oh=745d025504d6d1a48cdd49c59a60835c&oe=58D2DDB6)

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

![](https://scontent-hkg3-1.xx.fbcdn.net/v/t34.0-12/17409688_659613624235612_29208563_n.png?oh=724d65133ebbd0388c353579808f55d1&oe=58D2FBAE)

![](https://scontent-hkg3-1.xx.fbcdn.net/v/t34.0-12/17410213_659613597568948_821780634_n.png?oh=5bf06209274ade89631220a14fef1b7b&oe=58D1DE35)



[jekyll-docs]: http://joey914.github.io/home
[jekyll-gh]:   https://github.com/joey914/joey914
[jekyll-talk]: https://talk.joey914.com/
