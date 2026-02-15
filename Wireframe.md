# Wireframe: YASUSHI Thumbnail Portfolio

This document outlines the visual structure of the website using text.
Use this as a map when writing HTML.

## 📱 Mobile Layout (Smartphone)
>
> **Concept**: One column, vertical scroll. Big impact images.

```text
+---------------------------------------+
| [HEADER]                              |
| ≡ (Menu Icon)    YASUSHI Portfolio    |
+---------------------------------------+
| [HERO SECTION]                        |
|                                       |
|    (Background: Dark Collage)         |
|                                       |
|       一瞬で奪う、視線。              |
|    (Capturing eyes in an instant)     |
|                                       |
|          [ View Works ↓ ]             |
|                                       |
+---------------------------------------+
| [GALLERY SECTION] (Grid)              |
|                                       |
|  [Thumbnail 1 (Full Width)]           |
|  -----------------------------------  |
|  [Thumbnail 2 (Full Width)]           |
|  -----------------------------------  |
|  [Thumbnail 3 (Full Width)]           |
|                                       |
|  ... (Scroll for more)                |
+---------------------------------------+
| [ABOUT SECTION]                       |
|                                       |
|  [Profile Photo]                      |
|                                       |
|  **YASUSHI**                          |
|  Reboot 60 / Content Creator          |
|                                       |
|  人生の経験値が、表現の深みになる。   |
|  (Short Bio text...)                  |
+---------------------------------------+
| [CONTACT SECTION]                     |
|                                       |
|  ご依頼・ご相談はこちら               |
|                                       |
|  [ X (Twitter) DM ] (Button)          |
|                                       |
+---------------------------------------+
| [FOOTER]                              |
| © 2026 YASUSHI Portfolio              |
+---------------------------------------+
```

---

## 💻 Desktop Layout (PC)
>
> **Concept**: Multi-column, expansive, museum-like.

```text
+---------------------------------------------------------------+
| [HEADER]                                                      |
| YASUSHI Portfolio           Works    About    Contact   [ X ] |
+---------------------------------------------------------------+
| [HERO SECTION]                                                |
|                                                               |
|        一瞬で奪う、視線。                                     |
|                                                               |
|        (Background Image with Parallax Effect)                |
|                                                               |
+---------------------------------------------------------------+
| [GALLERY SECTION]                                             |
|                                                               |
| [ Thumb 1 ]   [ Thumb 2 ]   [ Thumb 3 ]   [ Thumb 4 ]     |
|                                                               |
| [ Thumb 5 ]   [ Thumb 6 ]   [ Thumb 7 ]   [ Thumb 8 ]     |
|                                                               |
| (Hover effect: Image gets slightly brighter & larger)         |
+---------------------------------------------------------------+
| [ABOUT SECTION]                | [CONTACT SECTION]            |
|                                |                              |
| [Photo]  **YASUSHI**           |  お仕事のご依頼は            |
|                                |  XのDMにて承ります。         |
| Reboot 60 / Content Creator    |                              |
| (Bio Text...)                  |  [ Send Message via X ]      |
|                                |                              |
+---------------------------------------------------------------+
| [FOOTER]                                                      |
| © 2026 YASUSHI Portfolio                                      |
+---------------------------------------------------------------+
```

---

## 🔍 Lightbox Detail (CSS Overlay)
>
> What happens when a thumbnail is clicked.

```text
[SCREEEEEN (Dark Overlay Background)]
|                                       |
|      +-------------------------+      |
|      |                         |      |
|      |   [ BIG THUMBNAIL ]     |      |
|      |                         |      |
|      +-------------------------+      |
|                                       |
|      Title: YouTubeサムネイルA        |
|      Client: 〇〇チャンネル様         |
|                                       |
|      [× Close (Back)]                 |
|                                       |
```

## 📝 Implementation Notes

1. **HTML Structure**: `header`, `main`, `footer` tags will be used.
2. **CSS**: Use `display: grid` for the Gallery to easily switch between Mobile (1 col) and Desktop (4 cols).
3. **Color**:
    * Background: `#1a1a1a` (Dark)
    * Text: `#ffffff` (White)
    * Button: `#FFFF00` (Electric Yellow) or Neon Blue
