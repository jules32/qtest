
Clone jules32/qtest repo

```
quarto create-project mybook --type book
quarto serve mybook

```

Realize I want qtest as a book, not with a `mybook` subdirectory (move by hand)

```
quarto serve qtest
```

Works perfectly

add .md and .ipynb to _quarto.yml

auto-serves