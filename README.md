# website

サイト：https://dafumiya.sfc.keio.ac.jp/website/

領域：/pub/WWW/dafumiya/


技術的な話
github で管理しています。
大まかな更新方法としては、github の dafumiya-lab organization の website リポジトリに push して
CNS サーバーの共同領域にリモートログインして pull する形をとります。
git pull するときは git のアクセストークンの設定が必要で少々面倒だった記憶があります。調べたら解決法が出てくるので、根気強くやっていただければと思います、

リモートログインの方法
https://cns-guide.sfc.keio.ac.jp/2023/CNSguide2023.pdf
CNSサーバーのところを読んでください

# GitHubに関して
Githubに使うSoftware：GitHub Desktop
GitHubからクローンするとき
git clone https://github.com/dafumiya-lab/website.git

自分の端末でコードの修正完了して、GitHubにpushするとき

GitHub Desktopからcommit to main(ちゃんとコメントを書きましょう)　その次にpush origin
(ソフト使えたくないならそれでも大丈夫です)

リモートログインしたあと、領域：/pub/WWW/dafumiya/にアクセス、GitHubから修正後のバージョンをpullする　git pull origin main
   
# HTMLに関して
