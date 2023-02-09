# Code Release
This template will also create puppet code release repository under the same module with a separate branch called release. 
This release branch contains github workflow and the release.txt

## GitHUb workflow
.github/workflow/release_manager.yaml

### release.txt
dev: tag/branch<br />
test: tag/branch<br />
stage: tag/branch<br />
prod: tag/branch<br />

Note: This release branch should not be merged into **main** branch

Thanks 
