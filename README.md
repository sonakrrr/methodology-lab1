# Methodology-lab1
Lab1 for methodologies and technologies of software development
## Functionality
This program is designed to convert text written in Markdown format into corresponding HTML code. Upon execution, the program takes a path to a Markdown file as input. The `MarkdownConverter` class is initialized with this file and stores its content in an internal variable. The `convert_to_html` method calls a series of sub-methods to process various Markdown elements such as:
- Bold Text: `**text**` becomes `<b>text</b>`.
- Italic Text: `_text_` becomes `<i>text</i>`.
- Monospaced Text: `` `text` `` becomes `<tt>text</tt>`.
- Preformatted Text: ``` ```text``` ``` becomes `<pre>text</pre>`.

After processing the text, the program returns it in HTML format wrapped in `<p>` tags. The main part of the program checks the correctness of the command-line arguments. If they are correct, an instance of the `MarkdownConverter` class is created, the text is converted to HTML, and if an output file is specified, the result is written to the file; if no output file is specified, the HTML is printed to the screen.
## How to start
To start using the program, you need to have Python downloaded on your computer.
Then all you need to do is copy this repository to your machine. You can do this using this command:
```shell
git clone https://github.com/sonakrrr/methodology-lab1
```
## How to use
This program was developed exclusively for console use. To run it, you need to pass arguments (input and output) using the following command:
```shell
python .\convert_markdown.py .\input_text.md --out .\output_text.html
```
You can leave no argument after the `--out` flag, and the result will be output to the command line.
## Revert commit
[Here is the link](https://github.com/sonakrrr/methodology-lab1/commit/1954bc0f22663aaaca69576fd086e6dce5f92ab0)
