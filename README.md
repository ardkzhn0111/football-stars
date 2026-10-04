# Football Stars

A one-page responsive website for Assignment 3, Responsive Web Design.

**Student:** Ardak Kazykhan  
**Group:** IT-2510  
**Repository:** https://github.com/ardkzhn0111/football-stars

## Open the website

Open `index.html` in a browser. An internet connection is needed for Bootstrap 5.3.8 CSS and the JavaScript bundle from jsDelivr. All player photographs are local.

Alternatively, serve this folder with VS Code Live Server or run `python -m http.server 8000` and open http://localhost:8000. There is no build step, package installation or custom JavaScript.

## Assignment criteria

| Requirement | Implementation |
| --- | --- |
| At least four sections | Home, Football Stars, Football Legends, About the Project |
| Task 1 custom CSS only | `#stars` has only custom classes and CSS Grid |
| Mobile-first breakpoints | Base: 1 column; min-width 768px: 2; min-width 992px: 3 |
| Additional breakpoint changes | Stars heading size and section padding change at 768px; heading alignment changes at 992px |
| Bootstrap grid | Home, legends and about use container, row and responsive col classes |
| Bootstrap cards | Legends use `col-12 col-md-6 col-lg-4` and `card` |
| Responsive order | Hero text uses `order-1 order-lg-2`; image uses `order-2 order-lg-1` |
| Responsive visibility | Hero note uses `d-none d-md-block` |
| Collapsible navbar | `navbar-expand-md`, collapse component and accessible toggler |
| Utilities | `p-4`, `py-5`, `mb-0`, `d-flex`, `gap-2`, `text-secondary` and more |
| Report | `report/Assignment3_ArdakKazykhan.docx` |
| Screenshots | `report/screenshots/`, captured at 375px, 768px and 1280px |

`style.css` is loaded after Bootstrap. The manual section does not use Bootstrap layout or utility classes; Bootstrap Reboot still supplies document-wide element defaults. Layout dimensions are fluid. Images use a percentage width, aspect ratio and object-fit rather than fixed layout widths. There are no floats or absolutely positioned layout elements.

## Verification

Checked in Chrome at 375 x 900, 768 x 900 and 1280 x 900 CSS pixels. Full-page screenshots include everything below the viewport.

- Both card grids display 1, 2 and 3 columns respectively.
- Document width matches viewport width at all three sizes, with no horizontal scrolling.
- Hero text is above the image below 992px; the image is on the left from 992px.
- Extra hero note is hidden at 375px and visible at 768px and 1280px.
- Mobile menu opens and closes; its legends link navigates to the correct anchor.
- All six local image files load, Bootstrap CSS loads, and no JavaScript page errors occur.

## Photo credits

The files below were downloaded as Wikimedia Commons thumbnails. Displayed photographs are cropped with CSS `object-fit: cover`. Legend photographs also have a CSS grayscale treatment. These presentation changes do not overwrite the source images. CC-licensed image adaptations retain their respective licenses; third-party photographs are not claimed as original work.

| Local file | Author and source | License |
| --- | --- | --- |
| `assets/images/messi.jpg` | Bryan Berlin, [Leo Messi Argentina v Egypt 7 July 2026-1](https://commons.wikimedia.org/wiki/File:Leo_Messi_Argentina_v_Egypt_7_July_2026-1.jpg) | [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) |
| `assets/images/ronaldo.jpg` | Bryan Berlin, [Cristiano Ronaldo Croatia v Portugal 2 July 2026-075 cropped](https://commons.wikimedia.org/wiki/File:Cristiano_Ronaldo_Croatia_v_Portugal_2_July_2026-075_%28cropped%29.jpg) | [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) |
| `assets/images/mbappe.jpg` | Bryan Berlin, [Kylian Mbappe France v Senegal 16 June 2026-391 cropped](https://commons.wikimedia.org/wiki/File:Kylian_Mbappe_France_v_Senegal_16_June_2026-391_%28cropped%29.jpg) | [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) |
| `assets/images/pele.jpg` | Unknown photographer, El Gráfico, [Pele con brasil cropped](https://commons.wikimedia.org/wiki/File:Pele_con_brasil_%28cropped%29.jpg) | Public domain, as documented on Commons |
| `assets/images/maradona.jpg` | Unknown photographer, El Gráfico, [Argentina celebrando copa cropped](https://commons.wikimedia.org/wiki/File:Argentina_celebrando_copa_%28cropped%29.jpg) | Public domain, as documented on Commons |
| `assets/images/zidane.jpg` | Hadi Abyar / Tasnim News Agency, [Zinedine Zidane by Tasnim 03](https://commons.wikimedia.org/wiki/File:Zinedine_Zidane_by_Tasnim_03.jpg) | [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) |

## Learning references

- [Bootstrap 5.3 setup](https://getbootstrap.com/docs/5.3/getting-started/introduction/)
- [Bootstrap grid](https://getbootstrap.com/docs/5.3/layout/grid/)
- [Bootstrap navbar](https://getbootstrap.com/docs/5.3/components/navbar/)
- [MDN media queries](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_media_queries/Using_media_queries)

The site's short descriptions are editorial summaries of playing styles rather than current club or live statistical information.
