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

![image](https://user-images.githubusercontent.com/44167150/115675689-1d0bf980-a34f-11eb-9b5c-62edb86d8e76.png)
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

![image](https://user-images.githubusercontent.com/44167150/115676092-88ee6200-a34f-11eb-8089-f640560d627d.png)
![image](https://user-images.githubusercontent.com/44167150/113009486-46829c80-9178-11eb-9f69-2a5e6bb2b0da.png)

