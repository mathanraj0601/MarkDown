Markdown are light weight markup language 
It is used to format text,add images etc in github 
we can able convert it to html and host as a static page

Like Html it also have elements or tags like heading,paragragh ect..

below are the example and the result of the tags

Headings ( h1-h6 )

#heading1 -> h1
##heading2 -> h2 
###heading3 -> h3
####heading4 -> h4
#####heading5 -> h5
######headings -> h6

Tip : 
1,Always try to nest the heading in correct way that help to have a table of content
2,only one # heading 1 in the markdown file

output :
#heading1
##heading2
###heading3
####heading4
#####heading5
######headidng6


Styling Fonts

Bold -> **bold**
Italic -> *italic*
strike through -> ~~strike through~~

Links 

to external website,github repos etc.,

["put-the-word-that-you-need-to-display"](the-actual-link-to-website)

Output :
The google website [link](www.google.com)

Images

to add relative or global images

![alt-text](image-link)

output
![github-logo](https://www.google.com/url?sa=i&url=https%3A%2F%2Fgithub.com%2Flogos&psig=AOvVaw3P-_6U_MqfQnJFRxd5Porq&ust=1693114933964000&source=images&cd=vfe&opi=89978449&ved=0CBAQjRxqFwoTCNiXuePO-YADFQAAAAAdAAAAABAE)

List 

ordered,unordered ,nested and tass list

ordered 

1.one
2.two
3.three

tip: is to use 1. infront all so that if we change the order we don't need to manage the numbering
example

output :

correct sequence

1.one
2.two
3.three

output

1. one
2. two
3. three

changed sequence number not changed 

2.two
1.one
3.three

output

2. two
1. one
3. three

if we use 1. in all element of the list then number will change automatically

2. two
1. one
3. three

output

1. two
1. one
1. three

unordered list

-one 
-two
-three

or

*one
*two 
*three

output

- one 
- two 
- three


* one 
* two 
* three

Tip : it is recommended to use '-' over '*' so that no confusion between bold and unordered list.

Task list
very use full in PR and issue where we show the progress in comment

-[]one
-[]two
-[]three

output
- []one
- []two
- []three

put x inside the bracket to make it tick or mark it complete

-[x]one
-[x]two
-[ ]three

example
- [x]one
- [x]two
- [ ]three

Nested list

-one
 -one.one
-two
 -two.one
 -two.two

give a indent to make it as a nested list

output

- one
 - one.one
- two
 - two.one
 - two.two


Tables

|c1|c2|c3|
|:---|:---:|---:|
|r1 c1|r2 c2| r3 c3|

|| use to give a cell
:--- left align
:---: center align
---: right alignn

output

| c1 | c2 | c3 |
| :--- | :---: | ---: |
| r1 c1 | r2 c2 | r3 c3 |

code

it is used as inline and block element as it help us to write code in particular language , show the diff or changes what we make

this is a 'inline' element

output

this is a 'inline' element

'''
Block element
'''

'''ts
    const first name='mathan'
'''

''' diff
+const first name='mathan raj
-const first name='mathan'
'''

output

'''
Block element
'''

'''ts
    const first name='mathan'
'''

''' diff
+ const first name='mathan raj
- const first name='mathan'
'''

Quotes 

it is very helpful in mentioninng the context and answering the question

Q/A

>who are you
i am mathan

output

> who are you

i am mathan

context

>can we go with option 2 
Yes  we can go with option 2 it a great way of doing it

output

> can we go with option 2 

Yes  we can go with option 2 it a great way of doing it


Comments
We can use the same comments we use in html to comment  ini markdown
"<!--  -->"

Example

This is a comment

<!-- This a  commnet -->


Collapsable content

To have collapsable content like expand and view 

we use two tags like summary,details

<details>
<summary> 
    Click here
</summary>
    You have clicked
</details>

output

<details>
<summary> 
    Click here
</summary>
    You have clicked
</details>

We can use markdown and html in the same page but cannot mix in the same component
