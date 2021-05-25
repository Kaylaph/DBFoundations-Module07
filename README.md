## Introduction

The purpose of this paper is to explain the concepts learned in Module 07 on functions, specifically the 3 types 1) scalar, 2) inline table-value, and 3) multi-statement table-value.
You can use the [editor on GitHub](https://github.com/Kaylaph/DBFoundations-Module07/edit/main/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Explain when you would use a SQL UDF.

SQL functions can either be built-in functions or user defined functions (UDFs). UDFs are custom functions and can be used when built-in functions don’t provide the specific functionality we need. An example of when a UDF would be used is for check constraints, see Figure 1.

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Explain the differences between Scalar, Inline, and Multi-Statement Functions.

There are 3 types of UDFs, scalar, inline table-value, and multi-statement table-value. Both inline and multi-statement are table-value meaning they return tables as outputs while scalar functions return a single value. The difference between inline and multi-statement is multi-statement can accept more than one statement. 
The 3 types also differ in their syntax. For scalar, there needs to be a return/end block and the schema name must be included, see Figure 2a. For inline, there is no return/end block, see Figure 2b. For multi-statement, there needs to be a return/end block, see Figure 2c.

### Summary

To recap, Module 07 focuses on the different types of functions and this paper specifically addresses UDFs, when they are used and the different types of UDFs.
