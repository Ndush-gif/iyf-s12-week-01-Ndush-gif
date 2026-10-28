# Week 1: Web Foundations

## Author
- **Name:** Catherine Nduku
- **GitHub:** [@Ndush-gif]([(https://github.com/Ndush-gif))
- **Date:** October 3, 2026

## Project Description
A multi-page personal portfolio built with HTML. It has a home page, an About page, a Projects page and a Contact page with a form, all using semantic HTML and the same navigation. I also explored browser DevTools (see [devtools-exploration.md](devtools-exploration.md)), audited the site for accessibility (see [accessibility-report.md](accessibility-report.md)) and completed five daily challenges.

## Technologies Used
- HTML
- CSS (basic styling for the navigation)
- Git and GitHub
- VS Code
- GitHub Pages
- Lighthouse and WAVE (accessibility testing)

## Features
- Four pages with the same navigation and the current page marked
- Semantic structure on every page: `header`, `nav`, `main`, `footer`
- A contact form with linked labels, `fieldset`/`legend` groups and required fields
- A `mailto:` link for my email
- `semantic-conversion.html`: a `div`-based page rebuilt with semantic tags
- Five daily challenges in the [daily-challenges](daily-challenges/) folder

## How to Run
1. Clone this repository
2. Open `index.html` in your browser, or use the Live Server extension in VS Code.   

## Lessons Learned
- Semantic tags describe what content is, and fixing my page with `<main>` raised my Lighthouse accessibility score from 97 to 100.
- Links between pages depend on where each file lives: a page inside `daily-challenges/` needs `../index.html` to reach the home page.
- Windows can hide file extensions, which is how I ended up with `contact.html.html`.
- Markdown and HTML behave differently: backticks and tags I pasted into an HTML page showed up wrongly.
- Before pushing from a second computer, I need to run `git pull`, or the two copies cause a merge conflict.
  
## Challenges Faced
- I had a merge conflict in `index.html` after working on two computers. I fixed it by removing the conflict markers and keeping one clean version of the file.
- My Home link failed from a daily challenge page because of the folder path, and I solved it by using `../`.
- Uploading images and screenshots was confusing at first, so I reread the notes and searched online.
- VS Code would not commit until I opened the repository folder itself instead of a subfolder.

## Screenshots (optional)
![VS Code extensions](https://github.com/Ndush-gif/iyf-s12-week-01-Ndush-gif/blob/main/images/Screenshots/vscode-extensons.JPG)

 ## Live demo
 [ndush-gif.github.io](https://ndush-gif.github.io/iyf-s12-week-01-Ndush-gif/)
