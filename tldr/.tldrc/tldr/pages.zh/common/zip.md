# zip

> 将文件打包并压缩（存档）为 zip 文件。
> 更多信息：<https://manned.org/zip>.

- 递归地打包和压缩文件和目录：

`zip -r {{压缩文件.zip}} {{路径/到/文件}} {{路径/到/目录1}} {{路径/到/目录2}}`

- 添加到压缩档案中并排除不需要的文件：

`zip -r {{压缩文件.zip}} {{路径/到/目录}} -x {{路径/到/不需要的文件}}`

- 使用最高压缩级别 9 压缩目录和内容：

`zip -r -{{9}} {{压缩文件.zip}} {{路径/到/目录}}`

- 创建一个加密压缩档案（将会提示输入密码）：

`zip -e -r {{压缩文件.zip}} {{路径/到/目录}}`

- 将文件添加到现有的 zip 文件：

`zip {{压缩文件.zip}} {{路径/到/文件}}`

- 从现有 zip 文件中删除文件：

`zip -d {{压缩文件.zip}} "{{foo/*.tmp}}"`

- 将指定目录及其内容打包并拆分为多个 zip 文件（例如：若干个 3 GB 的 zip 包）：

`zip -r -s {{3g}} {{压缩文件.zip}} {{路径/到/目录}}`

- 列出指定压缩档案中的文件（不提取文件）：

`zip -sf {{压缩文件.zip}}`
