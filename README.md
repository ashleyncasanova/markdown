## **Markdown Tutorials**
### [**Basics**](https://www.markdowntutorial.com/)

1. Italics and Bold

    * _Italics_
    ```
        _Italics_
    ```

    * **Bold**
    ```
        **Bold**
    ```

    *   **_Both_**
    ```
        **_Both_**
    ```

1. Headers

    * # Header one
    ```
        # Header one
    ```

    * ## Header two
    ```
        ## Header two
    ```

    * ### Header three
    ```
        ### Header three
    ```

    * #### Header four
    ```
        #### Header four
    ```

    * ##### Header five
    ```
        ##### Header five
    ```

    * ###### Header six
    ```
        ###### Header six
    ```

1. Links

    * Inline links
        * [Visit GitHub!](www.github.com)
        ```
            [Visit GitHub!](www.github.com)
        ```
        * [You're **really, really** going to want to see this.](www.dailykitten.com)
        ```
            [You're **really, really** going to want to see this.](www.dailykitten.com)
        ```
        * The Latest News from [the BBC](www.bbc.com/news)
        ```
            The Latest News from [the BBC](www.bbc.com/news)
        ```
    * Reference Links
        * Do you want to [see something fun][a fun place]?  Well, do I have [the website for you][another fun place]!

        [a fun place]: www.zombo.com
        [another fun place]: www.google.com

        ```
            Do you want to [see something fun][a fun place]?  
            Well, do I have [the website for you][another fun place]!

            [a fun place]: www.zombo.com
            [another fun place]: www.google.com
        ```
1. Images
    * Inline Image Link
        * ![Benjamin Bannekat](https://octodex.github.com/images/bannekat.png)
        ```
            ![Benjamin Bannekat](https://octodex.github.com/images/bannekat.png)
        ```
        > Note: Alt text ([Benjamin Bannekat] in this case) is a phrase or sentence that describes the image for the visually impaired

        > Note: You can use the following syntax to resize images
        
        * <img src="https://octodex.github.com/images/bannekat.png" alt="Benjamin Bannekat" width="250" height="250">
        ```
            <img src="https://octodex.github.com/images/bannekat.png" alt="Benjamin Bannekat" width="250" height="250">
        ```
       
        


    
    * Reference Image
        * [The founding father][Father]

        [Father]: http://octodex.github.com/images/founding-father.jpg
        ```
            [The founding father][Father]

            [Father]: http://octodex.github.com/images/founding-father.jpg
        ```
        
      

1. Blockquotes
    * I read this interesting quote the other day:

        > "Her eyes had called him and his soul had leaped at the call. To live, to err, to fall, to triumph, to recreate life out of life!"

    ```
        I read this interesting quote the other day:

            > "Her eyes had called him and his soul had leaped at the call. To live, to err, to fall, to triumph, to recreate life out of life!"
    ```
1. Lists
    * Ordered (numbered)
        1. Cut the cheese
        2. Slice the tomatoes
        3. Rub the tomatoes in flour

        ```
         1. Cut the cheese
         2. Slice the tomatoes
         3. Rub the tomatoes in flour
        ```
        > Note: can write the same list using all ones and markdown will be the same

    * Unordered (bullet point)
        * Milk
        * Eggs
        * Salmon
        * Butter
        ```
         * Milk
         * Eggs
         * Salmon
         * Butter
        ```
1. Paragraphs
    * Single straight line: add each verse to its own line

        Do I contradict myself?
        Very well then I contradict myself,
        (I am large, I contain multitudes.)
        ```
        Do I contradict myself?
        Very well then I contradict myself,
        (I am large, I contain multitudes.)
        ```
    * Hard Break: forcefullt insert a new line using spaces

        Do I contradict myself?

        Very well then I contradict myself,

        (I am large, I contain multitudes.)
        ```
        Do I contradict myself?

        Very well then I contradict myself,

        (I am large, I contain multitudes.)
        ```
    * Soft Break: insert two spaces after each row  
    
        Do I contradict myself?  
        Very well then I contradict myself,  
        (I am large, I contain multitudes.)
        ```
        Do I contradict myself?  
        Very well then I contradict myself,  
        (I am large, I contain multitudes.)
        ```
    
### [**Extended**](https://www.markdownguide.org/extended-syntax/)
1. **Tables**

| Syntax      | Description | Test Text     |
| :---        |    :----:   |          ---: |
| Header      | Title       | Here's this   |
| Paragraph   | Text        | And more      |
```
| Syntax      | Description | Test Text     |
| :---        |    :----:   |          ---: |
| Header      | Title       | Here's this   |
| Paragraph   | Text        | And more      |
```
> Note: Cell widths can vary and output will be the same

> Note: Can align text in the columns using colon/s (:)

> Option: Try Markdowns [Table Generator](https://www.tablesgenerator.com/markdown_tables) for a graphical approach


2. **Fenced Codeblocks**
```
    {
     "firstName": "John",
     "lastName": "Smith",
     "age": 25
    }
```

    ```
        ```
        {
         "firstName": "John",
         "lastName": "Smith",
         "age": 25
        }
        ```
    ```

3. **Syntax Hilighting**
```json
    {
     "firstName": "John",
     "lastName": "Smith",
     "age": 25
    }
```
```
    ```json
    {
     "firstName": "John",
     "lastName": "Smith",
     "age": 25
    }
    ```
```
4. Footnotes

> Note: Cannot get to work.. may need to download a different version of markdown (common mark, GFM, etc..) a list is available in the header link above.

```
Here's a simple footnote,[^1] and here's a longer one.[^bignote]

[^1]: This is the first footnote.

[^bignote]: Here's one with multiple paragraphs and code.

    Indent paragraphs to include them in the footnote.

    `{ my code }`

    Add as many paragraphs as you like.
```
### **Other**
1. [**Anchoring**](https://www.youtube.com/watch?v=EKqhENATIKg)

Step 1: Make a header with a section called Defines and another called Custom/Names.

Step 2: Link each section using the format below.

>Note: The hashtag links to a header somewhere in the page; when you click the text it will bring you to that header.

Step 3: Add the sections you want to link to.

>Note: For a header with spaces, you can just use a dash, but for all other non-standard characters you have to make a custom name (header + html name field). 

```markdown
# Header
[Defines](#defines)

[Custom/Names](#custom-names)
.

.

.

.

### Defines
These are the defines

### <a name="custom-names"></a>Custom/Names
these are custom names
```
# Header
[Defines](#defines)

[Custom/Names](#custom-names)
.

.

.

.

### Defines
These are the defines

### <a name="custom-names"></a>Custom/Names
these are custom names