
# MyST cheatsheet

[MyST syntax lecture](myst_cheatsheet)

<https://jupyterbook.org/customize/config.html>


# MyST Admonitions

``` {warning} Nota:
⚠️ Este livro representa a opinião única e exclusivamente dos autores.
```

``` {tip} Nota:
⚠️ Este livro representa a opinião única e exclusivamente dos autores.
```


<div class="admonition note" name="html-admonition" style="background: lightgreen; padding: 10px">
<p class="title">This is the **title** Título!</p>
This is the *content*
</div>

<div class="admonition">
<p>Some **content**</p>
  <div class="admonition tip">
  <div class="title">Dica</div>
  <p>Paragraph 1</p>
  <p>Paragraph 2</p>
  </div>
</div>

<div class="admonition note" name="html-admonition">
<p class="title">Nota</p>
Este é o *conteúdo*
</div>

<div class="admonition warning" name="html-warning">
<p class="title">Aviso</p>
Este é o *conteúdo*
</div>

<div class="admonition tip" name="html-tip">
<p class="title">Dica</p>
Este é o *conteúdo*
</div>

<div class="admonition caution" name="html-caution">
<p class="title">Cuidado</p>
Este é o *conteúdo*
</div>

<div class="admonition attention" name="html-attention">
<p class="title">Atenção</p>
Este é o *conteúdo*
</div>


<div class="admonition danger" name="html-danger">
<p class="title">Perigo!</p>
Este é o *conteúdo*
</div>


<div class="admonition error" name="html-error">
<p class="title">Erro</p>
Este é o *conteúdo*
</div>

<div class="admonition important" name="html-important">
<p class="title">Importante</p>
Este é o *conteúdo*
</div>

<div class="admonition seealso" name="html-seealso">
<p class="title">Veja também</p>
Este é o *conteúdo*
</div>


# MyST figuras

imagem normal:

```{image} ./img/github_panel.png
:alt: Painel do GitHub
:width: 200px
:align: center
```

figuras (com referenciamento)

```{figure} ./img/github_panel.png
---
width: 200px
name: directive-fig
---
Legenda da figura!
```




# MyST table formats

```{list-table} This table title
:header-rows: 1
:name: example-table

* - Training
  - Validation
* - 0
  - 5
* - 13720
  - 2744
```



# MyST internal referencing

(myst_cheatsheet)=
# MyST Cheat Sheet

{ref}`myst_cheatsheet`
{ref}`MyST syntax lecture <myst_cheatsheet>`
[MyST syntax lecture](myst_cheatsheet)



# MyST panels

:::{panels}
:container: +full-width
:column: col-lg-4 px-2 py-2
---
:header: bg-jb-one
**Get started**
^^^

**[](start/your-first-book.md)**: a step-by-step tutorial to get started.

**[](create-a-template-book)**: get started with a simple template book.

---
:header: bg-jb-two

**Learn more**
^^^
**[](structure:index)**: Learn how to structure and organize your content.

**[](content/index.md)**: Learn how to write rich narrative content.

**[](content/executable/index.md)**: Write computational content.
---
:header: bg-jb-three

**Be inspired**
^^^
[**The Jupyter Book Gallery**](http://gallery.jupyterbook.org): A gallery of community books that have been created with Jupyter Book.

[**The QuantEcon Python Lectures**](https://python.quantecon.org/intro.html): A full mathematical textbook built with a custom Jupyter Book theme.
:::




# MyST figure / link

:::{figure-md} fig-target
:class: myclass
<img src="img/fun-fish.png" alt="fishy" class="bg-primary mb-1" width="200px">
This is a caption in **Markdown**
:::

[Go to the fish!](fig-target)