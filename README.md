# MCP Weather Tool サンプル

このリポジトリは[Model Context Protocol](https://modelcontextprotocol.io/)を利用した天気情報ツールのサンプル実装です。

## クイックスタート

このプロジェクトは[Model Context Protocol Quickstart](https://modelcontextprotocol.io/quickstart/server)に基づいて実装されています。

### インストール

```bash
npm install
```

### ビルド

```bash
npm run build
```

### 使用方法

このツールは大規模言語モデル（LLM）と連携して天気情報を提供します。以下の機能が含まれています：

- 特定の州の気象警報を取得
- 指定された座標の天気予報を取得

## 技術仕様

- TypeScript/Node.js
- MCP SDK (`@modelcontextprotocol/sdk`)
- 天気データは[National Weather Service API](https://api.weather.gov/)から取得

## トラブルシューティング

実行時に`spawn node ENOENT`エラーが発生する場合は、以下を確認してください：

- Node.js が正しくインストールされているか
- シバン行(`#!/usr/bin/env node`)が正しく設定されているか
- 実行ファイルに適切な権限が付与されているか

詳細なデバッグ情報は[MCP のデバッグドキュメント](https://modelcontextprotocol.io/docs/tools/debugging)を参照してください。
