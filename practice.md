是一级標題
=======

# 一級標題
## 二级標題
### 三级標題
#### 123

```
function(){
    conso.log("Hello World");
}
```

---
* tony
* mary

1. jason
2. joe
3. terrens

[hyperlink](sample.com)

picture


![text](picture.site.jpg)

後面要加 tab
> 123123    
> 123123


| Column 1 | Column 2 | Column 3 |
| -------- | -------- | -------- |
| Text     | Text     | Text     |


|姓名|性别|年龄|國籍|
  |---|----|----|---|
  |有大JJ的妹子|男|94|日本|
  |有大ㄋㄋ的漢子|女|87|美國|



This is an H1
=============

This is an H2
-------------



# This is an H1

## This is an H2

###### This is an H6


# This is an H1 #

## This is an H2 ##

### This is an H3 ######


> This is a blockquote with two paragraphs. Lorem ipsum dolor sit amet,
> consectetuer adipiscing elit. Aliquam hendrerit mi posuere lectus.
> Vestibulum enim wisi, viverra nec, fringilla in, laoreet vitae, risus.
> 
> Donec sit amet nisl. Aliquam semper ipsum sit amet velit. Suspendisse
> id sem consectetuer libero luctus adipiscing.

---

> This is a blockquote with two paragraphs. Lorem ipsum dolor sit amet,
consectetuer adipiscing elit. Aliquam hendrerit mi posuere lectus.
Vestibulum enim wisi, viverra nec, fringilla in, laoreet vitae, risus.

> Donec sit amet nisl. Aliquam semper ipsum sit amet velit. Suspendisse
id sem consectetuer libero luctus adipiscing.

---

> This is the first level of quoting.
>
> > This is nested blockquote.
>
> Back to the first level.

---

> ## This is a header.
> 
> 1.   This is the first list item.
> 2.   This is the second list item.
> 
> Here's some example code:
> 
>     return shell_exec("echo $input | $markdown_script");

---
項目標記後面則一定要接著至少一個空白或tab。
*   Lorem ipsum dolor sit amet, consectetuer adipiscing elit.
    Aliquam hendrerit mi posuere lectus. Vestibulum enim wisi,
    viverra nec, fringilla in, laoreet vitae, risus.
*   Donec sit amet nisl. Aliquam semper ipsum sit amet velit.
    Suspendisse id sem consectetuer libero luctus adipiscing.

---

*   Lorem ipsum dolor sit amet, consectetuer adipiscing elit.
Aliquam hendrerit mi posuere lectus. Vestibulum enim wisi,
viverra nec, fringilla in, laoreet vitae, risus.
*   Donec sit amet nisl. Aliquam semper ipsum sit amet velit.
Suspendisse id sem consectetuer libero luctus adipiscing.

---

*   Bird
*   Magic

<address@example.com>

![Alt text](/path/to/img.jpg)

![Alt text](/path/to/img.jpg "Optional title")

- [x] This is a complete item
- [ ] This is an incomplete item

`Format one word or one line`

    code (4 spaces indent)

---

> Quote one sentences 
>>Quote two sentences 
>>>Quote three sentences 
---
*your text* 

_your text_ 

~~your text~~ 

~ your text ~

>Quote one sentence
>>> Quote multiple sentences

`Format one word or one line*`


    ```
    Format blocks of text
    ```



FB Messenger 使用 Markdown 語法來改變訊息格式有一點需要注意，行動裝置版本的 Messenger 是不會改變訊息格式的，會直接連帶將符號一起傳送（如下圖），只有電腦網頁版（上圖）才會顯示出改變，而上一個介紹的 Slack 則沒有這個問題，不論是電腦網頁版或是手機版都可以顯示出不同的文字格式。

**粗體**

*斜體*

~~刪除線~~

- 清單

- [ ] 待辦事項

- [ ] A任務
- [ ] B任務
- [x] C任務
- [ ] D任務

***
分隔線


mermaid
graph LR
A[Hard edge] -->B(Round edge)
    B --> C{Decision}
    C -->|One| D[Result one]
    C -->|Two| E[Result two]


sequence
Alice->Bob: Hello Bob, how are you?
Note right of Bob: Bob thinks
Bob-->Alice: I am good thanks!


$$
\begin{align*}
y = y(x,t) &= A e^{i\theta} \\
&= A (\cos \theta + i \sin \theta) \\
&= A (\cos(kx - \omega t) + i \sin(kx - \omega t)) \\
&= A\cos(kx - \omega t) + i A\sin(kx - \omega t)  \\
&= A\cos \Big(\frac{2\pi}{\lambda}x - \frac{2\pi v}{\lambda} t \Big) + i A\sin \Big(\frac{2\pi}{\lambda}x - \frac{2\pi v}{\lambda} t \Big)  \\
&= A\cos \frac{2\pi}{\lambda} (x - v t) + i A\sin \frac{2\pi}{\lambda} (x - v t)
\end{align*}
$$

---


|姓名|性别|年龄|國籍|
  |---|----|----|---|
  |有大JJ的妹子|男|94|日本|
  |有大ㄋㄋ的漢子|女|87|美國|



最後沒加 tab

這是第一行
這是第二行

---

最後有加 tab 加空白也可以

這是第一行  
這是第二行

LaTeX

$\sum_{k=1}^{k=n} k^2 = \frac{n(n+1)(n+2)}{6}$

超連結
======

* 超連結
<http://example.com> 
[超連結文字01](http://example.com) 


這個地方的`[sample]`為文件唯一值，不然多個地方出現會出現語法渲染錯誤 
[sample] 

[sample]: http://example.com

* 圖片 (最前面多個`!`)
![sampleImage](SampleImage01.png) 


分隔線 (`---`上都為空行才會變分隔線，不然會把上面一行變成 h2 標題)


--- 

分隔線
*** 

區塊文字(前面加 4 個空格) 
    Lorem ipsum dolor sit amet, consectetuer adipiscing Lorem ipsum dolor sit amet, consectetuer adipiscing Lorem ipsum dolor sit amet, consectetuer adipiscing Lorem ipsum dolor sit amet, consectetuer adipiscing