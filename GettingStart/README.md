#Rozetta's Git：Getting Start
##GitHubのアカウント準備
1. GitHubのアカウント登録するため、GitHubの[トップページ](https://github.com/)にアクセスします。
<!--img src="https://github.com/rozetta/RozettAnnounce/blob/master/assets/github-01-620x652.png" class="img-responsive" -->
2. 「Free」を選んでから「Finish sign up」ボタンをクリックします。
<img src="https://github.com/rozetta/rozettaannounce/blob/master/assets/github-02-02-620x521.png" class="img-responsive" />
3. ここまでGitHubのアカウント登録は完了。
4. Two-factor authenticationを設定する (Google Authenticatorがお勧めです。)
<img src="https://github.com/rozetta/rozettaannounce/blob/master/assets/github-authen.png" class="img-responsive" >
5. Personal Access Tokenを作成します。（すべての権限を入れてください。）※今後Passworの代わりにPersonalAccessTokenを利用するため、個人のローカル環境に保存してください。
6. Accountを送ります。 ※そのあとにユーザーをRozettaTeamに追加します。

参考：[今さら聞けない！GitHubの使い方【超初心者向け】](https://techacademy.jp/magazine/6235)

##Gitツールの準備
###SourceTree (任意)
1. SourceTreeの[トップページ](https://ja.atlassian.com/software/sourcetree)にアクセスし、プログラムダウンロードします。
2. SourceTreeのアカウント設定をする必要があります。
<img src="https://github.com/rozetta/rozettaannounce/blob/master/assets/7d585eec-cda2-762b-febe-499f2121f74e.png" class="img-responsive" />
3. Githubのアカウントを追加します。（Githubの場合はプロトコルはHTTPSです。）※GithubのUser,Password画面が表示したら、Passwordの箇所に「PersonalAccessToken」を記入します。
4. リポジトリからクローンします。
<img src="https://github.com/rozetta/RozettaAnnounce/blob/master/assets/sourcetree-clone-repo.png" class="img-responsive" />

参考:
[はじめてのSourceTree(使い方編)](http://qiita.com/naoki85/items/c7660d70347e9e70b201),
[Source Treeの使い方](http://qiita.com/takamichi_tsutsumi/items/6358a74a62d4fc15d1a5)

###Gitのコマンドライン (Windows) (任意)
1. Git for Windowsをインストールする。 [Git for Windows](https://git-for-windows.github.io/)
2. Git for Windows起動します。<br/>
<img src="https://github.com/rozetta/rozettaannounce/blob/master/assets/git-for-window.png" class="img-responsive" />
3. Gitのフォルダーを準備します。<br/>
`$ mkdir c:\GitRepo`<br/>
`$ cd c:\GitRepo`
4. GitのRepositoryをCloneします。<br/>
`git clone <リポジトリフォルダへのhttpパス>`

参考：
[Gitの基本的な使い方メモ](http://qiita.com/opengl-8080/items/451c5967cbbc262f4f0d)

##Gitのルール
###CATチーム
1. Branch作成については、Mantisの番号として作成します。「issue/MantisXXXXXX」など
<!--img src="https://github.com/rozetta/githubtraining/blob/master/assets/github-authen.png" class="img-responsive" -->
2. MasterブランチにPullRequestにて、Reviewが必要なので、Reviewerを設定してください。
<!--img src="https://github.com/rozetta/githubtraining/blob/master/assets/github-authen.png" class="img-responsive" -->
3. ReviewerがMergeした後に、Branchを必ず削除します。
