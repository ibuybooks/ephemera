# Ephemera, or; Emails & Exchanges from the Archives

<div align="center">
  <img src="https://github.com/user-attachments/assets/2b3e26e0-1340-4d62-ba22-80b34ce397e9" width="350" alt="Book Cover">
  
  <br>
  <br>

  [![Follow @ibuybooks](https://img.shields.io/badge/Follow%20%40ibuybooks-000000?logo=X&logoColor=white&style=for-the-badge)](https://x.com/ibuybooks)
  [![LaTeX](https://img.shields.io/badge/LaTeX-008080?style=for-the-badge&logo=latex&logoColor=white)](#)
  [![License](https://img.shields.io/badge/Free%20for%20Non--Commercial%20Use-007bff?style=for-the-badge&logo=github&logoColor=white&labelColor=282828&color=007bff)](#)
  ![Made with ❤️ by Gavin](https://img.shields.io/badge/Made_with_❤️_by-Gavin-red?style=for-the-badge)
      
  [![Stars](https://img.shields.io/github/stars/ibuybooks/ephemera?style=for-the-badge&color=2F323A)](https://github.com/ibuybooks/ephemera/stargazers)
  [![Size](https://img.shields.io/github/repo-size/ibuybooks/ephemera?style=for-the-badge&color=2F323A)](https://github.com/ibuybooks/ephemera)
  [![Downloads](https://img.shields.io/github/downloads/ibuybooks/ephemera/total?style=for-the-badge&color=2F323A)](https://github.com/ibuybooks/ephemera/releases)

  <br>

  >*"Experience, as the source of knowledge, is also the basis for criticizing false beliefs, which is necessary for knowledge to continue its development."*
  >
  > — Ray Peat
</div>

<br>

>[!NOTE]
> **MEDICAL ADVICE DISCLAIMER**
> 
> The information contained in this repository is for educational and informational purposes only and is not intended as medical advice. You should not rely on this information to make decisions about your health or medical treatment. The author is not responsible for any use or misuse of this content.

<br>

<div align="center">
  <h2>⚡ Quick Start</h2>
  <h3>Download Latest Release</h3>
  <p>Download the Latest Pre-Built PDF Release</p>
  
  [![Download][Download-Badge]][Download-Link]

  [Download-Badge]: https://img.shields.io/badge/Download_Latest_Release-2563eb?style=for-the-badge&logo=github&logoColor=white&labelColor=1e40af
  [Download-Link]: https://github.com/ibuybooks/ephemera/releases/download/v0.0.1/Ephemera.or.Emails.Exchanges.from.the.Archives.pdf
  
  <sup>📖 See README for More Information</sup>
</div>

<div align="center">
  <h2>📌 README</h2>
</div>

<h3>📎 About:</h3>

**Ephemera, or; Emails & Exchanges from the Archives**  
*e·phem·er·a /əˈfem(ə)rə/: things that exist or are used or enjoyed for only a short time.*

This repository contains quotes, question and answers, and email exchanges; all originally shared to the Ray Peat Forum from 2012-2024. This project is an attempt to gether, from this source, as well as elsewhere, the volume of exchanges with Ray Peat, which have been either unsearchable, unorganized, or are just not well known about; and to preserve them in a single, well-maintained, searchable source. The current code contains just over 1,400 entries originating from the Ray Peat Forum, as well as the original Email Wiki.

<div align="center">
  <h2>🛠️ Build Instructions</h2>
</div>

<h3>📋 Prerequisites:</h3>

- A TeX distribution (i.e., MiKTeX, or TeX Live for the `tlmgr` command).
- EB Garamond & Open Sans fonts installed.

<h3>🔧 Required LaTeX Packages:</h3>

Ensure `tlmgr` and all installed packages are up-to-date:

```bash
tlmgr update --self --all
```

Install the required packages:

```bash
tlmgr install fontspec, xcolor, graphicx, tikz, babel, csquotes, microtype, selnolig, fontawesome5, mhchem, siunitx, tcolorbox, enumitem, imakeidx, totcount, hyperref, cleveref
```

<h3>🏗️ Compilation:</h3>

```bash
lualatex Ephemera && lualatex Ephemera
```



