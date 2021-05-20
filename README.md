# netlify_form
## 参考サイト

[NetlifyとGithubを連携させ、サイトのアップロード作業を自動化する方法](https://rightcode.co.jp/blog/information-technology/netlify-github-up)

[【Netlify】Forms機能を利用して問い合わせフォームを作成する](https://qiita.com/NaokiIshimura/items/bce2f0b865ec1bc16a53)

## 手順

1. GitHubリポジトリを作成します

2. NetlifyとGitHubを連携します

3. リポジトリを選択します

4. デプロイするブランチ、ビルドコマンド、公開するディレクトリなどを設定します

5. Deploy siteします

6. URLが払い出されるので、Site settings → General からサイト名を変更します

7. Site settings → Forms から通知方法（メール、 slack）を設定します

8. netlify formsを利用するフォームにnetlify属性を追加します  
この時、`/`から始まるパスをaction属性を設定すると成功画面を設定できます。

9. デプロイするブランチにプッシュします

10. netlify forms機能へのWelcomeメールが届きます

## デモ

[nycreation-form.netlify.app](https://nycreation-form.netlify.app/)

[![Netlify Status](https://api.netlify.com/api/v1/badges/c03a9622-d554-46ce-9080-2370a444dae4/deploy-status)](https://app.netlify.com/sites/nycreation-form/deploys)
