# html1

Natootokiのgit練習です。

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