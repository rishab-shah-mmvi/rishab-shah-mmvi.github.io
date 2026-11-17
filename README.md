# Rishab Shah | Resume website

My personal resume website, built with plain HTML and CSS for my Web Development course. It uses no framework and no JavaScript.

**Live site:** https://rishabshah26.github.io/

## Files

| File | What it is |
| --- | --- |
| `index.html` | The page content |
| `style.css` | All the styling |
| `scroll-effects.css` | Three small effects that follow the scroll position, kept separate because they use newer CSS |
| `rishab-shah.jpg` | My photo |
| `favicon.png` | The small icon in the browser tab |
| `og-image.png` | The preview image shown when the link is shared |
| `rishab-shah-resume.pdf` | My resume as a PDF |
| `letter-of-recommendation-*.pdf` | Six letters of recommendation |
| `research-*.pdf` | Three research papers |
| `certificate-*.pdf` | Six certificates |
| `greenrx-pitch-deck.pdf` | The GreenRx pitch deck |

## Design

Calm and minimal, with a little movement. Each section works like a spec sheet, with the title on the left and the details on the right.

- Font: Inter, from Google Fonts, used for everything
- Colours: white, near-black and grey, a pale blue wash at the top, one blue accent, and a dark band at the end
- Layout: Flexbox for the navigation bar and entries, CSS Grid for the sections, cards and the activities timeline, and media queries for tablets, phones and print
- Text: sentences are justified so both edges line up; headings, labels and cards stay left-aligned
- Small screens: a full-screen menu that opens with the `:target` selector, section titles that stay under the header, and cards that swipe sideways
- Motion: the intro fades in when the page loads, the photo enlarges when clicked, and three scroll effects run where the browser supports them. All of it switches off when a visitor has asked for reduced motion
