# CLAUDE.md
必ず日本語で回答してください。
This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Status

フィッシングサイト教育デモンストレーション用のNext.jsアプリケーション。授業での教育目的でセキュリティ意識向上を目指す。

## Development Commands

プロジェクトディレクトリ: `/Users/kurosuhirotoshi/dev/claudecode/sample/phishing-education-demo`

- Development server: `npm run dev`
- Build: `npm run build`
- Lint: `npm run lint`
- Type check: `npx tsc --noEmit`

## Architecture Overview

- Next.js App Router構成
- TypeScript + Tailwind CSS
- 主要ページ:
  - `/` - メイン画面
  - `/phishing` - フィッシング体験画面
  - `/education` - 教育コンテンツ画面
  - `/admin` - 管理画面

## Important Notes

- 教育目的のみで使用
- 実際の認証情報は収集しない
- ローカル環境での使用を前提