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

![GitHub Logo](https://github.com/images/logo.png)