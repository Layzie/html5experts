# Algowhatnow?

#{  http://aerotwist.com/ } : 掲載されているサイトのURL  
#{ Paul Lewis } : 原文の著者名  
#{ http://aerotwist.com/blog/algowhatnow/ } : 原文の記事URL  
#{ Algowhatnow? } : 原文のタイトル

* * *

## クレジット

This article is translated with permission of <a href="#{ original.site_url }">#{ original.author }</a>.
You can find original article at <a href="#{ original.article_url }">#{ title }</a>.

本記事は<a href="#{ original.site_url }">#{ original.author }</a>氏の了承を得て翻訳された記事です。  
原文は<a href="#{ original.article_url }">#{ title }</a>に掲載されています。

* * *
There have been some posts recently that lament the way that companies hire front-end developers, and in particular "Computer Science questions". I feel like throwing my hat in the ring on this one, because I have some thoughts.

最近企業がフロントエンドディベロッパーの雇用について嘆いている投稿がいくつかありました。特に"コンピュータサイエンスについての質問"についてです。私はある考え方を持っているので、この問題に明快に答えられるように思ってます。

My 2 ½ year old son knows what an algorithm is, even though he’s never heard the word. He knows how I make a coffee, and guides me through the process. He even helps me out a little by tipping coffee all over the place. He knows all the steps and ensures I Do Things Properly™. (I’m certain Mummy puts him up to it.)

私の2歳半の息子は、言葉自体は聞いたことがなくてもアルゴリズムが何なのかを知っています。息子は私がどのようにコーヒーを入れるかを知っていて、作る過程を先導してくれます。至るところにあるティッピングしたコーヒー豆を取りのぞくのを少しでも手伝eてくれさえします。彼は全ての過程を知っていて私がきちんと物事をするということを保障しています。(ママがそうさせるに決まってます)

It kind of goes like this:

こんな感じで進めます。

1.  Get some coffee beans.
2.  Chuck them in a bean grinder.
3.  Grind beans.
4.  Chuck coffee powder into coffee machine.
5.  Boil water and wait for it to cool down a little; Daddy does *not* abide burnt coffee.
6.  Pour water on the coffee.
7.  Wait.
8.  Pour coffee into the mug; apply milk.
9.  Watch Daddy drink it and return to his Happy Place.

1.  コーヒー豆を持ってきます。
2.  コーヒー豆をグラインダーに放りこみます。
3.  豆を挽きます。
4.  コーヒーメーカーに挽いた粉を放りこみます。
5.  水を沸かしてちょっとだけ冷まします。パパは焦げたコーヒーに耐えられ*ないよ*
6.  コーヒーにお湯を注ぎます。
7.  待ちます。
8.  ミルクを加えて、マグカップにコーヒーを注ぎます。
9.  パパがコーヒーを飲んでるのを見て、いつもの場所に帰ります。

An algorithm is just a list of ordered steps, and nothing to be particularly concerned about. I regard the ability to break down a task into steps as a basic building block for a programmer of any level.

アルゴリズムとは単に決められた手順のリストであって、特に心配するようなことは何もないのです。どんなレベルのプログラマーでも基礎の組み立てブロックのようにタスクを分解するという能力は持っていると考えています。

OK, but why would you ask me to write Quicksort?
================================================

The real problem is not algorithmic design questions per se, but “Computer Science” algorithmic questions, e.g. “build a binary tree” or “write Quicksort”. The objection seems to be that these are irrelevant to front-end development, i.e. you will *never* find yourself doing or dealing with any of this on the web. You’ll spend your time wiring up events, dealing with browser issues or CSS being bonkers (for a change). A few years ago I would have agreed with this point of view, but now I disagree.

> The complex problems we face building apps will, in some cases at least, be eerily similar to “classic” Computer Science problems.

Let me ask you this: **are apps more or less complex than they were 5 years ago?** The answer is, of course, that they are more complex. They are often more complicated as well. This leads me to think that we are going to find (and are already finding) that the problems we face building apps can be eerily similar to “classic” Computer Science problems. It makes sense, then, to understand these problems, as well as the best-known solutions and data structures. Not that you should need to memorize a given solution, but you should know how it solves the problem so that you can either apply a similar strategy to your own code, or know which API or library you need and *why*. This empowers you to avoid reinventing the wheel and to make better choices.

In order to entirely disregard Computer Science, then, you really need to be sure that you have **no use for it**. We saw “print on the web” die and we have moved from simple scripts to building apps. In the same way we are soon going to see expectations of our knowledge and abilities escalate, and it’d be good to be ready for that. We will be building (if we aren’t already) very complicated and complex applications, meaning we will need to understand our code design decisions. And most of the time that walks us right into Computer Science.

Go forth and learn
==================

If you *are* interested in learning about algorithms and Computer Sciencey things, then [Udacity have a course](https://www.udacity.com/course/cs215). It’s in Python, but that’s no bad thing, and you can whack that on your list of Awesome Stuff I Can Do.

Confirmation Bias
=================

In the interests of full disclosure, I should say that I have a Computer Science degree. Am I simply just defending my own experience as the only valid one? No, because I’m **not** saying you can’t be a good developer without first learning Computer Science. That’s not what I think. Many developers for whom I have the highest respect have no formal CS training at all. What they **do** tend to have is a good brain and a desire to learn. In many cases they arrive at very sound CS-like solutions to coding problems, because they perceive the complexity of what they’re asking the computer to do.

In any case the fact that someone can arrive at good solutions doesn’t negate the benefits of actually learning Computer Science and understanding the best-known solutions to various classes of problems. They *will* show up in your apps eventually, if they haven’t already.

Conclusion
==========

Computer Science represents problem spaces very neatly and gives a language for us to discuss complex and complicated problems. Since web development is tending in that direction, that seems like something we should embrace. In fact, that’s *exactly* why I think companies are asking those Computer Science questions.

