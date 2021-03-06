---
layout: post
title:  "Clojure 学习日记 —— 0序言"
date:   2016-01-20
categories: clojure
---
* content
{:toc}

### lisp介绍

说起clojure可能没多少人知道，可能最多只知道她是一种函数式语言、lisp方言，类似common lisp，  

lisp的设计思想是公认的强大，有人甚至说当今最高级的主流语言，也只是刚刚接近1958年出生的Lisp所在的水平，
而且之后发展的语言都有借鉴部分的lisp的思想，像java、python、ruby等。 

现在lisp作为一种小众语种，知道的人少，学习的人更少了，这其中的曲曲折折、坑坑洼洼我也不是很了解，  
到底是什么原因导致一个如此牛掰的语言沦落至此？原因总结如下(我是没资格说这种话的，参考大牛)  

> 1. 最最大的原因，生态圈有问题，因为她太太灵活了，你根本不可能制作出一款IDE来
> 2. lisp残缺不全，源码其实只写了一部分，但是就是这一部分包括宏定义这些就可以让常人仰望了
> 3. lisp是一种研究型、实验室语言，应用不广，无法推广。

在我大二的时候很迷恋lisp，看了一点语法，大概了解了lisp现状最后不得不不了了之，难是一部分原因，主要是你付出后得到的回报几乎微乎其微。  
综合这些来看，其实现在有人学习lisp主要出于一种图腾崇拜思想去学习它，类似用emacs喝咖啡的感觉。  

***

### clojure介绍

虽然lisp现在发展几乎停滞，但是取lisp精华，去其糟粕的变种语言如Scheme、clojure却一直在前进。  
2015暑假，在我大三的这一年我美丽地邂逅了clojure，又重新燃起我对lisp的喜爱，clojure有很多优点，我只说我比较看重的几点。  

> 1. 基于jvm平台的lisp变种，弥补的lisp那可怕的生态圈又保持着lisp的灵活高效。  
> 2. 可以被应用到企业上，据我所知clojure有一些优秀的web框架，如果学好clojure可能还能找的一个不错的工作。  
> 3. clojure+clojureScript几乎可以实现全栈，用一种语言实现全栈，想想该有多舒坦，而且还是这种简洁的语言。  
> 4. clojure的社区还是比较活跃的，在国内是有点冷淡，但是国外还是很热的，很多人在讨论她。

综上所述，clojure的这个坑我是掉定了，我也愿意！  

***

### 关于本文

2015下半年断断续续的学了一点时间的clojure语法，但是只是囫囵吞枣，感觉什么都没学到，再加上学校课程也挺紧的，
索性推翻，重新学一遍，谨以本文做个记录，记录下心得，记录下我大clojure的成长之路。
