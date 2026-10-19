# Rhea Dense Rounded Theme

A neutral gray theme with 12px text, large rounded controls, and dense spacing; supports light and dark modes.

Install this directory or its release archive in OpenAgent Plugins, then select Rhea Dense Rounded Theme in General → Appearance. Light/dark and system appearance are supported. User appearance overrides apply last.

Sidebar hover and selection intentionally share the same colors in both modes.
Their package-owned fills use OKLCH lightness 0.90 in light mode and 0.36 in
dark mode, matching the collection's interaction contrast while retaining the
neutral palette. OpenAgent's Style contrast setting scales these fills last.
The independent `--sidebar-selected` and `--sidebar-selected-foreground` tokens
reference `--sidebar-accent` and `--sidebar-accent-foreground`, respectively.

Requires the OpenAgent theme-fonts-v1 capability. This is a Svelte/Bits UI adaptation of the upstream visual grammar; React component libraries and icon libraries are not switched by a theme. Fonts and licenses are bundled in this plugin under fonts/ and work offline; CJK glyphs use system fallbacks.

recipe.json records every independent mix option. provenance.json pins the MIT-licensed shadcn source. This package contains no scripts, remote fonts, or executable stylesheets.

Publish plugin.json, recipe.json, provenance.json, fonts/, LICENSE, and this README as a GitHub release archive; keep the manifest repository and version aligned with the release.
