# html1

Natootokiのgit練習です。

sshの設定をしました。

pubファイルの内容はcmdで

type ファイル名

を実行することで確認できました。

.sshの中にconfigというファイルを作ることで

コマンドライン上でgitHubを動かせるようになりました。

git push origin mainができず、

error: src refspec manin does not match any

が表示され、

git push origin HEAD:<GitHub上のpush先のbranch名>

をすると解決しました。

git push origin master:main

でも同様にpushすることができました。

ローカルのブランチ名をmasterからmainに変更しました。

git push origin main

でpushすることができるようになりました。