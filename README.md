# Markdown
This repository is for practice of Markdown language.

## What is a Markup language?
A markup language is a computer language that uses tags to define elements within a document. It is human-readable, meaning markup files contain standard words, rather than typical programming syntax. While several markup languages exist, the two most popular are HTML and XML.

HTML is a markup language used for creating webpages. The full form of HTML is Hypertext Markup Language. The contents of each webpage are defined by HTML tags. Basic page tags, such as <head>, <body>, and <div> define sections of the page, while tags such as <table>, <form>, <image>, and <a> define elements within the page. Most elements require a beginning and end tag, with the content placed between the tags. For example, a link to the TechTerms.com home page may use the following HTML code:

`<a href="http://www.techterms.com">TechTerms.com</a>`

XML is used for storing structured data, rather than formatting information on a page. While HTML documents use predefined tags (like the examples above), XML files use custom tags to define elements. For example, an XML file that stores information about computer models may include the following section:

```
<computer>
  <manufacturer>Dell</manufacturer>
  <model>XPS 17</model>
  <components>
    <processor>2.00 GHz Intel Core i7</processor>
    <ram>6GB</ram>
    <storage>1TB</storage>
  </components>
</computer>
```

XML is called the "Extensible Markup Language" since custom tags can be used to support a wide range of elements. Each XML file is saved in a standard text format, which makes it easy for software programs to parse or read the data. Therefore, XML is a common choice for exporting structured data and for sharing data between multiple programs.

**Note**<br>
Since both HTML and XML files are saved in a plain text format, they can be viewed in a standard text editor. You can also view the HTML source of an open webpage by selecting the "View Source" option. This feature is found in the View menu of most Web browsers.


## What is Markdown?
Markdown is a lightweight markup language that you can use to add formatting elements to plaintext text documents. Created by John Gruber in 2004, Markdown is now one of the world’s most popular markup languages.

Using Markdown is different than using a WYSIWYG editor. In an application like Microsoft Word, you click buttons to format words and phrases, and the changes are visible immediately. Markdown isn’t like that. When you create a Markdown-formatted file, you add Markdown syntax to the text to indicate which words and phrases should look different.

You can add Markdown formatting elements to a plaintext file using a text editor application. Or you can use one of the many Markdown applications for macOS, Windows, Linux, iOS, and Android operating systems. There are also several web-based applications specifically designed for writing in Markdown.

You don’t even need to download anything. There are several online Markdown editors that you can use to try writing in Markdown. Dillinger is one of the best online Markdown editors. Just open the site and start typing in the left pane. A preview of the rendered document appears in the right pane.

## How Markdown works?
When you write in Markdown, the text is stored in a plaintext file that has an .md or .markdown extension. But then what? How is your Markdown-formatted file converted into HTML or a print-ready document?

The short answer is that you need a Markdown application capable of processing the Markdown file. There are lots of applications available — everything from simple scripts to desktop applications that look like Microsoft Word. Despite their visual differences, all of the applications do the same thing. Like Dillinger, they all convert Markdown-formatted text to HTML so it can be displayed in web browsers.

Markdown applications use something called a Markdown processor (also commonly referred to as a “parser” or an “implementation”) to take the Markdown-formatted text and output it to HTML format. At that point, your document can be viewed in a web browser or combined with a style sheet and printed. You can see a visual representation of this process below.

![Markdown Process Image](markdown.PNG)

To summarize, this is a four-part process:

1. Create a Markdown file using a text editor or a dedicated Markdown application. The file should have an .md or .markdown extension.
2. Open the Markdown file in a Markdown application.
3. Use the Markdown application to convert the Markdown file to an HTML document.
4. View the HTML file in a web browser or use the Markdown application to convert it to another file format, like PDF.

## What's Markdown good for?
Markdown is a fast and easy way to take notes, create content for a website, and produce print-ready documents.

It doesn’t take long to learn the Markdown syntax, and once you know how to use it, you can write using Markdown just about everywhere. Most people use Markdown to create content for the web, but Markdown is good for formatting everything from email messages to grocery lists.

Creating websites, documents (online or offline), books, presentations, emails, documentation (for example on GitHub) are some examples of what we can do with Markdown.

**Below are the guidelines for using Markdown:**


## How to denote headings?
- A single `#` will denote the largest heading.
- Double `##` will denote smaller heading.
- Triple `###` will denote smallest heading.

Examples are as follows:
# Single `#`
## Double `##`
### Triple `###`
#### Four times `####`

## How to denote bullets?
A simple `-` will denote a round bullet. Example is as below:
- This is a simple round bullet generated by using a `-` symbol.

To generate numbered bullet, we can simply add numbers 1,2,3, etc. Example is as below:
1. This is point no. 1 generated using `1.`
2. This is point no. 2 generated using `2.`

## How to type bold letters?
Bold letters are generated using double ** symbol in start and end of the text. Example is as below:
**This is bold text**

## How to denote an online link?
Online links or path to a file on local computer can be denoted in below way:<br>
`[name of link/file](link_to_file)`

Example: [Google](https://www.google.com)

## How to denote new line character?
A new line character is denoted by `<br>` in markdown language. By typing `<br>` in the end of a line, we can print the next words starting from the next new line. It needs to be used when we mention a bulleted list, bold letters, comments, etc.

## How to denote a comment?
A comment is mentioned by a pair of back ticks. One back tick at the start and the other at the end. Below is a comment:<br>
`This is a comment.`<br>

Comments can be generated using multiple back ticks also. If multiple comments are present serially, then we can denote them in below manner,

`
bash
This is a bash command.
Bash is an interpreter program.
`

Comments can be used to escape the special meaning of characters.
