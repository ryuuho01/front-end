# Name
お店予約アプリケーションのフロントエンドの環境を構築する。
  
# Installation
以下、gitをインストールしてあることを前提に進めます。  
すでにインストールされている場合は飛ばす場所を  
(*)で示しました。
  
【フロントエンド環境構築】  
コマンドプロンプト、もしくはターミナルを起動  
デスクトップへ移動  
cd desktop  
  
GitHubからクローンし、フォルダに移動  
git clone https://github.com/ryuuho01/front-end.git  
cd front-end  
  
(*)Node.jsをインストールされていない方  
nvm install v14.18.1  
  
(*)Node.jsのバージョンがv14.18.1でない方  
nvm use v9.3.0  
  
(*)Vue CLIをインストール  
npm install -g @vue/cli  
  
(*)yarnをインストール  
npm install -g yarn  
  
yarnのライブラリをインストール  
yarn install  
  
vee-validateをインストール  
yarn add vee-validate@3  
  
auth-nextをインストール  
yarn add @nuxtjs/auth-next  
  
proxyをインストール  
yarn add @nuxtjs/proxy  
  
dotenvをインストール  
yarn add @nuxtjs/dotenv  
  
cross-envをインストール  
yarn add cross-env  
  
sassをインストール  
yarn add --dev sass-loader@10  
  
.envを作成し、  
touch .env  
vi .env  
環境変数を設定。以下の環境変数を追加  
BASE_URL=http://localhost:3000  
  
最後に起動  
yarn dev  
  
ブラウザにアクセス  (別途バックエンドの起動も必要)  
http://localhost:3000  
  