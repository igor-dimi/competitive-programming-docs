
---
title: "Page One"
weight: 1
# bookFlatSection: false
# bookToc: true
# bookHidden: false
# bookCollapseSection: false
# bookComments: true
---


This is some content

{{<button relref="/" >}} Get Home {{</button >}}

{{< columns >}}
# Left Content

Here is some content. Lorem ipsum dolor sit amet
<--->

# Mid Content
there is yet another content...

<--->

# Right Content
There is another one. Let me go ahead and type a little more
{{< /columns >}}

{{< details title="Title" >}}
## Some content
This is some content
{{< /details >}}


{{< expand >}}
## This is to expand
Look at all these chicken
{{< /expand >}}

{{< hint info >}}
**Importnat**  
Some times you need to blah blah and blah blah regardless of blah blah blah
{{< /hint >}}

{{< hint danger >}}
**Don't forget!**  
You should never forget to blah blah
{{< /hint >}}

I really don't know man... let me try something else..:
{{< katex >}}
\sum_{i=1}^{10}a_i^2 
{{< /katex >}}
Is this it?

I didn't understand why this is not working as I intended it to... ? 
{{< katex display >}}
f(x) = \int_{-\infty}^\infty\hat f(\xi)\,e^{2 \pi i \xi x}\,d\xi
{{< /katex >}}

```cpp
int main(int argc, char** argv){
    std::cout << "Hello world!" << std::endl;
    return 0;
}
```

{{< mermaid class="text-center">}}
graph TD;
    A --> B;
    A --> C;
    B --> D;
    C --> D;
{{< /mermaid >}}

```bash
$ echo 'hey there'
```

{{< tabs >}}
{{< tab "MacOS" >}} # MacOS Content  
Here ocmes the MacOS content... so on
{{< /tab >}}
{{< tab "Linux" >}} # Linux Content  
This is the Linux content
{{< /tab >}}
{{< /tabs >}}


[homework](/something.pdf)


[link to second page](/competitive-programming-docs/docs/page-two)  

<https://www.wikipedia.org>




