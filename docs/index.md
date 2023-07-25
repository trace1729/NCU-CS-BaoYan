# NCU-CS-保研求生指南

## 简介

各位同学，你们好！
这里是NCU-CS-保研求生指南，大家收集和共享计算机保研资料的地方，由衷感谢大家愿意抽出时间进行无私地投稿，感谢大家为这个千秋万代的事业献出的点点滴滴，预祝大家都能拿到心仪的offer，本指南现阶段先进行夏令营经验贴以及往届的相关信息的整理，供大家查阅和借鉴。

## 写作指南

### [#]() md 基本语法

| 元素 | Markdown 语法 |
| --- | --- |
| [标题（Heading）](https://markdown.com.cn/basic-syntax/headings.html) | `# H1   ## H2   ### H3` |
| [粗体（Bold）](https://markdown.com.cn/basic-syntax/bold.html) | `**bold text**` |
| [斜体（Italic）](https://markdown.com.cn/basic-syntax/italic.html) | `*italicized text*` |
| [引用块（Blockquote）](https://markdown.com.cn/basic-syntax/blockquotes.html) | `> blockquote` |
| [有序列表（Ordered List）](https://markdown.com.cn/basic-syntax/ordered-lists.html) | `1. First item` `2. Second item` `3. Third item`|
| [无序列表（Unordered List）](https://markdown.com.cn/basic-syntax/unordered-lists.html) | `- First item   - Second item   - Third item   ` |
| [代码（Code）](https://markdown.com.cn/basic-syntax/code.html) | `` `code` `` |
| [分隔线（Horizontal Rule）](https://markdown.com.cn/basic-syntax/horizontal-rules.html) | `---` |
| [链接（Link）](https://markdown.com.cn/basic-syntax/links.html) | `[title](https://www.example.com)` |
| [图片（Image）](https://markdown.com.cn/basic-syntax/images.html) | `![alt text](image.jpg)` |

### [#](https://markdown.com.cn/cheat-sheet.html#%E6%89%A9%E5%B1%95%E8%AF%AD%E6%B3%95#扩展语法) 扩展语法

这些元素通过添加额外的功能扩展了基本语法。但是，并非所有 Markdown 应用程序都支持这些元素。

| 元素 | Markdown 语法 |
| --- | --- |
| [表格（Table）](https://markdown.com.cn/extended-syntax/tables.html) | `| Syntax      | Description |   | ----------- | ----------- |   | Header      | Title       |   | Paragraph   | Text        |` |
| [代码块（Fenced Code Block）](https://markdown.com.cn/extended-syntax/fenced-code-blocks.html) | ` ```   {     "firstName": "John",     "lastName": "Smith",     "age": 25   }   ``` ` |
| [脚注（Footnote）](https://markdown.com.cn/extended-syntax/footnotes.html) | Here's a sentence with a footnote. `[^1]`
`[^1]`: This is the footnote. |
| [标题编号（Heading ID）](https://markdown.com.cn/extended-syntax/heading-ids.html) | `### My Great Heading {#custom-id}` |
| [定义列表（Definition List）](https://markdown.com.cn/extended-syntax/definition-lists.html) | `term   : definition` |
| [删除线（Strikethrough）](https://markdown.com.cn/extended-syntax/strikethrough.html) | `~~The world is flat.~~` |
| [任务列表（Task List）](https://markdown.com.cn/extended-syntax/task-lists.html) | `- [x] Write the press release   - [ ] Update the website   - [ ] Contact the media` |


### [#]() md 进阶语法

1. 可以使用`!!! [note | warning | tips]`来生成矩形框(注意正文部分需要缩进一个tab， 不能用空格)

    ```
    !!! note
        This is note

    !!! warning
        This is warning

    !!! warning "可指定显示的字符串"
        This is warning

    !!! tips
        This is Tips

    ??? tips
        可折叠
    ```

    比如上述代码会有以下效果

    !!! note
        This is note

    !!! warning
        This is warning

    !!! warning "可指定显示的字符串"
        This is warning

    !!! tips
        This is Tips

    ??? tips
        可折叠

2. 可以使用 `<span class="box box-XX">XXX</span>` 来给文字加背景, 比如

    - <span class="box box-green">过了</span>
    - <span class="box box-red">没有过</span>

3. 可以使用 $\LaTeX$ 语法来改变字体大小

    - `$\small 你是谁$`  $\small 你是谁$
    - `$\large 你是谁$`  $\large 你是谁$
    - `$\Large 你是谁$`  $\Large 你是谁$
    - `$\LARGE 你是谁$`  $\LARGE 你是谁$
    - `$\huge 你是谁$`  $\huge 你是谁$


Created by Class of 2024.

Website maintained by Kaichen Gong, Erhao Shu.
