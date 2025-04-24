# Delete a Git Branch Locally

>> git branch -d dev
>> git branch -d test

# Delete a Git Branch Remotely
>> git push origin :dev
>> git push origin :test

# How to checkout another branch without commit changes 
- Temporarily store your changes:
>> git stash
- Then switch branches:
>> git checkout other-branch
- And re-apply your changes:
>> git stash pop

# how to list tags.
>> git tag 
- v1.7

# how to delete tag locally and remotely:
- delete tag locally
>> git tag -d v1.7
- delete tag remotely
>> git push origin --delete v1.7

![GitHub Logo](https://www.shutterstock.com/shutterstock/photos/2492842415/display_1500/stock-photo-blond-hair-girl-taking-photo-with-camera-in-wheat-field-2492842415.jpg)