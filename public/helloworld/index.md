# Helloworld


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


