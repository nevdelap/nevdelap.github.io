# How to update this repository

## Update the profile README

Edit `README.md` to change the profile links, quote, or pinned repository list. Keep the repository list in sync with the pinned repositories shown on [GitHub](https://github.com/nevdelap).

## Save and push your changes

From the repository directory, edit the files and use Jujutsu to describe and push the change:

```sh
jj status
jj describe -m "Update profile README"
jj bookmark set main -r @
jj git push --bookmark main
```

This repository currently contains the README and this guide, but no website source or publishing configuration. Changes pushed here update the GitHub repository; publishing changes to [nevdelap.com](https://nevdelap.com) depends on its separate setup.
