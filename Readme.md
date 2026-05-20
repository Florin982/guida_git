
## Mostra  i branch locali (*  = corrente )

```git branch```

## Crea un nuovo branch

```git branch feature/login   ``` 

## Crea e mi sposta in branch

```git switch -c feature/login   ``` 

## Torna al branch precedente

```git switch -   ``` 

## push in branch che ho crato in locale 
``` git push --set-upstream origin feature/login  ```

## Rinomina il branch corrente
git branch -m nuovo-nome 

git push origin HEAD:feature/login

##
git log 

``` (venv) flo@florincernat:~/python_projects/guida_git$ git log
commit e723e5aec6806d4f3bb25cf240429a170887a95b (HEAD -> nuovo-nome, origin/feature/login)
Author: Florin-Cernat <florin.cernat.82@gmail.com>
Date:   Wed May 20 11:20:07 2026 +0200

    sec commit

commit 0fdae31308dfff29503880189feedb53b54179de
Author: Florin-Cernat <florin.cernat.82@gmail.com>
Date:   Wed May 20 11:17:33 2026 +0200

    commit in login

commit 4415c24602db2674f74a5390398c173db198241e (origin/main, main)
Author: Florin-Cernat <florin.cernat.82@gmail.com>
Date:   Wed May 20 11:04:19 2026 +0200

    primo commit
(venv) flo@florincernat:~/python_projects/guida_git$ git status
On branch nuovo-nome
Your branch is up to date with 'origin/feature/login'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   Readme.md ```

     