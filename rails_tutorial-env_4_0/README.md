# rails_tutorial-env_4_0 cookbook


「Railsチュートリアル 4.0版」を写経するために、vagrant up で使える環境を作りました(ただし、Berkshelf v2系向け)。  
なお、実際に使うには、手元の環境に合わせてBox名などを変更する必要があります。

vagrant up したときの環境は以下の通りです。

* Ubuntu 12.04.3
* rbenv + Ruby 2.0.0
* gem
 * Rails 4.0.2
* Sublime Text をインストール (Githubにあったcookbookを利用)
* Node.js をインストール (Ubuntuのパッケージ)
* SQLite Database Browser (Ubuntuのパッケージ)
* Terminalでgitのbranchが見えるように、.bashrcを編集
* bundle時の`--no-ri --no-rdoc'を、.gemrcに追記
　  
　  

Berkshelfでの作り方などは以下のBlogにまとめてあります。  
[The RSpec Book用にVagrant環境を作成し、写経してみた](http://d.hatena.ne.jp/thinkAmi/20140110/1389305987)