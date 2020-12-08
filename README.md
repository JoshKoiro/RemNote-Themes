# RemNote-Theme
Custom Themes for RemNote

## Dark Theme for RemNote
The first theme in this repo is a dark theme for RemNote based on the original theme created at https://github.com/ethomasv/RemNoteTheme

![dark theme](screenshots/dark theme.png)

### Installation
Paste the follow code into a new blank CSS block on the Custom CSS page of your RemNote to get the latest updates:
`@import url('https://joshkoiro.github.io/RemNote-Theme/darkStyle.css');`

If you would like to customize the css variables copy the code below and modify as required. Do not delete the !important keywords so they override the values defined in the base css style.
```
:root {
    --main-background-c: #212527!important;     /* Main Window, Bottom Bar, Doc View, Sticky Top, Pages, Queue */
    --secondary-background-c: #1a1d1f!important;     /* Sidebar, Quotes, icons, Portals, Embedded Search, Settings Menu */
    --elevated-background-c: #212527!important;     /* Queue Cards, Popups */
    --hover-background-c: #111314!important;     /* Hover */
    --border-c: #555!important;

    --font-c: #c9c8ca!important;
    --font-dark-c: rgba(240, 240, 239, .6)!important;
    --font-background-c: #aaa!important;

    --font-red-c: #c5272d!important;
    --font-orange-c:#bd5113!important;
    --font-yellow-c:#ebaa1f!important;
    --font-blue-c: #0f509b!important;
    --font-green-c:#096809!important;
    --font-purple-c:#5a1799!important;

    --main-font-spacing: 0.01em!important;
    --bold-font-spacing: 0.02em!important;
    --semiwide-font-spacing: 0.05em!important;
    --wide-font-spacing: 0.1em!important;

    --normal-font-weight: 400!important;
    --focus-font-weight: 500!important;
    --bold-font-weight: 600!important;
    --sidebar-width: 240px!important;
    --link-image-size:32px!important;
}
```

## Light "Roam" Theme for RemNote
The second theme is a light style based heavily on Roam's base theme.

![light theme](screenshots/light theme.png)

### Installation
Paste the follow code into a new blank CSS block on the Custom CSS page of your RemNote to get the latest updates:
`@import url('https://joshkoiro.github.io/RemNote-Theme/lightStyle.css');`

If you would like to customize the css variables copy the code below and modify as required. Do not delete the !important keywords so they override the values defined in the base css style.
uncomment and replace the @import link to modify the font face.

```
/*@import url('https://fonts.googleapis.com/css2?family=Quicksand:wght@300;400;500;600;700&display=swap');*/

:root {
    --main-background-c: #fefeff;     /* Main Window, Bottom Bar, Doc View, Sticky Top, Pages, Queue */
    --light-secondary-background-c:rgba(0,0,0,0.05);
    --right-pane-background-c:rgb(218,225,231);
    --secondary-background-c:rgb(25,32,37);     /* Sidebar, Quotes, icons, Portals, Embedded Search, Settings Menu */
    --elevated-background-c: #ffffff;     /* Queue Cards, Popups */
    --hover-background-c: #cfcfcf;     /* Hover */
    --border-c: rgba(0,0,0,0.1);
    --rem-c: rgba(0,0,0,0.5);

    --font-body: "Quicksand";

    --font-c: #1d1d1d;
    --font-dark-c: rgba(0, 0, 0, 0.6);
    --font-sidebar-c:rgb(115, 133, 149);
    --font-background-c: #aaa;
    --main-link-c:rgb(7, 98, 150);

    --font-red-c: #c5272d;
    --font-orange-c:#bd5113;
    --font-yellow-c:#ebaa1f;
    --font-blue-c: #0f509b;
    --font-green-c:#096809;
    --font-purple-c:#6c3f96;

    --main-font-spacing: 0.01em;
    --bold-font-spacing: 0.02em;
    --semiwide-font-spacing: 0.05em;
    --wide-font-spacing: 0.3em;

    --normal-font-weight: 400;
    --focus-font-weight: 500;
    --bold-font-weight: 700;
    --sidebar-width: 300px;
    --link-image-size:32px;
    --todo-color:rgb(112, 79, 150);
    --todo-check-color:rgb(200,200,200);
    --checkbox-size:1.5em;
}
```