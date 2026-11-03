# Tutorial Básico de Markdown

> Arquivo criado em 06/10/2026 — Guia exemplificativo para iniciantes

Markdown é uma linguagem de marcação leve para formatar texto de forma simples e legível. É muito usada em README, documentação, GitHub, Discord, Notion, etc.

---

## 1. Títulos

Use `#` no início da linha. Quanto mais `#`, menor o nível:

```markdown
# Título nível 1
## Título nível 2
### Título nível 3
#### Título nível 4
##### Título nível 5
###### Título nível 6
```

Resultado:

# Título nível 1
## Título nível 2
### Título nível 3

---

## 2. Parágrafos e quebras de linha

Apenas escreva o texto normalmente. Para novo parágrafo, pule uma linha.

Para quebra de linha simples, termine a linha com dois espaços  
assim, ou use `<br>`.

---

## 3. Ênfase no texto

```markdown
**negrito**
*itálico*
***negrito e itálico***
~~riscado~~
==marcado== (nem todo renderizador suporta)
```

Resultado:

**negrito**
*itálico*
***negrito e itálico***
~~riscado~~

---

## 4. Listas

### Lista não ordenada

```markdown
- Item 1
- Item 2
  - Subitem 2.1
  - Subitem 2.2
* Também funciona com *
+ Também funciona com +
```

- Item 1
- Item 2
  - Subitem 2.1
  - Subitem 2.2

### Lista ordenada

```markdown
1. Primeiro
2. Segundo
3. Terceiro
```

1. Primeiro
2. Segundo
3. Terceiro

### Lista de tarefas (task list)

```markdown
- [x] Tarefa concluída
- [ ] Tarefa pendente
```

- [x] Tarefa concluída
- [ ] Tarefa pendente

---

## 5. Links

```markdown
[Texto do link](https://exemplo.com)
[Link com título](https://exemplo.com "Passe o mouse aqui")
<https://exemplo.com> - link automático
```

Resultado:

[Texto do link](https://exemplo.com)
<https://exemplo.com>

---

## 6. Imagens

```markdown
![Texto alternativo](https://via.placeholder.com/200 "Legenda opcional")
```

Exemplo:

![Logo Markdown](https://markdown-here.com/img/icon256.png "Logo Markdown")

---

## 7. Citações (Blockquote)

```markdown
> Isso é uma citação.
> Ela pode ter várias linhas.
>
> > Citação aninhada.
```

> Isso é uma citação.
> Ela pode ter várias linhas.
>
> > Citação aninhada.

---

## 8. Código

### Código inline

Use crases: `` `código` ``

Exemplo: Para instalar, use `npm install`.

### Bloco de código

Use três crases + linguagem opcional:

````markdown
```python
def ola():
    print("Olá, Markdown!")
```
````

Resultado:

```python
def ola():
    print("Olá, Markdown!")
```

```javascript
console.log("Olá, Markdown!");
```

---

## 9. Linha horizontal

Três ou mais `-`, `*` ou `_`:

```markdown
---
***
___
```

---

## 10. Tabelas

```markdown
| Nome  | Idade | Cidade      |
|-------|-------|-------------|
| Ana   | 25    | São Paulo   |
| Bruno | 30    | Rio de Janeiro |
| Carla | 28    | Belo Horizonte |
```

| Nome  | Idade | Cidade      |
|-------|-------|-------------|
| Ana   | 25    | São Paulo   |
| Bruno | 30    | Rio de Janeiro |
| Carla | 28    | Belo Horizonte |

Alinhamento:

```markdown
| Esquerda | Centro | Direita |
|:---------|:------:|--------:|
| a        | b      | c       |
```

| Esquerda | Centro | Direita |
|:---------|:------:|--------:|
| a        | b      | c       |

---

## 11. Extras úteis

### Detalhes expansíveis (GitHub)

```html
<details>
  <summary>Clique para expandir</summary>
  Conteúdo escondido aqui!
</details>
```

<details>
  <summary>Clique para expandir</summary>
  Conteúdo escondido aqui!
</details>

### Emoji

Você pode usar `:nome:` em GitHub/Discord:

:rocket: :tada: :heart: :+1:

### Notas de rodapé

```markdown
Texto com nota[^1].

[^1]: Esta é a nota de rodapé.
```

### Comentário invisível

```html
<!-- Este comentário não aparece no preview -->
```

<!-- Este comentário não aparece no preview -->

---

## 12. Exemplo completo

```markdown
# Meu Projeto

## Descrição
Projeto **incrível** feito em *Python*.

## Instalação
1. Clone o repositório
2. Rode `pip install -r requirements.txt`

## Uso
> Exemplo simples de uso.

| Comando | Descrição |
|---------|-----------|
| `run`   | Executa o app |
| `test`  | Roda os testes |

[Ver documentação](https://exemplo.com)
```

---

## Resumo rápido (Cheat Sheet)

- `#` título
- `**negrito**`, `*itálico*`, `~~riscado~~`
- `-` lista, `1.` lista numerada, `- [ ]` tarefa
- `[texto](url)` link, `![alt](url)` imagem
- `>` citação
- `` `código` `` e ` ```bloco``` `
- `|` tabela
- `---` linha horizontal

Bons estudos! 🚀
