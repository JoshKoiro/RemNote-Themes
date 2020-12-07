# RemNote-Theme
Custom Theme for RemNote

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
