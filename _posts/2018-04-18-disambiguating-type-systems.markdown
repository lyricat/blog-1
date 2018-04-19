---
title: Disambiguating language type systems
date: 2018-04-19 11:18:17
---

<link href='{{ site.url }}/stylesheets/main.css' rel='stylesheet' type='text/css' />


A common mistake people make is conflating *strong* typing with *static* typing. 

There are four key terms when discussing a languages type system:

* Strong typing
* Weak typing
* Static typing
* Dynamic typing

A *strongly* typed language is one in which the type of a variable is explicitly declared, like in C++ or Java:

```c++
int mNum = 3;
char mWord = "hello";
```

A *weakly* typed language is one in which the type is *not* explicitly declared, like in Python or JavaScript:

```js
let mNum = 3;
let mWord = "hello";
```

A *statically* typed language is one in which the type of an object cannot change, such as in Python


```python
m_num = 3
m_num = "hello" # Error!
```

A *dynamically* typed language is one in which the type of the object *can* change, like in JavaScript:

```js
let mNum = 3;
mNum = "hello"; // Valid!
```


### Notes

As far as I know, all **strongly** typed languages are *static* - strong is a superset of static. Below are some examples of languages and where they fit in the type system described above.

<div class="table100 tableTop ver1 m-b-110">
	<table data-vertable="ver1">
		<thead>
			<tr class="row100 head">
				<th class="column100 column1" data-column="column1"></th>
				<th class="column100 column2" data-column="column2">Static Typing</th>
				<th class="column100 column3" data-column="column3">Dynamic Typing</th>
			</tr>
		</thead>
		<tbody>
			<tr class="row100">
				<td class="column100 column1" data-column="column1">Strong Typing</td>
				<td class="column100 column2" data-column="column2">C++, Java</td>
				<td class="column100 columnred column3" data-column="column3">--</td>
			</tr>
			<tr class="row100">
				<td class="column100 column1" data-column="column1">Weak Typing</td>
				<td class="column100 column2" data-column="column2">Python</td>
				<td class="column100 column3" data-column="column3">JavaScript</td>
			</tr>
		</tbody>
	</table>
</div>