# メンタルヘルス系アプリ

## DEMO

  - n/a

## 紹介と使い方

  - 自分の心の動きや思いを視覚的に見ることで、自己需要、自己理解、自己成長等をサポートします。
  - テンポラリーな視覚化やインタラクティブ性ですが、indexページのパルスは、ユーザの入力で変化します。
  - まだ、コンテンツはありませんが、ユーザ登録すると履歴の登録や様々なメニューが使えるようになる予定です。
  - カウンセラーやコーチなどにコンタクトできます。
  - カウンセリンクやコーチングを提供している方は、サービスの登録ができます。

## 工夫した点

  - D3.jsで、ユーザの入力によって視覚化を変える部分と入力のしやすさ、ロードした後の印象を前回から改善しました。
  - 今回のテーマであったクラスの使用は、アクセスする時間帯によって、indexのh1タグメッセージが変わる部分に適用しました。本来、見せるコンテンツ自体も少し変えたかったのですが、間に合いませんでした。
  - この構想の背景は、ユーザの共感を得やすくするためと、深夜にこうしたサイトにアクセスする方は、深刻な悩みを抱えているケースがあるためです。

## 苦戦した点

  - パルスをインタラクティブにする点、indexページは、tailwindに頼れなかったため、全体のバランスを整える点に苦労しました。入力インタフェースは、まだ改善が必要ですが、時間が足りませんでした。
  - 管理者、カウンセラー、一般ユーザと、ログインが３タイプあるのですが、うまく動いているコードを流用しても、エラー続出でした。修正が間に合わず、限時点では、ユーザの詳細ページは、ログイン情報と紐づいていません。

## 参考にした web サイトなど

  - https://www.d3indepth.com/transitions/
  - https://d3-graph-gallery.com/index.html
  - https://datacrayon.com/

