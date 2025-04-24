# Delete a Git Branch Locally

>> git branch -d dev
>> git branch -d test

# Delete a Git Branch Remotely
>> git push origin :dev
>> git push origin :test

# How to checkout another branch without commit changes 
Temporarily store your changes:
>> git stash
Then switch branches:
>> git checkout other-branch
And re-apply your changes:
>> git stash pop