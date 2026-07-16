# Code Demo Script — Portfolio Page (profile.html)

Target time: 3:00 to present + 1:00 for questions. Practice with a timer.
Demo file: **profile.html** (the styled version). index.html is the older
Practice 2 file — only mention it if asked.

---

## 1. Project overview (about 30 seconds)

> "This is my personal portfolio page. I built it for our HTML and CSS
> coursework to practice semantic HTML, external CSS, and different kinds
> of selectors. It has an About Me section, my skills and interests, a
> contact form, and a link to my GitHub."

## 2. Feature demo — pick ONE to actually click through (about 60-90 seconds)

Recommended: the **contact form** + **button hover**, because it's visual
and easy to point at.

> "Here's the contact form. Each label is connected to its input by
> matching `for` and `id` attributes — that's what makes the form
> accessible. And here's the Send button — watch what happens when I hover
> over it."
>
> *(hover over the Send button on screen so the color change shows)*
>
> "That color change is a `button:hover` rule in my CSS file."

## 3. Technical explanation (about 60 seconds)

> "All the styling lives in one external file, `styles.css`, linked from
> the `head` with a `link` tag. Keeping CSS separate from HTML is a
> pattern from the course — it keeps structure and presentation apart.
>
> "The four content sections — About, Skills, Interests, and Contact — all
> share one grouped CSS selector, so they get the same card-style
> background and spacing without repeating the same rules four times.
>
> "One challenge I ran into: my name in the header used a custom font,
> and at narrow screen widths it wrapped onto two lines. I fixed it by
> reducing the font size and testing again at a few different widths."

## 4. Invite questions (about 15-20 seconds)

> "That's my portfolio page — I'd love to answer any questions."

---

# Quick recognition cheat sheet

Use this to drill yourself: cover the right two columns, look at the
snippet, say the label and the one-sentence explanation out loud.

| Snippet | 1-2 word label | Plain English | Say this in the demo |
|---|---|---|---|
| `<header id="page-header">` | Page header | The top banner with my name and tagline | "This is the header — it holds my name and tagline." |
| `<main>` | Main content | Wraps the primary page content, one per page | "The `main` tag marks the primary content area." |
| `<section class="about">` | Section + class | A content block; class lets sections share styling | "Each part of the page is a `section` with a class for styling." |
| `<link rel="stylesheet" href="styles.css">` | Stylesheet link | Connects this HTML file to the external CSS file | "This link connects the page to my CSS file." |
| `.about, .skills, .interests, .contact { ... }` | Grouped selector | One rule applied to four sections at once | "I grouped these four selectors so they share one style instead of repeating it." |
| `label for="name"` / `input id="name"` | Label-input pair | Matching `for`/`id` connects a label to its field | "The label and input are linked by matching `for` and `id`." |
| `button:hover` | Hover state | Changes the button's look when the mouse is over it | "This hover rule changes the Send button's color on mouseover." |
| `@font-face` + `font-family: "Brother Signature"` | Custom font | Loads and applies a local font file | "This loads my custom signature font for the header." |
| `<footer><a href="https://github.com/jheusler">` | Footer link | A link to my GitHub profile in the footer | "The footer links out to my GitHub profile." |

---

# Likely questions and short answers

1. **Why classes for the sections?** So multiple sections can share one style rule.
2. **Why an ID for the header?** It's a single unique element, so an ID fits.
3. **Does the form actually send anything?** No — it's HTML structure only, no backend or JavaScript behind it.
4. **What does the hover rule do?** Changes the button's background color while the mouse is over it.
5. **How does the custom font work?** `@font-face` names the font file, and `font-family` applies it to the heading.

---

# Night-of checklist

- [ ] Read this script once out loud, no screen.
- [ ] Read it again while clicking through profile.html in the browser.
- [ ] Time yourself once. Trim if over 3:00.
- [ ] Get some sleep — you already have working code and a script; the rest is just saying it out loud.
