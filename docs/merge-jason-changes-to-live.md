## Merge Jason's changes to live

### Follow the steps below to merge the Jason's changes from test to live environment

1. Create a new branch from master
2. Compare and download changes from test server through [SFTP on vscode](https://marketplace.visualstudio.com/items?itemName=liximomo.sftp)
3. Verify and commit the changes in the new branch
4. Merge the branch to test
5. On server after the branch is merged on test revert the changes
6. Merge to branch to master
7. Take pull on server on both test and live environment so that both environment has the files updated via git
