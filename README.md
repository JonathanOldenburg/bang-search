# 🔎 Bang Search Redirector

I started watching this video [i made my own search engine (kind of)](https://www.youtube.com/watch?v=_DnNzRaBWUU&t=737s), where he builds a similar webpage to use in any browser. Then I challenge myself to build the same concept using github pages.

## How to Use

### Add as Custom Search Engine

1. Go to your browser's **Search Engine Settings**.
2. Add a new search engine:
   - **Name:** Bang Search
   - **Keyword:** `!` (or any you like)
   - **URL:**
     ```
     https://bang-search.jonathanoldenburg.github.io?q=%s
     ```

---

### How to Search

Just use your query followed by a **bang code** (a `!` plus a letter).
Example:

```
how to train a falcon !g
```

This redirects you to Google with the search `"how to train a falcon"`.

---

## Supported Bang Codes

| Code | Engine        |
|------|---------------|
| `!g` | Google        |
| `!b` | Bing          |
| `!d` | DuckDuckGo    |
| `!y` | Yahoo         |
| `!s` | Startpage     |
| `!q` | Qwant         |
| `!e` | Ecosia        |
| `!a` | AOL           |
| `!w` | Wikipedia     |
| `!r` | Reddit        |
| `!h` | DuckDuckGo (HTML) |
| `!m` | MetaGer       |
| `!n` | Neeva         |
| `!z` | ZoomInfo      |
| `!l` | LinkedIn      |
| `!f` | Facebook      |
| `!i` | Instagram     |
| `!t` | Twitter / X   |
| `!p` | Pinterest     |
| `!u` | YouTube       |
| `!c` | China Daily   |
| `!j` | JSTOR         |
| `!k` | Kagi          |
| `!o` | Openverse     |

> Example: `quantum entanglement !j` → Searches JSTOR for academic papers on quantum entanglement.

## Isn't there better options(built in funcionallity or browser extensions)?

Yes! but this project was just meant to have fun and a little challenge
