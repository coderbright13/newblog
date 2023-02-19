---
title: "Helloworld2"
subtitle: ""
date: 2023-01-01T00:40:36+08:00
lastmod: 2023-01-01T00:40:36+08:00
draft: false
authors: [waitbright, PCloud]
description: ""

tags: ["test"]
categories: ["good"]

series: ["aa"]
series_weight: 1

hiddenFromHomePage: false
hiddenFromSearch: true

featuredImage: "/images/avatar.png"
featuredImagePreview: ""

toc:
  enable: true
math:
  enable: true
lightgallery: false
license: ""
---

三星
apple
<!--more-->

## 龙头企业
- 三星
- 美国
- 法国

```go
package main

import "fmt"

func main() {
    fmt.Println("hello")
}
```

## 随便写写
这是一个很长的故事，需要慢慢道来。
今天是一个阳光明媚的上午，我很开心，有好的事情要发生，看了《徐云流浪中国》
### 咚咚锵
这是一个很棒的故事
#### hello world
### world
明天会更好![oo](/assets/images/avatar.png)
### world2
hello this is a good test
emoj
:joy: :smile: :angry: :cry:

{{< figure src="/images/lighthouse.webp" title="Lighthouse (figure)" >}}


{{< highlight html >}}
<section id="main">
    <div>
        <h1 id="title">{{ .Title }}</h1>
        {{ range .Pages }}
            {{ .Render "summary"}}
        {{ end }}
    </div>
</section>
{{< /highlight >}}

{{< mermaid >}}graph LR;
    A[Hard edge] -->|Link text| B(Round edge)
    B --> C{Decision}
    C -->|One| D[Result one]
    C -->|Two| E[Result two]
{{< /mermaid >}}

{{< mermaid >}}sequenceDiagram
    participant Alice
    participant Bob
    Alice->>John: Hello John, how are you?
    loop Healthcheck
        John->John: Fight against hypochondria
    end
    Note right of John: Rational thoughts <br/>prevail...
    John-->Alice: Great!
    John->Bob: How about you?
    Bob-->John: Jolly good!
{{< /mermaid >}}


showcase 用于在页面上插入一个个人项目的展示柜.

showcase shortcode 有以下命名参数:
- title [required] (第一个位置参数)
项目名称.
- summary [required] (第二个位置参数)
项目简介.
- image [required] (第三个位置参数)
预览图的链接.
- link [required] (第四个位置参数)
项目主页的链接.
- column [optional] (fifth positional parameter)
这个参数定义一行显示几个 showcase. 默认的值是 2, 默认一行显示两个 showcase. 你可以将它改为 1, 2 或 3. 需要注意的是, 当用户使用小屏幕访问网站时, 每行显示的 showcase 数量将会被自动调整以保证最好的体验.