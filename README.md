### สร้าง Branch

> `git checkout -b <branch-name>`

### Merge มายัง Branch ปัจจุบัน

> `git merge <branch-name>`

### ลบ Branch ออกจาก Local repository

> `git branch -d <branch-name>`

### ลบ Branch ออกจาก Remote repository

> `git push origin :<branch-name>`

### รวม 2 Commit ล่าสุดเข้าด้วยกัน

> `git reset --soft HEAD^`
> `git commit --amend`