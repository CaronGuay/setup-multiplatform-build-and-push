# setup-multiplatform-build-and-push

git tag -d v3
git push --delete origin v3

git tag -a -m 'first' v3
git push --follow-tags
