# 目次

- [使用技術](#technology-used)
- [環境構築](#build-environment)
- [実行方法](#how-to-run)
- [Git](#git)
- [ディレクトリ構成](#directory-configuration)

<h2 id="technology-used">使用技術</h2>

<!-- 言語、フレームワーク、ミドルウェア、インフラの一覧とバージョンを記載 -->

| 言語・フレームワーク | バージョン |
| -------------------- | ---------- |
| Python               | 3.11.4     |
| React                | 18.2.0     |

<!-- シールド一覧 -->
<p style="display: inline">
  <!-- フロントエンドの言語一覧 -->
  <!-- フロントエンドのフレームワーク一覧 -->
  <img src="https://img.shields.io/badge/-React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB">
  <!-- バックエンドのフレームワーク一覧 -->
  <!-- バックエンドの言語一覧 -->
  <img src="https://img.shields.io/badge/-Python-F2C63C.svg?logo=python&style=for-the-badge">
  <!-- ミドルウェア一覧 -->
  <!-- インフラ一覧 -->
</p>

<h2 id="build-environment">環境構築</h2>

### Frontend

```
npm ci
```

### Backend

```
pip3 install -r requirements.txt
```

<h2 id="how-to-run">実行方法</h2>

### Frontend

#### run local server

```
npm run dev
```

### Backend

#### run local server

```
python3 main.py

```

#### migration

```
alembic upgrade head
```

<h2 id="git">Git</h2>

### ブランチの分け方

| ブランチ名                           | 役割                       |
| ------------------------------------ | -------------------------- |
| master                               | 公開するものを置くブランチ |
| feature/{issue 番号}\_{issue の概要} | 新機能開発中に使うブランチ |

<h2 id="directory-configuration">ディレクトリ構成</h2>

```
root/
  |-- README.md
  |-- docs
  `-- src
      |-- backend
      |   |-- alembic.ini
      |   |-- migration
      |   |-- requirement.txt
      |   `-- schemas
      `-- frontend
```
