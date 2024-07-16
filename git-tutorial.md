#gitの機能

　githubは、リモートレポジトリのホスティングサービスの一つで、オープンソースソフトウェアの主要なポータルサイトである。

　mainのほかに新しいbranchを作成することで、mainにコミットする前に実験や編集ををすることができる。

　他ユーザーのリモートレポジトリはtemplateでいくつでもforkできる。
また、issuesでレポジトリに関する問題・課題・バグ・機能追加・質問などがあげられる。
projectsでissuesなどの管理ができる。

#コマンド

gh codespace create -r OWNER/REPO_NAME [-b BRANCH]
    新しいcodespaceを作成

gh codespace delete -c CODESPACE-NAME
    codespaceを削除する

git init
    新しいGitリポジトリを初期化する

git clone
    既存のリポジトリを複製する

git status
    現在のリポジトリの状態を表示する

git add
    ファイルをステージングエリアに追加する

git commit
    ステージングエリアにある変更をコミットする
    