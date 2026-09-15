# 📚 Novels, Manga & Reading — Open-Source Collection

> A curated collection of **open-source readers, manga/novel servers, source/extension ecosystems, downloaders, ebook tools, and translation projects**.
>
> **Curation goal:** quality over quantity — prefer projects that are useful, maintained, technically interesting, or historically important.

---

## 🧭 Categories

- [📖 Novel & Web-Novel Readers](#-novel--web-novel-readers)
- [🗯️ Manga / Manhwa / Comic Readers](#️-manga--manhwa--comic-readers)
- [🔌 Extensions & Source Ecosystems](#-extensions--source-ecosystems)
- [🖥️ Self-Hosted Reading Servers](#️-self-hosted-reading-servers)
- [📚 Ebook Readers & Libraries](#-ebook-readers--libraries)
- [⬇️ Downloaders & Offline Archives](#️-downloaders--offline-archives)
- [🌐 Translation, OCR & Bilingual Tools](#-translation-ocr--bilingual-tools)
- [⭐ Quick Picks](#-quick-picks)
- [🏗️ Ecosystem Map](#️-ecosystem-map)
- [📌 Curation Rules](#-curation-rules)

---

## 📖 Novel & Web-Novel Readers

| Project | Platform | Description |
|---|---|---|
| [LNReader](https://github.com/lnreader/lnreader) | Android | Open-source light/web-novel reader with a plugin-based source system. |
| [IReader](https://github.com/IReaderorg/IReader) | Android / Desktop | Open-source reader for novels, light novels, web novels and ebooks; supports LNReader and Legado sources. |
| [Legado](https://github.com/gedoor/legado) | Android | Highly configurable novel reader with custom book-source/rule support. |
| [LightNovelReader](https://github.com/dmzz-yyhyy/LightNovelReader) | Android | Light-novel reading application. |
| [NovelDokusha](https://github.com/nanihadesuka/NovelDokusha) | Android | Novel-reading application for online sources. |

---

## 🗯️ Manga / Manhwa / Comic Readers

| Project | Platform | Description |
|---|---|---|
| [Mihon](https://github.com/mihonapp/mihon) | Android | Open-source manga reader and major continuation of the Tachiyomi ecosystem. |
| [TachiyomiSY](https://github.com/jobobby04/TachiyomiSY) | Android | Feature-rich Tachiyomi-derived manga reader. |
| [Neko](https://github.com/nekomangaorg/Neko) | Android | Manga reader focused on MangaDex. |

---

## 🔌 Extensions & Source Ecosystems

| Project | Ecosystem | Description |
|---|---|---|
| [Keiyoushi Extensions](https://github.com/keiyoushi/extensions) | Manga | Community-maintained extensions for compatible manga readers. |
| [LNReader Plugins](https://github.com/lnreader/lnreader-plugins) | Novels | Plugin ecosystem/issues for LNReader. |
| [Light-Novel-Yuedu-Source](https://github.com/ZWolken/Light-Novel-Yuedu-Source) | Novels | Source/rule project for the YueDu ecosystem. |

> **Why this category matters:** readers are only part of the ecosystem. Source/extension repositories often provide the bridge between a reader and the content sources it can index.

---

## 🖥️ Self-Hosted Reading Servers

For readers who want a **personal library accessible from multiple devices**.

| Project | Best for | Highlights |
|---|---|---|
| [Komga](https://github.com/gotson/komga) | Manga / comics / ebooks | Web reader, metadata, collections, REST API, OPDS, Kobo Sync and KOReader Sync. |
| [Kavita](https://github.com/Kareadita/Kavita) | Manga / comics / books | Cross-platform server with web readers, metadata, collections and user management. |
| [Suwayomi Server](https://github.com/Suwayomi/Suwayomi-Server) | Manga | Server-based manga reading ecosystem with extensions and a web UI. |
| [BookLore](https://github.com/booklore-app/booklore) | Books / comics | Self-hosted multi-user library with metadata, smart shelves, OPDS and a built-in reader. |
| [Calibre-Web](https://github.com/janeczku/calibre-web) | Ebooks | Web interface for browsing, reading and downloading ebooks stored in a Calibre database. |

---

## 📚 Ebook Readers & Libraries

Useful when your novel collection is primarily **EPUB/PDF/CBZ/etc.** rather than an online source.

| Project | Platform | Description |
|---|---|---|
| [Readest](https://github.com/readest/readest) | Windows / macOS / Linux / Android / iOS / Web | Modern open-source ebook reader supporting formats including EPUB, PDF, MOBI, FB2, CBZ and TXT. |
| [Foliate](https://github.com/johnfactotum/foliate) | Linux | GTK ebook reader supporting common ebook formats and OPDS libraries. |
| [Calibre-Web](https://github.com/janeczku/calibre-web) | Self-hosted | Browser-based ebook library and reader built around a Calibre database. |

---

## ⬇️ Downloaders & Offline Archives

| Project | Purpose |
|---|---|
| [Lightnovel Crawler](https://github.com/lncrawl/lightnovel-crawler) | Download supported web novels and create offline ebooks such as EPUB. |
| [Free Manga Downloader](https://github.com/riderkick/FMD) | Manga downloading utility. |
| [HakuNeko](https://github.com/manga-download/hakuneko) | Desktop downloader/reader for manga and other online media sources. |

> **Copyright / legal note:** downloading tools should only be used where you have the right to access, download, archive, or otherwise use the material. Respect copyright, publisher/author rights, and each site's terms.

---

## 🌐 Translation, OCR & Bilingual Tools

| Project | Purpose |
|---|---|
| [Manga Image Translator](https://github.com/zyddnys/manga-image-translator) | Automated manga-image translation and text replacement workflows. |
| [Bilingual Book Maker](https://github.com/yihong0618/bilingual_book_maker) | Creates bilingual ebooks using translation workflows. |

---

## ⭐ Quick Picks

| If you want... | Start with... |
|---|---|
| ⭐ Android light/web novels | **LNReader** |
| ⭐ Android novel + ebook flexibility | **IReader** |
| ⭐ Highly configurable novel sources | **Legado** |
| ⭐ Android manga | **Mihon** |
| ⭐ MangaDex-focused reading | **Neko** |
| ⭐ Self-hosted manga/comics | **Komga** |
| ⭐ Self-hosted manga + ebooks | **Kavita** |
| ⭐ Self-hosted book/comic library | **BookLore** |
| ⭐ Cross-platform ebook reading | **Readest** |
| ⭐ Web-novel offline archiving | **Lightnovel Crawler** |
| ⭐ Manga translation | **Manga Image Translator** |

---

## 🏗️ Ecosystem Map

```text
                         READING ECOSYSTEM
                                │
          ┌─────────────────────┼─────────────────────┐
          │                     │                     │
       READERS               SERVERS                TOOLS
          │                     │                     │
   ┌──────┴──────┐       ┌──────┴──────┐       ┌─────┴──────┐
   │             │       │             │       │            │
 NOVELS        MANGA   LIBRARIES     WEB UI  DOWNLOAD    TRANSLATE
   │             │       │             │       │            │
LNReader       Mihon   Komga         Kavita  LNCrawl       MIT
IReader        Neko    BookLore      Calibre  FMD          BBM
Legado         TachiyomiSY          Web       HakuNeko
   │             │
   └──────┬──────┘
          │
     SOURCES / EXTENSIONS
          │
   ┌──────┴─────────┐
   │                │
Keiyoushi      LNReader Plugins
Extensions
```

---

## 🔎 Related GitHub Topics

- [Light Novels](https://github.com/topics/light-novels)
- [Ebook Readers](https://github.com/topics/ebook-reader)

---

## 📌 Curation Rules

A repository should ideally satisfy several of these:

- Open source or source-available with a clear license.
- Useful to readers, archivists, developers or self-hosters.
- Maintained **or** historically significant.
- Has a clear README/documentation.
- Offers meaningful functionality rather than being a trivial duplicate.
- Copyright/legal considerations are clear when downloading is involved.

### Suggested status tags

- 🟢 **Active** — regular development/releases.
- 🟡 **Slow** — infrequent development but still useful.
- 🔵 **Stable** — mature and relatively complete.
- 🟠 **Fork** — derivative project with meaningful additional functionality.
- 🔴 **Archived** — no longer maintained; retain only when historically useful.

---

## 🤝 Contributing

Found a project worth adding?

Please provide:

1. Repository link
2. One-line description
3. Primary platform
4. Category
5. What makes it useful or different
6. Maintenance status

**Don't optimize this list for star count. Optimize it for usefulness.**
