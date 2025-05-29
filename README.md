# gtools - simple github tools

Some simple scripts to help with github.

ginit - initiate project. Defaults to public if not --private. Repo must not exist on github. Make sure to delete .git directory in local directory before running. `-z` flag defaults to nothing for description and tags.

gup - update current project.

gupall - updates all projects in current directory. Wont consider repo with submods but updates all the same, so be careful if main repo is out of sync with submods.
