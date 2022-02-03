<!--Markdown Tutorial-->
MD Romi  
I am a small learner </br>
Now I Learn Github
---  
# MD Romi  
## MD Romi  
### MD Romi  
#### MD Romi  
###### MD Romi  
###### MD Romi  
<p>This is MD Romi. I am a Developer, Programmer and learner. And I am a student of F.P.I </p>

<i>This is an italic text</i>  
_This is second italic text_ 

__This is an bold text__

<del> Strikethrough </del>  
~~Strikethrough~~  

` Inline code block `  
` <h1> Bangladesh </h1>`  

` Multiple line code block `
```c
#include <stdio.h>

int main()
{
    int x = 0, i, n;
    char str[20];

    scanf("%d\n", &n);

    for (i = 0; i < n; i++)
    {
        scanf(" %[^\n]",str); //x++ ++x
        if(str[1] == ('+'))
        {
            x++;
        }
        else if(str[1] == ('-'))
        {
            --x;
        }
    }
    printf("%d\n", x);



    return 0;
}
```

```javascript
/*====================
7.logical And Or Operators
CMD: [ node 3.chapter_three/7.logicalAndOr.js ]
===================*/
//7.logicalAndOr.js

var name = ''
var myName = ''
var myFirstName = ' ' 

//1
if(myName.length == 0){
    myFirstName = 'Md Romi' 
} else{
    myFirstName = name 
}
console.log(myFirstName.length) // result [7]

//2
var fullName = name || 'MD Romi'
console.log(fullName)

//3
var isOk = true
if(isOk){
    console.log('Everything is Ok')
}
isOk && console.log('Everything is Ok')
```
--- 

__List In HTML__  
<ol>
    <li> Item1 </li>
    <li> Item2 </li>
    <li> Item3 </li>
</ol>

__Order List of Markdown__  
1. Item1
1. Item2
3. Item3  
    i. Sub Item 3.1  
    ii. Sub Item 3.2  
    iii. Sub Item 3.3  
4. Item4
5. Item5  

</br>

__Unorder List of Markdown__ 
- Item 1
- Item 2
- Item 3  
    - Item3.1
    - Item3.2
    - Item3.3
- Item 4
- Item 5

__Task List__ 
- [x] Item 1
- [x] Item 2
- [] Item 3

</br>

__Automatic Link__   
https://www.mdromi.com

__Desable Link__   
`https://www.mdromi.com`

__Markdown Link Sytax__   
<p> [title](link) </p>
[Md Romi](https://www.mdromi.com)

<p> Second Methods </p>
[Md Romi][websitelink]   

[facebook][facebooklink] 

</br>

__Image Sytax__  
<p>![alt text](image) </p>  
![Profile](./images/MdRomi.jpg)
<img src = "./images/Md_Romi.jpg" title = "Profile Image"/>
🙂



</br>

__Table Sytax__  
| Name | Email |   
| ------- | ----- |
| MD Romi | Text is here |
| MD Romi | Text is here |
| MD Romi | Text is here |
| MD Romi | Text is here |
| MD Romi | Text is here |


<!-- All link is here-->
[websitelink]: https://www.mdromi.com
[facebooklink]: https://www.facebook.com