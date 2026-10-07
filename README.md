# SAGE-Bench

**Scene-graph Assessment &amp; Generation Evaluation** — documentation site for
the [InternScenes](https://github.com/DobricLilujun/InternScenes2isaacsim)
scene-graph benchmark library.

🌐 **Live docs:** https://dobriclilujun.github.io/SAGE-Bench

The files at the repository root are the **built, static site** (served by
GitHub Pages). The `source/` folder holds the Markdown sources, the
dependency-free builder (`build.py`), the CSS theme, the Lunr.js search, and
the logo — so the site can be regenerated from scratch:

```sh
python source/build.py        # rebuilds the site into source/output/
```

The scene-graph library itself lives in
[InternScenes2isaacsim](https://github.com/DobricLilujun/InternScenes2isaacsim)
under `src/internscenes/` (modules: `scene_graph`, `relations`, `coordinate`,
`vlm_annotate`, `evaluate_graph`, `render_multi`).
