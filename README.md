# Bookers2

本を読んだユーザーが、本のタイトルと感想を投稿することができるwebアプリケーション


* 使用言語・フレームワーク<br>
  →使用言語：Ruby, Javascript, HTML, CSS<br>
  →フレームワーク：Ruby on rails

* 開発環境（インフラ・DB）<br>
 →開発環境：AWS cloud9<br>
 →サーバー：AWS EC2<br>
 →DB：sqlite3

* なぜその言語・フレームワークを選んだか<br>
  →Rubyを学習したことがなかったため、開発を行いながらRubyの学習も進めたいと考えたため<br>
  →MVCパターンについて学習することでフロントエンドとバックエンドの理解が深まると考えたため

* 成果物のこだわり<br>
  →Ruby on railsで基本とされている7つのアクションを全て利用した（new, create, index, show, edit, update, destroy）<br>
  →ユーザー機能を追加した<br>
  →セキュリティーを考慮した設計を心がけた
  →画面レイアウトを考えて設計を行なった（bootstrap）

* 反省点<br>
  →このアプリケーション独自の機能がないため、利用者が魅力を感じない可能性がある

* <h5>画面レイアウト</h5>
<h3>トップページ</h3>
→Log inをクリックしてログイン画面、Sign Upをクリックしてユーザーサインアップ画面に遷移
<img width="1710" alt="top" src="https://github.com/szkTJ29/bookers2/assets/87642790/735c07d4-bd18-4d09-b04c-157ff974da0c">
<h3>ログイン画面</h3>
→ログイン後はログインユーザーのユーザー詳細画面に遷移
<img width="1710" alt="log in" src="https://github.com/szkTJ29/bookers2/assets/87642790/54afc8ed-9a52-477b-8199-4bef48471c43">
<h3>サインアップ画面</h3>
→サインアップ後はログインユーザーのユーザー詳細画面に遷移
<img width="1710" alt="sign up" src="https://github.com/szkTJ29/bookers2/assets/87642790/7e152ff1-1f15-4f5e-9047-4bc693b2d453">
<h3>アバウトページ</h3>
<img width="1710" alt="about" src="https://github.com/szkTJ29/bookers2/assets/87642790/de47de00-350f-4c1d-b87c-2583583479ce">

<h3>本の投稿一覧</h3>
→titleをクリックしてその本の投稿詳細画面に遷移、フォームのtitleとopinionを入力後Create Bookをクリックして新規投稿
<img width="1710" alt="books:index" src="https://github.com/szkTJ29/bookers2/assets/87642790/c6c47176-6510-410a-9c78-089479457c02">

<h3>本の投稿詳細</h3>
→Editをクリックしてその本の投稿編集画面に遷移、Destroyをクリックして投稿削除、フォームのtitleとopinionを入力後Create Bookをクリックして新規投稿
<img width="1710" alt="books:show" src="https://github.com/szkTJ29/bookers2/assets/87642790/51195aa0-db85-4ea0-a5f9-40177351e750">
<h3>本の投稿編集</h3>
→Showをクリックしてその本の投稿詳細画面、Backをクリックして投稿一覧画面に遷移、DUpdate Bookをクリックして投稿内容更新
<img width="1710" alt="books:edit" src="https://github.com/szkTJ29/bookers2/assets/87642790/ea17b653-571f-4ae2-b619-cbe1e9e2f8b5">
<h3>ユーザーの一覧</h3>
→Showをクリックしてそのユーザーの詳細画面に遷移、フォームのtitleとopinionを入力後Create Bookをクリックして新規投稿
<img width="1710" alt="users:index" src="https://github.com/szkTJ29/bookers2/assets/87642790/976f2a17-a125-4b94-8664-79a4eec2a720">

<h3>ユーザーの編集</h3>
→フォームのnameとintroductionを変更し、ユーザー画像をアップロードした後にUpdate Userをクリックしてユーザー情報更新
<img width="1710" alt="users:edit" src="https://github.com/szkTJ29/bookers2/assets/87642790/c892f7ff-fe8d-400f-86fa-e1403a3dff31">

