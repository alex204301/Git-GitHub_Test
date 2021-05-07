# Basic Syntax

## Headers

- ū ���� (���� ����)

    ```
    Heading Level 1
    ===============
    ```

- ���� ���� (���� ������)

    ```
    Heading Level 2
    ---------------
    ```

- Heading (�۸Ӹ�)

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

- Heading�� ���� �� #�ϰ� ��ĭ�� ��� �� �ܾ �ٿ��� �Ѵ�.

    | ���� ��� | Ʋ�� ��� |
    | - | - |
    | `# heading` | `#heading` |

<br>

----

## Emphasis

1. Bold
    - `** + �ܾ� + **` or `__ + �ܾ� + __`�� ����ϸ� �ܾ ���� ǥ���� �� �ִ�.
  
        ```
        **Bold Word**
        __Bold Word**
        ``` 
        > **Bold Word**

2. Italic
    - `* + �ܾ� + *` or `_ + �ܾ� + _`�� ����ϸ� �ܾ ��￩�� ǥ���� �� �ִ�.
        
        ```
        *Italic Word*
        _Italic Word_
        ``` 
        > *Italic Word*


<br>

----

## BlockQuotes

- `> + ����` �� ����ϸ� �ο빮�� ����� �� �ִ�.
    ```
    > First Blockquote
    > > Second Blockquote
    > > > Third Blockqutoe
    ```

    > First Blockquote
    > > Second Blockqutoe
    > > > Third Blockquote
- Blockquote �ȿ��� �ٸ� ��ũ�ٿ� ������ ����� �� �ִ�.
    > ## Header
    > - List
    > 
    > **Bold**, *Italic*, ~~cancelline~~

<br>

----

## LineBreak

1. `<br>`�� ����ϸ� ���� �ٲ��.
   
   ```
   ù��° ����. <br>
   �ι�° ����.
   ```
2. ���� �������� 3ĭ �̻��� ���� ���� �ٺ��� ���� �ٲ��.
    
    ```
    ù��° ����.()()() //()�� ����
    �ι�° ����.
    ```

<br>

---

## Lists

1. Unordered
    - `*, -, + ` ���� ��ȣ�� ���� ���ʿ� ����Ͽ� ���� �� �ִ�.

    ```
    - First Item
        - Indent
    - Second Item  
    ```
    >- First Item
    >    - Indent
    >- Second Item  
2. Ordered
    - `����. + ����`�� ����Ͽ� ����ȭ�� ����Ʈ ���� �� �ִ�.
    - ����Ʈ�� �տ� ���� ���ڿ� ������� ������ 1���� ������������ ���ǵȴ�.
    
    ```
    1. First Item
        1. Indent 
        3. Indent 2         //�� ���ڿ� ������� 2�� �ٴ´�.
    2. Second Item
    ``` 
    >1. First Item
    >    1. Indent 
    >    3. Indent 2 
    >2. Second Item
- ����Ʈ�� �߰��� �̹���, CodeBlock, Blockquote ���� �� �� �ִ�.
 
<br>

----

## Code

- Code ǥ��
  - `` ` + �ܾ�, ���� + ` ``�� ����Ͽ� code�� ǥ���� �� �ִ�.
      
      ```
      `This is code.`
      ```
      > `This is code.`
  - ( `` ) �� ����Ͽ� code�� ǥ���ϸ� ������ ����.
      
      > `` ( ` ) ���ڸ� code�� ǥ�� ���� ``
- CodeBlock
    1. �鿩���� (Indent)

        >    ������ �鿩�����Ͽ� ����ϸ� 
        >
        >        �̷��� �ڵ� ���� �����.
        >
        >    �鿩���Ⱑ ������ ������� ���ư���.
       
        `���� ���� ������ �ν��� ����� �ȵȴ�.`

    2. �ڵ� ��� �ڵ� ( ``` )�� ��, �� �ٿ� ���

<br>

---

## Horizontal

- �Ʒ� ���ô� ��� ������ ���� �� ����Ѵ�.
    ```
    ---

    ***
    ___
    ```

<br>

---

## Links

- `Optional Title`�� �������� �ɼ����� ���� �ʾƵ� �ȴ�.
- ��ũ���� URL�ܿ��� ������ Section �� ���������� �����ϴ�.
    
    ```
    [����](#Section Title)
    ```

    > See Section : [Emphasis](#emphasis)

<br>

- �ܺ� ��ũ
    - `[����](��ũ, "Optional Title")`�� ����Ͽ� ��ũ�� �����.
    
    ```
    [Google](https://google.com, "Go google")
    ```
    > Link : [Google](https://google.com, "Go google")

- ���� ��ũ
    - �Ʒ��� ���� ������ ����Ѵ�.   
    `[����][��]`  
    <br>
    `[��]: ��ũ "Optional Title"`

    ```
    [Google][googlelink]

    [googlelink]: https://google.com "Go google"
    ```

    > Link : [Google][googlelink]

    [googlelink]: https://google.com "Go google"

- �ڵ� ����
    - �Ϲ����� URL, �̸����� ��� ������ �������� ��ũ�� �����Ѵ�. 

    ```
    �ܺ� ��ũ : <https://google.com>
    �̸��ϸ�ũ : <alex204301@naver.com>
    ``` 

    > �ܺ� ��ũ : <https://google.com>   
    > �̸��ϸ�ũ : <alex204301@naver.com>

<br>

---

## Image

- �Ʒ��� ���� ������ ����ϰ� path�� �̹��� ��θ� ���´�.   
    `![�̹��� ����](�̹��� ��� "Optional title")`
    
    ```
    ![�ٴ� ����](OceanBeach.jpg "Ocean Beach")
    ```
    ![�ٴ� ����](OceanBeach.jpg "Ocean Beach")

- �Ʒ��� ���� �̹����� ��ũ�� �߰��� ���� �ִ�.
    
    `[![�̹��� ����](�̹��� ��� "Optional Title")](��ũ)`
    
    ```
    [![����](London.jpg "London")](https://www.lonelyplanet.com/england/london)
    ```
    [![����](London.jpg "London")](https://www.lonelyplanet.com/england/london)

<br>

---

## Escaping Characters

- ( \ )�� ���� �տ� ����Ͽ� Ư���� ���ڵ��� ǥ���� �� �ִ�.
> \*  <- ó�� ����Ʈ ������ �ʰ� ǥ�� ����   
> �� �ܿ��� ( \ ), ( ` ), ( _ ) �� ǥ�� ����

<br>

---

## GFM

- ���� ������ ���� GitHub Repository ��ũ
> Link : [GitHub Repository](https://github.com/alex204301/GFM_Test "GitHub Repository")

<br>

---
