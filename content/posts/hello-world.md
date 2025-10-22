---
title: "Hello World"
date: 2025-10-22
draft: false
categories: ["随笔"]
tags: ["Hugo", "Vercel", "PaperMod"]
---
第一篇文章！这是一篇用 Hugo + PaperMod + Vercel 部署的示例。

```go
// 示例代码块（启用行号与语法猜测）
package main
import "fmt"
func main() { fmt.Println("hello world") }


---

# 4) 自定义页脚（可选）

## `layouts/partials/footer.html`
```html
{{/* 仅在需要“备案/版权/自定义链接”时添加此文件；否则可删除整个 layouts 目录 */}}
<footer class="footer">
  <div class="container" style="text-align:center; opacity:0.75; font-size:0.9rem;">
    <span>© {{ now.Year }} {{ .Site.Params.author }} · 由 Hugo & PaperMod 驱动 · 部署于 Vercel</span>
  </div>
</footer>