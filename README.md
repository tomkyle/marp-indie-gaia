# Indie Gaia Marp Theme


### Original Gaia Theme 
Original Gaia theme on GitHub:

https://github.com/marp-team/marp-core/blob/main/themes/gaia.scss

Source Code:

https://raw.githubusercontent.com/marp-team/marp-core/refs/heads/main/themes/gaia.scss

## Usage

### The easy way (with VS Code)

https://yoanbernabeu.github.io/MARP-Template-Library/docs/intro

The easiest and fastest solution is to use the [Marp for VS Code](https://marketplace.visualstudio.com/items?itemName=marp-team.marp-vscode) extension.

1. Find your theme in our library ([Dracula](https://yoanbernabeu.github.io/MARP-Template-Library/docs/themes/dracula) for example).
2. Copy the url of the CSS file.
3. Add a `.vscode/settings.json` file in your project.
4. Add the following line in your `.vscode/settings.json` file (replace the `Dracula url` with your theme url):

```json
{
    "markdown.marp.themes": [
        "https://raw.githubusercontent.com/dracula/marp/master/dracula/dracula.css"
    ]
}
```



## Development Notes

Add Git subtree:

```shell
$ git subtree add --prefix=themes git@github.com:marp-team/marp-core.git main --squash
```

Update subtree:

```shell
$ git subtree pull --prefix=themes git@github.com:marp-team/marp-core.git main --squash
```

