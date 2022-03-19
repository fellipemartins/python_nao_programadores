
# MyST cheatsheet

[MyST syntax lecture](myst_cheatsheet)


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