# Personal Website & HTML Learning Page

This repository contains a single HTML file that serves a dual purpose:

1.  A template for a personal portfolio website.
2.  A comprehensive example file for learning a wide variety of HTML5 tags and their proper usage.

The page is structured semantically to demonstrate best practices in web development. It covers everything from basic metadata and text formatting to complex forms and embedded media.

---

## Features & HTML Elements Covered

This file is an excellent resource for understanding how different HTML elements work together to build a complete web page.

### 📄 **Document Structure & Metadata**

- `<!DOCTYPE html>`: Defines the document type.
- `<head>`: Contains all the meta-information.
  - `<meta>`: For character set (`charset`), `description`, `keywords`, `author`, `viewport`, and Open Graph social tags (`og:title`, etc.).
  - `<title>`: The title that appears in the browser tab.
  - `<link>`: To connect the CSS stylesheet (`style.css`) and favicon.
  - `<script>`: To link the JavaScript file (`script.js`) with the `defer` attribute.

### 🏛️ **Semantic Layout Elements**

- `<body>`: Contains the visible page content.
- `<header>`: Introductory content, including `<h1>` and `<nav>`.
- `<nav>`: A set of navigation links.
- `<main>`: The main content of the page, divided into sections.
- `<section>`: Thematic groupings of content (About, Skills, Projects, etc.).
- `<article>`: Self-contained compositions, like a project entry.
- `<aside>`: Content that is tangentially related to the main content (Quick Links).
- `<footer>`: Contains footer information like copyright and contact details (`<address>`).

### ✍️ **Text & Content Formatting**

- Headings (`<h1>`, `<h2>`, `<h3>`).
- Paragraphs (`<p>`).
- Emphasis (`<em>`, `<i>`).
- Importance (`<b>`).
- Stylistic text (`<u>`, `<mark>`).
- Quotes (`<blockquote>`), abbreviations (`<abbr>`), and keyboard input (`<kbd>`).
- Preformatted text and code (`<pre>`, `<code>`).
- Lists: Unordered `<ul>`, ordered `<ol>`, and description lists `<dl>`.

### 🖼️ **Media & Embedded Content**

- Images: `<img>`.
- Figures with captions: `<figure>` and `<figcaption>`.
- Media: `<video>`, `<audio>`, and `<iframe>` (for embedding YouTube videos).
- Other embedded objects: `<object>` (for PDFs) and `<embed>` (for GIFs/plugins).

### 📋 **Tables & Forms**

- `<table>`: With a `<caption>`, `<thead>`, `<tbody>`, `<tfoot>`, and `colspan` attribute.
- `<form>`: A complete form with various input types.
  - `<fieldset>` and `<legend>` to group form controls.
  - `<label>` for accessibility.
  - `<input>` with types like `text`, `email`, `date`, `color`, `file`, `number`, `radio`, `checkbox`, `range`, `submit`, and `reset`.
  - `<textarea>` for multi-line text input.

### ✨ **Other Elements**

- `<details>` & `<summary>`: For creating interactive disclosure widgets.
- `<progress>`: To display the progress of a task.
- `<meter>`: To represent a scalar measurement within a known range (like battery level).

---

## How to Use

1.  **Clone or download** the repository.
2.  **Open `index.html`** in your web browser to see the page.
3.  **Customize the content**:
    - Replace `[Your Name]` and other placeholder text with your own information.
    - Change the `src` attributes of `<img>`, `<video>`, etc., to point to your own media files.
    - Modify `style.css` to change the look and feel of the page.
    - Add functionality in `script.js`.

---

<div dir="rtl">

# صفحة شخصية و صفحة لتعلم HTML

يحتوي هذا المستودع على ملف HTML واحد يخدم غرضًا مزدوجًا:

1.  قالب لموقع شخصي (Portfolio).
2.  ملف مثال شامل لتعلم مجموعة واسعة من وسوم (tags) لغة HTML5 واستخدامها الصحيح.

تم تصميم الصفحة ببنية دلالية (semantically) لإظهار أفضل الممارسات في تطوير الويب. يغطي كل شيء بدءًا من البيانات الوصفية الأساسية وتنسيق النصوص، وصولًا إلى النماذج المعقدة والوسائط المضمنة.

---

## المميزات وعناصر HTML المستخدمة

يعتبر هذا الملف مصدرًا ممتازًا لفهم كيفية عمل عناصر HTML المختلفة معًا لبناء صفحة ويب كاملة.

### 📄 **بنية المستند والبيانات الوصفية (Metadata)**

- `<!DOCTYPE html>`: يُعرّف نوع المستند.
- `<head>`: يحتوي على جميع المعلومات الوصفية.
  - `<meta>`: لترميز الأحرف (`charset`)، والـ`description` (الوصف)، والـ`keywords` (الكلمات المفتاحية)، والـ`author` (المؤلف)، والـ`viewport` (منفذ العرض)، ووسوم Open Graph الاجتماعية (`og:title`، إلخ).
  - `<title>`: العنوان الذي يظهر في علامة تبويب المتصفح.
  - `<link>`: لربط ملف التنسيق CSS (`style.css`) والأيقونة (favicon).
  - `<script>`: لربط ملف JavaScript (`script.js`) مع خاصية `defer`.

### 🏛️ **عناصر التخطيط الدلالية (Semantic Layout)**

- `<body>`: يحتوي على محتوى الصفحة المرئي.
- `<header>`: المحتوى الافتتاحي، بما في ذلك `<h1>` و `<nav>`.
- `<nav>`: مجموعة من روابط التنقل.
- `<main>`: المحتوى الرئيسي للصفحة، مقسم إلى أقسام.
- `<section>`: تجمعات مواضيعية للمحتوى (عني، المهارات، المشاريع، إلخ).
- `<article>`: محتوى مستقل بذاته، مثل وصف مشروع.
- `<aside>`: محتوى ذو صلة هامشية بالمحتوى الرئيسي (روابط سريعة).
- `<footer>`: يحتوي على معلومات التذييل مثل حقوق النشر وتفاصيل الاتصال (`<address>`).

### ✍️ **تنسيق النصوص والمحتوى**

- العناوين (`<h1>`, `<h2>`, `<h3>`).
- الفقرات (`<p>`).
- التأكيد (`<em>`, `<i>`).
- الأهمية (`<b>`).
- نصوص منمّقة (`<u>`, `<mark>`).
- الاقتباسات (`<blockquote>`)، الاختصارات (`<abbr>`)، وإدخال لوحة المفاتيح (`<kbd>`).
- نصوص وكود منسقة مسبقًا (`<pre>`, `<code>`).
- القوائم: غير مرتبة `<ul>`، مرتبة `<ol>`، وقوائم الوصف `<dl>`.

### 🖼️ **الوسائط والمحتوى المضمن**

- الصور: `<img>`.
- الأشكال مع تسميات توضيحية: `<figure>` و `<figcaption>`.
- الوسائط: `<video>`، `<audio>`، و `<iframe>` (لتضمين فيديوهات يوتيوب).
- كائنات مضمنة أخرى: `<object>` (لملفات PDF) و `<embed>` (لصور GIF أو الإضافات).

### 📋 **الجداول والنماذج**

- `<table>`: مع `<caption>` (عنوان)، `<thead>` (رأس الجدول)، `<tbody>` (جسم الجدول)، `<tfoot>` (تذييل الجدول)، وخاصية `colspan`.
- `<form>`: نموذج كامل مع أنواع إدخال مختلفة.
  - `<fieldset>` و `<legend>` لتجميع عناصر النموذج.
  - `<label>` لتحسين إمكانية الوصول.
  - `<input>` بأنواع مثل `text`, `email`, `date`, `color`, `file`, `number`, `radio`, `checkbox`, `range`, `submit`, و `reset`.
  - `<textarea>` لإدخال نصوص متعددة الأسطر.

### ✨ **عناصر أخرى**

- `<details>` و `<summary>`: لإنشاء عناصر تفاعلية قابلة للفتح والإغلاق.
- `<progress>`: لعرض تقدم مهمة ما.
- `<meter>`: لتمثيل قياس ضمن نطاق معروف (مثل مستوى البطارية).

---

## كيفية الاستخدام

1.  **انسخ أو نزّل** المستودع.
2.  **افتح `index.html`** في متصفح الويب الخاص بك لرؤية الصفحة.
3.  **خصص المحتوى**:
    - استبدل `[Your Name]` والنصوص المؤقتة الأخرى بمعلوماتك الخاصة.
    - غير مسارات (`src`) الصور والفيديوهات (`<img>`, `<video>`, إلخ) لكي تشير إلى ملفاتك الخاصة.
    - عدّل ملف `style.css` لتغيير مظهر وتصميم الصفحة.
    - أضف وظائف برمجية في ملف `script.js`.

</div>
