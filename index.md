---
layout: default
title: Molley Docs
stylesheets:
  - /assets/site.css
head_inject:
  - '<meta name="theme-color" content="#000000">'
inline_scripts:
  - |
    console.log("Inline scripts run after the page content renders.");
scripts:
  - src: https://cdn.jsdelivr.net/npm/mermaid@11/dist/mermaid.min.js
    defer: true
  - inline: |
      document.addEventListener("DOMContentLoaded", () => {
        mermaid.initialize({ startOnLoad: true });
      });
body_end_inject:
  - '<div id="docs-root"></div>'
---

# Welcome

This repository is configured as a GitHub Pages site powered by Jekyll.  
Use the front matter above as a reference for injecting custom scripts, inline code, or HTML blocks into the generated output.
