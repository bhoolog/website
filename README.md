# Bhoologam

A bilingual science blog exploring the wonders of our world in English and Malayalam.

## 🚀 Live Site
Visit: [https://your-username.github.io/bhoologam](https://your-username.github.io/bhoologam)

## 📝 Writing a New Blog Post

1. Create a new `.md` file in the `posts/` folder
2. Use this naming convention: `YYYY-MM-DD-post-title.md`
3. Add frontmatter at the top:
```yaml
---
title: Your Post Title
author: Author Name
date: 2025-11-25
excerpt: Brief description of the post
category: Category Name
image: URL or path to thumbnail image
---
```

4. Write your content in Markdown
5. Commit and push to GitHub

## 📁 Folder Structure

- `posts/` - All blog post markdown files
- `assets/images/posts/` - Post-specific images
- `assets/images/thumbnails/` - Thumbnail images
- `assets/videos/` - Video files
- `assets/animations/` - Animated content

## 🎨 Supported Markdown

- Headers: `#`, `##`, `###`
- **Bold**, *Italic*
- Lists (ordered and unordered)
- Links: `[text](url)`
- Images: `![alt](url)`
- Code blocks with syntax highlighting
- Blockquotes
- Tables

## 📸 Adding Images

### Local Images
```markdown
![Alt text](../assets/images/posts/your-post/image.jpg)
```

### External Images
```markdown
![Alt text](https://example.com/image.jpg)
```

## 🎥 Adding Videos

### Local Videos
```html
<video controls width="100%">
  <source src="../assets/videos/your-video.mp4" type="video/mp4">
</video>
```

### YouTube Embed
```html
<iframe width="100%" height="400" src="https://www.youtube.com/embed/VIDEO_ID" frameborder="0" allowfullscreen></iframe>
```

## 🔧 Setup

1. Fork this repository
2. Update `index.html` with your GitHub username and repo name
3. Enable GitHub Pages in repository settings
4. Add your posts to the `posts/` folder
5. Push changes and your blog will update automatically!

## 📄 License

MIT License - Feel free to use and modify
