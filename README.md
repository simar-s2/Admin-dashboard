# Admin Dashboard

A dashboard UI layout built to practice **CSS Grid**: a fixed sidebar, a header
band, and a main content area of cards. One of
[The Odin Project](https://www.theodinproject.com/) intermediate HTML/CSS
exercises.

> 🚧 The committed code is the layout skeleton (`header` / `menu` / `content`
> grid regions). Styling is still in progress.

> 📸 **Screenshot needed**: the full dashboard once styled, showing the sidebar, header, and card grid. Save to `docs/dashboard.png` and replace this line with `![Dashboard](docs/dashboard.png)`.

## Run it

Open `index.html` in a browser. No build step.

## How it works

The page is one grid container. The sidebar spans the full height on the left, the
header sits across the top of the remaining space, and the content area fills the
rest, using `grid-template-areas` to place each region. Inside the content area a
second grid lays out the project cards responsively.

## Built with

HTML · CSS Grid

## License

Released under the [MIT License](LICENSE).
