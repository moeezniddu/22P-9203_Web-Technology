# HTML Newspaper Recreation - Voice of Time (Nawa-i-Waqt)

## Student Information
- **Name:** [Moeez Uddin]
- **Roll Number:** [22P-9203]
- **Section:** [BsCS 8A]

## Original Newspaper
- **Name:** نوائے وقت (Nawa-i-Waqt) / Voice of Time
- **Date:** Thursday, August 18, 1988 (5 Muharram 1409 AH)
- **Source:** Historical newspaper archive documenting the tragic plane crash of President Zia-ul-Haq

## Project Description
This project recreates a historic Pakistani newspaper front page from August 18, 1988, reporting the death of President Muhammad Zia-ul-Haq in a plane crash. The original Urdu newspaper has been translated to English and recreated using pure HTML5 with inline CSS styling. The layout preserves the traditional newspaper aesthetic with multiple columns, a prominent headline banner, photo gallery of victims, and comprehensive coverage including international reactions.

## Features Implemented
- **Semantic HTML5 Structure:** Used `<article>`, `<header>`, `<section>`, `<aside>`, and `<footer>` tags for proper document structure
- **Multiple Table Layouts:** Implemented nested tables for precise column control (3-column header, 4-column photo gallery, 2-column main content, 3-column article text)
- **7 Images with Alt Text:** All images include descriptive alt attributes for accessibility compliance
- **Proper Heading Hierarchy:** Structured h1-h4 headings throughout the document
- **Two List Types:** Unordered list (`<ul>`) for international reactions and ordered list (`<ol>`) for incident details
- **Vintage Newspaper Styling:** Yellowish-white paper background (#f9f6e8) with classic serif fonts (Playfair Display, Merriweather)
- **Inline CSS Only:** All styling implemented through inline style attributes as per project requirements
- **HTML Comments:** Each major section documented with explanatory comments
- **Proper Indentation:** Consistent 4-space indentation throughout the code

## Challenges Faced
The main challenge was creating a three-column article layout with equal widths and vertical dividing lines using only inline CSS. I solved this by implementing a nested table structure with three cells set to 33% width each, applying border-right properties to create column separators. Another difficulty was maintaining authentic newspaper aesthetics while ensuring accessibility—I addressed this by using carefully selected vintage colors, appropriate typography, and writing detailed alt text descriptions for all images (e.g., "President Muhammad Zia-ul-Haq official portrait photograph" instead of generic labels).

## File Structure
```
├── english_newspaper.html    # Main HTML newspaper file
├── README.md                          # This file
└── images/                            # Newspaper images
    ├── OIP.jpg                        # President Zia photo
    ├── MB.jpg                         # US Ambassador photo
    ├── akhtrt.jpg                     # General Akhtar photo
    ├── bg.jpg                         # Brigadier photo
    ├── wasim.jpg                      # General Waseem photo
    ├── crash.jpg                      # Crash site photo
    └── sogwar.jpg                     # Mourning crowd photo
```

## How to View
1. Download or clone this repository
2. Ensure all image files are in the same directory as the HTML file (or update image paths)
3. Open `newspaper_final_guideline.html` in any modern web browser
4. No additional dependencies or server required

## Technical Requirements Met
✅ Proper `<!DOCTYPE html>` and HTML5 structure  
✅ Semantic HTML5 tags (`<header>`, `<article>`, `<section>`, `<aside>`, `<footer>`)  
✅ Multiple `<table>` elements for layout  
✅ 7+ images with descriptive alt attributes  
✅ Proper heading hierarchy (h1-h4)  
✅ Both `<ul>` and `<ol>` lists included  
✅ HTML comments explaining major sections  
✅ Consistent indentation (4 spaces)  
✅ Inline CSS only (no external stylesheets)  
✅ No JavaScript or frameworks  

## Content Translation
All Urdu content has been translated to English and completely rephrased in original words to ensure uniqueness. The translation maintains journalistic integrity while adapting the content for an English-speaking audience.

## Browser Compatibility
Tested and working on:
- Google Chrome (latest)
- Mozilla Firefox (latest)
- Microsoft Edge (latest)
- Safari (latest)

## Academic Integrity
This project was completed individually following all course guidelines. All content is original work with proper translation and rephrasing from the source material.

## License
This is an educational project created for academic purposes.

---
**Course:** Web Development / HTML Fundamentals  
**Assignment:** HTML Newspaper Recreation  
**Submission Date:** [Your Submission Date]
