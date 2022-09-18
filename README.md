<p align="center">
  <img height="100" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/latex/latex.png" alt="" />
  <img height="100" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/python/python.png" alt="" />
  <img height="100" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/tensorflow/tensorflow.png" alt="" />
  <img height="100" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/docker/docker.png" alt="" />
</p>

<p align="center">
  <img height="400" src="report/_INCLUDES/main/4/x_train.png" alt="" />
</p>

Menu:

- [Task](#task)
- [How to run app](#how-to-run-app)
- [Application stack](#application-stack)
- [Project tree](#project-tree)

## Task

Write coursework.

## How to run app

```bash
make tex # tex to pdf
```

## Application stack

- [vs code][vs_code]
- [sumatra PDF][sumatra_pdf]
- [vs code PDF][vs_code_pdf]
- [vs code matherial icon theme][vs_code_material_icon_theme]
- [docker-compose][docker]
- [make][make]
- visual studio
- python
- python tensorflow

## Project tree

```bash
sudo apt install tree
tree --charset ascii -a -I ".git|docker|*.drawio.bkp|*.drawio.dtmp|*.pdf" > README.tree.txt
```

[View project tree](README.tree.txt)

<!-- = = = = = = = = = = = = = = = = -->

[vs_code]: https://code.visualstudio.com/#alt-downloads
[sumatra_pdf]: https://www.sumatrapdfreader.org/free-pdf-reader
[vs_code_pdf]: https://marketplace.visualstudio.com/items?itemName=tomoki1207.pdf
[vs_code_material_icon_theme]: https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme
[docker]: https://www.docker.com/get-started/
[make]: https://stackoverflow.com/questions/32127524/how-to-install-and-use-make-in-windows#comments-32127632
