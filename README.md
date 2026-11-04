# siteeditor-build

Release-Binaries von `siteeditor-build` — dem Headless-Builder von siteeditor.

Dieses Repo enthält **nur Releases**, keinen Quelltext. Die GitHub-Pages-Workflows,
die siteeditor in App-Repos erzeugt (`.github/workflows/siteeditor-pages.yml`),
laden das Binary von hier:

`https://github.com/robert-boulanger/siteeditor-build/releases/download/v<version>/siteeditor-build-x86_64-unknown-linux-musl.tar.gz`

Zu jedem Asset gibt es eine `.sha256`-Datei.
