# sample.md

## a heading
A *regular* paragraph adjacent to the above heading

Note:
[markdownlint 0.14.0 (Visual Studio Code Extension)][vscode-markdownlint] shows a warning shown below.
> \[markdownlint\] MD022/blank-around-headers: Headers should be surrounded by blank lines

[vscode-markdownlint]: https://github.com/DavidAnson/vscode-markdownlint

## Unordered list

A paragraph
- A list item adjacent to the above paragraph

Note:
[markdownlint 0.14.0 (Visual Studio Code Extension)][vscode-markdownlint] shows a warning shown below.
> [markdownlint] MD032/blanks-around-lists: Lists should be surrounded by blank lines

## square bracket

[hoge]
This is not a link.

[hoge]
[fuga]
This is a link.

[hoge] fuga [piyo]
This is not a link.

[hoge][piyo]
This is a link.

[[hoge]]
This is not a link.

[[hoge]]
[[fuga]]
This is not a link.

[[hoge]] fuga [[piyo]]
This is not a link.

[[hoge]][[piyo]]
This is not a link.

[hoge]: https://www.google.co.jp/?q=hoge
[fuga]: https://www.google.co.jp/?q=fuga
[piyo]: https://www.google.co.jp/?q=piyo
[[hoge]]: www.google.co.jp/?q=hoge2
[[fuga]]: www.google.co.jp/?q=fuga2
[[piyo]]: www.google.co.jp/?q=piyo2
