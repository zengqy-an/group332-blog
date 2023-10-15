---
title: Hello World
tags: hello world
categories: hello world

---
Welcome to [Hexo](https://hexo.io/)! This is your very first post. Check [documentation](https://hexo.io/docs/) for more info. If you get any problems when using Hexo, you can find the answer in [troubleshooting](https://hexo.io/docs/troubleshooting.html) or you can ask me on [GitHub](https://github.com/hexojs/hexo/issues).

## Quick Start

This is my fisrt post.

### Create a new folder

```bash
$ mkdir blog-source
$ cd blog-source
$ hexo init  # 初始化仓库
$ tree -L 1  # 查看结构(brew install tree)
```


### Create a new post

``` bash
$ hexo new "My New Post"
```

More info: [Writing](https://hexo.io/docs/writing.html)

### Run server

``` bash
$ hexo server
```

More info: [Server](https://hexo.io/docs/server.html)

### Generate static files

``` bash
$ hexo generate
```

More info: [Generating](https://hexo.io/docs/generating.html)

### Deploy to remote sites

``` bash
$ hexo deploy
```

More info: [Deployment](https://hexo.io/docs/one-command-deployment.html)

## Details

### Mathematical formula


use following code

```bash
{% mathjax %} 
{V = \left\lbrace v_{0}, v_{1}, …, v_{n} \right\rbrace} 
{% endmathjax %}
```
Math formulas can be displayed correctly, as follows:

{% mathjax %} 
{V = \left\lbrace v_{0}, v_{1}, …, v_{n} \right\rbrace} 
{% endmathjax %}




### Code 

```python
import numpy as np

a = np.arange(1, 1, 10)
```


