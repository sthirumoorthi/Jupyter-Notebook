# Jupyter-Notebook
Detailed note or hints on the Jupyter notebook

Here’s how to format Markdown cells in Jupyter notebooks in the IBM Data Science Experience.

# Headings: 
Use #s followed by a blank space for notebook titles and section headings:


(# title)

(## major headings)

(### subheadings)

(#### 4th level subheadings)

# Emphasis: 
Use this code: Bold: (__string__) or (**string**) Italic: (_string_) or (*string*)

# Line breaks: 
Sometimes markdown doesn’t make line breaks when you want them. Use 2 spaces or this code for a manual line break: (<br>)

# Indented quoting: 
Use a greater than sign (>) and then a space, then type the text. The text is indented and has a gray horizontal line to the left of it until the next carriage return.

# Bullets: 
Use the dash sign (- ) with a space after it, or a space, a dash, and a space ( - ), to create a circular bullet. To create a sub bullet, use a tab followed a dash and a space. You can also use an asterisk instead of a dash, and it works the same.

# Numbered lists: 
Start with 1. followed by a space, then it starts numbering for you. Start each line with some number and a period, then a space. Tab to indent to get subnumbering.

# Graphics: 
You can attach image files directly to a notebook only in Markdown cells. Drag and drop your images to the Markdown cell to attach it to the notebook. To add images to other cell types, you can use only graphics that are hosted on the web. You can’t add captions for graphics at this time. 
Use this code: (<img src="url.gif" alt="Alt text that describes the graphic" title="Title text" />)

# Geometric shapes: 
Use this code with a decimal or hex reference number from here: UTF-8 Geometric shapes
(&#reference_number;)

# Horizontal lines: 
Use three asterisks: (***)

# Internal links: 
To link to a heading, use this code: [heading title](#heading-title) For the text in the parentheses, replace spaces and special characters with a hyphen. Make sure to test all the links!
Alternatively, you can add an ID for a heading right above the title. Use this code: <a id="heading_ID"></a> Make sure that the heading_ID is unique within the notebook.
Use this code for the link and make sure to test all the links! [heading title](#heading_ID)

# External links: 
Use this code and test all links! [link text](http://url)

Reference: 
https://ingeh.medium.com/markdown-for-jupyter-notebooks-cheatsheet-386c05aeebed
