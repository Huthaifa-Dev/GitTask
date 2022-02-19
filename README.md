# GitTask
Git task 


- create local repo
- Create 3 files [ `a.txt`, `b.text`, `c.text` ].
- Ignore `c.txt`.
- Commit the new files.
- Change on `a.txt`
    - git status
    - Commit your changes (make sure to have a clear commit message (best practice).
- Change on `b.txt`
    - git status
    - Commit
- Create two new branches from `master`
    - `updateRight`: Change something on `a.txt`, add a new file `d.txt`
    - `updateLeft`: Change something on `a.txt`, add a new file `anything.txt`
- Create a new branch from `master`, call it `mergeBranches`
    - Merge `updateRight` to the new `mergeBranches` branch.
    - Merge `updateLeft` to the new `mergeBranches` branch.
    - Got conflicts? fix them 😀
- Push your local repository to GitHub.
- Create a new merge request from `mergebranch` to `master`.
    - Merge it.
