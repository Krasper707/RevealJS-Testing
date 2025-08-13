---
marp: true
title: Product Documentation - MyApp
author: Karthik M
theme: default
paginate: true
---

<!-- _class: lead -->
<!-- _header: **MyApp Product Documentation** -->
<!-- _footer: "Contact: 24f2001293@ds.study.iitm.ac.in" -->

# **MyApp**  
## Product Documentation

> Streamlined. Maintainable. Future-proof.

---

<!-- _backgroundColor: #f5f5f5 -->

## 📜 Overview

- **Purpose:**  
  Provide maintainable, version-controlled documentation for *MyApp*.
- **Formats:**  
  HTML, PDF, PPTX, Images.
- **Tools:**  
  - Marp CLI  
  - VS Code Marp Extension  

---

<!-- _backgroundColor: #ffffff -->

## 📂 File Structure

```plaintext
docs/
├── slides.md         # This presentation
├── images/           # Assets & backgrounds
├── themes/           # Custom themes
└── package.json      # Build scripts

```
<!-- _backgroundColor: #fff -->
<!-- _header: **Custom Theme Example** -->

<style>
section {
  font-family: 'Segoe UI', sans-serif;
  background-color: #fafafa;
}
h1, h2, h3 {
  color: #0055aa;
}
blockquote {
  font-style: italic;
  color: #555;
}
</style>

## 🎨 Custom Theme Styling

> Consistent look & feel for branding.

---

<!-- Background image slide -->
![bg cover](images/bg-abstract.jpg)

# 📷 Background Image Example

---

## ⚙️ Build Commands

```bash
# Start live preview
npm run start

# Export to PDF
npm run pdf

# Export to PPTX
npm run pptx
```
!-- _header: **Algorithmic Complexity** -->
## 📊 Algorithmic Complexity Example

For a function with *n* inputs:

- Linear: $O(n)$  
- Quadratic: $O(n^2)$  
- Logarithmic: $O(\log n)$  

$$
T(n) = an^2 + bn + c \quad \Rightarrow \quad O(n^2)
$$

---

## ✅ Best Practices

1. Keep slides minimal  
2. Optimize images before including  
3. Include speaker notes when needed  
4. Use consistent branding  
5. Test in target output format  

---

# Thank You  
📧 **24f2001293@ds.study.iitm.ac.in**
