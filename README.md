# svn
A simple Docker container with subversion CLI. This container can be used to pull folders from GitHub.

## Example

Command:
    docker container run --rm -it -v $(pwd)/out:/wd bhgedigital/svn sh -c "svn checkout https://github.com/lodash/lodash/trunk/ /wd"

Outcome:
    The master branch from repo lodash/lodash in github.com is copied to folder $(pwd)/out


