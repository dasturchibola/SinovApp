2017-12-26T08:51:38.068Z - info: [ui] [AppStore] loading 4 repositories from store
2017-12-26T08:51:38.071Z - info: [ui] [AppStore] found account: azumukupoe (Takumi)
2017-12-26T08:51:40.492Z - info: [ui] launching: 1.0.11 (Windows 10.0.17063)
2017-12-26T08:51:40.921Z - info: [ui] Executing getRecentBranches: git log -g --no-abbrev-commit --pretty=oneline HEAD -n 2500 -- (took 2.548s)
2017-12-26T08:51:41.065Z - info: [ui] Executing getBranches: git for-each-ref --format=%(refname)%00%(refname:short)%00%(upstream:short)%00%(objectname)%00%(author)%00%(parent)%00%(symref)%00%(subject)%00%(body)%00%1F refs/heads refs/remotes (took 2.695s)
2017-12-26T08:51:41.713Z - info: [ui] Stats reported.
2017-12-26T08:51:42.363Z - info: [ui] Executing installGlobalLFSFilter: git lfs install --skip-repo (took 3.329s)
2017-12-26T08:51:42.547Z - info: [ui] Executing getStatus: git status --untracked-files=all --branch --porcelain=2 -z (took 4.479s)
2017-12-26T08:51:55.168Z - info: [ui] Executing fetch: git -c credential.helper= fetch --progress --prune origin (took 2.120s)
2017-12-26T08:51:55.171Z - error: [ui] `git -c credential.helper= fetch --progress --prune origin` exited with an unexpected code: 128.
fatal: unable to access 'https://github.com/azumukupoe/FastHub.git/': SSL certificate problem: unable to get local issuer certificate

2017-12-26T08:51:55.932Z - error: [ui] `git -c credential.helper= fetch --progress --prune upstream` exited with an unexpected code: 128.
fatal: unable to access 'https://github.com/k0shk0sh/FastHub.git/': SSL certificate problem: unable to get local issuer certificate

2017-12-26T08:57:07.876Z - error: [ui] `git -c credential.helper= fetch --progress --prune origin` exited with an unexpected code: 128.
fatal: unable to access 'https://github.com/azumukupoe/FastHub.git/': SSL certificate problem: unable to get local issuer certificate

2017-12-26T08:57:08.635Z - error: [ui] `git -c credential.helper= fetch --progress --prune upstream` exited with an unexpected code: 128.
fatal: unable to access 'https://github.com/k0shk0sh/FastHub.git/': SSL certificate problem: unable to get local issuer certificate

2017-12-26T09:02:20.565Z - error: [ui] `git -c credential.helper= fetch --progress --prune origin` exited with an unexpected code: 128.
fatal: unable to access 'https://github.com/azumukupoe/FastHub.git/': SSL certificate problem: unable to get local issuer certificate

2017-12-26T09:02:21.277Z - error: [ui] `git -c credential.helper= fetch --progress --prune upstream` exited with an unexpected code: 128.
fatal: unable to access 'https://github.com/k0shk0sh/FastHub.git/': SSL certificate problem: unable to get local issuer certificate

2017-12-26T09:07:33.236Z - error: [ui] `git -c credential.helper= fetch --progress --prune origin` exited with an unexpected code: 128.
fatal: unable to access 'https://github.com/azumukupoe/FastHub.git/': SSL certificate problem: unable to get local issuer certificate

2017-12-26T09:07:33.962Z - error: [ui] `git -c credential.helper= fetch --progress --prune upstream` exited with an unexpected code: 128.
fatal: unable to access 'https://github.com/k0shk0sh/FastHub.git/': SSL certificate problem: unable to get local issuer certificate

2017-12-26T09:08:57.597Z - info: [main] opening in browser: https://desktop.github.com/release-notes/
2017-12-26T09:09:52.017Z - info: [ui] [AppStore.getAccountForRemoteURL] account found for remote: https://github.com/azumukupoe/chromiumUpdater.git - azumukupoe (has token)
2017-12-26T09:09:53.261Z - info: [ui] Executing clone: git -c credential.helper= clone --recursive --progress -- https://github.com/azumukupoe/chromiumUpdater.git C:\Users\azumu\Documents\GitHub\chromiumUpdater (took 1.240s)
2017-12-26T09:09:53.262Z - error: [ui] `git -c credential.helper= clone --recursive --progress -- https://github.com/azumukupoe/chromiumUpdater.git C:\Users\azumu\Documents\GitHub\chromiumUpdater` exited with an unexpected code: 128.
Cloning into 'C:\Users\azumu\Documents\GitHub\chromiumUpdater'...
fatal: unable to access 'https://github.com/azumukupoe/chromiumUpdater.git/': SSL certificate problem: unable to get local issuer certificate

2017-12-26T09:12:20.699Z - info: [ui] [AppStore.getAccountForRemoteURL] account found for remote: https://github.com/azumukupoe/desktop.git - azumukupoe (has token)
2017-12-26T09:12:21.751Z - info: [ui] Executing clone: git -c credential.helper= clone --recursive --progress -- https://github.com/azumukupoe/desktop.git C:\Users\azumu\Documents\GitHub\desktop (took 1.049s)
2017-12-26T09:12:21.752Z - error: [ui] `git -c credential.helper= clone --recursive --progress -- https://github.com/azumukupoe/desktop.git C:\Users\azumu\Documents\GitHub\desktop` exited with an unexpected code: 128.
Cloning into 'C:\Users\azumu\Documents\GitHub\desktop'...
fatal: unable to access 'https://github.com/azumukupoe/desktop.git/': SSL certificate problem: unable to get local issuer certificate

