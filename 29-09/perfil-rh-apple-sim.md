# Perfil da base rh-apple-sim

Modulo 6, ciclo 6.2. DECC0294, UFMA, Curso de Administracao.
Gerado em 29/09/2026 as 09:17 pelo script atividade_modulo6.py.

| Caracteristica | Valor |
|---|---|
| Arquivo | dados/rh-apple-sim.csv |
| Separador | ; |
| Codificacao | utf-8-sig |
| Linhas | 600 |
| Colunas | 19 |
| Linhas duplicadas | 0 |

## Visao geral das colunas

| Coluna | Tipo | Vazios | % vazios | Distintos |
|---|---|---|---|---|
| id_funcionario | texto | 0 | 0.0% | 600 |
| departamento | categoria | 0 | 0.0% | 8 |
| cargo | texto | 0 | 0.0% | 32 |
| nivel | categoria | 0 | 0.0% | 5 |
| localizacao | categoria | 0 | 0.0% | 5 |
| regime_trabalho | categoria | 0 | 0.0% | 3 |
| genero | categoria | 0 | 0.0% | 3 |
| idade | numero | 0 | 0.0% | 37 |
| tempo_empresa_anos | numero | 0 | 0.0% | 116 |
| data_admissao_mm_aaaa | texto | 0 | 0.0% | 146 |
| salario_mensal_brl | numero | 0 | 0.0% | 189 |
| bonus_anual_brl | numero | 0 | 0.0% | 592 |
| avaliacao_desempenho_1a5 | numero | 0 | 0.0% | 5 |
| satisfacao_1a5 | numero | 0 | 0.0% | 4 |
| horas_treinamento_ano | numero | 0 | 0.0% | 71 |
| faltas_dias_ano | numero | 0 | 0.0% | 16 |
| horas_extras_mes | numero | 0 | 0.0% | 24 |
| promocao_ultimos_2anos | categoria | 0 | 0.0% | 2 |
| saiu_em_2025 | categoria | 0 | 0.0% | 2 |

## Colunas numericas

| Coluna | Minimo | Mediana | Media | Maximo | Soma |
|---|---|---|---|---|---|
| idade | 19 | 33 | 33,40 | 56 | 20.041 |
| tempo_empresa_anos | 0,20 | 2,70 | 3,52 | 18,60 | 2.110,20 |
| salario_mensal_brl | 3.700 | 8.050 | 11.726,50 | 32.400 | 7.035.900 |
| bonus_anual_brl | 2.267 | 10.318,50 | 16.345,97 | 77.943 | 9.807.579 |
| avaliacao_desempenho_1a5 | 1 | 4 | 3,63 | 5 | 2.178 |
| satisfacao_1a5 | 2 | 4 | 4,28 | 5 | 2.570 |
| horas_treinamento_ano | 0 | 29 | 29,17 | 84 | 17.503 |
| faltas_dias_ano | 0 | 2 | 2,39 | 21 | 1.432 |
| horas_extras_mes | 0 | 6 | 6,35 | 25 | 3.810 |

Quando a media fica muito acima da mediana, ha poucos valores altos
puxando o resumo. Apresente as duas medidas no seu relatorio.

## Colunas de categoria e texto

### id_funcionario (texto, 600 valores distintos)

- EMP0001: 1 ocorrencia(s)
- EMP0002: 1 ocorrencia(s)
- EMP0003: 1 ocorrencia(s)
- EMP0004: 1 ocorrencia(s)
- EMP0005: 1 ocorrencia(s)

### departamento (categoria, 8 valores distintos)

- Varejo - Loja (Apple Store): 189 ocorrencia(s)
- Engenharia de Software: 121 ocorrencia(s)
- Suporte - AppleCare: 70 ocorrencia(s)
- Hardware e Design de Produto: 57 ocorrencia(s)
- Financas, RH e Juridico: 53 ocorrencia(s)

### cargo (texto, 32 valores distintos)

- Especialista Vendas: 43 ocorrencia(s)
- Lider de Loja: 40 ocorrencia(s)
- Estoquista: 38 ocorrencia(s)
- Genius (Suporte Loja): 37 ocorrencia(s)
- Gerente Engenharia: 33 ocorrencia(s)

### nivel (categoria, 5 valores distintos)

- Pleno: 186 ocorrencia(s)
- Junior: 166 ocorrencia(s)
- Gerente: 116 ocorrencia(s)
- Senior: 110 ocorrencia(s)
- Lead: 22 ocorrencia(s)

### localizacao (categoria, 5 valores distintos)

- Sao Paulo-SP: 224 ocorrencia(s)
- Remoto-BR: 169 ocorrencia(s)
- Manaus-AM (fabrica): 95 ocorrencia(s)
- Rio-RJ: 59 ocorrencia(s)
- Cupertino-EUA (remoto BR): 53 ocorrencia(s)

### regime_trabalho (categoria, 3 valores distintos)

- Presencial: 407 ocorrencia(s)
- Hibrido: 114 ocorrencia(s)
- Remoto: 79 ocorrencia(s)

### genero (categoria, 3 valores distintos)

- M: 329 ocorrencia(s)
- F: 257 ocorrencia(s)
- NB: 14 ocorrencia(s)

### data_admissao_mm_aaaa (texto, 146 valores distintos)

- 07/2025: 23 ocorrencia(s)
- 08/2025: 14 ocorrencia(s)
- 12/2024: 13 ocorrencia(s)
- 02/2025: 12 ocorrencia(s)
- 11/2024: 11 ocorrencia(s)

### promocao_ultimos_2anos (categoria, 2 valores distintos)

- nao: 497 ocorrencia(s)
- sim: 103 ocorrencia(s)

### saiu_em_2025 (categoria, 2 valores distintos)

- nao: 466 ocorrencia(s)
- sim: 134 ocorrencia(s)

## O que olhar neste perfil

- Coluna com um unico valor distinto nao informa nada e pode sair da analise.
- Coluna com todos os valores distintos costuma ser identificador.
- Percentual de vazios acima de 20% limita qualquer conclusao sobre a coluna.
- Maximo muito acima da mediana e onde moram os erros de digitacao.
- Linha duplicada infla contagem e soma. Confira antes de calcular qualquer total.

## Minhas tres observacoes ao ler este perfil

ESCREVA AQUI as tres coisas que mais surpreenderam voce:

1. 
2. 
3. 
