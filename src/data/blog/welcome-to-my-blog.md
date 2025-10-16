---
author: PG
pubDatetime: 2025-01-15T12:00:00Z
title: Welcome to My Blog
slug: welcome-to-my-blog
featured: true
draft: false
tags:
  - meta
  - introduction
description: The inaugural post for pg.gl - exploring what this blog will be about and showing off some of its capabilities.
---

Welcome to my new blog at pg.gl! This is where I'll be sharing my thoughts on technology, programming, and whatever else catches my attention.

## Table of contents

## What This Blog is About

I plan to use this space to document my learning journey, share interesting projects, and occasionally rant about things that matter to me in the tech world.

## Code Examples

One of the key features I wanted was excellent code highlighting. Let me show you what that looks like:

```python file="hello.py"
def fibonacci(n):
    """Generate the first n Fibonacci numbers."""
    a, b = 0, 1
    result = []

    for _ in range(n):
        result.append(a)
        a, b = b, a + b

    return result

# Example usage
print(fibonacci(10))  # [0, 1, 1, 2, 3, 5, 8, 13, 21, 34]
```

And here's some JavaScript with syntax highlighting:

```javascript file="app.js"
// A simple async function example
async function fetchUserData(userId) {
  try {
    const response = await fetch(`https://api.example.com/users/${userId}`);

    if (!response.ok) {
      throw new Error(`HTTP error! status: ${response.status}`);
    }

    const data = await response.json();
    return data;
  } catch (error) {
    console.error('Failed to fetch user data:', error);
    throw error;
  }
}

// Usage
fetchUserData(123).then(user => {
  console.log('User:', user);
});
```

## Images

The blog also supports beautiful image rendering. Here's an example of how images look:

![A beautiful sunset](https://images.pexels.com/photos/1181677/pexels-photo-1181677.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1)

<figcaption class="text-center">
  Photo by <a href="https://www.pexels.com/@simonmigaj">Simon Migaj</a> on Pexels
</figcaption>

## Embedding Videos

You can easily embed YouTube videos or other media. Here's how you'd embed a video:

<iframe width="560" height="315" src="https://www.youtube.com/embed/dQw4w9WgXcQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen style="max-width: 100%; margin: 2rem auto; display: block;"></iframe>

## Technical Features

This blog is built with:

- **Astro** - A modern static site generator optimized for speed
- **AstroPaper Theme** - A beautiful, minimalist theme with great typography
- **GitHub Pages** - Free, reliable hosting
- **GitHub Actions** - Automated deployments on every push

The whole setup is optimized for performance and SEO, with features like:

- Automatic image optimization
- Syntax highlighting for code blocks
- RSS feed generation
- Sitemap generation
- Dark/light mode support
- Mobile-responsive design

## What's Next?

I'm excited to start sharing content here. Some topics I'm planning to write about:

- Deep dives into Python libraries and frameworks
- Web performance optimization techniques
- Interesting algorithms and data structures
- Developer productivity tips
- Book reviews and learning resources

Stay tuned for more posts!
