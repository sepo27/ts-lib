## Flow

### 1) Clone

Clone without history (top commit only):

```bash
git clone git@github.com:sepo27/ts-lib.git <lib-name> --depth 1
```

### 2) Update remote url

```bash
git remote set-url origin <LIB_REPO_URL>
```

### 3) Update package.json

- name
- version
- description
- repository
- author
- (?) license
- bugs, homepage

### 4) Update README

### 5) Update all packages (optional)

_(i) Install npm-check first (if not so far)_

```bash
npm install -g npm-check
```

Update pakages

```bash
npm-check -y
```

### 6) Initial commit

```bash
git add --all && git commit --amend -am "<Init commit message>"
```

### 7) Push

```bash
git push -u origin/master
```
