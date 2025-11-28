# Takashi Abeホームページ

GitHub Pagesを使用したiPhoneTakashi Abeのホームページです。

## 構成

- **index.html**: 開発者ホームページ（メインページ）
- **app-ads.txt**: Googleのapp-ads.txtファイル（既に設定済み）
- **app1/**: サンプルアプリページ
  - `index.html`: アプリの説明
  - `privacy.html`: プライバシーポリシー
  - `terms.html`: 利用規約
  - `qa.html`: よくある質問
  - `support.html`: サポート

## カスタマイズ方法

### 1. 開発者ホームページの編集

`index.html`を編集して、以下を変更してください：

- ヘッダーのタイトルとサブタイトル
- アプリカードの内容（アプリ名、説明、リンク）
- フッターの著作権表示

### 2. 新しいアプリページの追加

1. `app1`フォルダをコピーして、新しいフォルダ名（例：`app2`）にリネーム
2. 各HTMLファイル内の「アプリ名1」を実際のアプリ名に変更
3. 各ページの内容を実際のアプリ情報に合わせて編集
4. `index.html`に新しいアプリカードを追加

### 3. アプリページの編集

各アプリフォルダ内のファイルを編集：

- **index.html**: アプリの説明、機能、使い方など
- **privacy.html**: プライバシーポリシー（必要に応じて法律家に確認）
- **terms.html**: 利用規約（必要に応じて法律家に確認）
- **qa.html**: よくある質問と回答
- **support.html**: サポート連絡先（メールアドレスを実際のものに変更）

### 4. スタイルのカスタマイズ

`styles.css`を編集して、デザインをカスタマイズできます：

- カラースキーム（グラデーションの色）
- フォントサイズ
- レイアウト

## GitHub Pagesでの公開方法

1. このリポジトリをGitHubにプッシュ
2. GitHubリポジトリの「Settings」→「Pages」に移動
3. 「Source」で「Deploy from a branch」を選択
4. 「Branch」で「main」（または「master」）を選択
5. 「/ (root)」を選択して「Save」をクリック
6. 数分後に、`https://[ユーザー名].github.io/[リポジトリ名]/`でアクセス可能になります

## 注意事項

- `app-ads.txt`はルートディレクトリに配置されているため、GitHub Pagesで公開されると`https://[ユーザー名].github.io/[リポジトリ名]/app-ads.txt`でアクセス可能になります
- プライバシーポリシーと利用規約は、実際のアプリの内容に合わせて適切に編集してください
- サポートページのメールアドレスは、実際の連絡先に変更してください

## ファイル構造

```
AppHomePage/
├── index.html          # 開発者ホームページ
├── styles.css          # スタイルシート
├── app-ads.txt         # Google app-ads.txt
├── app1/               # アプリ1のページ
│   ├── index.html
│   ├── privacy.html
│   ├── terms.html
│   ├── qa.html
│   └── support.html
└── README.md           # このファイル
```

## ライセンス

このプロジェクトは、開発者の用途に合わせて自由にカスタマイズしてご利用ください。

