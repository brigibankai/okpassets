# Oakland Pride — Custom HTML Assets

This repository holds the custom-built HTML widgets used across Oakland Pride's digital presence. Each file is a self-contained web component ready to be embedded in a website, displayed on a screen, or shared with a web developer for integration.

---

## What is a GitHub Repository?

A **repository** (or "repo") is like a shared folder in the cloud that stores files along with a full history of every change ever made to them. GitHub is the platform that hosts it. Think of it like Google Drive, but built specifically for code — every edit is tracked, nothing is lost, and multiple people can collaborate safely.

This repo lives at:
`https://github.com/brigibankai/okpassets`

Anyone with the link can view the files. Only authorized contributors can make changes.

---

## What's in This Repo

### Animated Logos

| File | Description |
|---|---|
| `logoAni.html` | Oakland Pride animated logo — white oak tree illustration with pulsing stars and a sweeping shimmer effect. Designed for use on dark backgrounds. |
| `blackAnni.html` | "OAK" wordmark version of the animated logo — stylized script lettering with the tree graphic, concentric dot arcs, and the same shimmer animation. Black background variant. |

Both logos use smooth CSS animations with no external dependencies. The shimmer cycles every 9 seconds; star pulse cycles every ~2.4 seconds.

---

### Decorative Graphics

| File | Description |
|---|---|
| `anicircle.html` | A ring of white dots that rotates continuously. A purely decorative element — useful as a background accent, loading screen, or visual filler on display screens. Speed and dot color are adjustable at the top of the file. |
| `halfcircleanni.html` | A half-circle arc variant of the animated circle graphic. Same adjustable properties as `anicircle.html`. |

---

### Event Information Widgets

| File | Description |
|---|---|
| `tealStageSchedule.html` | Interactive stage schedule for the Latin Stage (Oakland Pride 2026, August 16). Displays 30-minute performer slots from 11:00 AM – 5:30 PM. Clicking any slot opens a modal with performer details. Teal and dark green color scheme. Performer names are placeholder "TBD" until confirmed. |
| `faq.html` | Accordion-style FAQ section covering common Oakland Pride 2026 questions: event date, location (Frank H. Ogawa Plaza, Downtown Oakland), age policy, ticketing, and how to get involved. Clicking a question expands it; only one answer shows at a time. Peach color scheme. |
| `ticker.html` | A horizontally scrolling ticker banner announcing the event. Displays date, location, hours, and "First Hour Free & Open to the Public" on a dark background with hot pink dividers. Loops seamlessly every 28 seconds. Pauses when hovered. |

---

## How to Use These Files

### Preview a file
1. Click any `.html` file name in the repo file list.
2. Click the **Raw** button in the top-right corner to see the plain code.
3. Save the file to your computer (`File → Save As` in your browser), then open it — it will render in any web browser (Chrome, Safari, Firefox).

### Share with a developer
Send them the direct link to the file in this repo. They can copy the code and embed it into any webpage or CMS (Squarespace, Webflow, Wix, etc.) using an **HTML embed block**.

### Embed via iframe
Each file can be dropped into a webpage as an iframe. A developer would use a snippet like this:

```html
<iframe src="URL_TO_FILE" width="100%" height="400" frameborder="0"></iframe>
```

Replace `URL_TO_FILE` with the raw file URL (e.g. from the **Raw** button on GitHub).

---

## Updating Content

Most event details (performer names, FAQ answers, ticker text) are written directly inside the HTML files and can be edited with any text editor. If you need to update something:

1. Ask a developer to edit the relevant file and push the change to this repo, or
2. Click the file in GitHub → click the **pencil (edit) icon** → make your change → click **Commit changes**.

Changes take effect immediately for anyone viewing the file after the commit.

---

## Questions or Access Issues

If you need to be added as a contributor to edit files directly, contact the repo owner at **brigido.j.bautista@gmail.com** or open an Issue in GitHub using the **Issues** tab at the top of the repo page.
