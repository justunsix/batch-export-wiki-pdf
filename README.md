# batch-export-wiki-pdf

[![Gitpod ready-to-code](https://img.shields.io/badge/Gitpod-ready--to--code-blue?logo=gitpod)](https://gitpod.io/#https://github.com/DefetC/batch-export-wiki-pdf)

汉语: 批量导出wiki(confluence)页面为pdf文件，包含子页面

English: Export wiki (confluence) pages in batches to pdf files, including sub-pages 

## Installation requirements

Have Python 3.8+

Get pyquery

```sh
pip install pyquery
```

## Run

Edit the script file with your configurations:

- Confluence URL
- Directory where PDF(s) should be exported to
- Name of Confluence wiki section/space
- Cookie (e.g. JSESSIONID)

Run it

```sh
python wiki_export.py
```
