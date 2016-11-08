# myself_demo
开发相关总结
> 1. 倍增类型

> nav>ul>li

```
<nav>
    <ul>
        <li></li>
    </ul>
</nav>
```
> div+p+bq

```
<div></div>
<p></p>
<blockquote></blockquote>
```
> div+div>p>span+em^bq
 
```
<div></div>
<div>
    <p><span></span><em></em></p>
    <blockquote></blockquote>
</div>

```
> 2. 倍增类型

> ul>li*5

```

<ul>
    <li></li>
    <li></li>
    <li></li>
    <li></li>
    <li></li>
</ul>
```
> ul>li.item$*5

```
<ul>
    <li class="item1"></li>
    <li class="item2"></li>
    <li class="item3"></li>
    <li class="item4"></li>
    <li class="item5"></li>
</ul>
```
> h$[title=item$]{Header $}*3

```
<h1 title="item1">Header 1</h1>
<h2 title="item2">Header 2</h2>
<h3 title="item3">Header 3</h3>
```
> ul>li.item$$$*5

```
<ul>
    <li class="item001"></li>
    <li class="item002"></li>
    <li class="item003"></li>
    <li class="item004"></li>
    <li class="item005"></li>
</ul>
```
> ul>li.item$@-*5

```
<ul>
    <li class="item5"></li>
    <li class="item4"></li>
    <li class="item3"></li>
    <li class="item2"></li>
    <li class="item1"></li>
</ul>
```
> ul>li.item$@3*5

```
<ul>
    <li class="item3"></li>
    <li class="item4"></li>
    <li class="item5"></li>
    <li class="item6"></li>
    <li class="item7"></li>
</ul>
```
> 3. ID 和 class 属性写法

> #header

```
<div id="header"></div>
```
> .title

```
<div class="title"></div>
```
> form#search.wide

```

<form id="search" class="wide"></form>
```
> p.class1.class2.class3

```

<p class="class1 class2 class3"></p>
```

> p[title="Hello world"]

```
<p title="Hello world"></p>
```
> td[rowspan=2 colspan=3 title]

```
<td rowspan="2" colspan="3" title=""></td>
```
> [a='value1' b="value2"]

```
<div a="value1" b="value2"></div>
```
> 4. text文本设置{}

> a{Click me}

```

<a href="">Click me</a>
```
> p>{Click }+a{here}+{ to continue}

```
<p>Click <a href="">here</a> to continue</p>
```
> 4. 隐形类

> .class

```
<div class="class"></div>
```
> em>.class

```
<em><span class="class"></span></em>
```

> ul>.class

```
<ul>
    <li class="class"></li>
</ul>
```
> table>.row>.col

```
<table>
    <tr class="row">
        <td class="col"></td>
    </tr>
</table>
```
> 5. html

> !

```
<html>
<head>
    <meta http-equiv="Content-Type" content="text/html;charset=UTF-8" />
    <title>Document</title>
</head>
<body>
    
</body>
</html>
```
> input:tel

```
<input type="tel" name="" id="" />
```

> input:number

```
<input type="number" name="" id="" />

```
> input:color

```
<input type="color" name="" id="" />
```
> input:checkbox或者input:c

```
<input type="checkbox" name="" id="" />
```
> input:radio或者 input:r

```
<input type="radio" name="" id="" />
```
> input:range

```

<input type="range" name="" id="" />
```
> input:file或者 input:f

```
<input type="file" name="" id="" />
```
> input: submit或者 input: s

```
<input type="submit" value="" />
```
> input:image或者 input:i

```
<input type="image" src="" alt="" />
```
> input:button, input:b

```

<input type="button" value="" />
```
> input:reset

```
<input type="reset" value="" />
```
> input:hidden, input:h

```
<input type="hidden" name="" />

```
> input:text, input:t

```
<input type="text" name="" id="" />
```
> input: search

```
<input type="search" name="" id="" />
```
> 

```

```
> select

```
<select name="" id=""></select>
```
> select:disabled, select:d

```
<select name="" id="" disabled="disabled"></select>
```
> option, opt

```
<option value=""></option>
```
> textarea

```
<textarea name="" id="" cols="30" rows="10"></textarea>
```
> marquee

```
<marquee behavior="" direction=""></marquee>
```
> 

```

```
> 

```

```
> 

```

```
> 

```

```





