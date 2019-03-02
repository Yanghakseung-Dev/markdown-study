# 코드(Code) 강조

```
<pre>, <code>로 변환됩니다.  
숫자 1번 키 왼쪽에 있는 `(Grave)를 입력하세요  
```

## 인라인(inline) 코드 강조

```
`background`혹은 `background-image` 속성으로 요소에 배경 이미지를 삽입할 수 있습니다.  
```

`background`혹은 `background-image` 속성으로 요소에 배경 이미지를 삽입할 수 있습니다.  


## 블록(block) 코드 강조

```
`를 3번 이상 입력하고 코드 종류도 적습니다.  

또는 4개의 공백 또는 하나의 탭으로 들여쓰기를 만나면 변환되기 시작하여 들여쓰지 않은 행을 만날때까지 변환이 계속된다.  

한줄 띄어쓰면 인식이 제대로 안되는 문제가 발생하곤 합니다.  

```

\``` [language] [title] [url] [link text]  
code snippet  
\```

```
This is a normal paragraph:

    This is a code block.
end code block.
```



\```html  
\<a href="https://www.google.co.kr/" target="_blank">GOOGLE</a>  
\```

\```css  
.list > li {  
  position: absolute;  
  top: 40px;  
}  
\```  

\```javascript  
function func() {  
  var a = 'AAA';  
  return a;  
}
\```

\```bash  
$ vim ./~zshrc  
\```

\```python  
s = "Python syntax highlighting"  
print s  
\```

\```  
No language indicated, so no syntax highlighting.   
But let's throw in a tag.  
\```  


```html
<a href="https://www.google.co.kr/" target="_blank">GOOGLE</a>  
```  

```css
.list > li {
  position: absolute;
  top: 40px;
}
```

```javascript
function func() {
  var a = 'AAA';
  return a;
}
```

```bash
$ vim ./~zshrc
```

```python
s = "Python syntax highlighting"
print s
```

```
No language indicated, so no syntax highlighting. 
But let's throw in a tag.
```
