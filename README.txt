AI相棒 PWA 試作品

内容:
- 日本語チャットUI
- 音声入力（ブラウザ対応時）
- 音声読み上げ
- ローカル会話履歴
- OpenAI互換Chat Completions API接続

重要:
このZIP自体はAIモデルを含みません。AIを利用するには、Ollama等のOpenAI互換API、またはAPIキーを持つサービスが必要です。完全無料で使うならPCにOllamaを入れ、PCとスマホを同じWi-Fiに接続して使う構成を推奨します。

スマホにインストールする手順:
1. ZIPをPCで展開
2. HTTPS対応の静的ホスティングへファイルをアップロード（GitHub Pages等）
3. AndroidのChromeで公開URLを開く
4. Chromeメニュー > ホーム画面に追加 / アプリをインストール

ローカルテスト:
HTTPSまたはlocalhostで配信してください。index.htmlを直接開くとPWA機能や音声認識が制限される場合があります。

Ollama接続例:
- OllamaをPCに導入し、使用するモデルをダウンロード
- LANからアクセスできるようOllamaを設定
- 接続先に http://PCのLAN IP:11434/v1/chat/completions を指定
- モデル名にインストール済みモデル名を指定
- ブラウザからのCORSアクセスを許可
環境によって必要な設定が異なります。APIキーを公開URLや共有端末に保存しないでください。
