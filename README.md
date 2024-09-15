# What is masadown ################
masadown is a lightweight markup language inspired by John Gruber's "Markdown" and other markup syntaxes.

It has the following features:

- **Clear and Understandable Syntax**\
  Aims to be easy to understand by eliminating complex rules.

- **Simple Implementation**\
  Primarily implemented using regular expressions and simple loops, making it easy to port.

- **Content Embedding with `{{Embedding}}` Syntax**\
  For example, `{{math:E = mc^{2}}}` can embed mathematical formulas, and `{{http://~}}` can embed content like posts from X (Twitter) or YouTube videos directly into the document. It can also be extended with custom embeddings.

- **Supports Tables, Footnotes, Attribute Additions, and More**\
  Tables can have merged cells, and other features include comments and container blocks.

*Note: Regarding compatibility with Markdown, most content is displayed as-is, but some detailed rules may differ, and some features may not be supported.*
