# git-rebase

## Step by step guide

1. In the main branch make two commits as M1 and M2.

![first-two](https://user-images.githubusercontent.com/52546856/215845482-1eff867d-c15e-4faa-aa06-d9a4bc55b89e.png)

2. Checkout to new feature branch named as "feature". Here make another two commits as F1 and F2.

![feature](https://user-images.githubusercontent.com/52546856/215843104-c0db3a8d-53d8-454c-adfc-e232c29e7b9e.png)

3. Again checkout to the main branch and make another commit as M3.

![master](https://user-images.githubusercontent.com/52546856/215842929-81805047-6a2e-42b5-92d5-8054ee06fbf9.png)


4. Now checkout to the feature branch. Now the base of the main branch is M3. but feature branch does not have that commit. Because I make the branch when main branch base at the M2.

5. Now I'm going to rebase the feature branch with main. First make sure you are in the feature branch. (```git branch```)
```git rebase main```

![rebase](https://user-images.githubusercontent.com/52546856/215845571-86d61318-bc73-498e-80a9-faa05560446b.png)

6. Now see the git history. commit history shows as follows.


### This proccess known as the git rebase.

### Readings - [Git rebase](https://senali.hashnode.dev/git-rebase)
