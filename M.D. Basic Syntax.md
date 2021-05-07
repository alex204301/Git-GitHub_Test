# Basic Syntax

## Headers

- 큰 제목 (문서 제목)

    ```
    Heading Level 1
    ===============
    ```

- 작은 제목 (문서 부제목)

    ```
    Heading Level 2
    ---------------
    ```

- Heading (글머리)

    ```
    # Heading Level 1
    ## Heading Level 2
    ### Heading Level 3
    #### Heading Level 4
    ##### Heading Level 5
    ###### Heading Level 6
    ```
    > # Heading Level 1
    > ## Heading Level 2
    > ### Heading Level 3
    > #### Heading Level 4
    > ##### Heading Level 5
    > ###### Heading Level 6
    > <br> 
    
    <br>

- Heading을 만들 때 #하고 한칸을 띄운 후 단어를 붙여야 한다.

    | 옳은 경우 | 틀린 경우 |
    | - | - |
    | `# heading` | `#heading` |

<br>

----

## Emphasis

1. Bold
    - `** + 단어 + **` or `__ + 단어 + __`를 사용하면 단어를 굵게 표현할 수 있다.
  
        ```
        **Bold Word**
        __Bold Word**
        ``` 
        > **Bold Word**

2. Italic
    - `* + 단어 + *` or `_ + 단어 + _`를 사용하면 단어를 기울여서 표현할 수 있다.
        
        ```
        *Italic Word*
        _Italic Word_
        ``` 
        > *Italic Word*


<br>

----

## BlockQuotes

- `> + 문장` 을 사용하면 인용문을 사용할 수 있다.
    ```
    > First Blockquote
    > > Second Blockquote
    > > > Third Blockqutoe
    ```

    > First Blockquote
    > > Second Blockqutoe
    > > > Third Blockquote
- Blockquote 안에서 다른 마크다운 문법을 사용할 수 있다.
    > ## Header
    > - List
    > 
    > **Bold**, *Italic*, ~~cancelline~~

<br>

----

## LineBreak

1. `<br>`을 사용하면 줄이 바뀐다.
   
   ```
   첫번째 문장. <br>
   두번째 문장.
   ```
2. 문장 마지막에 3칸 이상을 띄어쓰면 다음 줄부터 줄이 바뀐다.
    
    ```
    첫번째 문장.()()() //()는 띄어쓰기
    두번째 문장.
    ```

<br>

---

## Lists

1. Unordered
    - `*, -, + ` 등의 기호를 가장 왼쪽에 사용하여 만들 수 있다.

    ```
    - First Item
        - Indent
    - Second Item  
    ```
    >- First Item
    >    - Indent
    >- Second Item  
2. Ordered
    - `숫자. + 문장`을 사용하여 순서화된 리스트 만들 수 있다.
    - 리스트는 앞에 붙은 숫자에 상관없이 순서는 1부터 내림차순으로 정의된다.
    
    ```
    1. First Item
        1. Indent 
        3. Indent 2         //앞 숫자에 상관없이 2가 붙는다.
    2. Second Item
    ``` 
    >1. First Item
    >    1. Indent 
    >    3. Indent 2 
    >2. Second Item
- 리스트의 중간에 이미지, CodeBlock, Blockquote 등이 들어갈 수 있다.
 
<br>

----

## Code

- Code 표시
  - `` ` + 단어, 문장 + ` ``을 사용하여 code로 표시할 수 있다.
      
      ```
      `This is code.`
      ```
      > `This is code.`
  - ( `` ) 를 사용하여 code를 표시하면 다음과 같다.
      
      > `` ( ` ) 문자를 code로 표시 가능 ``
- CodeBlock
    1. 들여쓰기 (Indent)

        >    문장을 들여쓰기하여 사용하면 
        >
        >        이렇게 코드 블럭이 생긴다.
        >
        >    들여쓰기가 끝나면 원래대로 돌아간다.
       
        `한줄 띄어쓰지 않으면 인식이 제대로 안된다.`

    2. 코드 블록 코드 ( ``` )를 앞, 뒷 줄에 사용

<br>

---

## Horizontal

- 아래 예시는 모두 수평선을 만들 때 사용한다.
    ```
    ---

    ***
    ___
    ```

<br>

---

## Links

- `Optional Title`은 어디까지나 옵션으로 쓰지 않아도 된다.
- 링크에는 URL외에도 문서의 Section 등 여러가지가 가능하다.
    
    ```
    [제목](#Section Title)
    ```

    > See Section : [Emphasis](#emphasis)

<br>

- 외부 링크
    - `[제목](링크, "Optional Title")`을 사용하여 링크를 만든다.
    
    ```
    [Google](https://google.com, "Go google")
    ```
    > Link : [Google](https://google.com, "Go google")

- 참조 링크
    - 아래와 같은 형식을 사용한다.   
    `[제목][라벨]`  
    <br>
    `[라벨]: 링크 "Optional Title"`

    ```
    [Google][googlelink]

    [googlelink]: https://google.com "Go google"
    ```

    > Link : [Google][googlelink]

    [googlelink]: https://google.com "Go google"

- 자동 연결
    - 일반적인 URL, 이메일의 경우 적절한 형식으로 링크를 형성한다. 

    ```
    외부 링크 : <https://google.com>
    이메일링크 : <alex204301@naver.com>
    ``` 

    > 외부 링크 : <https://google.com>   
    > 이메일링크 : <alex204301@naver.com>

<br>

---

## Image

- 아래와 같은 형식을 사용하고 path에 이미지 경로를 적는다.   
    `![이미지 설명](이미지 경로 "Optional title")`
    
    ```
    ![바다 사진](OceanBeach.jpg "Ocean Beach")
    ```
    ![바다 사진](OceanBeach.jpg "Ocean Beach")

- 아래와 같이 이미지에 링크를 추가할 수도 있다.
    
    `[![이미지 설명](이미지 경로 "Optional Title")](링크)`
    
    ```
    [![런던](London.jpg "London")](https://www.lonelyplanet.com/england/london)
    ```
    [![런던](London.jpg "London")](https://www.lonelyplanet.com/england/london)

<br>

---

## Escaping Characters

- ( \ )를 문자 앞에 사용하여 특수한 문자들을 표시할 수 있다.
> \*  <- 처럼 리스트 만들지 않고 표시 가능   
> 이 외에도 ( \ ), ( ` ), ( _ ) 등 표시 가능

<br>

---

## GFM

- 과제 제출을 위한 GitHub Repository 링크
> Link : [GitHub Repository](https://github.com/alex204301/GFM_Test "GitHub Repository")

<br>

---
