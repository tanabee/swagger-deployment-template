## About

swagger.yaml を push すると CircleCI 経由で Swagger サーバーを Google App Engine にデプロイするテンプレートです。

## Usage

1. このリポジトリを Fork する
2. Fork したリポジトリを CircleCI と連携する
3. CircleCI で以下の Environment Variables を設定する
    * GOOGLE_COMPUTE_ZONE: Google Cloud Zone
    * GOOGLE_PROJECT_ID: Google Cloud Project ID
    * GCLOUD_SERVICE_KEY: Google Cloud service account json
4. swagger.yaml を修正して push する
5. CircleCI を経由して Google App Engine にデプロイされる
