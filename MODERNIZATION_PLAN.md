# SAM RICKLES VFX Portfolio - Modernization Plan

## Non-Negotiables (Must Keep)
- **Ubuntu font** - currently using Cufon JS rendering, will switch to Google Fonts
- **"SAM RICKLES" in all capitals** - header branding stays
- **VFX Reel** - Vimeo embed (currently http://vimeo.com/76830759)
- **Portfolio PDF** - Shot breakdown document
- **LinkedIn profile link** - http://www.linkedin.com/in/samrickles/
- **Filmography with movie poster images** - keep the poster grid

## Content to Remove
- Tutorials section (no longer needed)
- Past Projects sub-section
- IE6/IE7 compatibility hacks
- Cufon font rendering JS
- prettyPhoto lightbox (replace with modern solution)
- Flash/SWF files

## Pages/Sections for New Site
1. **Hero/Home** - Name, title, quick intro
2. **Reel** - Embedded VFX reel video + PDF breakdown
3. **About** - Revamped bio (needs jazzing up)
4. **Filmography** - Movie poster grid with titles

## Technical Modernization
| Old | New |
|-----|-----|
| jQuery 1.6 | Vanilla JS or minimal modern library |
| Cufon fonts | Google Fonts (Ubuntu) |
| prettyPhoto lightbox | Native HTML5 video / modern lightbox |
| IE conditionals | Remove entirely |
| Table-based/float layouts | CSS Grid / Flexbox |
| Multiple CSS files | Single consolidated stylesheet |
| Hash-based routing (#!/page_) | Clean sections or simple SPA |

## Existing Assets to Preserve
- `/images/` - Movie posters, profile photo, background
- `/docs/Sam_Rickles_Shot_Breakdown_2018_Web.pdf`
- Vimeo reel embed

## About Section Ideas (To Jazz Up)
- More dynamic presentation of experience
- Visual timeline or stats (years in industry, number of films, etc.)
- Skills/tools section (Houdini, Katana, Nuke)
- Highlight notable projects with visual callouts

## Design Direction
- Clean, modern single-page layout
- Dark theme (VFX industry standard)
- Responsive/mobile-friendly
- Smooth scroll navigation
- Subtle animations

---

*Ready to begin implementation after user approval.*
