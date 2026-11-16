# WozterDev 1.2.1

This release improves project setup and everyday local development across PHP, JavaScript, Python, and CMS projects.

## Project workflows

- Open a terminal in each project's folder with its active PHP, Node.js, or Python runtime available.
- Install npm dependencies during project creation when an npm-based project needs them, including Laravel frontend packages when Node.js is enabled. Existing installations are reused; projects declaring Yarn, pnpm, or Bun are not forced to use npm.
- Create Python projects in a project-local `.venv`, install packages from `requirements.txt`, and update them from the same manifest. Django projects now include `requirements.txt` too.
- Update dependencies with the package manager selected by each project's manifests and lock files: Composer, npm, Yarn, pnpm, pip, Poetry, uv, or Pipenv. WordPress and Joomla open their built-in updater pages.
- Run project sites with the runtime selected in the active environment.

## Interface and services

- Show framework logos in project lists and project creation choices, plus service logos in the service catalog.
- Replace project action labels with clear icons and hover descriptions.
- Start WozterDev maximized and restore it maximized from the notification area.
- Restart active managed web, database, and cache services for real, then report their resulting status.

## Downloads

- Windows x64: MSI installer
- Linux x64 and ARM64: `.tar.gz` application packages
- macOS Intel and Apple Silicon: `.zip` app bundles
- `SHA256SUMS.txt`: checksums for the five application packages

The attached files are prebuilt application packages and contain no WozterDev project source code. GitHub automatically displays source-archive links for release tags; the `v1.2.1` tag points to an empty snapshot, so those archives contain no files. The macOS app remains unsigned and may require approval in Privacy & Security on first launch. Linux and macOS users install project runtimes separately.
