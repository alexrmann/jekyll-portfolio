# jekyll-portfolio: Source Repo
A test repo for building a Jekyll portfolio and deployment workflow.

This is intended for building and testing a Jekyll workflow with deployment. This is the ***source*** repository.

An automated deployment process must be set up.

The `_site` folder is the *source folder* for deployment files. On build, these files will be updated. Then, a deployment process (e.g., Github action, Linux pipeline, etc.) will automatically push these files to a separate repository: the ***production*** repo. The production repo will be publicly accessible. The source repository will be private.
