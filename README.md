# FastHTML ボイラープレート

[FastHTML](https://fastht.ml/) プロジェクトをゼロコンフィギュレーションでVercelにデプロイします。

[![Vercelでデプロイ](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/vercel/examples/tree/main/framework-boilerplates/fasthtml&template=fasthtml)

_ライブ例: https://fasthtml-template.vercel.app_

詳細は [FastHTML ドキュメント](https://docs.fastht.ml/) をご覧ください。

## はじめに

必要な依存関係をインストールします:

```bash
pip install -r requirements.txt
```

## ローカルでの実行

http://0.0.0.0:5001 で開発サーバーを起動します

```bash
python main.py
```

プロジェクトに変更を加えると、サーバーは自動的にリロードされます。

## Vercelへのデプロイ

以下のコマンドでプロジェクトをVercelにデプロイします:

```bash
npm install -g vercel
vercel --prod
```

または、[gitインテグレーション](https://vercel.com/docs/deployments/git)を使用してリポジトリに `git push` します。

このテンプレートのソースコードを表示するには、[例のリポジトリ](https://github.com/vercel/vercel/tree/main/examples/fasthtml)をご覧ください。


```markdown
GitHub Copilotによる翻訳です。
```