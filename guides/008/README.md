## Logging
All Log
```js
git log
```
Spesifik Files
```js
git log -- <file>
```

Example Output:
```js
commit 9f7a734f129d9b7a0c5fcba2b51aa8a5b4c4de57 (HEAD -> master)
Author: dikanappoleonz <dikaadityaputra2@gmail.com>
Date:   Mon Sep 2 09:27:52 2024 +0700

    create new file
```

Visual Logging:
```js
git log --all --decorate --oneline --graph
```
Create Alias Command:
```js
alias graph="git log --all --decorate --oneline --graph"
```

Example Output:
```js
* 2e2f48c (HEAD -> fatina) <message>
| * 8b8cce9 (dika) <message>
|/
* a294154 (master) <message>
```