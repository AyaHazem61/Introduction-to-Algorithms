# ***This is a Note on whatever***
## this a smaller header
### and smaller
#### and smallest
[ get to code ](#creating-code-blocks)

[ Link of this tutorial ](https://www.youtube.com/watch?v=bTVIMt3XllM)

text without "#" before it will be automatically rendered as a paragraph.

**Bold Text**

*Italic Text*

~~crossed text~~

***~~Bold/Italic/crosses~~***

**Ordered List:**

1. first
    1. sub list
    1. 
    1. 
1. second
1. third

**Unordered List**
- one
- two
    - nested 
    - qsds
        - aaa
        - ooo

## **Creating code blocks**

---
```py
def binary_search(ls, target):
    left = 0
    right = len(ls) - 1
    while left <= right:
        mid = (left + right) // 2  # This formula might overflow
        mid = left + (right - left) // 2
        if ls[mid] == target:
            return mid
        elif ls[mid] > target:
            right = mid - 1
        else:
            left = mid + 1
    return -1
```
---

quote from somewhere

> This *is* a block **quote**
>> ~~nested~~ block quote -- <cite>writer</cite>

**attach image**

[![I hate Vscode](./data/img.jpg)](https://www.youtube.com/watch?v=bTVIMt3XllM)

- [ ] task #1
- [ ] task #2

## Table
| C1 | C2 | C3 |
| :----- | :----- | :----- |
| X | | |
| O | X | O |
| X | O | O |

<details>
<summary>Show more</summary>
more <br> txt <br> txt <br> tx

# list

- a
- b
- c

</details>
