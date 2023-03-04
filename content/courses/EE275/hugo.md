---
title: C?. Hugo ShortCode Demo
date: '2023-03-04'
type: book
weight: 100
---

<!--more--> <!-- This also prevent a abstract appearing in CoursePage -->

{{< icon name="clock" pack="fas" >}} 


## Hugo shortcode and its template
This is explained [here.](https://discourse.gohugo.io/t/can-we-use-hugo-commands-in-markdown-files/4937)


{{< myshortcode color="blue" >}} 

{{< myshortcode2 red >}} 

{{< myshortcode3 green >}} 
    **Oh** you cannot use markdown ~~here~~
{{< /myshortcode3 >}}

<!-- 如果不在一行里就不能改背景色了！ -->
{{% myshortcode3 green %}} 
**Now** you can use markdown ~~here~~ but you lose background color lol
{{% /myshortcode3 %}}


<!-- Two options for figure 但是注意，当前目录是_index.md所在的目录，即.\mmlabSiteGit\content\courses，所以要往上走一层 -->

<!-- shortcode figure -->
{{< figure src="../python_logo.png" title="Figure 1: ..." >}}
    
<!-- markdown figure -->
![png](../python_logo.png)
