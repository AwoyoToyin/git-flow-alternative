## An alternative to GitFlow

1. Create a branch from the master (feature-x), which is where the feature will be developed:
`git checkout -b feature-x`

2. Push the branch to the remote:
`git push -u origin feature-x`
With the branch in the remote repo, a pull request should be opened with it. A pull request is where all modifications are available to other members and they will be able to review it
