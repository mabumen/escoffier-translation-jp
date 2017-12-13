# README #

エスコフィエ『ル・ギード・キュリネール』新訳作業用リポジトリ

### 使い方 ###

Markdownファイル（.md）が作業ファイル=原稿です。

**番号（=章番号）で始まるディレクトリ内のMarkdownファイルに対してのみ編集してコミットするようにしてください**

命名規則は

節番号（やや恣意的です）-節名称-ppページ範囲.md

* 00-avant-propos.md
* 01-fonds-de-cuisine-pp1-12.md
* 02-grandes-sauces-de-base-pp13-17.md

**これらのファイルに対してだけ変更をコミットしてください。**


PDFは時折マージされます。単に組版イメージ確認のためです。

それ以外のファイル（TeX関連が主です）は、絶対に触らないようにご注意ください。


### Markdownファイル=原稿はブラウザ上で作業可能です ###

ブラウザでこのリポジトリを開き、ソース>目的の章のディレクトリ>作業ファイル、と進んでください。

.md ファイルをクリックして開くとMarkdownのプレビューモードで表示されます。「編集」をクリックして編集モードに移行します。

この状態で誤字、脱字、明らかなミスについては直接書き込んでください。コメントについては該当段落の下に、行頭を%（半角）で始めて間をあけず一行使ってください。

編集作業が終わったら、「コミット」してください。その際に「コメント欄」がある筈ですので、およその作業内容、提案、疑問点など何か必ず書いてください。
また、コミットする際に**「この変更へのプルリクエストを作成」に必ずチェックを入れて**おいてください。

### Markdownプレビューモードでの注番号について ###

プレビューモードでの注番号は、僕がエディタで半自動で注を入れた順の番号が表示されてしまいます。が、注番号からのリンク先は合っていますので、番号そのものについては気にしないでください。

PDFと違い、必ず「後注」の形式になっています。このあたりもあまり気にしないでください。所詮は「プレビュー」とお考えください。

### ブラウザ上で編集する際の注意 ###

ブラウザ上で編集する場合、「コミット」するまで変更は保存されません。僕はよくやってしまうのですが、誤ってページのリロード、バックなどしてしまうと、それまでの編集内容が全て失なわれてしまいます。

そのため、多少煩雑になっても、1ファイルまとめて全部徹底的に、ではなく、数回に分けて編集、コミットするほうが安全です。

あるいは、エディタにコピペして作業し、それを戻していただいても結構ですが、その場合は、**余計な空白行などが入らない**ようご注意ください。Diffによる変更点の比較がうまくいかなくなりますので。

もっとも、エディタで作業できるのであれば、アプリSourceTreeをお使いいただくほうが便利だと思います。