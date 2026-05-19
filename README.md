# GitHub Profile 3D Badges

Custom SVG badges for a GitHub profile README. They are static images, because
GitHub renders SVG/PNG/GIF in README files but does not run arbitrary JavaScript
or custom page-level CSS there.

## Add To Your Profile README

Put the `github-profile-badges` folder into the root of your profile repository
and paste this into your profile `README.md`:

```md
<p align="center">
  <img src="./github-profile-badges/assets/flow-state.svg" width="132" alt="Flow State achievement badge" />
  <img src="./github-profile-badges/assets/ship-it.svg" width="132" alt="Ship It achievement badge" />
  <img src="./github-profile-badges/assets/open-source.svg" width="132" alt="Open Source Pulse achievement badge" />
  <img src="./github-profile-badges/assets/secure-stack.svg" width="132" alt="Secure Stack achievement badge" />
</p>
```

If the SVG files are in another folder, change only the `src` paths.

## Files

- `assets/flow-state.svg` - terminal, focus, commit streak mood.
- `assets/ship-it.svg` - releases, deploys, finished tasks.
- `assets/open-source.svg` - PRs, discussions, open-source contribution.
- `assets/secure-stack.svg` - security, infrastructure, hardened builds.

## Customize

The visible labels are near the bottom of each SVG in `<text>` tags. Ring colors
come from the `ringA`, `ringB`, and `ringC` gradients. Ring completion is set by
the `stroke-dasharray` values on the three circles.
