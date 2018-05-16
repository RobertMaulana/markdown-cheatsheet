# Markdown cheatsheet

---
### A. Cara menulis header
---
##### 1. H1
`#`
##### 2. H2
`##`
##### 3. H3
`###`
##### 4. H4
`####`
##### 5. H5
`#####`

---
### B. Cara menulis garis horisontal
---
##### 1. Triple underscore
`___`
##### 2. Triple dash
`---`
##### 3. Triple bintang
`***`

---
### C. Cara menulis emphasis text
---
##### 1. **Bold**
`**text**`
##### 2. _Italics_
`_text_`
##### 3. ~~Garis tengah~~
`~~text~~`

---
### D. Cara menulis Quote
---
##### 1. Quote level 1
Contoh:
> Quote level 1
```
> Quote level 1
```
##### 2. Quote level 2
Contoh:
> Quote level 1
>> Quote level 2
```
> Quote level 1
>> Quote level 2
```
##### 3. Quote level 3
Contoh:
> Quote level 1
>> Quote level 2
>>> Quote level 3
```
> Quote level 1
>> Quote level 2
>>> Quote level 3
```

---
### E. Cara menulis list
---

##### 1. Unordered list
Contoh:
+ Ini list level 1
    - Ini list level 2

Code:
```
+ Ini list level 1
    - Ini list level 2
```
##### 2. Ordered list
Contoh:
1. Ini ordered list
2. Ini juga
Code:
```
1. Ini ordered list
2. Ini juga
```
---
### F. Cara menulis blok code
---

##### 1. Inline blok code

Contoh:
Untuk menulis huruf, kita bisa menggunakan code html `<b></b>` atau `<strong></strong>`.
Code:
```
Untuk menulis huruf, kita bisa menggunakan code html `<b></b>` atau `<strong></strong>`
```

##### 2. Multiline blok code

Contoh:
Untuk menulis function di javascript kita bisa menggunakan code dibawah ini
```
function exampleFunction () {
    return 0 
}
```
Code: 
Untuk menulis function di javascript kita bisa menggunakan code dibawah ini
` ``` `
function exampleFunction () {
    return 0 
}
` ``` `

##### 3. sintax highlight
Contoh:
Menulis code javascript
```javascript
const palyndrome = (str) => convertPalyndrome(str)
```
Code:
Menulis code javascript
` ```javascript`
const palyndrome = (str) => convertPalyndrome(str)
` ``` `
---
### G. Cara membuat table
---
##### 1. Table original
Contoh:
|No|Desc|
|---|---|
|1|Data structure|
|2|Algoritma|
Code:
```
|No|Desc|
|---|---|
|1|Data structure|
|2|Algoritma|
```

##### 2. Table rata kanan
Contoh:
|No|Desc|
|---|---:|
|1|Data structure|
|2|Algoritma|
Code:
```
|No|Desc|
|---|---:|
|1|Data structure|
|2|Algoritma|
```

---
### H. Cara membuat link
---
##### 1. Link biasa
Contoh:
Link ke [Google](google.com)
Code:
```
Link ke [Google](google.com)
```

##### 2. Link dengan tooltip
Contoh:
Link ke [Google](google.com "Link ke website google")
Code:
```
Link ke [Google](google.com "Link ke website google")
```

##### 3. Anchor link
Contoh:
###### Navigasi ke anchor link
  * [Chapter 1](#chapter-1)
  * [Chapter 2](#chapter-2)
  * [Chapter 3](#chapter-3)

## Chapter 1 <a id="chapter-1"></a>
Content for chapter one.

## Chapter 2 <a id="chapter-2"></a>
Content for chapter one.

## Chapter 3 <a id="chapter-3"></a>
Content for chapter one.

Code:
```
###### Navigasi ke anchor link
  * [Chapter 1](#chapter-1)
  * [Chapter 2](#chapter-2)
  * [Chapter 3](#chapter-3)

## Chapter 1 <a id="chapter-1"></a>
Content for chapter one.

## Chapter 2 <a id="chapter-2"></a>
Content for chapter one.

## Chapter 3 <a id="chapter-3"></a>
Content for chapter one.
```

### I. Cara membuat image
Contoh:
![Alt text](http://octodex.github.com/images/stormtroopocat.jpg "The Stormtroopocat")
Code:
```
![Alt text](http://octodex.github.com/images/stormtroopocat.jpg "The Stormtroopocat")
```
