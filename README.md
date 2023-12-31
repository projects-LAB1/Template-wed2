# Template-wed2
### Support Me

<ul style="list-style-type: none; margin: 0;">

<li style="display: inline-block; margin-right: 0.25rem;"><a href="https://www.buymeacoffee.com/xateeeiun0"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" width="150"/></a></li>

</ul>

## Run Locally
**Clone the project**

```bash
  git clone [https://github.com/projects-LAB1/Template-wed2.git)
```
**Go to the project directory**

```bash
  cd Template-wed2
```

![App Screenshot](https://i.pinimg.com/736x/53/38/5c/53385c7abf608b5b3359e3eda8f1d0c5.jpg)
## UML diagrams


<!--You can render UML diagrams using [Mermaid](https://mermaidjs.github.io/). For example, this will produce a sequence diagram:  -->

```mermaid
sequenceDiagram
Alice ->> Bob: Hello Bob, how are you?
Bob-->>John: How about you John?
Bob--x Alice: I am good thanks!
Bob-x John: I am good thanks!
Note right of John: Bob thinks a long<br/>long time, so long<br/>that the text does<br/>not fit on a row.

Bob-->Alice: Checking with John...
Alice->John: Yes... John, how are you?
```

And this will produce a flow chart:

```mermaid
graph LR
A[Square Rect] -- Link text --> B((Circle))
A --> C(Round Rect)
B --> D{Rhombus}
C --> D
```

And this will produce a flow chart:
```mermaid
erDiagram
    CUSTOMER ||--o{ ORDER : places
    ORDER ||--|{ LINE-ITEM : contains
    CUSTOMER }|..|{ DELIVERY-ADDRESS : uses
```
