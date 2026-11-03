# Tutorial Básico de Markdown

Guia exemplificativo para estudantes de Administração. Cada seção mostra primeiro a sintaxe e depois o resultado.

## 1. Títulos

```markdown
# Título 1
## Título 2
### Título 3
```

# Título 1
## Título 2
### Título 3

Use um `#` por nível, até seis níveis.

## 2. Parágrafos e quebras de linha

Deixe uma linha em branco entre parágrafos.

```markdown
Primeiro parágrafo.

Segundo parágrafo.
```

Primeiro parágrafo.

Segundo parágrafo.

## 3. Ênfase

```markdown
**negrito** para destaque forte
*itálico* para ênfase leve
~~riscado~~ para revisão
```

**negrito** para destaque forte
*itálico* para ênfase leve
~~riscado~~ para revisão

Exemplo da área: o **faturamento** cresceu *12%* no trimestre.

## 4. Listas

### Lista não ordenada

```markdown
- Planejamento
- Organização
- Direção
- Controle
```

- Planejamento
- Organização
- Direção
- Controle

### Lista ordenada

```markdown
1. Definir objetivo
2. Levantar dados
3. Analisar alternativas
4. Decidir
```

1. Definir objetivo
2. Levantar dados
3. Analisar alternativas
4. Decidir

### Lista de tarefas

```markdown
- [x] Levantar vendas de janeiro
- [ ] Gerar gráfico
- [ ] Apresentar à gerência
```

- [x] Levantar vendas de janeiro
- [ ] Gerar gráfico
- [ ] Apresentar à gerência

## 5. Links e imagens

```markdown
[Portal da UFMA](https://www.ufma.br)
![Gráfico de vendas](grafico.png)
```

[Portal da UFMA](https://www.ufma.br)
![Gráfico de vendas](grafico.png)

## 6. Citações

```markdown
> "Administrar é prever e decidir." — exemplo de citação
```

> "Administrar é prever e decidir." — exemplo de citação

## 7. Tabelas

```markdown
| Mês | Receita | Despesa |
|-----|--------:|--------:|
| Jan | 50.000  | 30.000  |
| Fev | 55.000  | 32.000  |
```

| Mês | Receita | Despesa |
|-----|--------:|--------:|
| Jan | 50.000  | 30.000  |
| Fev | 55.000  | 32.000  |

Os dois-pontos em `:--------` alinham a coluna: esquerda, direita ou centro (`:---:`).

## 8. Código

Código no texto: use crases, como em `faturamento - custo`.

Bloco de código:

```python
receita = 55000
custo = 32000
lucro = receita - custo
print(lucro)
```

## 9. Linha horizontal

Três traços `---` criam uma divisão:

---

## 10. Exercício rápido

Crie um arquivo `meu-relatorio.md` com:

1. Um título com o nome da empresa
2. Um parágrafo de 2 linhas sobre o mês
3. Uma lista de 3 metas
4. Uma tabela com Receita e Despesa
5. Uma tarefa marcada como concluída

---
*Arquivo criado como exemplo para a disciplina DECC0294 — Tecnologia da Informação e Comunicação Aplicada à Administração, UFMA.*
