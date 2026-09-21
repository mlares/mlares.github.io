# Friendlier personal site — review proposal

Branch: `proposal/friendlier-personal-site`

## Proposed visitor journey

1. **Home:** a personal greeting and existing portrait, with Explore my work and Get in touch as the main actions.
2. **Selected work:** three short introductions to recommendation systems, TOROS, and Corral, each with a simple workflow diagram and a direct link into the existing project page.
3. **Try something:** a featured bias–variance experiment and a link to the full lab.
4. **Background:** a brief connection between astronomy, applied machine learning, and teaching.
5. **Contact:** email and a meeting link, with the AI assistant explicitly identified as an assistant.

Primary navigation: **About · Projects · Lab · Writing · Contact**. The site name links home. About and the footer expose CV, Research, Teaching, and Outreach. Existing routes remain available.

## Pages to review

- `/`: hierarchy, voice, portrait, project summaries, and balance between work and personal background.
- `/about/`: proposed biography, assembled from existing site content.
- `/contact/`: personal contact choices and assistant labeling.
- `/projects/#recommendations`, `/projects/#toros`, `/projects/#corral`: direct case-study links.

The homepage uses the existing portrait at its native size, the existing teal palette, and responsive layouts. Workflow diagrams describe processes; they are not measured results or project screenshots. The detailed CV remains available at `/cv/`.

## Preview

On Ubuntu/Linux Mint, install the native build prerequisites once:

```sh
sudo apt-get install ruby-dev build-essential
```

From this repository, install gems locally (no sudo for Bundler) and start the preview:

```sh
bundle config set --local path vendor/bundle
bundle install
bundle exec jekyll serve --host 127.0.0.1
```

Open `http://127.0.0.1:4000/` and review the pages above at desktop and phone widths.

## Validation

- Full stylesheet compiled successfully with the existing Ruby Sass theme pipeline.
- Navigation and changed page front matter parsed successfully; homepage links and case-study anchors checked against local source.
- `git diff --check` passed.
- Full Jekyll 4.4.1 build passed after installing dependencies into `vendor/bundle`.
- Local preview returned HTTP 200 for Home, About, Contact, Projects, the bias–variance lab, and the compiled stylesheet; homepage content matched the proposal.
- Visual browser review remains pending. The legacy theme emits non-blocking Sass deprecation warnings.

This is a local branch proposal; it has not been deployed.
