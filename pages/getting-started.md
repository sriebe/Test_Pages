# Getting Started

This guide explains how to add new pages and link them together.

## Creating a New Page

1. Create a new `.md` file inside the `pages/` folder (or a sub-folder for a topic area).
2. Give it a clear, descriptive filename using lowercase letters and hyphens, e.g. `my-new-page.md`.
3. Start the file with a top-level heading that matches the page's subject.

```markdown
# My New Page

Content goes here.
```

## Linking to Another Page

Use a standard markdown relative link from the current file's location:

```markdown
[Page Title](other-page.md)
```

For pages in a sub-folder, adjust the path accordingly:

```markdown
<!-- From pages/ to pages/subtopic/detail.md -->
[Detail](subtopic/detail.md)

<!-- From pages/subtopic/detail.md back to pages/about.md -->
[About](../about.md)

<!-- Back to the home page from any page inside pages/ -->
[Home](../README.md)
```

## Obsidian Compatibility

If you open this repository as an Obsidian vault, the standard `[text](file.md)` links will resolve correctly. You can also use Obsidian's `[[wiki-link]]` syntax while editing locally — just be aware that bare `[[links]]` are not rendered by GitHub's web interface.

## Recommended Structure

```
README.md          ← home / index
pages/
  about.md
  getting-started.md
  topics.md
  <topic>/
    page-a.md
    page-b.md
```

## See Also

- [Home](../README.md)
- [About](about.md)
- [Topics](topics.md)
