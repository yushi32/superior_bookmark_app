# superior_bookmark_app

ブックマークを効率的に管理・消化するためのアプリです。

### アプリ名案
1. Laterless

”全ての「後で見る」を撲滅する”というコンセプトを掲げており、それを体現した命名。

2. HyperVault

vaultには「金庫」「秘密の場所」といった意味があり、ユーザーのブックマークを貴重な情報と捉え、それを強力に管理するという意味を込めた命名。

<br/>

## サービス概要
本アプリは、ブラウザのブックマーク機能を強化した最高のブックマーク管理アプリです。<br/>
ブックマークしたものの後で見返さないまま放置してしまう、大量に溜まったブックマークから目当てのページを探せない<br/>
といった悩みとはもうお別れです。

<br/>

## ユーザーが抱える課題
1. 後で見ようとブックマークに登録はするものの、自発的に見返すのが面倒で放置してしまう
2. ブックマークの肥大化によって、目当ての情報が探しにくいor見つけられない
3. 適切なカテゴリ分けが思いつかず、そもそもブックマークすること自体を諦めてしまう
4. 従来のブックマークでは、実際にページを開くまでは文字情報でしか中身の判断ができない<br/>
   （登録してから時間が経過して内容を忘れてしまったものや動画ページへのアクセス情報が少ない）

<br/>

## 解決方法
1. ブックマークされたページを定期的に通知することで、自動的にブックマークを消化できるようにする
2. フォルダ機能の他にタグ付け機能を用意し、目当ての情報にアクセスしやすくする
3. ブックマーク時に自動でドメインのタグと内容から予測したタグの2つを付与することで、カテゴリ分けを考えるコストを低減する
4. タグ付け機能とページのサムネイルを表示することによって、視覚的な情報を増やす

<br/>

## 想定されるユーザー層
- とりあえずブックマークに追加するだけしてそのまま放置してしまう方
- ブックマークが整理しきれず、目当ての情報にアクセスすることができない方
- 効率的に情報をキャッチアップする方法を探している方

<br/>

## サービスコンセプト
私自身、後で見ようとブックマークしたり、X（Twitter)でいいねをしておいたり、YouTubeのフォルダや履歴に残しておきはするものの、結局「後で見よう」に追加するだけで肝心の「後で見る」が実行出来ていませんでした。<br/>

いざ消化しようとした時には「後で見る」は大量に溜まってしまっていて、その量の多さに辟易して整理することすら億劫になっていました。<br/>
せっかく有益なページを発見しても見ることがなければ、知らないのと同じであり、この機会損失をプログラミングの力で解決できるのではないかと思いました。<br/>

本アプリでブックマークを管理し、自動的かつ効率的に情報を消化することによって、情報の滝に打たれるような使い心地を目指しています。<br/>
また、サービス利用時の煩わしさを極限まで取り払うこともコンセプトとしています。

<br/>

## 実装を予定している機能
### MVPリリース

- ログイン機能
- ブックマーク機能
- LINE通知機能
- Chrome拡張機能
- フォルダ機能、タグ付け機能
- タグを入力する際のオートコンプリート機能
- 登録時にドメインから自動でタグを生成・登録する機能
- タイトル、タグでの検索機能

### 本リリース
- 通知を任意の頻度・タイミングに設定できる機能
- アプリ内でのレコメンド機能
- SNSシェア機能
- ブックマークのサムネイル表示機能
- タグとは別にキャプションを付けられる機能
- 通知を特定のカテゴリに限定したり、ランダムにしたり設定できる機能
- Youtubeに任意のフォルダを作成し、そのフォルダに登録された動画を自動でブックマークに追加する機能
- タイトルや本文から適したタグを予測して付与する機能（on, off可能）
- 特定のサイトから送信された記事は対応したフォルダに自動で保存されるように設定できる機能
- ブックマーク管理のTipsを投稿できる機能

<br/>

## 画面遷移図

[Figma](https://www.figma.com/file/zQDdfYZbcgx3isA0kBJ6dr/%E7%94%BB%E9%9D%A2%E9%81%B7%E7%A7%BB%E5%9B%B3?type=design&node-id=0-1&mode=design&t=Y44nKjjD6CHSxsFL-0)

## ER図

![mermaid-diagram-2023-09-25-143623](https://github.com/yushi32/superior_bookmark_app/assets/133078588/c4a1b58c-5e90-411d-8dc7-7dae612052d9)

