# Maintainer guide — publishing and updating the course

[Course home](README.md) · [Roadmap](ROADMAP.md)

## Initial GitHub publication

1. Sign into the intended GitHub account and create `Thinking-in-Physical-AI` at https://github.com/new. Public is recommended if the owner is ready for people to view the shell; private is reasonable while reviewing it. Initialize with a README. Do not select a license until the owner decides.
2. Download GitHub Desktop from https://desktop.github.com/ and sign in. File → Clone Repository; select the new repository and a local path.
3. Extract the starter ZIP into a temporary location. Copy the **contents** of its `Thinking-in-Physical-AI` folder into the cloned repository root. Replace the initial README when prompted. Do not overwrite or remove the clone's `.git` directory, and do not nest the entire extracted folder inside the repository.
4. In GitHub Desktop, review changed files, commit to the default branch with `Initialize Thinking in Physical AI course shell (v0.1.0)`, and choose Push origin. Verify README and links on GitHub. If branch rules require a pull request, use a new branch and merge after review.
5. Optional: in GitHub Releases, create a `v0.1.0` tag and pre-release, making clear that the course is a shell. Add relevant repository topics and pin it to the profile if desired.

Official setup references: [repository quickstart](https://docs.github.com/en/repositories/creating-and-managing-repositories/quickstart-for-repositories), [GitHub Desktop cloning](https://docs.github.com/en/desktop/adding-and-cloning-repositories/cloning-and-forking-repositories-from-github-desktop), [committing and reviewing](https://docs.github.com/en/desktop/making-changes-in-a-branch/committing-and-reviewing-changes-to-your-project-in-github-desktop).

## Ongoing development

Start with [Module 01](course/01-think-about-physical-ai/01-physical-thinking/README.md). Open an issue for each module's implementation. Edit the existing lesson/lab/assignment/assessment files, add needed assets, follow the [authoring guide](templates/module-authoring-guide.md), and commit reviewed changes. Update module and roadmap statuses and changelog together. Use pull requests if collaborators review work.

Keep the Markdown repository as the source of truth. A separate GitHub Pages learning site is an optional later improvement; a Pages site, build pipeline and theme are not configured in this shell. Do not turn on an untested site configuration as if it were ready.
