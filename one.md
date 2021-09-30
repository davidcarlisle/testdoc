# example page


Some inline math \\(e=mc^2\\)


some display math
{% raw %}
$$
\frac{x+y}{y+z}\begin{pmatrix}1&2\\3&4\\5&6\end{pmatrix}
$$
{% endraw %}


Some Java


```java
public class HelloWorld {

    public static void main(String[] args) {
        // Prints "Hello, World" to the terminal window.
        System.out.println("Hello, World");
    }

}
```

Some more text with a list

* one
* two
* three



<details markdown=1>
<summary><span markdown=1>a summary with **bold** </span></summary>

a list5


* onez
* twoz
* threez

</details>


<details markdown=1>
<summary>a summary with <b>html bold</b></summary>

a list


* aaa
* bbbb
* ccc

</details>


## nested details

with a table



| a | b |
| 1 | 2 |



<details markdown=1>
<summary>a summary for an outer details</summary>

a list


* aaa
* bbbb
* ccc

    <details markdown=1>
    <summary>nested details</summary>

    a nested table

    | a | b |
    | 1 | 2 |

    </details>

* ddd

</details>


## more markdown

zzz
