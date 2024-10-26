<%* let bookTitle = await tp.system.prompt("Book Title?"); %>
<%* let authorName = await tp.system.prompt("Author Name?"); %>

# <% bookTitle %> by <% authorName %>
---
title: <% bookTitle %>
reviewer: MK
book:
    author:
        primary: <% authorName %>
        additional: 
        contributors:
    title: <% bookTitle %>
    year: 
reading-pace: ["fast", "medium", "slow"]
rating: 0.0-5.0
categories:
    - Book Reviews
    - [Science & Technology/Psychology & Philosophy/Leadership & Management]
tags:
    - [relevant-topics]

 date: <% tp.date.now("YYYY-MM-DD") %>
 lastmod: <% tp.date.now("YYYY-MM-DD") %> 
draft: true
---

## Summary

### Critical Analysis
## Review

### Key Insights

## Notable Quotes

## Recommendations