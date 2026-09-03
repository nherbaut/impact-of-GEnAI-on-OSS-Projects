# PDF mirror

Logical feed: impact of GEnAI on OSS Projects

Each workflow leaf state is represented by a directory path in the repository.
Managed PDF files use the pattern `paper-<id>--<name>.pdf`.
Managed notes files use the pattern `paper-<id>--<name>.md`.
Managed review submissions are exported under `reviews/review-<id>--<title>/paper-<id>--<title>.json`.
Managed notes files start with generated `paper-monitor/paper/v1` YAML front matter.
The front matter is read-only and regenerated from Paper Monitor metadata.
Editing the Markdown body below the front matter updates the paper notes in the application.
Moving a managed PDF between state directories changes the paper state.
Moving a managed notes file between state directories changes the paper state.
Committing a single new PDF with a DOI in the commit message creates a new paper.
