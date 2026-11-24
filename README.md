# Rachel Chidester — Nature-inspired digital resume (GitHub Pages)

Static HTML/CSS site for Rachel Chidester. No build step, frameworks, paid hosting, or JavaScript required. All content is plain readable HTML. Site preview locally: open `index.html` in a browser. Upload the **contents of this folder** to the root of a public GitHub repository, then enable **Settings → Pages → Deploy from a branch → main → /(root)**.

## Design

The visual direction is **inspired by** the supplied Wix nature-themed reference: full-width nature hero, minimal navigation, editorial serif typography, sage/forest green, and lots of breathing room. This is original HTML/CSS and **not** a Wix template export or identical reproduction. The exact Wix preview was not accessible to automated inspection, so this is an interpretation of the requested look and feel.

## Harbor hero photo / image rights

The homepage uses a remotely loaded photo titled **Presque Isle Harbor looking north**, from the Presque Isle Township website: https://presqueisletwp.org/wp-content/uploads/2021/01/presque-isle-harbor-looking-north-1024x682.png
Source/credit: https://presqueisletwp.org/area-lakes/

**IMPORTANT BEFORE PUBLISHING**: The township source does not indicate a reusable Creative Commons license. The image is *linked from the source site*, not copied into this archive. Obtain the photographer/source's authorization for this use, or replace the image with a personally owned or properly licensed photo before publishing publicly. If the photo is blocked by the source or the device is offline, a dark-green background is shown. To replace it, edit the `background-image` URL in `index.html` on the element with class `hero-photo`; ideally upload a licensed `assets/presque-isle-harbor.jpg` to your GitHub repo and set `url('assets/presque-isle-harbor.jpg')`. Keep or update attribution in `.photo-credit`.

The name **Presque Isle Harbor** refers to locations on both Lake Huron (Presque Isle Township) and Lake Superior (Marquette). This design uses the **Lake Huron, Presque Isle Township** location shown in the town's source image.

## ATS, SEO, and privacy

- Browser-accessible HTML has all job descriptions visible to search engines and text readers.
- `resume.json`, `resume.txt`, and selectable-text PDF are provided for copying and sharing. Job application systems still require tailored file uploads; a site alone does not guarantee ATS indexing.
- Phone number deliberately excluded from public website and downloadable PDF; confirm this preference before publishing.
- Before launch, add the live canonical URL and Open Graph URL to `index.html`, update `sitemap.xml.template` into `sitemap.xml`, and submit sitemap to Google Search Console if desired.
- Contact via email and LinkedIn. No analytics or tracking scripts; no forms that expose private data.

## Files

`index.html`, `styles.css`, `favicon.svg`, `.nojekyll`, `Rachel_Chidester_Resume.pdf`, `resume.txt`, `resume.json`, `llms.txt`, `robots.txt`, `sitemap.xml.template`.

## Update paths

- Summary/copy: `index.html` and machine-readable versions `resume.json` and `resume.txt`.
- Skills: three groups in `index.html` and corresponding resume files.
- Photo: `background-image` inline URL in `index.html`.
- PDF: keep `Rachel_Chidester_Resume.pdf` current as experience changes.

## Hosting

This package is ready to **publish as a new repo**. No changes have been made to any connected ShelterPawtners repositories. The user can connect a personal GitHub account for a dedicated public resume repository.
