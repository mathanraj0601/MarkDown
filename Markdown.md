# Markdown 
```
Markdowns are ' lightweight ' markup language 
It is used to format text, add images, etc. in GitHub 
We can convert it to HTML and host it as a static page
Like HTML it also has elements or tags like headings, paragraphs, etc.
below are the examples and the results of the tags
```



<details>
 <summary>
   Headings ( h1-h6 )
  </summary>

```
#heading1 -> h1
##heading2 -> h2 
###heading3 -> h3
####heading4 -> h4
#####heading5 -> h5
######headings -> h6
```
> Tip :
> 1. Always try to nest the heading incorrectly way that helps to have a table of content
> 1. Only one # heading 1 in the markdown file

### Output :
# heading1
## heading2
### heading3
#### heading4
##### heading5
###### heading6
</details>


<details>
 <summary>Styling Fonts</summary>
 
```
Bold -> **bold**
Italic -> *italic*
strike through -> ~~strike through~~
```
Output

- Bold -> **bold**
- Italic -> *italic*
- strike through -> ~~strike through~~
</details>

<details>
<summary> Links </summary>
 
```
to external websites, GitHub repos, etc.,
["put-the-word-that-you-need-to-display"](the-actual-link-to-website)
The google website [link](www.google.com)
```
Output :
The google website [link](www.google.com)
</details>

<details>
<summary>Images</summary>
 
```
to add relative or global images
![alt-text](image-link)
![github-image](https://qph.cf2.quoracdn.net/main-qimg-b2ffb3a32c2e07826c887815599de6f3)
```
output :

![github-image](https://qph.cf2.quoracdn.net/main-qimg-b2ffb3a32c2e07826c887815599de6f3)
</details>

<details>
 <summary>
  List
 </summary>
 
ordered, unordered, nested, and tass list

```
ordered 

1. one
2. two
3. three
```
> Tip: is to use 1. in front of all so that if we change the order we don't need to manage the numbering
example

```
correct sequence

1. one
2. two
3. three
```
output

1. one
2. two
3. three

```
changed sequence number not changed 

2. two
1. one
3. three
```
output

2. two
1. one
3. three

```
if we use 1. in all elements of the list then the number will change automatically

2. two
1. one
3. three
```

output

1. two
1. one
1. three

```
unordered list

-one 
-two
-three

or

*one
*two 
*three
```

output

- one 
- two 
- three


* one 
* two 
* three

```
> Tip: it is recommended to use '-' over '*' to avoid confusion between bold and unordered lists.

Task list
very use full in PR and issue where we show the progress in comment

-[]one
-[]two
-[]three

```

output
- [ ] one
- [ ] two
- [ ] three

```
put x inside the bracket to make it tick or mark it complete

-[x]one
-[x]two
-[ ]three
```

Output :

- [x] one
- [x] two
- [ ] three

```
Nested list

-one
  -one.one
-two
  -two.one
  -two.two

give a indent to make it as a nested list
```
output

- one
  - one.one
- two
  - two.one
  - two.two

</details>

<details>
 <summary> Tables </summary>
 
```
|c1|c2|c3|
|:---|:---:|---:|
|r1 c1|r2 c2| r3 c3|

|| use to give a cell
:--- left align
:---: center align
---: right align
```

output

| c1 | c2 | c3 |
| :--- | :---: | ---: |
| r1 c1 | r2 c2 | r3 c3 |
</details>



<details>
 <summary>
  Block and Inline element
 </summary>

```


it is used as an inline and block element as it helps us to write code in a particular language, show the diff or changes that we make

this is an 'inline' element

> Note: The actual syntax is ``` for closing and ending. Ignore the quotation in the code below
```
output

this is an 'inline' element

```

"```
Block element
``"

Code in Typescript

"``` ts
    const first name='mathan'
```"

Show the difference

"``` diff
+const first name='mathan raj
-const first name='mathan'
```"

```
output

```
Block element
```


``` ts
    const first name='mathan'
```

``` diff
+ const first name='mathan raj
- const first name='mathan'
```

</details>

<details>
 <summary>
  Quotes
 </summary>

```
it is very helpful in mentioning the context and answering the question

Q/A

> Who are you
I am Mathan

```
output

> Who are you

I am Mathan

</details>

<details>
 <summary>
  context
</summary>
 
```
> Can we go with option 2 
Yes  we can go with option 2 it is a great way of doing it

```
output

> Can we go with option 2 

Yes  we can go with option 2 it is a great way of doing it

</details>

<details>
 <summary>
  Comments
 </summary>

```
We can use the same comments we use in HTML to comment  on markdown
"<!-- This is a comment  -->"

```
Output
<!-- This is a comment -->
>  Note: Commented text is not visible

</details>

<details>
 <summary>
  Collapsable content

 </summary>
 

```
To have collapsable content like expand and view 

we use two tags like summary, details

<details>
<summary> 
    Click here
</summary>
    You have clicked
</details>

```
output

<details>
<summary> 
    Click here
</summary>
    You have clicked
</details>

</details>

```
 Note: We can use markdown and HTML on the same page but cannot mix in the same component
```
