# takahashi-slides

fork from [kuitos/takahashi-slides](https://github.com/kuitos/takahashi-slides)

# [Takahashimethod](https://en.wikipedia.org/wiki/Takahashi_method)

*support Chrome 45+ only*

## How to use

1. fork this repository.
2. create a new path on the root, such as `subdemo`.
3. write markdown document in the `css` folder and named index.md, the format is as follows.
4. create a static server,such as `python -m http.server` or [http-server](https://github.com/indexzero/http-server).
5. access the server address, like `localhost:8000/?subdemo`.
6. if access the web root,e.g. localhost:8000, the `index.md` on the root will shown.
7. then you can turn pages with `left` and `right` key, `PgUp` and `PgDn` key, or mouse click on the bottom side.

## Format of markdown document

1. a blank line means a new slide will be created.
2. an english comma(`,`) means content will display gradually (the comma don't display on the slide).
3. `~~strickout~~` will strickout the characters.
4. `![](css/image.png)` add a image.
5. `**highlight**` highlight, red font.
6. `*italic*` italic font.
7. `[text](?foldername)` link to local subdirectory, display subdirectory/index.md content.
8. `*` or `-` means list items.
9. `num. text` list items with serial num.
10. code and code block like the common markdown file.

prism has been updated to version 9000.0.1, also you can add more languages for code blocks, e.g.

<pre>
```python
print("Hello World!")
```
</pre>
