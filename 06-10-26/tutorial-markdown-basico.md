# Tutorial Básico de Markdown — RASCUNHO

> **Aviso: isto é rascunho, não é texto final.**
> **Decisão humana pendente:** revisar exemplos, validar tabelas e aprovar antes de entregar ao professor.

Guia exemplificativo para a disciplina DECC0294 — Tecnologia da Informação e Comunicação Aplicada à Administração, UFMA.

## Conceito usado aqui

**Definição:** Markdown é linguagem de marcação simples para formatar texto direto no código, que vira título, lista, tabela e tal sem precisar de editor complicado.

**Exemplo brasileiro:** aluno de Administração escreve relatório de estágio em Markdown e depois converte pra apresentar pra gerência de uma loja em São Luís.

**Referência verificável:** NAO SEI

## 1. Títulos

```markdown
# Título 1
## Título 2
### Título 3
```

Resultado:

# Título 1
## Título 2
### Título 3

Use cerquilha `#` por nível, vai até o nível máximo da sintaxe.

## 2. Parágrafos e quebras de linha

Deixe uma linha em branco entre parágrafos.

```markdown
Primeiro parágrafo.

Segundo parágrafo.
```

Resultado:

Primeiro parágrafo.

Segundo parágrafo.

## 3. Ênfase

```markdown
**negrito** para destaque forte
*itálico* para ênfase leve
~~riscado~~ para revisão
```

Resultado:

**negrito** para destaque forte
*itálico* para ênfase leve
~~riscado~~ para revisão

Exemplo da área: o **faturamento** cresceu *valor fictício para exemplo, sem fonte — não usar como dado real* no trimestre.

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

## 7. Tabelas — todos os valores abaixo são fictícios para exemplo, sem fonte

```markdown
| Mês | Receita | Despesa |
|-----|---------|---------|
| Jan | valor A | valor B |
| Fev | valor C | valor D |
```

| Mês | Receita | Despesa |
|-----|---------|---------|
| Jan | valor A | valor B |
| Fev | valor C | valor D |

Os dois-pontos em `:---` alinham a coluna: esquerda, direita ou centro (`:---:`).

## 8. Código

Código no texto: use crases, como em `faturamento - custo`.

Bloco de código:

```python
receita = valor_receita # fictício, sem fonte
custo = valor_custo # fictício, sem fonte
lucro = receita - custo
print(lucro)
```

## 9. Linha horizontal

Três traços `---` criam uma divisão:

---

## 10. Exercício rápido

Crie um arquivo `meu-relatorio.md` com:

- Um título com o nome da empresa
- Um parágrafo curto sobre o mês
- Uma lista com metas
- Uma tabela com Receita e Despesa com valores fictícios sinalizados
- Uma tarefa marcada como concluída

## Interpretação

Esse tutorial serve pra pegar a manha do básico e já aplicar no relatório da faculdade, sem enrolação.

## Limitação declarada

Não cobre tabelas avançadas, notas de rodapé nem exportação automática. Números aqui são todos inventados pra demonstração, sem valor de pesquisa.

---
*RASCUNHO para DECC0294 — UFMA. Revisão humana pendente antes de qualquer entrega final.*
