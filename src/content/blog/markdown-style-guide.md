---
title: 'Cinematic Markdown: دليل التنسيق البصري لكتابة المقالات السينمائية'
description: 'تعلم كيفية استخدام صيغة الـ Markdown لتنسيق تحليلاتك، مراجعات الـ Cinema، وتقارير الـ Cinematography داخل مدونة Astro الشخصية.'
pubDate: 'May 27 2026'
heroImage: '../../assets/blog-placeholder-1.jpg'
---

هذا الدليل المصغر يعلمك كيف تستخدم لغة الـ **Markdown** البسيطة لتنسيق نصوصك وتحليلاتك السينمائية لتظهر بشكل مريح للعين ومتوافق كلياً مع معايير الـ **Global SEO**.

## العناوين الفرعية (Headings)

في عالم الـ **Content Creation**، نستخدم الهاشتاق `#` لتوليد عناوين فرعية تُسهل على القارئ ومحركات البحث فهم هيكل المقال. يمكنك استخدام المستويات التالية لتوزيع الـ **Cinematic Analysis**:

# العنوان الرئيسي للمقال (H1) - يُكتب تلقائياً من الـ Title

## أقسام المقال الكبرى (H2) - نضع قبلها رمزي هاشتاق `##`

### العناوين الفرعية الداخلية (H3) - نضع قبلها ثلاثة رموز `###`

#### تفاصيل فرعية دقيقة (H4) - نضع قبلها أربعة رموز `####`

## الفقرات النصية (Paragraphs)

لكتابة فقرة عادية حول فلسفة الـ **Storytelling** أو مراجعة لفيلم وثائقي (**Documentary Breakdown**)، لا تحتاج لإضافة أي رموز؛ فقط ابدأ الكتابة مباشرة. وعندما تريد الانتقال إلى فقرة جديدة، اترك سطراً فارغاً واحداً ليتنفس النص بصرياً.

## التنسيق المتقدم للنصوص (Text Formatting)

* لجعل الكلمة **عريضة وبارزة (Bold)** لتجذب انتباه القارئ لمصطلح مثل الـ **Director**، ضعها بين نجمتين هكذا: `**Director**`.
* لجعل الكلمة *مائلة (Italic)* عند الإشارة لاسم فيلم مثل *Interstellar*، ضعها بين نجمة واحدة هكذا: `*Interstellar*`.
* لإنشاء قائمة نقطية غير مرتبة لمخرجينك المفضلين (مثل Christopher Nolan أو Quentin Tarantino)، ابدأ السطر بعلامة النجمة `*` متبوعة بمسافة.
> — <cite>Rob Pike[^1]</cite>
```

#### Output

> Don't communicate by sharing memory, share memory by communicating.<br>
> — <cite>Rob Pike[^1]</cite>

[^1]: The above quote is excerpted from Rob Pike's [talk](https://www.youtube.com/watch?v=PAAkCSZUG1c) during Gopherfest, November 18, 2015.

## Tables

### Syntax

```markdown
| Italics   | Bold     | Code   |
| --------- | -------- | ------ |
| _italics_ | **bold** | `code` |
```

### Output

| Italics   | Bold     | Code   |
| --------- | -------- | ------ |
| _italics_ | **bold** | `code` |

## Code Blocks

### Syntax

we can use 3 backticks ``` in new line and write snippet and close with 3 backticks on new line and to highlight language specific syntax, write one word of language name after first 3 backticks, for eg. html, javascript, css, markdown, typescript, txt, bash

````markdown
```html
<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8" />
    <title>Example HTML5 Document</title>
  </head>
  <body>
    <p>Test</p>
  </body>
</html>
```
````

### Output

```html
<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8" />
    <title>Example HTML5 Document</title>
  </head>
  <body>
    <p>Test</p>
  </body>
</html>
```

## List Types

### Ordered List

#### Syntax

```markdown
1. First item
2. Second item
3. Third item
```

#### Output

1. First item
2. Second item
3. Third item

### Unordered List

#### Syntax

```markdown
- List item
- Another item
- And another item
```

#### Output

- List item
- Another item
- And another item

### Nested list

#### Syntax

```markdown
- Fruit
  - Apple
  - Orange
  - Banana
- Dairy
  - Milk
  - Cheese
```

#### Output

- Fruit
  - Apple
  - Orange
  - Banana
- Dairy
  - Milk
  - Cheese

## Other Elements — abbr, sub, sup, kbd, mark

### Syntax

```markdown
<abbr title="Graphics Interchange Format">GIF</abbr> is a bitmap image format.

H<sub>2</sub>O

X<sup>n</sup> + Y<sup>n</sup> = Z<sup>n</sup>

Press <kbd>CTRL</kbd> + <kbd>ALT</kbd> + <kbd>Delete</kbd> to end the session.

Most <mark>salamanders</mark> are nocturnal, and hunt for insects, worms, and other small creatures.
```

### Output

<abbr title="Graphics Interchange Format">GIF</abbr> is a bitmap image format.

H<sub>2</sub>O

X<sup>n</sup> + Y<sup>n</sup> = Z<sup>n</sup>

Press <kbd>CTRL</kbd> + <kbd>ALT</kbd> + <kbd>Delete</kbd> to end the session.

Most <mark>salamanders</mark> are nocturnal, and hunt for insects, worms, and other small creatures.
