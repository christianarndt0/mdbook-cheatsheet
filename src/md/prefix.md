# Markdown Cheatsheet

This is an _unnumbered prefix chapter_ for a brief Markdown cheatsheet, built with mdBook.

Defined in `SUMMARY.md` as:

```markdown
[Markdown Cheatsheet](./md/prefix.md)
```

The following chapters (on desktop, see left) are defined as:

```markdown
- [CHAPTER X](./PATH/TO/*.md)
  - [CHAPTER X.1](./PATH/TO/*.md)
```

## General mdBook Structure

```bash
.
├── book
│   ├── ...
│   ├── webpage stuff
│   └── ...
├── book.toml
└── src
    ├── ...
    ├── *.md and images (can be nested)
    ├── ...
    └── SUMMARY.md
```

## Official mdBook Documentation

<https://rust-lang.github.io/mdBook/index.html>
