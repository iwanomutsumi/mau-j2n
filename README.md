情報通信ネットワーク　通信課題

## 出題１ 
Gitについて調べ、何をするツールで何が便利なのかなどを３００〜５００字程度にまとめてください。

Gitはソースコードを管理・共有するための分散型バージョン管理システムです。コードに加えられた変更を,レポジトリと言われるデータベースに、バージョンとして記録することにより、開発・管理がスムーズに行えます。例えば、ファイルを変更した場合、修正版・変更版など複数のファイルが存在すると、どのファイルを編集するべきか把握がしにくくなります。Gitではファイルを変更した場合、変更内容などの履歴と一緒にファイルを保存できるため、最新のファイルや変更状況がすぐにわかり、目的のファイルを把握しやすくなります。また、ファイルを上書きしたとしても、任意のバージョンへ戻すことも簡単にできます。その他、中央のサーバーに接続してファイルを管理する中央集中型に比べると、Gitはユーザーがそれぞれレポジトリを持つ分散型であるため、サーバーがオフラインになって使用できなくなるというリスクが無く管理することができます。

## 出題２
GitHubについて同様に調べ３００〜５００字程度にまとめてください。

GitHubはクラウド上でGitを使用してバージョン管理できるサービスです。クラウド上にレポジトリを保持できるプラットフォームであり、複数の開発者が１つのプロジェクトに関わって、お互いの編集をリアルタイムで把握することができます。チームメンバーが多くても変更が自動で記録され、ファイルの反映・共有も簡単に行うことができるため、複数で共同開発する場合などに非常に便利です。ユーザーのパソコン内にローカルレポジトリを作成し、GitHubをリモートレポジトリとして利用されることが多いようです。GitHubのメリットとしては、Gitよりもコラボレーション機能などが強化され、共同開発が行いやすい他、無料で利用できること、他の開発ツールと連携しやすいことなども挙げられます。また、GitHubはファイルが公開保存されているため、他者のファイルの検索閲覧ができ、世界中の人々のプログラムやデザインなどの成果物の保存・公開ができるWebサービスともなっています。

## 出題３
Markdownについて同様に調べ３００〜５００字程度にまとめてください。

Markdownはデジタル文章を作成するときに使用するHTMLなどのマークアップ言語を簡略化できるようにした言語です。マークアップ言語のようにタグが必要なく、文頭などに簡単な記号「#」「-」などをつけることで「見出し」や「リスト」などとして記述をすることができます。そのため、まるでワープロ原稿を打つように自然に記述していくことが可能で、初心者でもすぐに利用することができます。その他のメリットとして、コピー＆ペーストがそのまま使用できること、オフラインでも使用できること、特別なアプリが必要ないことなどが挙げられます。また、Markdown形式で記述されたファイルの拡張子である.mdファイルは、visual Sutudio Codeなどの変換プログラムで変換するとHTMLファイルなどにも簡単に変換することができ非常に便利です。

## 出題５
出題１〜４までの実現に必要となった作業記録を追記


### 出題とTO DO LISTと実施日時
   - 作業中はVSCで基本常に記録を残しておく
1. Visual Sutudio Cord を使えるようにする（記録も同時に行うため）
2026/02/06/6:20
2. （出題１） Gitについて調べる. 
2026/02/06/7:28
   - 何をするツール
   - 何が便利なのか 
   - 300〜500字にまとめる　2026/02/06/9:28
3. （出題２） GitHubについて調べる
2026/02/06/8:51
   - 何をするツール
   - 何が便利なのか
   - 300〜500字にまとめる 2026/02/06/10:08
4. （出題３） Markdownについて調べる
2026/02/06/9:02
   - 何をするツール
   - 何が便利なのか 
   - 300〜500字にまとめる 2026/02/06/10:41
5. 学習指導書の用語で知らないものをざっと調べる
   - .mdと書き出し方 2026/02/06/12:00
   - レポジトリ 2026/02/06/8:20
6. （出題４・5）出題１〜３をREADME.mdファイル作成する　2026/02/06/12:36
7. （出題４・5） git　インストール 2026/02/06/12:49
8. （出題４・5） git セットアップ  2026/02/06/17:25
9. （出題４・5） git　使い方 2026/02/07/10:19
   - git init
   - dit add
   - git commit
   - git push
10. （出題４・5） github アカウントの作成  2026/02/06/17:56
11. （出題４・5） github へのREADME.mdの公開 2026/02/07/12:52
12. （出題４・5） README.mdに作業記録を追記gitahubへ公開
    - ソフトウエアのインストール
    - コマンドの入力
    - 実行結果- 起こったエラー
    - 自分の建てた仮説・分かったこと
13. （出題6） README.mdの見直し,３回以上git commit

### 作業内容
#### １ Vsual Studio Code 使えるようにする

- Visual Studio Code をダウンロードしたい
→検索「Download Visual Studio Code.」→
https://code.visualstudio.com/download

- Visual Studio Code 日本語化したい
→検索 「vsc マークダウン 日本語　」→
https://qiita.com/heppokofrontend/items/8a795f3c516198e00165

- VJapanese Language Pack for Visual Studio Code をインストール→  
https://marketplace.visualstudio.com/items?itemName=MS-CEINTL.vscode-language-pack-ja

-  Visual Studio Code でmarkdownをプレビュー表示したい
→検索「vsc マークダウンプレビュー」→.   
https://qiita.com/k_maki/items/d2ed604ac967e029c9a9
→エディターを分割して片方を右クリック→プレビューを選択する

#### ２ （出題１） Gitについて調べる. 

- 全くわからないので初心者向けにまとめたサイトを探したい
→検索「Git」→
   - 図解解説】これ1本でGitをマスターできるチュートリアル！【完全版】／@Sicut_study(渡邉 臣 | JISOU)in JISOU | Reactプログラミングコーチング／Qiita
https://qiita.com/Sicut_study/items/0318cc136c189b179b7f

   → インストール・設定・GitHUbについても記載

   - 【入門】Gitとは？できることや使い方、GitHubとの違いをわかりやすく解説／カゴヤのサーバー研究室
https://www.kagoya.jp/howto/it-glossary/develop/git/
  - 【初心者向け】GITとは何か？GITの概念を解説／@a_goto
(goto)／Qiitq
https://qiita.com/a_goto/items/0fe40b17105d1ac1c40b
-  各サイトからポイントをいかに抜き出してみる

##### 〈何をするツール〉
- ソースコードなどを管理・共有する分散型バージョン管理システム(コードに加えられた変更をリポジトリと言われるデータベースにバージョンとして記録するシステム)
- サーバーが複数箇所に分散（ユーザーそれぞれがリポジトリを持つ。主となるサーバーがないのでオフラインにならず、他のリポジトリと同期可能）
##### 〈何が便利なのか〉
- 修正版・更新版などファイルが複数存在するとどれを編集するべきかわからなくなる。変更したかったかという変更履歴とともにファイルを保存できる。上書きしたとしても任意のバージョンへ簡単に戻すことが可能。
- チームで変更履歴とファイルをスムーズに共有できる。履歴の取り込み、ファイルの反映、履歴の枝分かれなど豊富な機能でチームの共同開発の効率化が図れる。
- デメリットとしてチーム全員がGitを理解し使用できる必要がある。さまざまな使い方ができるため、運用ルールを決めておかないと混乱が生じ効率が落ちる。
##### 〈用語メモ〉
- **リポジトリ**:ファイルや変更履歴を保存しておくデータベース。
  - ローカルPC上に存在するのがローカルリポジトリ。Webサーバー上に存在するのがリモートリポジトリ。
  - ユーザーがローカル環境でソースコードの編集などを行う際は、ローカルリポジトリを使う。
一方リモートリポジトリは、他ユーザーとファイル・変更履歴を共有する際に利用する。
- **コミット**：ファイルや変更履歴をリポジトリへ登録すること
- **プッシュ**：コミットを、ローカルリポジトリからリモートリポジトリへ反映させること。
プッシュを行うことで、ローカルリポジトリ上のファイルや変更履歴が、リモートリポジトリへアップロードされる。
- **add**：コミットを行う前の準備みたいなもので、ファイルを編集したことをインデックスに登録する作業です。
- **インデックス**:=ステージング（ともよばれる。）複数のファイルがある場合、変更していないファイルをコミットしないよう判断する仲介役。
検索→「Git インデックス」→
https://tetoblog.org/2021/06/git-index/
- **ワークツリー**:Git Worktreeは、同じリポジトリに複数の作業ディレクトリ（working tree）を持つことができる機能です。簡単に言うと、一つのGitリポジトリから複数のフォルダを作成し、それぞれで異なるブランチを同時に作業できるということです。ファイルをコミットしないよう判断する仲介役。
（今回はあり理関係ないかも？）
検索→「Git ワークツリー」→
https://zenn.dev/hiraoku/articles/56f4f9ffc6d186

##### （300〜500字にまとめる）
Gitはソースコードを管理・共有するための分散型バージョン管理システムです。コードに加えられた変更を,レポジトリと言われるデータベースに、バージョンとして記録することにより、開発・管理がスムーズに行えます。例えば、ファイルを変更した場合、修正版・変更版など複数のファイルが存在すると、どのファイルを編集するべきか把握がしにくくなります。Gitではファイルを変更した場合、変更内容などの履歴と一緒にファイルを保存できるため、最新のファイルや変更状況がすぐにわかり、目的のファイルを把握しやすくなります。また、ファイルを上書きしたとしても、任意のバージョンへ戻すことも簡単にできます。その他、中央のサーバーに接続してファイルを管理する中央集中型に比べると、Gitはユーザーがそれぞれレポジトリを持つ分散型であるため、サーバーがオフラインになって使用できなくなるというリスクが無く管理することができます。

#### 3 （出題２） GitHubについて調べる

- 全くわからないので初心者向けにまとめたサイトを探したい
→（gitについて検索したサイトも参照）検索「GitHUb」→
   - GitとGitHubの違いを理解して使い始めるには／Kinsta
   https://kinsta.com/jp/blog/git-vs-github/
   - GitHubとは？メリットやデメリット・注意点を解説！使い方や用語・基礎知識まとめ／blastengine
   https://blastengine.jp/blog_content/github/
   - GitHub(ギットハブ)とは？特徴や使い方を初心者向けにわかりやすく紹介／SAMURAI ENGINEER BLOG
   https://www.sejuku.net/blog/7901
- 各サイトからポイントをいかに抜き出してみる

##### 〈何をするツール〉
- クラウド上でgitをを使ってバージョン管理できるサービス。ユーザーのPC内にローカルレポジトリを作成、GItHubをリモートレポジトリとして利用捨ことが多い。世界で最も利用されている。
- 世界中の人々が自分の作品などの成果物（プログラムやデザインなど）を保存、公開できるWebサービスのことです。世界で1億人を超える人々が利用しています。
- プロジェクト管理や成果物の公開・共有、学習ツール
##### 〈何が便利なのか〉
- クラウドベースのストレージにコードのリポジトリを保持できるプラットフォームであるため、複数の開発者が1つのプロジェクトの作業を行い、お互いの編集をリアルタイムで確認できます。Webプロフェッショナル向けのネットワーキングサイトであるとも言えるでしょう。
- Gitのようにバージョン管理できる
- Gitよりプロジェクト管理とコラボレーさ本機能が強化されている。チーム全体でのコミュニケーションと享禄が促進され、共同開発が円滑に進行できる。
- チームメンバーが多くても変更が自動的に記録され、簡単に把握dきる。公開非公開保存が利用できる。他者のファイルが検索閲覧できる。コミュニティ機能が使える。
- 無料でも使用できる
- 他の開発ツールと連携しやすい
##### 〈300〜500字にまとめる〉
GitHubはクラウド上でGitを使用してバージョン管理できるサービスです。クラウド上にレポジトリを保持できるプラットフォームであり、複数の開発者が１つのプロジェクトに関わって、お互いの編集をリアルタイムで把握することができます。チームメンバーが多くても変更が自動で記録され、ファイルの反映・共有も簡単に行うことができるため、複数で共同開発する場合などに非常に便利です。ユーザーのパソコン内にローカルレポジトリを作成し、GitHubをリモートレポジトリとして利用されることが多いようです。GitHubのメリットとしては、Gitよりもコラボレーション機能などが強化され、共同開発が行いやすい他、無料で利用できること、他の開発ツールと連携しやすいことなども挙げられます。また、GitHubはファイルが公開保存されているため、他者のファイルの検索閲覧ができ、世界中の人々のプログラムやデザインなどの成果物の保存・公開ができるWebサービスともなっています。

#### 4 （出題3） Markdownについて調べる

- スクでやったが一応調べる
→検索「マークダウン」→
   - 【マークダウン記法とは？】マークダウンの書き方を網羅的に解説／backlog
   https://backlog.com/ja/blog/how-to-write-markdown
   - Markdown記法一覧／@oreo(oreo)in Goodpatch／Qiita
   https://backlog.com/ja/blog/how-to-write-markdown


##### 〈何をするツール〉
- デジタル文章を作るときに使うHTML（HyperText Markup Language）などのマークアップ言語を、簡略化できるようにプログラムされました。一言でまとめれば、「マークアップ」をより簡単に使えるようにしたものが、「マークダウン」ということになります。
##### 〈何が便利なのか〉
- 手軽に文章構造を明示できること
- 簡単で、覚えやすいこと
- 読み書きに特別なアプリを必要としないこと
- それでいて、対応アプリを使えば快適に読み書きできること
- コピペが可能
- オフラインでも使用可能
##### 〈300〜500字にまとめる〉
Markdownはデジタル文章を作成するときに使用するHTMLなどのマークアップ言語を簡略化できるようにした言語です。マークアップ言語のようにタグが必要なく、文頭などに簡単な記号「#」「-」などをつけることで「見出し」や「リスト」などとして記述をすることができます。そのため、まるでワープロ原稿を打つように自然に記述していくことが可能で、初心者でもすぐに利用することができます。その他のメリットとして、コピー＆ペーストがそのまま使用できること、オフラインでも使用できること、特別なアプリが必要ないことなどが挙げられます。また、Markdown形式で記述されたファイルの拡張子である.mdファイルは、visual Sutudio Codeなどの変換プログラムで変換するとHTMLファイルなどにも簡単に変換することができ非常に便利です。

#### 5 学習指導書の用語で知らないものをざっと調べる
   - .md
   検索「.md」
   gemini→テキストベースの軽量マークアップ言語「Markdown（マークダウン）」で記述されたファイルを指す拡張子
    - 【Markdown】.mdファイルをHTMLで出力する／BFT名古屋 TECH BLOG／Hatena Blog
    https://bftnagoya.hateblo.jp/entry/2022/04/27/134011
   - レポジトリ Git参照
   - mdファイル書き出し方
   検索「VSC　.mdファイル書き出し方」
   VSCodeで始めるMarkdown入門／@ourinhu269(oHrin)in愛知工業大学・システム工学研究会／Qiita
   https://qiita.com/ourinhu269/items/af1e2b4d7fb71a78aef3
   拡張子はmd です。つまり、ファイル名の最後に .md とつける必要があります。

#### 6 （出題４・5）出題１〜３をREADME.mdファイル作成する

VSCで作成し、.mdをファイル名につけて保存するだけでした

#### 7 （出題４・5） インストール
- Gitをインストールしたい
→検索「Git インストール」→1.5 使い始める 
  - Gitのインストール／git
https://git-scm.com/book/ja/v2/使い始める-Gitのインストール
  - Gitをインストールする方法（Windows、macOS、Linux別）／Kinsta
https://kinsta.com/jp/blog/install-git/
→インストーラーをどこからダウンロードするのかわからない。HomebrewというのをインストールしてGitをインストールする？

  - Gitサイト インストール mac版
https://git-scm.com/install/mac

  - [入門] Mac 環境における Git & Github の環境構築／@generosity_hiroto_taniguchi
(Hiroto Taniguchi)in 株式会社GENEROSITY／Qiita
https://qiita.com/generosity_hiroto_taniguchi/items/0a1c9a2548527f50b5ff
→MacはGitがデフォルトでインストールされているらしい！

- [ターミナル]git --version → git version 2.39.5 (Apple Git-154)
→ 入っていたけど最新バージョンではない 最新2.53.0

- Gitを最新バージョンにしたい
→検索「Gitを最新バージョンにしたいル」→Gitバージョンの確認と更新方法：完全ガイド
https://go.lightnode.com/ja/tech/how-to-check-and-update-git-version
→ 公式サイトでインストーラかHomebrewが必要。インストーラーの場所がわかないので、Homebrewで試してみる。

- Homebrewをインストールする https://brew.sh
  - [ターミナル]/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
→ ==> Checking for `sudo` access (which may request your password)...
Password:
→ インストールできない
  - [ターミナル]/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
→xcode-select --install
xcode-select: note: Command line tools are already installed. Use "Software Update" in System Settings or the softwareupdate command line interface to install updatesもうインストールされてるからアップデートをインストールして（システム設定かコマンドで）
→ システム設定でアップデートする

  - 再度- Homebrew https://brew.sh
  - [ターミナル]/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
→ [ターミナル]止まったっぽいので brew --version 
→zsh: command not found: brew → インストールできていない
→ まだインストール中かも（待ってみる）
→ 

  - ==> Next steps:
 Run these commands in your terminal to add Homebrew to your PATH:
    echo >> /Users/iwanomutsumi/.zprofile
    echo 'eval "$(/opt/homebrew/bin/brew shellenv zsh)"' >> /Users/iwanomutsumi/.zprofile
    eval "$(/opt/homebrew/bin/brew shellenv zsh)"

    コマンド入力しろって書いてい流みたいだけど
    どういこと？
    →ChatGPTに聞いてみる
    → Macの場合は必要でそのままコピペして一つづつ入れていけば良さそう。コマンドを入力後も特に反応はないので心そのままでも配ないそう。
→ [ターミナル] brew --version 
→Homebrew 5.0.13
→ バージョンが表示されたのでインストールできたよう
- GitをHomebrewでバージョンしたい
→ [ターミナル] brew install git 
→インストールされだした。
→ [ターミナル] git --version 
→git version 2.50.1 (Apple Git-155)
→最新ではない（Macに入っているバージョン）
- ChatGTPにアップデートの仕方を聞いた
→ [ターミナル]
brew update　と
brew upgrade git
→Warning: git 2.52.0_1 already installed
→ [ターミナル]git --version
→git version 2.50.1 (Apple Git-155)
- ChatGTPに原因と対処法を聞いた→Homebrrew側のgitが優先されていない（Macのgit優先）→パスを正しく変更する
→[ターミナル]which git（どっちのgit?）
→/usr/bin/git（Macのgit）
→[ターミナル]eval "$(/opt/homebrew/bin/brew shellenv zsh)"（パスをHomebrewのgit側へ）
→[ターミナル]which git（どっちのgit?）
→/opt/homebrew/bin/git（Homebrewのgit）
→ [ターミナル]git --version
→ git version 2.52.0（最新になった）

#### ８ （出題４・5） git セットアップ
- Gitを設置アップとは何？→使える状態にする準備（ChatGTP）
- 検索「git使い方」→- 図解解説】これ1本でGitをマスターできるチュートリアル！【完全版】／@Sicut_study(渡邉 臣 | JISOU)in JISOU | Reactプログラミングコーチング／Qiita
https://qiita.com/Sicut_study/items/0318cc136c189b179b7f

- →バージョン管理には「誰が」「いつ」「どのような変更をしたか」を記録するためにユーザー情報を付与しています。
その情報を利用前に設定する必要があります。名前とメールアドレスを設定する
  - → [ターミナル]git config --global user.name "Iwano Mutsumi"
→ 何もなし
  - → [ターミナル]git config git config --global user.email iwanomutsumi@gmail.com
→ error: no action specified→何して欲しいかわからないという意味で問題なし → ちゃんと設定できたか確かめる方法（Chatagpt）
  - → [ターミナル]git config --global --list
→ user.name=Iwano Mutsumi → 舐めしか出てこないからメールアドレスは設定できていない → よくみるとコマンドが間違ってたので再度実施
  - → [ターミナル]git config --global user.email iwanomutsumi@gmail.com
 → 何もなし（設定できたかも）
   - → [ターミナル]git config --global --list
→ user.name=Iwano Mutsumiとuser.email=iwanomutsumi@gmail.comが表示される。→ 設定できた。
- 自分のPCのローカルレポジトリとGitHubのリモートレポジトリの間をSSH接続できるようにする（ユーザー名やパシワード無しで簡単に同期できる）。公開鍵と秘密鍵を設定する。
   - → [ターミナル]cd ~/.ssh
   - → [ターミナル]ssh-keygen -t rsa
→ Generating public/private rsa key pair.（鍵作るよ）
Enter file in which to save the key (/Users/(username)/.ssh/id_rsa):（どこに鍵保存？）
Enter passphrase (empty for no passphrase):（鍵にパスフレーズつける？）
Enter same passphrase again:（確認のためもう一回パスフレーズ入れて）→ 個人で学習するなら変えずにOK。それぞれエンターしていく → どこに鍵を作ったか表示される


Your identification has been saved in /Users/iwanomutsumi/.ssh/id_rsa
Your public key has been saved in /Users/iwanomutsumi/.ssh/id_rsa.pub
The key fingerprint is:
SHA256:12+wt3kwvhSSNQsC+ZibShmsvzdnVgVu1a88tEP2jcc iwanomutsumi@iwanomutsuminoMacBook-Pro.local
The key's randomart image is:
+---[RSA 3072]----+
|        ..     . |
|        ..  . . .|
|     .   +...oo .|
|      o o .oo+=o.|
|     . oSo..=*o*.|
|    . o o.  .=X.E|
|     o .   ...=* |
|      o o +  +.o.|
|      .o =    +o |
+----[SHA256]-----+


   -  [ターミナル]ls ~/.ssh（鍵が作られたか確認）
   → id_rsa		id_rsa.pub（確認）
   -  [ターミナル]pbcopy < ~/.ssh/id_rsa.pub（クリップボードに公開鍵をコピー。GitHubに渡すため）
   → 特に反応なし（おそらくコピーされている）

#### 10 （出題４・5） github アカウントの作成
- GitHubアカウント作成→検索「」
→ GitHub でアカウントを作成する／GitHubドキュメント
https://docs.github.com/ja/get-started/start-your-journey/creating-an-account-on-github

- → 新しい個人用アカウントへのサインアップ
  - https://github.com/ に移動します。
  - [サインアップ] をクリックします。
  - または、[Google で続行] をクリックし、ソーシャル ログインを使用してサインアップします。
  - プロンプトに従って、個人アカウントを作成します。

  - 鍵の作り方２種類あった
    - 1・[ターミナル]ssh-keygen -t rsa（古い鍵の作り方）
     - 2・[ターミナル]ssh-keygen -t ed25519 -C "GitHubに登録したメールアドレス"（最近の鍵の作り方）
  -  [ターミナル]ls ~/.ssh（結果でどちらの鍵が作られたか確認）
     - 例：id_ed25519_github など（新しい作り方。GitHub推奨）
     - id_rsa / id_rsa.pub（古い作り方。rasで作ってる）

  -  [ターミナル]eval "$(ssh-agent -s)"（ssh-agent を起動して、その設定を今のターミナルに反映する。ssh-agent（鍵を覚える常駐係）を起動。環境変数を表示する）
  -  [ターミナル]ssh-add ~/.ssh/id_ed25519（ssh-agent を起動して、その設 → /Users/iwanomutsumi/.ssh/id_ed25519: No such file or directory（この場所に鍵はないよという意味）
  -  [ターミナル]ssh-add ~/.ssh/id_rsa（秘使うため、密鍵をPCに登録）
  → Identity added: /Users/iwanomutsumi/.ssh/id_rsa (iwanomutsumi@iwanomutsuminoMacBook-Pro.local)
- 古いやり方でやってみたけど鍵を新しく作り直してみたい
-  [ターミナル]ssh-keygen -t ed25519 -C "iwanomutsumi@gmail.com"

Generating public/private ed25519 key pair.
Enter file in which to save the key (/Users/iwanomutsumi/.ssh/id_ed25519): 
Enter passphrase for "/Users/iwanomutsumi/.ssh/id_ed25519" (empty for no passphrase): 
Enter same passphrase again: 


→３回Enter（フレーズなどで強化しない）

Your identification has been saved in /Users/iwanomutsumi/.ssh/id_ed25519
Your public key has been saved in /Users/iwanomutsumi/.ssh/id_ed25519.pub
The key fingerprint is:
SHA256:7yjbKlir7Ro1IlZtd9Sy9Dta15c744s4U+x47oVkJlw iwanomutsumi@gmail.com
The key's randomart image is:
+--[ED25519 256]--+
|         ..      |
|    .   .o .     |
|   . o ...+  E   |
|  . . . .....    |
|... o   S  oo+. .|
|.. o..   . +=+.o.|
|  .o .    + *. .o|
|  .oo .. + +.oo+ |
|  o+o.o+o ..*+.o+|
+----[SHA256]-----+

  -  [ターミナル]eval "$(ssh-agent -s)"
  →Agent pid 12580（こんなkんじのがでたらOK）
  -  [ターミナル]ssh-add ~/.ssh/id_ed25519（秘密鍵PCに登録）
  →Identity added: /Users/iwanomutsumi/.ssh/id_ed25519 (iwanomutsumi@gmail.com)
 -  [ターミナル]cat ~/.ssh/id_ed25519.pub（公開鍵をターミナルに表示・このコマンドは秘密鍵には絶丁使わないこと！）
 →ssh-ed25519 AAAAC3NzaC1lZDI1NTE5AAAAINVuoF6F0il7lt5gALnQOccsENqhj028mjt/7DTK/O+d iwanomutsumi@gmail.com

- GitHubサイトへ
右上アイコンから→setting>画面左のメニューからSSH and GPG keysをクリック->new SSH key→Add new SSH keyにこの鍵がわかるようtitleに任意の名前を(new_practice)、keyに公開鍵を入力。keytypeはそのままAuthentication key（認証用の鍵）

- リポジトリを作りたい
  - GitHubサイトから左のcreate repositoryを押す。
Repository nameを任意に決めます（git_practice）。真ん中のpublicもしくはprivateは各自選んでください。
入力したら右下の緑色のボタンを押します。
URLだけで見てもらうにはパブリックじゃないとだめっぽい。



#### 9 （出題４・5） git　使い方
   - git init （レポジトリを新規に作成）
はじめてのGit！initコマンドでリポジトリを作成してみよう！／侍エンジニアブログ
   https://www.sejuku.net/blog/71268
     - inittestというリポジトリを作成
     -  [ターミナル]mkdir inittest（ディレクトリを作る）
     -  [ターミナル]git init inittest（デレクトリの中にリポジトリを作る）
     →Initialized empty Git repository in /Users/iwanomutsumi/inittest/.git/（作られた）

   - git add（ワーキングツリーからインデックスに登録）
   0から解説！git addコマンドを使ってファイルを登録してみよう／侍エンジニアブログ
   https://www.sejuku.net/blog/71463

     - ＊ワーキングツリー（git initで初期化した場所）
     - ＊インデックス（ワーキングツリーに入っているファイル）
     - ローカルレポジトリ（PC内　記録される）
     - リモートレポジトリ（Gitサーバー上にある。今回はGitHub）

     -  [ターミナル]git add ファイル名（ワーキングツリー内の特定のファイルをインデックスに登録）
     -  [ターミナル]git add .（ワーキングツリー内のファイルをまとめて）
     -  [ターミナル]git reset HEAD ファイル名（間違ってaddした場合に取り消す）

     -  [ターミナル]git add README.md（ワーキングツリー内の特定のファイルをインデックスに登録）
     →atal: not a git repository (or any of the parent directories): .git（ターミナルがいる場所が違った？）
     -  [ターミナル]pwd（場所確認）
     →/Users/iwanomutsumi
     -  [ターミナル]ls（中身確認）
     →Desktop Downloads	Library Music Public ocuments	inittest	Movies Pictures
     -  [ターミナル]cd ~/Desktop/課題（README.mdのあるフォルダへ→ダメだった）
     -  [ターミナル]pwd（場所確認）
     →/Users/iwanomutsumi/Desktop/課題
     -  [ターミナル]ls（中身確認）
     →0 2 4	README_R.md 1 3 README README.md
     -  [ターミナル]git add README.md
     -  [ターミナル]cd /Users/iwanomutsumi/inittest/.git/（git initで出たurlダメだった→inittestが作業ツリーへ移動）
     -  [ターミナル]cd /Users/iwanomutsumi/inittest(作業ツリーへ移動)
     -  [ターミナル]cp ~/Desktop/課題/README.md .（作業ツリーへファイルをコピー。lsで確認）
     -  [ターミナル]git add README.md(できた)
     -  [ターミナル]git status(できたか確認)
     →On branch main
     No commits yet
     Changes to be committed:
     (use "git rm --cached <file>..." to unstage)
     new file:   README.md


   - git commit（Gitローカルレポジトリにファイルと変更を登録）
   はじめてのGit！コミット(commit)でファイルを登録してみよう／侍エンジニアブログ
   https://www.sejuku.net/blog/71279
     -  [ターミナル]git commit -m “追加コメントを入れられる”
     -  [ターミナル]git commit -m “出題１”
     → [main (root-commit) e4a055f] “出題１”
     1 file changed, 16 insertions(+)
     create mode 100644 README.md
     -  [ターミナル]git commit ファイル名（特定のファイルのみ）
     -  [ターミナル]git commit -m “コメント内容” ファイル名（コメント付きで特定のファイルのみ）
     -  [ターミナル]git commit .（現在のディレクトリ配下全て含めてコミット）

   - git push（リモートレポジトリにアップロード）
   【Git初心者向け】リポジトリの作成からpushまでを解説／侍エンジニアブログ
   https://www.sejuku.net/blog/70775
   - git git pushoよくあるエラー／初心者向けGit講座】git pushとgit remote設定の基本／URBAN
   https://www.urban-sp.jp/column/188/
     -  [ターミナル]git remote add origin レポジトリのURL（リモートリポジトリに追加）
     -  [ターミナル]git remote add origin https://github.com/iwanomutsumi/git_practice.git
   →github.com/iwanomutsumi/git_practice.git
error: remote origin already exists.（もうあるって言われた）
     -  [ターミナル]git remote set-url origin git@github.com:iwanomutsumi/git_practice.git（HTTPSのURLになっていたのでSSHに修正）
     -  [ターミナル]ssh -T git@github.com（SSH接続テスト.→GitHubからあいさつ来る）
     -  [ターミナル]git remote -v（リモートのurl確認）
     
     -  [ターミナル]git push -u origin main（originはリモート名、mainはブランチ名masterのこともある、-uは次からgit pushだけでOKにする）
     →書き換えられたっぽい内容が出る

     -  [ターミナル]git remote set-url origin git@github.com:iwanomutsumi/mau-j2n.git（Githubのレポジトリの名前を課題に合わせて変更）


#### 11 （出題４・5） github へのREADME.mdの公開
- https://github.com/iwanomutsumi/mau-j2n で閲覧可能確認