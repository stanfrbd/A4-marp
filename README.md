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

![image](https://user-images.githubusercontent.com/44167150/119787021-0ec27780-bed1-11eb-8638-f5b74cfea008.png)
![image](https://user-images.githubusercontent.com/44167150/119787121-2b5eaf80-bed1-11eb-8fcf-81439d2f1315.png)



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

![image](https://user-images.githubusercontent.com/44167150/119787209-45988d80-bed1-11eb-9aff-9c768b91537e.png)
![image](https://user-images.githubusercontent.com/44167150/119787297-5b0db780-bed1-11eb-9583-99ab09cf58d7.png)

