# adoc_deploy_test


/                   # プロジェクトのルートディレクトリ
├── .github/        # GitHub Actions などの設定を保存するディレクトリ
│   └── workflows/  # ワークフロー設定を入れる
│       └── deploy.yml  # デプロイ用のGitHub Actionsファイル
├── src/            # 執筆用のディレクトリ (writing ブランチで作業)
│   ├── index.adoc  # トップページのAsciiDocファイル
│   ├── posts/      # 個別記事を格納するディレクトリ
│   │   └── post1.adoc  # 記事1のAsciiDocファイル
│   └── assets/     # 画像などの静的ファイルを保存
│       └── image.png
├── .gitignore      # Git にコミットしないファイルを指定
└── README.md   