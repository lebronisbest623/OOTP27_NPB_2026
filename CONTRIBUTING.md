# Contributing

[한국어](./CONTRIBUTING.ko.md)

Thank you for your interest in contributing to The World Mod.

## Ways to Contribute

### 1. Submit Issues

Use GitHub Issues if you want to report:

- incorrect player data
- missing players
- logo or uniform problems
- ballpark issues
- FaceGen issues
- installation problems
- feature requests

No coding is required. Clear screenshots, file names, and short explanations are always helpful.

### 2. Pull Requests

Pull requests are welcome for quickstart fixes, resource improvements, and documentation updates.

#### Option A: Web Upload

1. Fork the repository on GitHub.
2. Open your fork and go to the folder you want to update.
3. Click `Add file` -> `Upload files`.
4. Upload your files.
5. Commit the changes.
6. Click `Contribute` -> `Open pull request`.
7. Submit your pull request with a short explanation.

#### Option B: Using Git

##### Step 1: Fork the Repository

Fork the repository from the GitHub page.

##### Step 2: Clone Your Fork

```bash
git clone https://github.com/YOUR_USERNAME/the-world-mod.git
cd the-world-mod
```

##### Step 3: Add Your Changes

Please place files in the appropriate location:

| Content | Folder |
|---------|--------|
| Quickstart files | `THE_WORLD_MOD.quick/` |
| Uniforms | `the-world-mod/uniform/` |
| Logos | `the-world-mod/logos/` |
| FaceGen | `the-world-mod/fg_files/` |
| Ballparks | `the-world-mod/ballparks/` |
| Documentation | repository root |

##### Step 4: Commit and Push

```bash
git add .
git commit -m "Describe your contribution"
git push
```

##### Step 5: Open a Pull Request

1. Go to your fork on GitHub.
2. Click `Contribute` -> `Open pull request`.
3. Explain what you changed and why.
4. Submit the pull request.

## Guidelines

- Keep file names consistent with the existing release structure.
- Do not rename folders unless there is a clear reason.
- If you update a licensed or credited asset, include the source and permission context when possible.
- If you change player data or visual assets, mention exactly which teams or players were affected.

## Questions?

Open an issue if you are unsure where a contribution belongs.
