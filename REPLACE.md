# Replace the current profile cleanly

1. In `justpainful/justpainful`, replace the current `README.md` with this package's `README.md`.
2. Delete the old `assets/header.svg`, `assets/footer.svg`, and the whole old `assets/icons/` folder.
3. Upload this package's `assets/xp-profile.svg`, `assets/xp-workspace.svg`, and `assets/ru-flag.svg` into `assets/`.
4. Delete `ASSETS.md`, `SETUP.md`, and `preview.html`; they are not needed in the profile repository.
5. Commit the change and hard-refresh the GitHub profile page after 30–90 seconds.

The new README deliberately has no HTML tables, because GitHub's profile renderer broke the previous nested-table layout and exposed literal `</td>` tags.
