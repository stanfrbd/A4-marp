# A4-marp

[Marp](https://marp.app/) CSS theme to do A4 presentations. Dark Mode, using Uncover Theme from Marp, and Atom One Dark Theme for code highlighting. 

The folder `.vscode` and the Marp plugin are mandaory to make it work.

Assuming VS Code and [Marp for VS Code](https://github.com/marp-team/marp-vscode) are already installed:

- Clone this project
- Open this entire folder in VS Code
- Start writing your `.md` file using

You need to have the folder `.vscode` + `settings.json`

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

![image](https://user-images.githubusercontent.com/44167150/122885011-f82c0680-d33e-11eb-906d-a491db84a852.png)
![image](https://user-images.githubusercontent.com/44167150/122885154-1abe1f80-d33f-11eb-8b36-4d9f9e529c08.png)



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

![image](https://user-images.githubusercontent.com/44167150/122885276-3a554800-d33f-11eb-8a3c-f89b563f4e60.png)
![image](https://user-images.githubusercontent.com/44167150/122885346-4b05be00-d33f-11eb-9e89-619c4dda125e.png)

