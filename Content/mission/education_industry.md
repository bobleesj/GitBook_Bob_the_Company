# Education Industry

## Sources of Learning
| Category | Platforms |
| --- | --- |
| Blog | Medium, Ray Wenderlich, App Coda We Heart Swift |
| Q&A | Stack Overflow, Quora |
| Online Course | Treehouse, Stanford, Coursera, Udemy, Devslopes |
| Book | Raywenderlich, Big Nerd Ranch
| eBook | Swift Document |
| Conference | Realm.io |
| YouTube | Let's build that app, The Swift Guy | 

Take a look at this video:

{% youtube src="https://www.youtube.com/watch?v=9bZkp7q19f0" %}{% endyoutube %}


<div align=center>

<img src="/assets/images/favicon-32x32.png"/>

```mermaid
graph TD;
  A-->B;
  A-->C;
  B-->D;
  C-->D;
```
</div>

<div align="center">
```mermaid
sequenceDiagram
    participant Alice
    participant Bob
    Alice->>John: Hello John, how are you?
    loop Healthcheck
        John->>John: Fight against hypochondria
    end
    Note right of John: Rational thoughts <br/>prevail...
    John-->>Alice: Great!
    John->>Bob: How about you?
    Bob-->>John: Jolly good!
```
</div>


<div align="center">
```mermaid
graph LR
    id1(This is the text in the box);
```
</div>

<div align="center">
```mermaid
graph LR
    id1((This is the text in the circle))
```
</div>


<div align="center">
```mermaid
graph TD
    B["fa:fa-twitter for peace"]
    B-->C[fa:fa-ban forbidden]
    B-->D(fa:fa-spinner);
    B-->E(A fa:fa-camera-retro perhaps?);
```
</div>


```mermaid
graph LR
     A-->B
     B-->C
     C-->A
     D-->C
```


```mermaid
graph TB
        subgraph one
        a1-->a2
        end
        subgraph two
        b1-->b2
        end
        subgraph three
        c1-->c2
        end
        c1-->a2
```

```mermaid
graph LR;
    A-->B;
    click A callback "Tooltip for a callback"
    click B "http://www.github.com" "This is a tooltip for a link"
```
