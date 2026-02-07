情報通信ネットワーク　通信課題

## 出題１ 
Gitについて調べ、何をするツールで何が便利なのかなどを３００〜５００字程度にまとめてください。

Gitはソースコードを管理・共有するための分散型バージョン管理システムです。コードに加えられた変更を、レポジトリと言われるデータベースに、バージョンとして記録することにより、開発・管理がスムーズに行えます。例えば、ファイルを変更した場合、修正版・変更版など複数のファイルが存在すると、どのファイルを編集するべきか把握がしにくくなります。Gitではファイルを変更した場合、変更内容などの履歴と一緒にファイルを保存できるため、最新のファイルや変更状況がすぐにわかり、目的のファイルを把握しやすくなります。また、ファイルを上書きしたとしても、任意のバージョンへ戻すことも簡単にできます。その他、中央のサーバーに接続してファイルを管理する中央集中型に比べると、Gitはユーザーがそれぞれレポジトリを持つ分散型であるため、サーバーがオフラインになって使用できなくなるというリスクが無く管理することができます。

## 出題２
GitHubについて同様に調べ３００〜５００字程度にまとめてください。

GitHubはクラウド上でGitを使用してバージョン管理できるサービスです。クラウド上にレポジトリを保持できるプラットフォームであり、複数の開発者が１つのプロジェクトに関わって、お互いの編集をリアルタイムで把握することができます。チームメンバーが多くても変更が自動で記録され、ファイルの反映・共有も簡単に行うことができるため、複数で共同開発する場合などに非常に便利です。ユーザーのパソコン内にローカルレポジトリを作成し、GitHubをリモートレポジトリとして利用されることが多いようです。GitHubのメリットとしては、Gitよりもコラボレーション機能などが強化され、共同開発が行いやすい他、無料で利用できること、他の開発ツールと連携しやすいことなども挙げられます。また、GitHubはファイルが公開保存されているため、他者のファイルの検索閲覧ができ、世界中の人々のプログラムやデザインなどの成果物の保存・公開ができるWebサービスともなっています。

## 出題３
Markdownについて同様に調べ３００〜５００字程度にまとめてください。

Markdownはデジタル文章を作成するときに使用するHTMLなどのマークアップ言語を簡略化できるようにした言語です。マークアップ言語のようにタグが必要なく、文頭などに簡単な記号「#」「-」などをつけることで「見出し」や「リスト」などとして記述をすることができます。そのため、まるでワープロ原稿を打つように自然に記述していくことが可能で、初心者でもすぐに利用することができます。その他のメリットとして、コピー＆ペーストがそのまま使用できること、オフラインでも使用できること、特別なアプリが必要ないことなどが挙げられます。また、Markdown形式で記述されたファイルの拡張子である.mdファイルは、visual Sutudio Codeなどの変換プログラムで変換するとHTMLファイルなどにも簡単に変換することができ非常に便利です。

## 出題５
出題１〜４までの実現に必要となった作業記録を追記

### gitとは
基本的には、初心者向けの解説サイトで調べ把握した。分かった内容については出題１〜３のまとめを参照。調べた時間、調べたサイト、は以下参照。

- gitについて調べる 2026/02/06/7:28

  - 図解解説】これ1本でGitをマスターできるチュートリアル！【完全版】／@Sicut_study(渡邉 臣 | JISOU)in JISOU | Reactプログラミングコーチング／Qiita https://qiita.com/Sicut_study/items/0318cc136c189b179b7f
  - 【入門】Gitとは？できることや使い方、GitHubとの違いをわかりやすく解説／カゴヤのサーバー研究室 https://www.kagoya.jp/howto/it-glossary/develop/git/
  - 【初心者向け】GITとは何か？GITの概念を解説／@a_goto(goto)／Qiitq https://qiita.com/a_goto/items/0fe40b17105d1ac1c40b


- githubについて調べる 2026/02/06/8:51

  - GitとGitHubの違いを理解して使い始めるには／Kinsta
  https://kinsta.com/jp/blog/git-vs-github/
  - GitHubとは？メリットやデメリット・注意点を解説！使い方や用語・基礎知識まとめ／blastengine
  https://blastengine.jp/blog_content/github/
  - GitHub(ギットハブ)とは？特徴や使い方を初心者向けにわかりやすく紹介／侍エンジニアリングブログ
  https://www.sejuku.net/blog/7901


- Markdownについて調べる 2026/02/06/9:02
  - 【マークダウン記法とは？】マークダウンの書き方を網羅的に解説／backlog
  https://backlog.com/ja/blog/how-to-write-markdown
  - Markdown記法一覧／@oreo(oreo)in Goodpatch／Qiita
  https://backlog.com/ja/blog/how-to-write-markdown



これ以降も基本的に初心者向けのサイトを適当に検索し、記事と異なる部分、よくわからない部分をChatGPTに頼りながら進めた。



### gitインストール

- 分かった手順
  - Macにはgitがあらかじめ入っていることもある。
    - 入っているバージョンを(一応)確かめる
  - バージョンアップする（インストールし直す）
    - Xcodeのコマンドラインツールをインストール
    - Homebrewをインストール（インストーラーがあるようだがわからなかった）
    - Homebrewでgitをインストール
    - macのgitとHomebrewのgitが存在してしまうので、Homebrewのgitを優先するように指定する
  - コマンドの種類
    - git --version（入っている（優先の）gitのバージョンは？）
    - xcode-select --install（xcordインストール）
    - /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)" （Homebrewをインストール）
    - brew --version （Homebrewnのバージョンは？）
    - brew install git （gitをインストール）
    - brew update（Homebrew最新にして）
    - brew upgrade git（それでgitアップデートして）
    - which git（どっちのgit優先?）
    - eval "$(/opt/homebrew/bin/brew shellenv zsh)"（パスをHomebrewのgit側へ）


- 実施内容 2026/02/06/12:49
  - gitが入っているか確認
    - [ターミナル] git --version （gitが入っているか？）
    - → git version 2.50.1 (Apple Git-155)（macに入っているちょっと古いやつ）
  - インストールし直す
    - Xcodeのコマンドラインツールをインストール
      - [ターミナル]xcode-select --install（xcordインストール）
      - → xcode-select: note: Command line tools are already installed. Use "Software Update" in System Settings or the softwareupdate command line interface to install updates → もうインストールされてるからアップデートをインストールして（システム設定かコマンドで）
      - → システム設定でソフトウェアアップデートする
    - Homebrewのインストール
      - Homebrew https://brew.sh（インストール用コマンドがのっている）
      - [ターミナル]/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)" （Homebrewインストール）
      - → [ターミナル]brew --version （Homebrewインストールされたか？）
      - → zsh: command not found: brew  （インストールできていない）
      - → まだインストール中かも（待ってみる）→ 

      - → ==> Next steps:Run these commands in your terminal to add Homebrew to your PATH: echo >> /Users/iwanomutsumi/.zprofile echo 'eval "$(/opt/homebrew/bin/brew shellenv zsh)"' >> /Users/iwanomutsumi/.zprofile eval "$(/opt/homebrew/bin/brew shellenv zsh)"
      - → 指示どうりコマンドを入れる
      - [ターミナル]echo >> /Users/iwanomutsumi/.zprofile
      - [ターミナル]echo 'eval "$(/opt/homebrew/bin/brew shellenv zsh)"' >> /Users/iwanomutsumi/.zprofile
      - [ターミナル]eval "$(/opt/homebrew/bin/brew shellenv zsh)"
       - [ターミナル] brew --version (インストールできたか確認)
      - → Homebrew 5.0.13（できた）
    - gitをインストール
      - [ターミナル] brew install git （gitをインストール）
      - [ターミナル] git --version （gitインストールされた？）
      - → git version 2.50.1 (Apple Git-155)（macのgitのままになっている）
      - [ターミナル]brew update（Homebrew最新にして）
      - [ターミナル]brew upgrade git（それでgitアップデートして）
      - → Warning: git 2.52.0_1 already installed（もうインストールされてる）
      - [ターミナル]git --version（もう一回バージョン聞いてみる）
      - → git version 2.50.1 (Apple Git-155)（まだmac）
    - Macのgitからhomebrewのgitに優先を変更する
      - ChatGTPによるとHomebrrew側のgitが優先されていない（Macのgit優先）
      - [ターミナル]which git（どっちのgit優先?）
      - → /usr/bin/git（Macのgit）
      - [ターミナル]eval "$(/opt/homebrew/bin/brew shellenv zsh)"（パスをHomebrewのgit側へ）
      - [ターミナル]which git（どっちのgit優先?）
      - → /opt/homebrew/bin/git（Homebrewのgit）
      - [ターミナル]git --version（git入ってる？）
      - → git version 2.52.0（Homebrewになってバージョンも上がった）
- 参考サイト
  - Gitをインストールしてみよう！Windows/Macどちらも丁寧に解説／侍エンジニアリングブログ https://www.sejuku.net/blog/73444
  - Gitをインストールする方法（Windows、macOS、Linux別）／kinsta https://kinsta.com/jp/blog/install-git/
  - ChatGPTサイト

### gitセットアップ

- 分かった手順
  - gitのバージョン管理には「誰が」「いつ」「どのような変更をしたか」を記録するためにユーザー情報を付与。その情報を利用前に設定する必要がある。
    - 名前を設定する
    - メールアドレスを設定する
  - 自分のPCのローカルレポジトリとGitHubのリモートレポジトリの間をSSH接続できるようにする（ユーザー名やパシワード無しで簡単に同期できる）。公開鍵と秘密鍵を設定する。
     - 鍵の作り方は２種類ある
     - 古い鍵の作り方（最初こちらで作っちゃった）
       - 鍵を作る場所に移動
       - SSH鍵生成ツールでRSA方式の鍵を作る
       - 保存場所やパスフレーズをつけて強化するか、もう一回パスフレーズ確認を聞かれる（今回は勉強のためなのでそのままにする。Enter3回のみ）
       - クリップボードに公開鍵をコピーしてgithubに渡せるようにする
       - 自分のPCに秘密鍵を登録
     - 新しい鍵の作り方（GitHub推奨・こちらに作り直した）
       - Githubでアカウントを作成しておく
       - 現在作られている鍵を確認（古いの一回作ったから）
       - 鍵を作成
       - 場所・フレーズ聞かれたら３回エンターは同じ
       - PCに秘密鍵登録
       - ターミナルに公開鍵表示させる
       - GitHubサイトへ。右上アイコンからsetting > 画面左のメニューからSSH and GPG keysをクリック → new SSH key → Add new SSH keyにこの鍵がわかるようtitleに任意の名前を(new_practice)、keyにターミナルに表示させた公開鍵を入力。keytypeはそのままAuthentication key（認証用の鍵）

- 実施内容 2026/02/06/17:25

  - 名前とメアドの登録
    - [ターミナル]git config --global user.name "Iwano Mutsumi"（名前登録）
    - [ターミナル]git config --global user.email iwanomutsumi@gmail.com（メアド登録）
    - [ターミナル]git config --global --list（登録できた？）
    - → user.name=Iwano Mutsumi
    - → user.email=iwanomutsumi@gmail.com (設定できた) 
  - SSH接続のための鍵を作る
    - [ターミナル]cd ~/.ssh（鍵作る場所に移動）
    - [ターミナル]ssh-keygen -t rsa（SSH鍵生成ツールでRSA方式の鍵を作る）
    - → Generating public/private rsa key pair.（鍵作るよ）
    - → Enter file in which to save the key (/Users/(username)/.ssh/id_rsa):（ここに鍵保存でいい？）
    - Enter（そのままそこで）
    - → Enter passphrase (empty for no passphrase):（鍵にパスフレーズつける？）
    - Enter(つけない)
    - → Enter same passphrase again:（確認のためもう一回パスフレーズ入れて）
    - Enter（つけない）
    - → Your identification has been saved in /Users/iwanomutsumi/.ssh/id_rsa Your public key has been saved in /Users/iwanomutsumi/.ssh/id_rsa.pub The key fingerprint is: SHA256:12+wt3kwvhSSNQsC+ZibShmsvzdnVgVu1a88tEP2jcc iwanomutsumi@iwanomutsuminoMacBook-Pro.local The key's randomart image is: +---[RSA 3072]----+|        ..     . |        ..  . . .||     .   +...oo .||      o o .oo+=o.||     . oSo..=*o*.||    . o o.  .=X.E||     o .   ...=* |      o o +  +.o.||      .o =    +o |+----[SHA256]-----+



    -  [ターミナル]ls ~/.ssh（鍵が作られた?）
    - → id_rsa		id_rsa.pub（作られた）
    -  [ターミナル]pbcopy < ~/.ssh/id_rsa.pub（クリップボードに公開鍵をコピー）
    -  [ターミナル]ssh-add ~/.ssh/id_rsa（秘密鍵をPCに登録）
    - → Identity added: /Users/iwanomutsumi/.ssh/id_rsa (iwanomutsumi@iwanomutsuminoMacBook-Pro.local)
  - 鍵が２種類あることに気がつく（もう一つの方法で作り直す）
    -  [ターミナル]ls ~/.ssh（結果でどちらの鍵が作られたか確認）
       - 例：id_ed25519_github など（新しい作り方。GitHub推奨）
       - id_rsa / id_rsa.pub（古い作り方。rasで作ってる）
      - githubアカウント作成 → 「GitHubアカウント作成へ」
    -  [ターミナル]ssh-keygen -t ed25519 -C "iwanomutsumi@gmail.com"（新しい鍵作る）
    - Generating public/private ed25519 key pair.Enter file in which to save the key (/Users/iwanomutsumi/.ssh/id_ed25519): Enter passphrase for "/Users/iwanomutsumi/.ssh/id_ed25519" (empty for no passphrase): Enter same passphrase again: 

    - →３回Enter（フレーズなどで強化しない）
    - → Your identification has been saved in /Users/iwanomutsumi/.ssh/id_ed25519 Your public key has been saved in /Users/iwanomutsumi/.ssh/id_ed25519.pub The key fingerprint is: SHA256:7yjbKlir7Ro1IlZtd9Sy9Dta15c744s4U+x47oVkJlw iwanomutsumi@gmail.com The key's randomart image is+--[ED25519 256]--+|         ..      ||    .   .o .     |   . o ...+  E   ||  . . . .....    |... o   S  oo+. .||.. o..   . +=+.o.|  .o .    + *. .o||  .oo .. + +.oo+ ||  o+o.o+o ..*+.o+|+----[SHA256]-----+

    -  [ターミナル]eval "$(ssh-agent -s)"（鍵できた？）
    - → Agent pid 12580（OK）
    -  [ターミナル]ssh-add ~/.ssh/id_ed25519（秘密鍵PCに登録）
    - → Identity added: /Users/iwanomutsumi/.ssh/id_ed25519 (iwanomutsumi@gmail.com)
    -  [ターミナル]cat ~/.ssh/id_ed25519.pub（公開鍵をターミナルに表示・このコマンドは秘密鍵には絶丁使わないこと！）
    - → ssh-ed25519 AAAAC3NzaC1lZDI1NTE5AAAAINVuoF6F0il7lt5gALnQOccsENqhj028mjt/7DTK/O+d iwanomutsumi@gmail.com（表示さてた公開鍵）

    - GitHubサイトで公開鍵を登録



- 参考サイト
  - 図解解説】これ1本でGitをマスターできるチュートリアル！【完全版】／@Sicut_study(渡邉 臣 | JISOU)in JISOU | Reactプログラミングコーチング／Qiita https://qiita.com/Sicut_study/items/0318cc136c189b179b7f
  - ChatGPT

### gitの使い方
2026/02/07/10:19.  
gitを使う前に、gitインストール・セットアップ、githubアカウント作成・レポジトリ作成しておくと良いかもしれない
#### git init
- 分かった手順
  - git init （レポジトリを新規に作成）
     - inittestという名前のリポジトリを作成
       - ディレクトリを作る
       - デレクトリの中にリポジトリを作る   

- 実施内容 
  -  [ターミナル]mkdir inittest（inittestというディレクトリを作る）
  -  [ターミナル]git init inittest（デレクトリの中にリポジトリを作る）
  - → Initialized empty Git repository in /Users/iwanomutsumi/inittest/.git/（この場所に作られた）

- 参考サイト
  - はじめてのGit！initコマンドでリポジトリを作成してみよう！／侍エンジニアブログ
   https://www.sejuku.net/blog/71268


#### git add
 分かった手順
  - git add（ワーキングツリーからインデックスに登録）
    - ターミナルの位置をワーキングツリーに移動
    - README.mdをワーキングツリーにコピー
    - README.mdをワーキングツリーからインデックスに登録
    - (この辺がわからなくて試行錯誤してしまった)
  - 場所について
    - ワーキングツリー（git initで初期化した場所）
     - インデックス（ワーキングツリーに入っているファイル）
     - ローカルレポジトリ（PC内　記録される）
     - リモートレポジトリ（Gitサーバー上にある。今回はGitHub）
  -  コマンドの種類 
     - git add ファイル名（ワーキングツリー内の特定のファイルをインデックスに登録）
     - git add .（ワーキングツリー内のファイルをまとめて）
     - git reset HEAD ファイル名（間違ってaddした場合に取り消す）

- 実施内容 

  - どこでどうすればコマンドが使えるのかわからなかった
    -  [ターミナル]git add README.md
    - → atal: not a git repository (or any of the parent directories): .git（ターミナルがいる場所が違った？ファイルの場所が悪い？）
    -  [ターミナル]pwd（場所確認）
    - → /Users/iwanomutsumi
    -  [ターミナル]ls（中身確認）
    - → Desktop Downloads	Library Music Public ocuments	inittest	Movies Pictures
    -  [ターミナル]cd ~/Desktop/課題（README.mdのあるフォルダへ移動）
    - ダメだった
    -  [ターミナル]pwd（場所確認）
    →/Users/iwanomutsumi/Desktop/課題
    -  [ターミナル]ls（中身確認）
    - →0 2 4	README_R.md 1 3 README README.md
    -  [ターミナル]git add README.md
    -  [ターミナル]cd /Users/iwanomutsumi/inittest/.git/（git initで出たurlへ移動してみる）
    - → ダメだった
  - ターミナルの位置とファイルの場所が分かった
    -  [ターミナル]cd /Users/iwanomutsumi/inittest(作業ツリーへ移動)
    -  [ターミナル]cp ~/Desktop/課題/README.md .（ワーキングツリーへファイルをコピー。lsで確認）
    -  [ターミナル]git add README.md(README.mdをインデックスに登録)
    -  [ターミナル]git status(できたか確認)
    - → On branch main
     No commits yet
     Changes to be committed:
     (use "git rm --cached <file>..." to unstage)
     new file:   README.md 

- 参考サイト
  - 0から解説！git addコマンドを使ってファイルを登録してみよう／侍エンジニアブログ
   https://www.sejuku.net/blog/71463


#### git commit
 分かった手順
  - git commit（Gitローカルレポジトリにファイルと変更を登録）
  - コマンドの種類
    - git commit -m “追加コメントを入れられる”
    - git commit ファイル名（特定のファイルのみ）
    - git commit -m “コメント内容” ファイル名（コメント付きで特定のファイルのみ）
    - git commit .（現在のディレクトリ配下全て含めてコミット）

- 実施内容 
  - [ターミナル]git commit -m “出題１”
  - → [main (root-commit) e4a055f] “出題１”
     1 file changed, 16 insertions(+)
     create mode 100644 README.md

- 参考サイト
  - はじめてのGit！コミット(commit)でファイルを登録してみよう／侍エンジニアブログ
   https://www.sejuku.net/blog/71279


#### git push
- 分かった手順
    - git push（リモートレポジトリにアップロード）
    - コマンド種類
      - git remote add origin リモートレポジトリのSSHのURL（リモートリポジトリに追加）
      - git remote set-url origin（URLを変更する場合）
      - ssh -T git@github.com（SSH接続テスト.）
      - git remote -v（リモートのurl確認）

- 実施内容 
  - HTTP接続用のURLを使ってた
    -  [ターミナル]git remote add origin https://github.com/iwanomutsumi/git_practice.git
    - → github.com/iwanomutsumi/git_practice.git error: remote origin already exists.（もうある?って言われた）
  - SSH用のURLに変えることが分かった
    -  [ターミナル]git remote set-url origin git@github.com:iwanomutsumi/git_practice.git（HTTPSのURLになっていたのでSSHに修正）
    -  [ターミナル]ssh -T git@github.com（SSH接続テスト.）
    - → GitHubからあいさつ来る（OKということ）
    -  [ターミナル]git remote -v（リモートのurl確認）
    - → origin	git@github.com:iwanomutsumi/git_practice.git (fetch)
    - → origin	git@github.com:iwanomutsumi/git_practice.git (push)  
    -  [ターミナル]git push -u origin main（githubにファイルをアップロード。originはリモート名、mainはブランチ名 masterのこともある、-uは次からgit pushだけでOKにする）
    - → アップロードされたっぽい内容が出る
  -  githubのレポジトリの名前を課題の条件で作り忘れていたので名前をサイト上で変更
     -  [ターミナル]git remote set-url origin git@github.com:iwanomutsumi/mau-j2n.git（Githubのレポジトリの名前を課題に合わせて変更したのでこちらも変更しておく）

- 参考サイト
  - 【Git初心者向け】リポジトリの作成からpushまでを解説／侍エンジニアブログ
   https://www.sejuku.net/blog/70775
  - git git pushoよくあるエラー／初心者向けGit講座】git pushとgit remote設定の基本／URBAN
   https://www.urban-sp.jp/column/188/


### Githubアカウント作成

- 分かった手順
  - githubサイトでアカウントの作成
    - githubのサイト https://github.com/ に移動。
    - [サインアップ] をクリック。
    - または、[Google で続行] をクリックし、ソーシャル ログインを使用してサインアップします。
    - プロンプトに従って、個人アカウントを作成します。
  - githubのレポジトリ（リモートレポジトリ）の作成
    - GitHubサイトから左のcreate repositoryを押す。
    - Repository nameを任意に決める（git_practiceにしたけど課題で指定があったので後でmau-j2nに変更する）。
    - publicもしくはprivateを選ぶ。（urlで閲覧してもらうのでpublic）
    - 入力したら右下の緑色のボタンを押す。

- 実施内容 2026/02/06/17:56
  - 上記の手順でサイト上で作成


- 参考サイト

  - GitHub でアカウントを作成する／GitHubドキュメント
https://docs.github.com/ja/get-started/start-your-journey/creating-an-account-on-github


### githubへのREADME。mdの公開方法
2026/02/07/14:52
- git pushまでを行えば閲覧可能（gitの使い方参照）
- https://github.com/iwanomutsumi/mau-j2n で閲覧可能確認