# 朝活ブログ部サイト 実装フォルダ

この `site` フォルダは、朝活ブログ部サイトの本番実装です。

作業仕様は親フォルダの `AGENTS.md` / `CLAUDE.md` を正とします。

```text
/Users/shin/Documents/00_Obsidian/02_開発/094_朝活ブログ部サイト/AGENTS.md
/Users/shin/Documents/00_Obsidian/02_開発/094_朝活ブログ部サイト/CLAUDE.md
```

記事追加は `site/articles/*.md` にMarkdownを置き、親フォルダで `python3 build.py` を実行してHTMLを再生成します。

本番URL:

```text
https://asakatsu-blog-notes.vercel.app/
```
