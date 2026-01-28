# Sopra FS26 - Tutorial 1

**Render `.qmd` file:**

```{bash}
quarto render tutorial_1.qmd --to pdf
```

to render to a specific format (pdf and html are supported)

```{bash}
quarto render tutorial_1.qmd
```

to render to all formats


**Live preview:**

```{bash}
quarto preview tutorial_1.qmd
```

---

All images are stored in the `assets` folder.

**Callout blocks**

- can create with fenced quarto divs: `:::{.callout-note icon=false appearance=minimal collapse="true" title="Setup ssh key"}`
- supported types: `note`, `tip`, `caution`, `warning`, `important`
- `icon=false` to remove the icon
- `appearance` can be `default`, `simple`, `minimal`
- `collapse="true"` to collapse the block by default, `collapse="false"` to show it by default - but collapsible
