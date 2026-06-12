# gothamizer.github.io

The **dashboard of dashboards** — a live index of every Gothamizer dashboard, at
[gothamizer.github.io](https://gothamizer.github.io/).

It reads the public GitHub API client-side and lists every repo under
[`gothamizer`](https://github.com/gothamizer) that has GitHub Pages enabled.
No build step, no cron: publish a new Pages dashboard and it appears here on the
next page load. Edit a repo's GitHub description and it updates the blurb.

To hide a repo from the board (e.g. a superseded version), add its name to the
`HIDE` set near the top of the `<script>` in `index.html`.
