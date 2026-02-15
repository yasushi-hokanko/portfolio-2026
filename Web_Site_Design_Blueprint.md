# Website Design Blueprint: YASUSHI Thumbnail Portfolio

## 1. Project Overview (概要)

- **Project Name**: YASUSHI Thumbnail Portfolio
- **Goal**: クライアント（YouTuber、編集者）に「サムネイル制作スキル」を直感的に伝え、受注につなげる。
  - **CTR（クリック率）へのこだわり**と**デザインの美しさ**の両立をアピールする。
- **Target Audience**:
  - YouTubeチャンネル運営者（ビジネス系、エンタメ系問わず）
  - 動画編集プロダクションのディレクター
  - 「目を惹くサムネイルが欲しいが、安っぽいのは嫌」な層
- **Key Message**:
  - **「一瞬で奪う、視線。(Capturing eyes in an instant.)」**
  - **「Reboot 60: 人生の経験値が、表現の深みになる。」**

## 2. Concept & Brand Identity (世界観)
>
> **Reference**: `00_UserProfile/01_価値観(Core_Values).md` & `03_執筆スタイル(Style_Guidelines).md`

- **Tone & Voice**: **「Vivid & Professional」**
  - コンテンツ（サムネイル）は派手で目を惹くが、サイト自体はそれを引き立てる「美術館」のように静謐でモダン。
  - 信頼感（Professional）とインパクト（Vivid）の融合。
- **Color Palette**:
  - Primary: **Matte Black / Dark Grey** (#1a1a1a) - サムネイルの色を引き立てる背景。
  - Secondary: **White** (#ffffff) - テキスト。
  - Accent: **Electric Yellow / Neon Blue** - 「クリックしたくなる」アクセントカラー。
- **Typography**:
  - Japanese: Noto Sans JP (太さの使い分けでインパクトを出す)
  - English: Oswald or Roboto Condensed (サムネイルっぽい力強さ)
- **Aesthetics**:
  - **Grid Layout**: 隙間のないグリッド、またはMasonryレイアウトで「量感」と「質」を一覧で見せる。
  - **Hover Effects**: マウスオーバーで少し拡大・明度が上がるなどの「触れる」インタラクション。

## 3. Functional Requirements (機能要件) - Phase 1 (MVP)
>
> **「まずはここから」**: JavaScriptを使わず、HTMLとCSSだけで実装できる範囲に絞ります。

- [x] **Responsive Web Design**: **必須**。スマホとPCで見やすく表示（CSS Flexbox/Gridを使用）。
- [x] **Simple Gallery**: サムネイルを綺麗に並べる。
- [x] **CSS Lightbox**: 画像をクリックすると拡大表示する（CSSの`:target`などで実装）。
- [x] **Contact Link**: フォームは作らず、**「X (Twitter) のDM」**へ飛ばすボタンを置く。

## 4. Content Structure (Sitemap)

### Home (/) - 1ページ完結 (Single Page)

- **Hero Area**: キャッチコピーと自分の肩書き。
- **Portfolio Section**: サムネイル画像を単純にグリッドで並べる。
- **About Section**: 簡単な自己紹介。
- **Contact Section**: Xへのリンクボタン。

## 5. Technology Stack (技術選定)

- **Core**: **HTML5, CSS3** (No JavaScript required for MVP).
- **Hosting**: GitHub Pages (最も簡単で無料)。

## 6. Security & Safety (セキュリティ・安全対策)
>
> **初心者が「絶対に守るべき」ネット公開の鉄則**

1. **NO API Keys in Code (APIキーをコードに書かない)**
    - HTML/CSSの中に、Google MapsやFormsなどの「APIキー」を直接書かない。
    - 万が一外部サービスを使う場合は、必ず環境変数などを経由する（今回は外部サービスを使わないので安全）。
2. **No Personal Data on Repo (個人情報を上げない)**
    - 電話番号、住所、LINE IDなどをコードに記述しない。
    - Gitに一度上げると履歴に残るため、最初から書かないこと。
3. **Use HTTPS**
    - GitHub Pagesを使えば自動的に**HTTPS（鍵マーク付きの安全な通信）**になり、ユーザーに安心感を与えられる。
4. **Copyright Images (画像の権利)**
    - ポートフォリオに載せるサムネイルは、自身の著作物か、許可を得たものだけに限定する。

## 7. Development Roadmap (ロードマップ)

- **Phase 1: Design & Prototype**
  - [x] Approve Blueprint
  - [x] Collect Works (MVP uses placeholders)
  - [x] Draft Wireframe (Done)
- **Phase 2: Development (MVP)**
  - [x] Setup Git Repository (Use project root)
  - [x] Build Gallery Layout (HTML/CSS)
  - [x] Implement CSS Lightbox
- **Phase 3: Content & Polish (Next Steps)**
  - [ ] **Replace Images** (画像を本物に差し替える)
  - [ ] Write Portfolio Descriptions
  - [ ] **Security Check** (個人情報・キーの混入がないか確認)
- **Phase 4: Launch**
  - [ ] Deploy (GitHub Pages)
