# Jacopo Gonzini

A small personal links page, built with HTML and CSS. No dependencies, tracking,
third-party requests, or build step. Open `index.html` directly to view it locally.

Light and dark themes follow the visitor's system appearance preference and
respond when it changes. Instrument Serif and DM Mono are hosted locally in
`assets/fonts/`, along with their SIL Open Font License files.

Update the biography and links in `index.html`, and the visual styles in
`styles.css`. Email is omitted until a public contact address is selected.

## Public CV

`cv/jacopo-gonzini-cv.tex` is the editable public source, based on the selected
`GonziniJacopo.pdf` and its matching LaTeX source. The personal email and phone
are removed. The private originals remain in the Curriculum folder.

Build with LuaLaTeX (TeX Live):

```sh
lualatex -interaction=nonstopmode -halt-on-error -output-directory=assets cv/jacopo-gonzini-cv.tex
```

The site downloads `assets/jacopo-gonzini-cv.pdf`. Check PDF text, metadata,
and link annotations for personal contact details before publishing any update.
Do not add private CVs to this repository or its Git history.

## Hosting

The files can be served by any static host. For GitHub Pages, publish the root
directory of the `main` branch through the repository's Pages settings. Relative
asset paths support both a project URL and a custom domain.
