# Crown & Glory Hair Studio - Web Development Project

Welcome to the official repository for **Crown & Glory Hair Studio**, a multi-page web application built to showcase hair care services, custom styling, photo galleries, and booking inquiries.

---

## Part 2 Overview & Implementation

In Part 2, the website was updated from a plain structure to a fully styled, user-friendly front-end application. Key enhancements include:

* **Unified Visual Styling:** Created a external CSS stylesheet (`css/style.css`) incorporating a soft luxury palette (blush pink, rose gold, cream, and charcoal).
* **Typography & Hierarchy:** Integrated Google Fonts (*Playfair Display* for luxury editorial headings and *Poppins* for clean body copy).
* **Responsive Layouts:** Designed card-based sections, customized pill buttons, and hover animations for an interactive user experience.
* **Structural Cleanup:** Re-organized all HTML pages into the root project directory and placed styles within a dedicated `css/` directory.

---

## Changelog (Addressing Part 1 Feedback)

The following fixes were implemented based on Formative 1 Part 1 marker feedback:

1. **Fixed Page Navigation & Linking:**
   * **Issue:** HTML files were nested incorrectly inside the `css` folder, causing broken relative paths and unstyled pages.
   * **Fix:** Moved all `.html` files (`index.html`, `about.html`, `services.html`, `enquiry.html`, `contact.html`) to the root directory so internal links work seamlessly across all pages.

2. **Corrected CSS Stylesheet Linking:**
   * **Issue:** Pages loaded as plain black and white text without styling.
   * **Fix:** Updated the `<head>` section of every HTML file to correctly reference `css/style.css`.

3. **Detailed Documentation:**
   * **Issue:** README lacked detailed project breakdown.
   * **Fix:** Expanded the README to include a detailed changelog, folder structural overview, and updated reference citations.

---

## Folder Structure

```text
WEDE/
├── css/
│   └── style.css
├── about.html
├── contact.html
├── enquiry.html
├── index.html
├── services.html
└── README.md

## References

* Google Fonts. 2026. *Playfair Display & Poppins Font Families*. Available at: <https://fonts.google.com/> [Accessed 17 September 2026].
* Mozilla Developer Network (MDN). 2026. *CSS Building Blocks: Linking Stylesheets*. Available at: <https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks> [Accessed 17 September 2026].
* W3Schools. 2026. *HTML Links - Hyperlinks*. Available at: <https://www.w3schools.com/html/html_links.asp> [Accessed 17 September 2026]. 