# jekyll-portfolio: Source Repo
A test repo for trying out Jekyll SSG.

This is intended for building and testing a Jekyll workflow with deployment. This is the **source** repository.

An automated deployment process must be set up.

The `_site` folder is the *source folder* for deployment files. On build, these files will be updated. A Github action or other process is needed to push these files on build to a separate repository: the **production** repo. The production repo will be publicly accessible. The source repository will be private.