

## 1. Objective

The objective of this assignment is to create a typography showcase webpage using HTML, CSS, and Google Fonts. The webpage demonstrates different font families, font sizes, font weights, text alignment, text decoration, font styles, letter spacing, and line height.

## 2. Requirements

- Visual Studio Code
- HTML
- CSS
- Google Fonts
- Google Chrome
- Live Server extension (optional)

## 3. Project Folder Structure

Create a folder named `Assignment-5.3` with the following files:

```text
Assignment-5.3/
│
├── index.html
├── style.css
└── Assignment-5.3.md
```

## 4. HTML Code (index.html)

Create a file named `index.html` and paste the following complete code:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Typography Showcase Page</title>

    <!-- Google Fonts: Poppins and Lora -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>

    <link href="https://fonts.googleapis.com/css2?family=Lora:ital,wght@0,400;0,500;0,600;0,700;1,400;1,500&family=Poppins:wght@300;400;500;600;700;800&display=swap"
          rel="stylesheet">

    <!-- External CSS File -->
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <!-- Header Section -->
    <header class="hero">
        <p class="eyebrow">DESIGN • READABILITY • CREATIVITY</p>

        <h1>Typography Showcase</h1>

        <p class="hero-description">
            Discover how fonts, spacing, alignment, and text styles
            transform an ordinary webpage into a beautiful design.
        </p>

        <a href="#heading-styles" class="hero-link">Explore Typography</a>
    </header>

    <!-- Main Content -->
    <main>

        <!-- Section 1: Heading Styles -->
        <section id="heading-styles" class="showcase-section">
            <p class="section-label">01 / FONT HIERARCHY</p>

            <h2>Heading Styles</h2>

            <p class="section-intro">
                Headings organize content and help readers understand
                the importance of different sections.
            </p>

            <div class="type-sample">
                <h1 class="heading-one">Heading One — 40px</h1>
                <p class="sample-note">
                    Large headings are useful for the main title of a page.
                </p>
            </div>

            <div class="type-sample">
                <h2 class="heading-two">Heading Two — 32px</h2>
                <p class="sample-note">
                    Secondary headings introduce important sections.
                </p>
            </div>

            <div class="type-sample">
                <h3 class="heading-three">Heading Three — 24px</h3>
                <p class="sample-note">
                    Smaller headings divide content into clear topics.
                </p>
            </div>

            <div class="type-sample">
                <h4 class="heading-four">Heading Four — 18px</h4>
                <p class="sample-note">
                    Smaller headings work well for subsections and labels.
                </p>
            </div>
        </section>

        <!-- Section 2: Paragraph Styles -->
        <section id="paragraph-styles" class="showcase-section">
            <p class="section-label">02 / BODY TEXT</p>

            <h2>Paragraph Styles</h2>

            <p class="section-intro">
                Body text should be comfortable to read. Font family,
                size, line height, and alignment all affect readability.
            </p>

            <div class="paragraph-card">
                <h3>Standard Paragraph</h3>

                <p class="standard-paragraph">
                    Typography is an important part of web design.
                    A suitable font and comfortable line spacing make
                    information easier to read. Good typography also
                    creates a consistent visual experience for visitors.
                </p>
            </div>

            <div class="paragraph-card">
                <h3>Centered Paragraph</h3>

                <p class="centered-paragraph">
                    Every word has a place, every heading has a purpose,
                    and every line contributes to the overall design.
                </p>
            </div>

            <div class="paragraph-card">
                <h3>Justified Paragraph</h3>

                <p class="justified-paragraph">
                    A well-designed webpage balances appearance with
                    readability. Typography helps present information
                    in a clear structure so that visitors can understand
                    the content and move through the page comfortably.
                </p>
            </div>
        </section>

        <!-- Section 3: Text Emphasis -->
        <section id="text-emphasis" class="showcase-section">
            <p class="section-label">03 / VISUAL EMPHASIS</p>

            <h2>Text Emphasis</h2>

            <p class="section-intro">
                Different text styles can highlight important information
                and create visual variety.
            </p>

            <div class="emphasis-card">
                <h3>Bold Text</h3>
                <p class="bold-text">
                    Bold text makes important words stand out.
                </p>
            </div>

            <div class="emphasis-card">
                <h3>Italic Text</h3>
                <p class="italic-text">
                    Italic text can emphasize a phrase or introduce a
                    different tone.
                </p>
            </div>

            <div class="emphasis-card">
                <h3>Underlined Text</h3>
                <p class="underlined-text">
                    This sentence demonstrates text decoration.
                </p>
            </div>

            <div class="emphasis-card">
                <h3>Letter Spacing</h3>
                <p class="spaced-text">
                    CREATIVE TYPOGRAPHY
                </p>
            </div>

            <div class="emphasis-card">
                <h3>Uppercase and Small Labels</h3>
                <p class="uppercase-text">
                    design with purpose
                </p>
            </div>

            <div class="quote-box">
                <p class="quote">
                    "Typography is the voice of visual communication."
                </p>

                <p class="quote-author">— Typography Showcase</p>
            </div>
        </section>

    </main>

    <!-- Footer -->
    <footer>
        <p>Typography Showcase Page | Created with HTML and CSS</p>
    </footer>

</body>
</html>
```

## 5. CSS Code (style.css)

Create a file named `style.css` in the same folder and paste the following code:

```css
/* Universal Selector */
* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}

/* General Page Styling */
html {
    scroll-behavior: smooth;
}

body {
    font-family: "Lora", Georgia, serif;
    background-color: #f5f7fb;
    color: #273449;
    font-size: 16px;
    line-height: 1.8;
}

/* Hero Header */
.hero {
    background: linear-gradient(135deg, #172554, #4338ca);
    color: #ffffff;
    text-align: center;
    padding: 75px 20px 85px;
}

.eyebrow {
    font-family: "Poppins", sans-serif;
    font-size: 12px;
    font-weight: 600;
    letter-spacing: 3px;
    margin-bottom: 18px;
    color: #c7d2fe;
}

.hero h1 {
    font-family: "Poppins", sans-serif;
    font-size: 48px;
    font-weight: 800;
    line-height: 1.25;
    margin-bottom: 20px;
}

.hero-description {
    max-width: 680px;
    margin: 0 auto 28px;
    font-family: "Lora", Georgia, serif;
    font-size: 18px;
    line-height: 1.9;
    color: #e0e7ff;
}

.hero-link {
    display: inline-block;
    font-family: "Poppins", sans-serif;
    font-size: 14px;
    font-weight: 600;
    text-decoration: none;
    color: #172554;
    background-color: #ffffff;
    padding: 12px 24px;
    border-radius: 6px;
    transition: background-color 0.3s ease;
}

.hero-link:hover {
    background-color: #c7d2fe;
}

/* Main Content */
main {
    max-width: 1000px;
    margin: 45px auto;
    padding: 0 22px;
}

/* Showcase Sections */
.showcase-section {
    background-color: #ffffff;
    padding: 35px;
    margin-bottom: 32px;
    border-radius: 14px;
    box-shadow: 0 5px 20px rgba(23, 37, 84, 0.07);
}

.section-label {
    font-family: "Poppins", sans-serif;
    font-size: 12px;
    font-weight: 700;
    letter-spacing: 2px;
    color: #6366f1;
    margin-bottom: 8px;
}

.showcase-section > h2 {
    font-family: "Poppins", sans-serif;
    font-size: 32px;
    font-weight: 700;
    line-height: 1.4;
    color: #172554;
    margin-bottom: 12px;
}

.section-intro {
    font-family: "Lora", Georgia, serif;
    font-size: 16px;
    line-height: 1.9;
    color: #64748b;
    margin-bottom: 28px;
}

/* Heading Styles */
.type-sample {
    padding: 22px 0;
    border-top: 1px solid #e2e8f0;
}

.heading-one,
.heading-two,
.heading-three,
.heading-four {
    font-family: "Poppins", sans-serif;
    color: #273449;
    line-height: 1.4;
}

.heading-one {
    font-size: 40px;
    font-weight: 800;
}

.heading-two {
    font-size: 32px;
    font-weight: 700;
}

.heading-three {
    font-size: 24px;
    font-weight: 600;
}

.heading-four {
    font-size: 18px;
    font-weight: 500;
}

.sample-note {
    font-family: "Lora", Georgia, serif;
    font-size: 14px;
    line-height: 1.8;
    color: #64748b;
    margin-top: 5px;
}

/* Paragraph Styles */
.paragraph-card {
    padding: 22px;
    margin-top: 18px;
    background-color: #f8fafc;
    border-left: 4px solid #6366f1;
    border-radius: 7px;
}

.paragraph-card h3,
.emphasis-card h3 {
    font-family: "Poppins", sans-serif;
    font-size: 17px;
    font-weight: 600;
    color: #3730a3;
    margin-bottom: 10px;
}

.standard-paragraph {
    font-family: "Lora", Georgia, serif;
    font-size: 16px;
    line-height: 1.9;
    text-align: left;
}

.centered-paragraph {
    font-family: "Lora", Georgia, serif;
    font-size: 17px;
    line-height: 1.8;
    text-align: center;
}

.justified-paragraph {
    font-family: "Lora", Georgia, serif;
    font-size: 16px;
    line-height: 2;
    text-align: justify;
}

/* Text Emphasis */
.emphasis-card {
    background-color: #f8fafc;
    padding: 20px;
    margin-top: 18px;
    border-radius: 7px;
}

.bold-text {
    font-family: "Poppins", sans-serif;
    font-weight: 700;
    font-size: 17px;
}

.italic-text {
    font-family: "Lora", Georgia, serif;
    font-style: italic;
    font-size: 17px;
}

.underlined-text {
    font-family: "Poppins", sans-serif;
    text-decoration: underline;
    text-decoration-color: #6366f1;
    text-decoration-thickness: 2px;
    text-underline-offset: 5px;
}

.spaced-text {
    font-family: "Poppins", sans-serif;
    font-size: 17px;
    font-weight: 700;
    letter-spacing: 4px;
    color: #4338ca;
}

.uppercase-text {
    font-family: "Poppins", sans-serif;
    font-size: 14px;
    font-weight: 600;
    text-transform: uppercase;
    letter-spacing: 2px;
    color: #475569;
}

/* Quote Styling */
.quote-box {
    background-color: #eef2ff;
    padding: 28px;
    margin-top: 25px;
    border-radius: 8px;
    text-align: center;
}

.quote {
    font-family: "Lora", Georgia, serif;
    font-size: 22px;
    font-style: italic;
    font-weight: 500;
    line-height: 1.8;
    color: #312e81;
}

.quote-author {
    font-family: "Poppins", sans-serif;
    font-size: 13px;
    font-weight: 600;
    text-align: right;
    margin-top: 12px;
    color: #6366f1;
}

/* Footer */
footer {
    background-color: #172554;
    color: #e0e7ff;
    text-align: center;
    padding: 22px 15px;
    font-family: "Poppins", sans-serif;
    font-size: 13px;
}

/* Responsive Design */
@media (max-width: 600px) {
    .hero {
        padding: 55px 18px;
    }

    .hero h1 {
        font-size: 34px;
    }

    .hero-description {
        font-size: 16px;
    }

    main {
        margin: 25px auto;
        padding: 0 12px;
    }

    .showcase-section {
        padding: 22px 18px;
    }

    .showcase-section > h2 {
        font-size: 26px;
    }

    .heading-one {
        font-size: 32px;
    }

    .heading-two {
        font-size: 27px;
    }

    .heading-three {
        font-size: 22px;
    }

    .spaced-text {
        letter-spacing: 2px;
    }

    .quote {
        font-size: 19px;
    }
}
```

## 6. Google Fonts Used

This webpage uses two complementary font families from Google Fonts.

| Font Family | Usage |
|---|---|
| Poppins | Headings, labels, buttons, and emphasized text |
| Lora | Paragraphs, descriptions, and quotation text |

**Poppins** is a modern sans-serif font that works well for headings and labels.

**Lora** is a serif font that gives paragraphs and quotations a readable, editorial appearance.

The Google Fonts stylesheet is linked inside the HTML `<head>` section. An internet connection is required to load the fonts. If the fonts cannot be loaded, the browser uses the specified fallback fonts.

## 7. Typography Properties Used

| Property | Purpose |
|---|---|
| `font-family` | Selects the font family. |
| `font-size` | Sets the size of the text. |
| `font-weight` | Controls the thickness of the text. |
| `text-align` | Aligns text left, center, right, or justified. |
| `text-decoration` | Adds or removes underlines and other text decorations. |
| `font-style` | Makes text normal or italic. |
| `letter-spacing` | Adjusts the spacing between characters. |
| `line-height` | Controls the spacing between lines of text. |
| `text-transform` | Changes letter case, such as uppercase. |

## 8. Steps to Run the Website

1. Open Visual Studio Code.
2. Create a folder named `Assignment-5.3`.
3. Create `index.html` and paste the HTML code.
4. Create `style.css` and paste the CSS code.
5. Save both files using `Ctrl + S`.
6. Ensure that both files are in the same folder.
7. Open `index.html` using Live Server or Google Chrome.
8. Check all three sections: Heading Styles, Paragraph Styles, and Text Emphasis.
9. Confirm that the Google Fonts load correctly and that the page displays the different font sizes, weights, alignments, and text decorations.

## 9. Expected Output

The webpage should contain:

- A gradient header with a large typography title.
- Heading Styles with four different heading sizes.
- Paragraph Styles showing left-aligned, centered, and justified text.
- Text Emphasis examples showing bold, italic, underlined, and letter-spaced text.
- Two Google Fonts with different purposes.
- Consistent line height, spacing, and font weights.
- A responsive layout that works on mobile screens.

## 10. Result

The typography showcase webpage was successfully created using HTML and CSS. Two complementary Google Fonts, Poppins and Lora, were applied to headings and body text. Different font sizes, font weights, text alignments, text decorations, font styles, letter spacing, and line heights were demonstrated in three sections.

## 11. Submission

Submit the following files:

1. `index.html` — HTML structure of the typography showcase webpage.
2. `style.css` — CSS file containing all typography styles.
3. `Assignment-5.3.md` — Assignment documentation.


