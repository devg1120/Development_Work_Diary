
<!-- TO DO: add more details about me later -->

<style>
H1{color:Blue !important;}
H2{color:DarkOrange !important;}
p{color:Black !important;}
</style>

# Color Test Document

## Second Heading

This is a test to see how the colors work.

### HISTORY
| MM/DD | TARGET |　DETAIL |
| ---- | ---- | ----|
| TD | TD | TD |
| TD | TD | TD |


## Tasks
- [ ] #1
- [ ] https://github.com/jlord/sheetsee.js/issues/26
- [ ] task
- [x] done task

```suggestion
This is only suggested change code!!
```

Here is a simple footnote[^1].

A footnote can also have multiple lines[^2].

[^1]: My reference.
[^2]: To add line breaks within a footnote, prefix new lines with 2 spaces.
  This is a second line.

<span style="color:orange;">Word up</span>


#  Development work diary
<details  open>
<summary>MarkDown languages</summary>

---

# 見出し1です
## 見出し2です
### 見出し3です

これは **太字** です。
これは __太字__ です。

これは *斜体* です。
これは _斜体_ です。

これは ~~訂正線~~です。
これは<u>下線</u>です。

[tex colors](https://gist.github.com/luigiMinardi/4574708d404cdf4fe0da7ac6fe2314db)

$\color{red}{\textsf{lorem ipsum}}$	
$\color{#f00}{\textsf{lorem ipsum}}$	

$\color{rgb(255,0,0)}{\textsf{lorem ipsum}}$	
$\color{rgba(255,0,0, 0.4)}{\textsf{lorem ipsum}}$	

$\color{hsl(0,100%,50%)}{\textsf{lorem ipsum}}$	
$\color{hsla(0,100%,50%, 0.4)}{\textsf{lorem ipsum}}$	

$\textcolor{red}{\textsf{lorem ipsum}}$

$\color{blue}{\textsf{lorem ipsum}}$	

$\color{green}{\textsf{lorem ipsum}}$	

$\Huge{\textsf{lorem ipsum}}$	


## Font Styles

To change the font style you need to add suffixes to the `\text`.  

|suffix|   syntax  |          command         |          result         |
| ---  |    ---    |            ---           |           ---           |
`none` |  `\text`  |  `$\text{lorem ipsum}$`  | $\text{lorem ipsum}$
`\rm`  | `\textrm` | `$\textrm{lorem ipsum}$` | $\textrm{lorem ipsum}$
`\sf`  | `\textsf` | `$\textsf{lorem ipsum}$` | $\textsf{lorem ipsum}$
`\bf`  | `\textbf` | `$\textbf{lorem ipsum}$` | $\textbf{lorem ipsum}$
`\up`  | `\textup` | `$\textup{lorem ipsum}$` | $\textup{lorem ipsum}$
`\tt`  | `\texttt` | `$\texttt{lorem ipsum}$` | $\texttt{lorem ipsum}$


### Table with some color examples

| $\color{black}{\textsf{Black}}$ |  $\color{blue}{\textsf{Blue}}$ | $\color{brown}{\textsf{Brown}}$ | $\color{darkgray}{\textsf{Dark Gray}}$  | $\color{gray}{\textsf{Gray}}$ | 
| ------------- | ------------- | ------------- | ------------- | ------------- | 
| $\color{lightgray}{\textsf{Light Gray}}$ |  $\color{green}{\textsf{Green}}$ | $\color{lightblue}{\textsf{Light Blue}}$ | $\color{lime}{\textsf{Lime}}$  | $\color{magenta}{\textsf{Magenta}}$ |
| $\color{olive}{\textsf{Olive}}$ |  $\color{orange}{\textsf{Orange}}$ | $\color{pink}{\textsf{Pink}}$ | $\color{purple}{\textsf{Purple}}$  | $\color{red}{\textsf{Red}}$ | 
| $\color{teal}{\textsf{Teal}}$ |  $\color{violet}{\textsf{Violet}}$ | $\color{white}{\textsf{White}}$ | $\color{yellow}{\textsf{Yellow}}$  | $\color{BurntOrange}{\textsf{Burnt Orange}}$ |


## Font Sizes

|                command              |                result              |
|                  ---                |                 ---                |
`$\Huge{\textsf{lorem ipsum}}$`       | $\Huge{\textsf{lorem ipsum}}$
`$\huge{\textsf{lorem ipsum}}$`       | $\huge{\textsf{lorem ipsum}}$
`$\LARGE{\textsf{lorem ipsum}}$`      | $\LARGE{\textsf{lorem ipsum}}$
`$\Large{\textsf{lorem ipsum}}$`      | $\Large{\textsf{lorem ipsum}}$
`$\large{\textsf{lorem ipsum}}$`      | $\large{\textsf{lorem ipsum}}$
`$\normalsize{\textsf{lorem ipsum}}$` | $\normalsize{\textsf{lorem ipsum}}$
`$\small{\textsf{lorem ipsum}}$`      | $\small{\textsf{lorem ipsum}}$
`$\scriptsize{\textsf{lorem ipsum}}$` | $\scriptsize{\textsf{lorem ipsum}}$
`$\tiny{\textsf{lorem ipsum}}$`       | $\tiny{\textsf{lorem ipsum}}$


> これは引用です。
> これは引用です。これは引用です。
> 

| Rank | Languages |
|-----:|-----------|
|     1| JavaScript|
|     2| Python    |
|     3| SQL       |

これは<span style="color: red; ">赤文字</span>です

これは<span style="color: red; ">赤文字</span>です	

これは<span style="color: gray; ">赤文字</span>です	

これは `code` です

```
from webssh import handler
from webssh.handler import IndexHandler, WsockHandler, NotFoundHandler
from webssh.settings import (
    get_app_settings,  get_host_keys_settings, get_policy_setting,
    get_ssl_context, get_server_settings, check_encoding_setting
)
```
```python
print("Hello World")
```

- [x] #739
- [ ] https://github.com/octo-org/octo-repo/issues/740
- [ ] Add delight to the experience when all tasks are complete :tada:



1. 番号リストA
1. 番号リストB
1. 番号リストB-1
1. 番号リストB-2
1. 番号リストC



The background color is `#ffffff` for light mode and `#000000` for dark mode.




---
</details>

> [!NOTE]
> Highlights information that users should take into account, even when skimming.

> [!TIP]
> Optional information to help a user be more successful.

> [!IMPORTANT]
> Crucial information necessary for users to succeed.

> [!WARNING]
> Critical content demanding immediate user attention due to potential risks.

> [!CAUTION]
> Negative potential consequences of an action.



<!---------------------------------------------------->

<details>
<summary>gswebssh</summary>
  
## TODO
- [x] #739
- [ ] https://github.com/octo-org/octo-repo/issues/740
- [ ] Add delight to the experience when all tasks are complete :tada:

##  gswebssh
-  pytyon based web
-  remote ssh

###  webssh


  - webssh
  - webssh_test
       > python ./main.py --port=8000
###  golden-layout-vite3/
> golden-layout    ES6 modify   vite setting

###  golden-layout-vite3-UIkit/
> goldem-layout     UIkit dashboard      2024/04/31
</details>
<!---------------------------------------------------->



