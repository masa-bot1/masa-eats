# Node.jsの公式イメージを使用
FROM node:18

# 作業ディレクトリを指定
WORKDIR /app

# package.jsonとpackage-lock.jsonをコピー
COPY package*.json ./

# 依存関係をインストール
RUN npm install

# ソースコードをコピー
COPY . .

# デフォルトコマンドを設定
CMD ["npm", "run", "serve"]
