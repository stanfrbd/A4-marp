# A4-marp

[Marp](https://marp.app/) CSS theme to do A4 presentations. Dark Mode, using Uncover Theme from Marp, and Atom One Dark Theme for code highlighting. 

The folder `.vscode` and the Marp plugin are mandaory to make it work.

Assuming VS Code and [Marp for VS Code](https://github.com/marp-team/marp-vscode) are already installed:

- Clone this project
- Open this entire folder in VS Code
- Start writing your `.md` file using

You need to have the folder `.vscode` + `settings.json`

### My custom script to create a quick note ~ to add in `~/.bashrc` or `~/.zshrc`

```sh
function notes() {
        mkdir "$1" && cd "$1" && mkdir .vscode
        wget -q "https://raw.githubusercontent.com/stanfrbd/A4-marp/main/.vscode/settings.json"
        mv settings.json .vscode
        echo "---" >> "$1".md
        echo "marp: true" >> "$1".md
        echo "theme: a4-dark" >> "$1".md
        echo "paginate: true" >> "$1".md
        echo "---" >> "$1".md
        echo "" >> "$1".md
        date=$(date)
        echo "<!-- $date -->" >> "$1".md
        echo "" >> "$1".md
        echo "# $1" >> "$1".md
        wget -q "https://raw.githubusercontent.com/stanfrbd/A4-marp/main/a4-light.css"
        wget -q "https://raw.githubusercontent.com/stanfrbd/A4-marp/main/a4-dark.css"
        wget -q "https://raw.githubusercontent.com/stanfrbd/A4-marp/main/atom-one-dark.css"
        code .
}
```
> Usage: `notes <project_name>`
> 
> This will a create a foler `<project_name>` containing a file `<project_name>.md` with the date inside. \
> This will also create the folder `<project_name>/.vscode` and the custom A4 themes from this repo.

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

## Printing - gain of ink

> Use the light theme and change this in your `a4-light.css`

```css
pre {
    border-radius: .4em;
    padding: 0.2em 0.5em;
    line-height: 1.15;
    overflow-x: auto;
    /* background-color: #202228; */
    padding: 0.6em;
    word-break: break-all;
    white-space: pre-wrap !important;
    font-size: 94%;
    border-style: solid;
    border-width: 1px;
}

code {
    font-family: Consolas, "Liberation Mono", Menlo, Courier, monospace;
    /* color: #abb2bf; */
    color: black;
    overflow-x: auto;
}
```

![image](https://user-images.githubusercontent.com/44167150/127450871-21ef653f-e0bc-4554-b8de-8004a11c2b1a.png)

# Newest one

In your `.vscode/settings.json`  

```json
{
    "markdown.marp.themes": [
      "https://raw.githubusercontent.com/stanfrbd/A4-marp/refs/heads/main/a4-clean.css"
    ]
}
```

and then at the top of the MD file:  

```markdown
---
marp: true
theme: a4-clean
paginate: true
---
```
