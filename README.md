<p align='center'><br><a href='https://thenounproject.com/term/components/1286164'><img src='https://user-images.githubusercontent.com/74385/75975632-f9100d80-5f2c-11ea-8c20-72a98b8de15e.png' width='96'></a><br></p>

<h1 align='center'>
Prettier plugin: Markdown code fences
</h1>

<p align='center'>
Plugin for <a href='https://prettier.io'>Prettier</a> to format Markdown files with code fences
</p>

<p align='center'>
<!-- badges here -->
</p>
<br>

> NB: This micro-package is offered as-is and is only supported on a best effort basis.

## Description

Converts indented code blocks into fenced code blocks.

<table>
<tr>
<th>Before</th>
<th>After</th>
</tr>
<tr>
<td>

```md
## This is a Markdown file

Here are some terminal commands.

    cd /
    find . -name systemd
    uname -a
```

</td><td>

````md
## This is a Markdown file

Here are some terminal commands.

```
cd /
find . -name systemd
uname -a
```
````

</td>
</tr>
</table>

## Usage

Install the plugin into an npm project and it will work automatically.

```sh
yarn add --dev @rstacruz/prettier-plugin-markdown-code-fences prettier
yarn run prettier --write file.md
```

## Thanks

**prettier-plugin-markdown-code-fences** © 2020, Rico Sta. Cruz. Released under the [MIT] License.<br>
Authored and maintained by Rico Sta. Cruz with help from contributors ([list][contributors]).

> [ricostacruz.com](http://ricostacruz.com) &nbsp;&middot;&nbsp;
> GitHub [@rstacruz](https://github.com/rstacruz) &nbsp;&middot;&nbsp;
> Twitter [@rstacruz](https://twitter.com/rstacruz)

[![](https://img.shields.io/github/followers/rstacruz.svg?style=social&label=@rstacruz)](https://github.com/rstacruz) &nbsp;
[![](https://img.shields.io/twitter/follow/rstacruz.svg?style=social&label=@rstacruz)](https://twitter.com/rstacruz)

[mit]: http://mit-license.org/
[contributors]: http://github.com/rstacruz/prettier-plugin-marprettier-plugin-markdown-code-fencesdown-code-fences/contributors
