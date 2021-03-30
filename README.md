# A4-marp

[Marp](https://marp.app/) CSS theme to do A4 presentations. Dark Mode, using Uncover Theme from Marp, and Atom One Dark Theme for code highlighting. 

The folder `.vscode` and the Marp plugin are mandaory to make it work.

Assuming VS Code and [Marp for VS Code](https://github.com/marp-team/marp-vscode) are already installed:

- Clone this project
- Open this entire folder in VS Code
- Start writing your `.md` file using 

## Dark theme

Put

```markdown
---
marp: true
theme: a4-dark
paginate: true
---
```

at the beginning of the `.md` file.

![image](https://user-images.githubusercontent.com/44167150/112986262-9013bd00-9161-11eb-9b3b-67be80e6e774.png)
![image](https://user-images.githubusercontent.com/44167150/112986440-c94c2d00-9161-11eb-9e81-2db88df794f2.png)



## Light theme

Put

```markdown
---
marp: true
theme: a4-light
paginate: true
---
```

at the beginning of the `.md` file.

![image](https://user-images.githubusercontent.com/44167150/112986120-65296900-9161-11eb-94ac-098876508ecc.png)
![image](https://user-images.githubusercontent.com/44167150/112986598-f8fb3500-9161-11eb-8738-13cfe5584f1f.png)
