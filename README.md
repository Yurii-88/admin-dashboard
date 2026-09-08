# Admin Dashboard

A responsive admin dashboard built with **HTML and CSS** as part of [The Odin Project](https://www.theodinproject.com/) curriculum.

The project recreates the layout of an admin dashboard using **CSS Grid**, **Flexbox**, responsive media queries, and **Material Design Icons**.

## Features

- Dashboard layout with sidebar, header, main content, and right sidebar
- Responsive design for desktop, tablet, and mobile screen sizes
- Project cards with action icons
- Announcements section
- Trending users section
- Search bar
- User profile and welcome section
- Responsive navigation
- Material Design Icons via CDN
- No JavaScript or external frameworks required

## Technologies

- HTML5
- CSS3
- CSS Grid
- Flexbox
- CSS Media Queries
- Material Design Icons

## Layout

The dashboard consists of:

- **Sidebar** — navigation links and dashboard branding
- **Header** — search bar, user information, and action buttons
- **Projects** — grid of project cards
- **Announcements** — site updates and notifications
- **Trending** — list of trending users and their projects

## Responsive Design

The layout adapts to different screen sizes using CSS media queries:

- **Desktop** — two-column dashboard with a sidebar and content area
- **Tablet** — simplified content layout with the right column positioned alongside the content
- **Mobile** — stacked layout with a full-width sidebar and single-column content

## Icons

The project uses [Material Design Icons](https://pictogrammers.com/library/mdi/) through the jsDelivr CDN. No package installation is required.

```html
<link
  rel="stylesheet"
  href="https://cdn.jsdelivr.net/npm/@mdi/font@7.4.47/css/materialdesignicons.min.css"
/>
```

Icons can then be added using MDI classes:

```html
<span class="mdi mdi-home"></span>
```

## Project Structure

```text
admin-dashboard/
├── index.html
├── styles.css
└── README.md
```

## Credits

- Dashboard design inspired by [The Odin Project](https://www.theodinproject.com/) Admin Dashboard project.
- Icons provided by [Material Design Icons](https://pictogrammers.com/library/mdi/).
