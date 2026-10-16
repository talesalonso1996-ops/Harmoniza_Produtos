# Documentação da harmonização de produtos POF 1987–2017
_Gerado por `hp_onda.py consolidar`. Não editar à mão._

Método: `.claude/skills/harmoniza-pof/CONSTITUICAO.md`. Histórico completo: `decisoes_todas.csv`.

## Ondas
| onda | tipo | decisões | aplicadas | PR |
|---|---|---|---|---|
| 2026-09-11_arthurwelle_base | base | 0 | 0 |  |
| 2026-09-11_arthurwelle_cirurgia | familia | 23 | 23 |  |
| 2026-10-16_claude-v3_1995-copia-de-1987 | familia | 2 | 2 |  |
| 2026-10-16_claude-v3_2017-quadros-deslocados | familia | 8 | 8 |  |
| 2026-10-16_claude-v3_alimentos-bebidas-outros | familia | 19 | 19 |  |
| 2026-10-16_claude-v3_alimentos-cereais-hortalicas-frutas | familia | 12 | 12 |  |
| 2026-10-16_claude-v3_alimentos-cocos-farinhas-panif-carnes | familia | 34 | 34 |  |
| 2026-10-16_claude-v3_alimentos-visceras-a-oleos | familia | 23 | 23 |  |
| 2026-10-16_claude-v3_comida-fora-de-casa | familia | 1 | 1 |  |
| 2026-10-16_claude-v3_cynthia-folha-32 | pendencia | 22 | 22 |  |
| 2026-10-16_claude-v3_cynthia-folha-37 | pendencia | 10 | 10 |  |
| 2026-10-16_claude-v3_cynthia-folha-38 | pendencia | 20 | 20 |  |
| 2026-10-16_claude-v3_cynthia-folha-400006 | pendencia | 22 | 22 |  |
| 2026-10-16_claude-v3_educacao-despesas-diversas | familia | 33 | 33 |  |
| 2026-10-16_claude-v3_habitacao-servicos | familia | 37 | 37 |  |
| 2026-10-16_claude-v3_nao-consumo | familia | 26 | 26 |  |
| 2026-10-16_claude-v3_pendencias-formulario | familia | 15 | 15 |  |
| 2026-10-16_claude-v3_pendencias-validacao-e-criar | familia | 37 | 37 |  |
| 2026-10-16_claude-v3_recreacao-cultura | familia | 18 | 18 |  |
| 2026-10-16_claude-v3_vazios-por-grupo | familia | 6 | 6 |  |
| 2026-10-16_claude-v3_vestuario-transporte-higiene-saude | familia | 39 | 39 |  |

## Regras ativas
| id | tipo | enunciado | grupos | anos |
|---|---|---|---|---|
| 2026-09-11_arthurwelle_cirurgia#r1 | excecao_r1 | Em 2002:42015 o item implante de cabelo não propaga a R1: a célula segue o conceito dominante (outros tratamentos) e o implante fica registrado como contaminação. | 36005;36006 | 2002 |
| 2026-09-11_arthurwelle_cirurgia#r2 | excecao_r1 | Em 2002:42016 o item instrumentador cirúrgico não propaga a R1: a célula segue o conceito dominante (enfermagem) e o instrumentador fica registrado como contaminação. | 36005;36006;36010 | 2002 |
| 2026-09-11_arthurwelle_cirurgia#r3 | excecao_r1 | Em 2002:42046 o item consulta médica nutricionista não propaga a R1: a célula segue o conceito dominante (consulta médica) e o nutricionista fica registrado como contaminação. | 36004;36005 | 2002 |
| 2026-09-11_arthurwelle_cirurgia#r4 | excecao_r1 | Em 2002:42008 os itens de exame ginecológico/pré-natal/preventivo e de exame oftalmológico não propagam a R1: a célula segue o conceito dominante (exames de laboratório) e eles ficam registrados como contaminação. | 36004;36008 | 2002 |

## Grupos (320 ativos, 0 extintos)

### 1. Cereais e leguminosas

#### 01101 — Arroz integral; Arroz não especificado; Arroz polido
1.1 Cereais · status **ativo** · criado em base
Células por ano: 1987: 4 · 1995: 4 · 2002: 6 · 2008: 10 · 2017: 14 (padrão 11111)
- Decisão 2026-10-16_claude-v3_pendencias-formulario#p07 MOVER **aceita** (01101 → 01199). IA: Um agregado de cereais e leguminosas não é arroz; a folha de resíduo do nível é o destino coerente, como pede a sugestão humana. Humano (claude-ia (ADR 0005)): —

#### 01102 — Milho seco; Milho em grão; Milho verde em conserva; Milho verde em espiga
1.1 Cereais · status **ativo** · criado em base
Células por ano: 1987: 5 · 1995: 4 · 2002: 6 · 2008: 7 · 2017: 7 (padrão 11111)
- Decisão 2026-10-16_claude-v3_comida-fora-de-casa#p01 REVISAR **aceita**. IA: Não há como decidir célula a célula sem uma regra: hoje a mesma despesa (refrigerante tomado na rua) muda de grupo conforme a edição. Duas opções coerentes: (A) tudo do quadro de comida fora em 16104 (ou num grupo novo 'Alimentação fora do domicílio' dividido em refeição e lanche/bebida), o que dá uma série de 'comer fora' comparável; (B) tudo por produto, o que soma comer fora a comer em casa em cada produto. A IA recomenda (A), porque o questionário separa o quadro em todas as edições e porque o IBGE publica alimentação fora do domicílio à parte. É decisão estrutural (REGRA, possivelmente CRIAR), por isso fica para o humano (ADR 0005). Humano (claude-ia (ADR 0005)): —

#### 01103 — Aveia
1.1 Cereais · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 1 · 2017: 1 (padrão 11111)

#### 01104 — Cevada
1.1 Cereais · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 1 · 2017: 1 (padrão 11111)
- Decisão 2026-10-16_claude-v3_pendencias-validacao-e-criar#p05 MANTER **aceita**. IA: A mudança da planilha v2026 para a base (lá 01103, hoje 01104) é a classificação que as outras edições usam para os mesmos produtos (20 de 20 ocorrências): correção legítima. Nada a mudar. Humano (claude-ia (ADR 0005)): —

#### 01105 — Trigo
1.1 Cereais · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 1 · 2017: 1 (padrão 11111)
- Decisão 2026-10-16_claude-v3_pendencias-validacao-e-criar#p06 MANTER **aceita**. IA: A mudança da planilha v2026 para a base (lá 01103, hoje 01105) é a classificação que as outras edições usam para os mesmos produtos (20 de 20 ocorrências): correção legítima. Nada a mudar. Humano (claude-ia (ADR 0005)): —

#### 01199 — Outros
1.1 Cereais · status **ativo** · criado em base
Células por ano: 1987: 5 · 1995: 4 · 2002: 1 · 2008: 3 · 2017: 4 (padrão 11111)
- Decisão 2026-10-16_claude-v3_alimentos-cereais-hortalicas-frutas#p07 MOVER **aceita** (01199 → 01299). IA: Outlier pontual: os mesmos produtos estão em 01299 em todas as outras edições em que aparecem (pelo menos 4); só em 2002 a célula está em 01199, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 01299) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_pendencias-formulario#p07 MOVER **aceita** (01101 → 01199). IA: Um agregado de cereais e leguminosas não é arroz; a folha de resíduo do nível é o destino coerente, como pede a sugestão humana. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_pendencias-validacao-e-criar#p02 REVISAR **aceita**. IA: As outras edições não confirmam com clareza nem o grupo atual nem o da planilha antiga. Recomendação da IA: 01199 Outros, o grupo mais frequente nas outras edições. Humano (claude-ia (ADR 0005)): —

#### 01201 — Feijão-fradinho
1.2 Leguminosas · status **ativo** · criado em base
Células por ano: 1987: 2 · 1995: 1 · 2002: 1 · 2008: 2 · 2017: 2 (padrão 11111)
- Decisão 2026-10-16_claude-v3_alimentos-cereais-hortalicas-frutas#p01 MOVER **aceita** (01208 → 01201). IA: Outlier pontual: os mesmos produtos estão em 01201 em todas as outras edições em que aparecem (pelo menos 3); só em 1987 a célula está em 01208, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 01201) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —

#### 01202 — Feijão-jalo
1.2 Leguminosas · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 1 · 2017: 1 (padrão 11111)
- Decisão 2026-10-16_claude-v3_pendencias-validacao-e-criar#p23 MANTER **aceita**. IA: A mudança da planilha v2026 para a base (lá 01208, hoje 01202) é a classificação que as outras edições usam para os mesmos produtos (8 de 8 ocorrências): correção legítima. Nada a mudar. Humano (claude-ia (ADR 0005)): —

#### 01203 — Feijão-manteiga
1.2 Leguminosas · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 1 · 2017: 2 (padrão 11111)
- Decisão 2026-10-16_claude-v3_alimentos-cereais-hortalicas-frutas#p08 MOVER **aceita** (01299 → 01203). IA: Outlier pontual: os mesmos produtos estão em 01203 em todas as outras edições em que aparecem (pelo menos 3); só em 2017 a célula está em 01299, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 01203) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_pendencias-validacao-e-criar#p03 REVISAR **aceita**. IA: As outras edições não confirmam com clareza nem o grupo atual nem o da planilha antiga. Recomendação da IA: 01299 Outras, o grupo mais frequente nas outras edições. Humano (claude-ia (ADR 0005)): —

#### 01204 — Feijão-mulatinho
1.2 Leguminosas · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 2 · 2017: 2 (padrão 11111)

#### 01205 — Feijão-preto
1.2 Leguminosas · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 2 · 2017: 2 (padrão 11111)

#### 01206 — Feijão-rajado
1.2 Leguminosas · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 1 · 2017: 1 (padrão 11111)

#### 01207 — Feijão-roxo
1.2 Leguminosas · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 1 · 2017: 1 (padrão 11111)

#### 01208 — Outros feijões
1.2 Leguminosas · status **ativo** · criado em base
Células por ano: 1987: 10 · 1995: 10 · 2002: 7 · 2008: 9 · 2017: 11 (padrão 11111)
- Decisão 2026-10-16_claude-v3_alimentos-cereais-hortalicas-frutas#p01 MOVER **aceita** (01208 → 01201). IA: Outlier pontual: os mesmos produtos estão em 01201 em todas as outras edições em que aparecem (pelo menos 3); só em 1987 a célula está em 01208, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 01201) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_pendencias-validacao-e-criar#p13 MANTER **aceita**. IA: A mudança da planilha v2026 para a base (lá 01103, hoje 01208) é a classificação que as outras edições usam para os mesmos produtos (12 de 12 ocorrências): correção legítima. Nada a mudar. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_pendencias-validacao-e-criar#p24 REVISAR **aceita**. IA: As outras edições não confirmam com clareza nem o grupo atual nem o da planilha antiga. Sem par nas outras edições. Humano (claude-ia (ADR 0005)): —

#### 01209 — Grão de bico
1.2 Leguminosas · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 1 · 2017: 1 (padrão 11111)
- Decisão 2026-10-16_claude-v3_pendencias-validacao-e-criar#p15 MANTER **aceita**. IA: A mudança da planilha v2026 para a base (lá 01103, hoje 01209) é a classificação que as outras edições usam para os mesmos produtos (12 de 12 ocorrências): correção legítima. Nada a mudar. Humano (claude-ia (ADR 0005)): —

#### 01210 — Lentilha
1.2 Leguminosas · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 1 · 2017: 1 (padrão 11111)
- Decisão 2026-10-16_claude-v3_pendencias-validacao-e-criar#p16 MANTER **aceita**. IA: A mudança da planilha v2026 para a base (lá 01103, hoje 01210) é a classificação que as outras edições usam para os mesmos produtos (12 de 12 ocorrências): correção legítima. Nada a mudar. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_pendencias-validacao-e-criar#p21 MANTER **aceita**. IA: A mudança da planilha v2026 para a base (lá 01209, hoje 01210) é a classificação que as outras edições usam para os mesmos produtos (8 de 8 ocorrências): correção legítima. Nada a mudar. Humano (claude-ia (ADR 0005)): —

#### 01211 — Tremolo
1.2 Leguminosas · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 1 · 2017: 1 (padrão 11111)
- Decisão 2026-10-16_claude-v3_pendencias-validacao-e-criar#p14 MANTER **aceita**. IA: A mudança da planilha v2026 para a base (lá 01103, hoje 01211) é a classificação que as outras edições usam para os mesmos produtos (12 de 12 ocorrências): correção legítima. Nada a mudar. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_pendencias-validacao-e-criar#p20 MANTER **aceita**. IA: A mudança da planilha v2026 para a base (lá 01209, hoje 01211) é a classificação que as outras edições usam para os mesmos produtos (8 de 8 ocorrências): correção legítima. Nada a mudar. Humano (claude-ia (ADR 0005)): —

#### 01212 — Soja em grão
1.2 Leguminosas · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 2 · 2017: 2 (padrão 11111)
- Decisão 2026-10-16_claude-v3_pendencias-validacao-e-criar#p07 MANTER **aceita**. IA: A mudança da planilha v2026 para a base (lá 01103, hoje 01212) é a classificação que as outras edições usam para os mesmos produtos (14 de 14 ocorrências): correção legítima. Nada a mudar. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_pendencias-validacao-e-criar#p22 MANTER **aceita**. IA: A mudança da planilha v2026 para a base (lá 01209, hoje 01212) é a classificação que as outras edições usam para os mesmos produtos (8 de 8 ocorrências): correção legítima. Nada a mudar. Humano (claude-ia (ADR 0005)): —

#### 01213 — Ervilha em grãos
1.2 Leguminosas · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 1 · 2017: 1 (padrão 11111)

#### 01299 — Outras
1.2 Leguminosas · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 6 · 2017: 7 (padrão 11111)
- Decisão 2026-10-16_claude-v3_alimentos-cereais-hortalicas-frutas#p07 MOVER **aceita** (01199 → 01299). IA: Outlier pontual: os mesmos produtos estão em 01299 em todas as outras edições em que aparecem (pelo menos 4); só em 2002 a célula está em 01199, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 01299) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_alimentos-cereais-hortalicas-frutas#p08 MOVER **aceita** (01299 → 01203). IA: Outlier pontual: os mesmos produtos estão em 01203 em todas as outras edições em que aparecem (pelo menos 3); só em 2017 a célula está em 01299, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 01203) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_pendencias-formulario#p01 MANTER **aceita**. IA: As sugestões do formulário já estão aplicadas no estado do repositório. Nada a mudar. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_pendencias-validacao-e-criar#p02 REVISAR **aceita**. IA: As outras edições não confirmam com clareza nem o grupo atual nem o da planilha antiga. Recomendação da IA: 01199 Outros, o grupo mais frequente nas outras edições. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_pendencias-validacao-e-criar#p03 REVISAR **aceita**. IA: As outras edições não confirmam com clareza nem o grupo atual nem o da planilha antiga. Recomendação da IA: 01299 Outras, o grupo mais frequente nas outras edições. Humano (claude-ia (ADR 0005)): —

### 2. Hortaliças

#### 02101 — Agrião
2.1 Hortaliças folhosas e florais · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 2 · 2017: 2 (padrão 11111)

#### 02102 — Alface
2.1 Hortaliças folhosas e florais · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 2 · 2017: 2 (padrão 11111)

#### 02103 — Cheiro-verde
2.1 Hortaliças folhosas e florais · status **ativo** · criado em base
Células por ano: 1987: 3 · 1995: 3 · 2002: 3 · 2008: 3 · 2017: 5 (padrão 11111)
- Decisão 2026-10-16_claude-v3_alimentos-cereais-hortalicas-frutas#p03 MOVER **aceita** (02107 → 02103). IA: Outlier pontual: os mesmos produtos estão em 02103 em todas as outras edições em que aparecem (pelo menos 4); só em 1995 a célula está em 02107, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 02103) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —

#### 02104 — Couve; Couve-brócolis
2.1 Hortaliças folhosas e florais · status **ativo** · criado em base
Células por ano: 1987: 2 · 1995: 2 · 2002: 3 · 2008: 6 · 2017: 6 (padrão 11111)

#### 02105 — Couve-flor
2.1 Hortaliças folhosas e florais · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 2 · 2017: 2 (padrão 11111)

#### 02106 — Repolho fresco; Repolho
2.1 Hortaliças folhosas e florais · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 2 · 2017: 3 (padrão 11111)

#### 02107 — Outras; Acelga
2.1 Hortaliças folhosas e florais · status **ativo** · criado em base
Células por ano: 1987: 23 · 1995: 22 · 2002: 25 · 2008: 32 · 2017: 56 (padrão 11111)
- Decisão 2026-10-16_claude-v3_alimentos-cereais-hortalicas-frutas#p03 MOVER **aceita** (02107 → 02103). IA: Outlier pontual: os mesmos produtos estão em 02103 em todas as outras edições em que aparecem (pelo menos 4); só em 1995 a célula está em 02107, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 02103) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —

#### 02201 — Abóbora comum; Abóbora
2.2 Hortaliças frutosas · status **ativo** · criado em base
Células por ano: 1987: 6 · 1995: 6 · 2002: 16 · 2008: 15 · 2017: 16 (padrão 11111)

#### 02202 — Abobrinha
2.2 Hortaliças frutosas · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 1 · 2017: 2 (padrão 11111)

#### 02203 — Berinjela
2.2 Hortaliças frutosas · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 2 · 2017: 3 (padrão 11111)

#### 02204 — Cebola; Cebola fresca
2.2 Hortaliças frutosas · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 2 · 2002: 2 · 2008: 2 · 2017: 3 (padrão 11111)

#### 02205 — Chuchu
2.2 Hortaliças frutosas · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 1 · 2017: 3 (padrão 11111)

#### 02206 — Jiló
2.2 Hortaliças frutosas · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 2 · 2017: 2 (padrão 11111)

#### 02207 — Pepino fresco
2.2 Hortaliças frutosas · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 2 · 2017: 2 (padrão 11111)

#### 02208 — Pimentão
2.2 Hortaliças frutosas · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 2 · 2017: 2 (padrão 11111)

#### 02209 — Quiabo
2.2 Hortaliças frutosas · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 1 · 2017: 2 (padrão 11111)

#### 02210 — Tomate
2.2 Hortaliças frutosas · status **ativo** · criado em base
Células por ano: 1987: 2 · 1995: 2 · 2002: 2 · 2008: 2 · 2017: 3 (padrão 11111)
- Decisão 2026-10-16_claude-v3_comida-fora-de-casa#p01 REVISAR **aceita**. IA: Não há como decidir célula a célula sem uma regra: hoje a mesma despesa (refrigerante tomado na rua) muda de grupo conforme a edição. Duas opções coerentes: (A) tudo do quadro de comida fora em 16104 (ou num grupo novo 'Alimentação fora do domicílio' dividido em refeição e lanche/bebida), o que dá uma série de 'comer fora' comparável; (B) tudo por produto, o que soma comer fora a comer em casa em cada produto. A IA recomenda (A), porque o questionário separa o quadro em todas as edições e porque o IBGE publica alimentação fora do domicílio à parte. É decisão estrutural (REGRA, possivelmente CRIAR), por isso fica para o humano (ADR 0005). Humano (claude-ia (ADR 0005)): —

#### 02211 — Vagem
2.2 Hortaliças frutosas · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 2 · 2008: 3 · 2017: 3 (padrão 11111)

#### 02212 — Outras; Maxixe; Azeitona em conserva; Outros feijões
2.2 Hortaliças frutosas · status **ativo** · criado em base
Células por ano: 1987: 18 · 1995: 18 · 2002: 28 · 2008: 37 · 2017: 41 (padrão 11111)
- Decisão 2026-10-16_claude-v3_alimentos-cereais-hortalicas-frutas#p02 MOVER **aceita** (13210 → 02212). IA: Outlier pontual: os mesmos produtos estão em 02212 em todas as outras edições em que aparecem (pelo menos 3); só em 1987 a célula está em 13210, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 02212) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_alimentos-cereais-hortalicas-frutas#p05 MOVER **aceita** (13210 → 02212). IA: Outlier pontual: os mesmos produtos estão em 02212 em todas as outras edições em que aparecem (pelo menos 3); só em 1995 a célula está em 13210, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 02212) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_alimentos-cereais-hortalicas-frutas#p06 MOVER **aceita** (16103 → 02212). IA: Outlier pontual: os mesmos produtos estão em 02212 em todas as outras edições em que aparecem (pelo menos 3); só em 1995 a célula está em 16103, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 02212) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —

#### 02301 — Alho
2.3 Hortaliças tuberosas e outras · status **ativo** · criado em base
Células por ano: 1987: 2 · 1995: 2 · 2002: 1 · 2008: 1 · 2017: 1 (padrão 11111)

#### 02302 — Batata-doce
2.3 Hortaliças tuberosas e outras · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 1 · 2017: 2 (padrão 11111)

#### 02303 — Batata-inglesa
2.3 Hortaliças tuberosas e outras · status **ativo** · criado em base
Células por ano: 1987: 2 · 1995: 1 · 2002: 1 · 2008: 2 · 2017: 2 (padrão 11111)

#### 02304 — Batata não especificada; Batata-baroa; Batata-aipo
2.3 Hortaliças tuberosas e outras · status **ativo** · criado em base
Células por ano: 1987: 5 · 1995: 4 · 2002: 5 · 2008: 4 · 2017: 5 (padrão 11111)
- Decisão 2026-10-16_claude-v3_comida-fora-de-casa#p01 REVISAR **aceita**. IA: Não há como decidir célula a célula sem uma regra: hoje a mesma despesa (refrigerante tomado na rua) muda de grupo conforme a edição. Duas opções coerentes: (A) tudo do quadro de comida fora em 16104 (ou num grupo novo 'Alimentação fora do domicílio' dividido em refeição e lanche/bebida), o que dá uma série de 'comer fora' comparável; (B) tudo por produto, o que soma comer fora a comer em casa em cada produto. A IA recomenda (A), porque o questionário separa o quadro em todas as edições e porque o IBGE publica alimentação fora do domicílio à parte. É decisão estrutural (REGRA, possivelmente CRIAR), por isso fica para o humano (ADR 0005). Humano (claude-ia (ADR 0005)): —

#### 02305 — Beterraba
2.3 Hortaliças tuberosas e outras · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 3 · 2017: 3 (padrão 11111)

#### 02306 — Cenoura
2.3 Hortaliças tuberosas e outras · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 2 · 2017: 2 (padrão 11111)

#### 02307 — Inhame
2.3 Hortaliças tuberosas e outras · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 1 · 2017: 2 (padrão 11111)

#### 02308 — Mandioca
2.3 Hortaliças tuberosas e outras · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 1 · 2017: 3 (padrão 11111)

#### 02309 — Outras; Cará
2.3 Hortaliças tuberosas e outras · status **ativo** · criado em base
Células por ano: 1987: 7 · 1995: 7 · 2002: 7 · 2008: 11 · 2017: 14 (padrão 11111)
- Decisão 2026-10-16_claude-v3_alimentos-cereais-hortalicas-frutas#p09 REVISAR **aceita**. IA: Os mesmos produtos estão em 01101 nas duas outras edições em que aparecem; em 2002 estão em 02309. Duas edições contra uma, sem segunda fonte (IBGE neutro ou ausente, sem revisão manual): pela ADR 0005 não é óbvio. Recomendação da IA: mover, salvo razão de conceito. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_comida-fora-de-casa#p01 REVISAR **aceita**. IA: Não há como decidir célula a célula sem uma regra: hoje a mesma despesa (refrigerante tomado na rua) muda de grupo conforme a edição. Duas opções coerentes: (A) tudo do quadro de comida fora em 16104 (ou num grupo novo 'Alimentação fora do domicílio' dividido em refeição e lanche/bebida), o que dá uma série de 'comer fora' comparável; (B) tudo por produto, o que soma comer fora a comer em casa em cada produto. A IA recomenda (A), porque o questionário separa o quadro em todas as edições e porque o IBGE publica alimentação fora do domicílio à parte. É decisão estrutural (REGRA, possivelmente CRIAR), por isso fica para o humano (ADR 0005). Humano (claude-ia (ADR 0005)): —

### 3. Frutas

#### 03101 — Abacate
3.1 Frutas de clima tropical · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 1 · 2017: 1 (padrão 11111)

#### 03102 — Abacaxi
3.1 Frutas de clima tropical · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 1 · 2017: 2 (padrão 11111)

#### 03103 — Banana-d'água
3.1 Frutas de clima tropical · status **ativo** · criado em base
Células por ano: 1987: 2 · 1995: 1 · 2002: 1 · 2008: 1 · 2017: 2 (padrão 11111)

#### 03104 — Banana-maçã
3.1 Frutas de clima tropical · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 1 · 2017: 1 (padrão 11111)

#### 03105 — Banana-prata
3.1 Frutas de clima tropical · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 2 · 2017: 2 (padrão 11111)

#### 03106 — Outras bananas; Banana-ouro; Banana-da-terra
3.1 Frutas de clima tropical · status **ativo** · criado em base
Células por ano: 1987: 8 · 1995: 8 · 2002: 8 · 2008: 9 · 2017: 9 (padrão 11111)

#### 03107 — Laranja-baía
3.1 Frutas de clima tropical · status **ativo** · criado em base
Células por ano: 1987: 0 · 1995: 0 · 2002: 1 · 2008: 1 · 2017: 1 (padrão 00111)

#### 03108 — Laranja-lima
3.1 Frutas de clima tropical · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 1 · 2017: 1 (padrão 11111)

#### 03109 — Laranja-pêra
3.1 Frutas de clima tropical · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 1 · 2017: 1 (padrão 11111)

#### 03110 — Laranja-seleta
3.1 Frutas de clima tropical · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 1 · 2017: 1 (padrão 11111)

#### 03111 — Limão comum
3.1 Frutas de clima tropical · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 2 · 2008: 4 · 2017: 6 (padrão 11111)

#### 03112 — Mamão
3.1 Frutas de clima tropical · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 1 · 2017: 2 (padrão 11111)

#### 03113 — Manga
3.1 Frutas de clima tropical · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 1 · 2017: 2 (padrão 11111)

#### 03114 — Maracujá
3.1 Frutas de clima tropical · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 1 · 2017: 2 (padrão 11111)

#### 03115 — Melancia
3.1 Frutas de clima tropical · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 1 · 2017: 1 (padrão 11111)

#### 03116 — Melão
3.1 Frutas de clima tropical · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 1 · 2017: 2 (padrão 11111)

#### 03117 — Tangerina
3.1 Frutas de clima tropical · status **ativo** · criado em base
Células por ano: 1987: 2 · 1995: 2 · 2002: 1 · 2008: 1 · 2017: 1 (padrão 11111)

#### 03118 — Outras; Outras laranjas; Goiaba; Acerola
3.1 Frutas de clima tropical · status **ativo** · criado em base
Células por ano: 1987: 9 · 1995: 11 · 2002: 38 · 2008: 50 · 2017: 56 (padrão 11111)
- Decisão 2026-10-16_claude-v3_alimentos-cereais-hortalicas-frutas#p04 MOVER **aceita** (03205 → 03118). IA: Outlier pontual: os mesmos produtos estão em 03118 em todas as outras edições em que aparecem (pelo menos 3); só em 1995 a célula está em 03205, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 03118) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_cynthia-folha-38#p02 REVISAR **aceita**. IA: A revisão manual aponta outlier pontual, mas o detector não o confirmou: a célula tem itens sem histórico ou de outro conceito, ou o histórico não é unânime (R1). Precisa olhar a célula inteira. Humano (claude-ia (ADR 0005)): —

#### 03201 — Caqui
3.2 Frutas de clima temperado · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 0 · 2008: 0 · 2017: 0 (padrão 11000)

#### 03202 — Maçã
3.2 Frutas de clima temperado · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 0 · 2008: 1 · 2017: 1 (padrão 11011)

#### 03203 — Pêra
3.2 Frutas de clima temperado · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 1 · 2017: 1 (padrão 11111)

#### 03204 — Uva
3.2 Frutas de clima temperado · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 2 · 2017: 2 (padrão 11111)

#### 03205 — Outras; Pêssego; Morango; Ameixa
3.2 Frutas de clima temperado · status **ativo** · criado em base
Células por ano: 1987: 47 · 1995: 51 · 2002: 19 · 2008: 23 · 2017: 26 (padrão 11111)
- Decisão 2026-10-16_claude-v3_alimentos-cereais-hortalicas-frutas#p04 MOVER **aceita** (03205 → 03118). IA: Outlier pontual: os mesmos produtos estão em 03118 em todas as outras edições em que aparecem (pelo menos 3); só em 1995 a célula está em 03205, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 03118) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_alimentos-cereais-hortalicas-frutas#p10 REVISAR **aceita**. IA: Os mesmos produtos estão em 03118 nas duas outras edições em que aparecem; em 2002 estão em 03205. Duas edições contra uma, sem segunda fonte (IBGE neutro ou ausente, sem revisão manual): pela ADR 0005 não é óbvio. Recomendação da IA: mover, salvo razão de conceito. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_alimentos-cocos-farinhas-panif-carnes#p17 REVISAR **aceita**. IA: Os mesmos produtos estão em 04104 nas duas outras edições em que aparecem; em 2002 estão em 03205. Duas edições contra uma, sem segunda fonte (IBGE neutro ou ausente, sem revisão manual): pela ADR 0005 não é óbvio. Recomendação da IA: mover, salvo razão de conceito. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_comida-fora-de-casa#p01 REVISAR **aceita**. IA: Não há como decidir célula a célula sem uma regra: hoje a mesma despesa (refrigerante tomado na rua) muda de grupo conforme a edição. Duas opções coerentes: (A) tudo do quadro de comida fora em 16104 (ou num grupo novo 'Alimentação fora do domicílio' dividido em refeição e lanche/bebida), o que dá uma série de 'comer fora' comparável; (B) tudo por produto, o que soma comer fora a comer em casa em cada produto. A IA recomenda (A), porque o questionário separa o quadro em todas as edições e porque o IBGE publica alimentação fora do domicílio à parte. É decisão estrutural (REGRA, possivelmente CRIAR), por isso fica para o humano (ADR 0005). Humano (claude-ia (ADR 0005)): —

### 4. Cocos, castanhas e nozes

#### 04101 — Coco-açaí em pasta; Açaí (emulsão)
4.1 Cocos · status **ativo** · criado em base
Células por ano: 1987: 2 · 1995: 2 · 2002: 2 · 2008: 2 · 2017: 1 (padrão 11111)
- Decisão 2026-10-16_claude-v3_comida-fora-de-casa#p01 REVISAR **aceita**. IA: Não há como decidir célula a célula sem uma regra: hoje a mesma despesa (refrigerante tomado na rua) muda de grupo conforme a edição. Duas opções coerentes: (A) tudo do quadro de comida fora em 16104 (ou num grupo novo 'Alimentação fora do domicílio' dividido em refeição e lanche/bebida), o que dá uma série de 'comer fora' comparável; (B) tudo por produto, o que soma comer fora a comer em casa em cada produto. A IA recomenda (A), porque o questionário separa o quadro em todas as edições e porque o IBGE publica alimentação fora do domicílio à parte. É decisão estrutural (REGRA, possivelmente CRIAR), por isso fica para o humano (ADR 0005). Humano (claude-ia (ADR 0005)): —

#### 04103 — Coco-da-baía
4.1 Cocos · status **ativo** · criado em base
Células por ano: 1987: 2 · 1995: 1 · 2002: 3 · 2008: 3 · 2017: 4 (padrão 11111)
- Decisão 2026-10-16_claude-v3_comida-fora-de-casa#p01 REVISAR **aceita**. IA: Não há como decidir célula a célula sem uma regra: hoje a mesma despesa (refrigerante tomado na rua) muda de grupo conforme a edição. Duas opções coerentes: (A) tudo do quadro de comida fora em 16104 (ou num grupo novo 'Alimentação fora do domicílio' dividido em refeição e lanche/bebida), o que dá uma série de 'comer fora' comparável; (B) tudo por produto, o que soma comer fora a comer em casa em cada produto. A IA recomenda (A), porque o questionário separa o quadro em todas as edições e porque o IBGE publica alimentação fora do domicílio à parte. É decisão estrutural (REGRA, possivelmente CRIAR), por isso fica para o humano (ADR 0005). Humano (claude-ia (ADR 0005)): —

#### 04104 — Outros
4.1 Cocos · status **ativo** · criado em base
Células por ano: 1987: 19 · 1995: 19 · 2002: 23 · 2008: 25 · 2017: 27 (padrão 11111)

### 5. Farinhas, féculas e massas

#### 05101 — Farinha de mandioca
5.1 Farinhas · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 3 · 2017: 3 (padrão 11111)

#### 05102 — Farinha de rosca
5.1 Farinhas · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 1 · 2017: 1 (padrão 11111)

#### 05103 — Farinha de trigo
5.1 Farinhas · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 2 · 2017: 2 (padrão 11111)

#### 05104 — Farinha vitaminada
5.1 Farinhas · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 6 · 2008: 4 · 2017: 4 (padrão 11111)
- Decisão 2026-10-16_claude-v3_comida-fora-de-casa#p01 REVISAR **aceita**. IA: Não há como decidir célula a célula sem uma regra: hoje a mesma despesa (refrigerante tomado na rua) muda de grupo conforme a edição. Duas opções coerentes: (A) tudo do quadro de comida fora em 16104 (ou num grupo novo 'Alimentação fora do domicílio' dividido em refeição e lanche/bebida), o que dá uma série de 'comer fora' comparável; (B) tudo por produto, o que soma comer fora a comer em casa em cada produto. A IA recomenda (A), porque o questionário separa o quadro em todas as edições e porque o IBGE publica alimentação fora do domicílio à parte. É decisão estrutural (REGRA, possivelmente CRIAR), por isso fica para o humano (ADR 0005). Humano (claude-ia (ADR 0005)): —

#### 05105 — Outras
5.1 Farinhas · status **ativo** · criado em base
Células por ano: 1987: 12 · 1995: 10 · 2002: 11 · 2008: 15 · 2017: 23 (padrão 11111)
- Decisão 2026-10-16_claude-v3_alimentos-cocos-farinhas-panif-carnes#p01 MOVER **aceita** (05105 → 05206). IA: Outlier pontual: os mesmos produtos estão em 05206 em todas as outras edições em que aparecem (pelo menos 3); só em 1987 a célula está em 05105, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 05206) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_alimentos-cocos-farinhas-panif-carnes#p18 REVISAR **aceita**. IA: Os mesmos produtos estão em 05103 nas duas outras edições em que aparecem; em 1987 estão em 05105. Duas edições contra uma, sem segunda fonte (IBGE neutro ou ausente, sem revisão manual): pela ADR 0005 não é óbvio. Recomendação da IA: mover, salvo razão de conceito. Humano (claude-ia (ADR 0005)): —

#### 05201 — Amido de milho
5.2 Féculas · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 1 · 2017: 1 (padrão 11111)

#### 05202 — Fubá de milho; Creme de milho
5.2 Féculas · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 0 · 2017: 0 (padrão 11100)

#### 05203 — Fécula de mandioca
5.2 Féculas · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 0 · 2017: 0 (padrão 11100)

#### 05204 — Flocos de milho
5.2 Féculas · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 2 · 2017: 2 (padrão 11111)

#### 05206 — Flocos de cereal; Flocos de aveia; Flocos de outros cereais; Outras
5.2 Féculas · status **ativo** · criado em base
Células por ano: 1987: 8 · 1995: 7 · 2002: 5 · 2008: 12 · 2017: 21 (padrão 11111)
- Decisão 2026-10-16_claude-v3_alimentos-cocos-farinhas-panif-carnes#p01 MOVER **aceita** (05105 → 05206). IA: Outlier pontual: os mesmos produtos estão em 05206 em todas as outras edições em que aparecem (pelo menos 3); só em 1987 a célula está em 05105, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 05206) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —

#### 05301 — Macarrão com ovos; Macarrão não especificado; Macarrão sem ovos
5.3 Massas · status **ativo** · criado em base
Células por ano: 1987: 3 · 1995: 3 · 2002: 4 · 2008: 9 · 2017: 14 (padrão 11111)

#### 05302 — Massa de pastel
5.3 Massas · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 1 · 2017: 1 (padrão 11111)

#### 05303 — Massa de pizza; Outras; Massa de lasanha
5.3 Massas · status **ativo** · criado em base
Células por ano: 1987: 12 · 1995: 12 · 2002: 10 · 2008: 18 · 2017: 22 (padrão 11111)
- Decisão 2026-10-16_claude-v3_alimentos-cocos-farinhas-panif-carnes#p14 MOVER **aceita** (16102 → 05303). IA: Outlier pontual: os mesmos produtos estão em 05303 em todas as outras edições em que aparecem (pelo menos 3); só em 2002 a célula está em 16102, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 05303) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —

### 6. Panificados

#### 06101 — Pão de forma industrializado
6.1 Pães · status **ativo** · criado em base
Células por ano: 1987: 3 · 1995: 3 · 2002: 2 · 2008: 4 · 2017: 4 (padrão 11111)
- Decisão 2026-10-16_claude-v3_alimentos-cocos-farinhas-panif-carnes#p19 REVISAR **aceita**. IA: Os mesmos produtos estão em 06104 nas duas outras edições em que aparecem; em 2002 estão em 06101. Duas edições contra uma, sem segunda fonte (IBGE neutro ou ausente, sem revisão manual): pela ADR 0005 não é óbvio. Recomendação da IA: mover, salvo razão de conceito. Humano (claude-ia (ADR 0005)): —

#### 06102 — Pão doce
6.1 Pães · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 3 · 2017: 3 (padrão 11111)

#### 06103 — Pão francês
6.1 Pães · status **ativo** · criado em base
Células por ano: 1987: 2 · 1995: 2 · 2002: 1 · 2008: 3 · 2017: 5 (padrão 11111)
- Decisão 2026-10-16_claude-v3_comida-fora-de-casa#p01 REVISAR **aceita**. IA: Não há como decidir célula a célula sem uma regra: hoje a mesma despesa (refrigerante tomado na rua) muda de grupo conforme a edição. Duas opções coerentes: (A) tudo do quadro de comida fora em 16104 (ou num grupo novo 'Alimentação fora do domicílio' dividido em refeição e lanche/bebida), o que dá uma série de 'comer fora' comparável; (B) tudo por produto, o que soma comer fora a comer em casa em cada produto. A IA recomenda (A), porque o questionário separa o quadro em todas as edições e porque o IBGE publica alimentação fora do domicílio à parte. É decisão estrutural (REGRA, possivelmente CRIAR), por isso fica para o humano (ADR 0005). Humano (claude-ia (ADR 0005)): —

#### 06104 — Pão caseiro; Pão de forma de padaria; Pão de milho; Pão de queijo; Pão integral; Torrada; Outros
6.1 Pães · status **ativo** · criado em base
Células por ano: 1987: 22 · 1995: 18 · 2002: 22 · 2008: 56 · 2017: 58 (padrão 11111)
- Decisão 2026-10-16_claude-v3_alimentos-bebidas-outros#p05 MOVER **aceita** (06104 → 16106). IA: Outlier pontual: os mesmos produtos estão em 16106 em todas as outras edições em que aparecem (pelo menos 3); só em 1995 a célula está em 06104, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 16106) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_comida-fora-de-casa#p01 REVISAR **aceita**. IA: Não há como decidir célula a célula sem uma regra: hoje a mesma despesa (refrigerante tomado na rua) muda de grupo conforme a edição. Duas opções coerentes: (A) tudo do quadro de comida fora em 16104 (ou num grupo novo 'Alimentação fora do domicílio' dividido em refeição e lanche/bebida), o que dá uma série de 'comer fora' comparável; (B) tudo por produto, o que soma comer fora a comer em casa em cada produto. A IA recomenda (A), porque o questionário separa o quadro em todas as edições e porque o IBGE publica alimentação fora do domicílio à parte. É decisão estrutural (REGRA, possivelmente CRIAR), por isso fica para o humano (ADR 0005). Humano (claude-ia (ADR 0005)): —

#### 06201 — Bolo de trigo; Outros bolos
6.2 Bolos · status **ativo** · criado em base
Células por ano: 1987: 8 · 1995: 7 · 2002: 21 · 2008: 36 · 2017: 40 (padrão 11111)

#### 06301 — Biscoito doce
6.3 Biscoitos, roscas, etc. · status **ativo** · criado em base
Células por ano: 1987: 2 · 1995: 2 · 2002: 4 · 2008: 10 · 2017: 8 (padrão 11111)
- Decisão 2026-10-16_claude-v3_comida-fora-de-casa#p01 REVISAR **aceita**. IA: Não há como decidir célula a célula sem uma regra: hoje a mesma despesa (refrigerante tomado na rua) muda de grupo conforme a edição. Duas opções coerentes: (A) tudo do quadro de comida fora em 16104 (ou num grupo novo 'Alimentação fora do domicílio' dividido em refeição e lanche/bebida), o que dá uma série de 'comer fora' comparável; (B) tudo por produto, o que soma comer fora a comer em casa em cada produto. A IA recomenda (A), porque o questionário separa o quadro em todas as edições e porque o IBGE publica alimentação fora do domicílio à parte. É decisão estrutural (REGRA, possivelmente CRIAR), por isso fica para o humano (ADR 0005). Humano (claude-ia (ADR 0005)): —

#### 06302 — Biscoito salgado
6.3 Biscoitos, roscas, etc. · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 2 · 2008: 5 · 2017: 5 (padrão 11111)
- Decisão 2026-10-16_claude-v3_comida-fora-de-casa#p01 REVISAR **aceita**. IA: Não há como decidir célula a célula sem uma regra: hoje a mesma despesa (refrigerante tomado na rua) muda de grupo conforme a edição. Duas opções coerentes: (A) tudo do quadro de comida fora em 16104 (ou num grupo novo 'Alimentação fora do domicílio' dividido em refeição e lanche/bebida), o que dá uma série de 'comer fora' comparável; (B) tudo por produto, o que soma comer fora a comer em casa em cada produto. A IA recomenda (A), porque o questionário separa o quadro em todas as edições e porque o IBGE publica alimentação fora do domicílio à parte. É decisão estrutural (REGRA, possivelmente CRIAR), por isso fica para o humano (ADR 0005). Humano (claude-ia (ADR 0005)): —

#### 06303 — Biscoito não especificado; Rosca doce; Rosca não especificada; Rosca salgada; Outros
6.3 Biscoitos, roscas, etc. · status **ativo** · criado em base
Células por ano: 1987: 7 · 1995: 7 · 2002: 7 · 2008: 15 · 2017: 28 (padrão 11111)
- Decisão 2026-10-16_claude-v3_alimentos-cocos-farinhas-panif-carnes#p20 REVISAR **aceita**. IA: Os mesmos produtos estão em 06302 nas duas outras edições em que aparecem; em 2002 estão em 06303. Duas edições contra uma, sem segunda fonte (IBGE neutro ou ausente, sem revisão manual): pela ADR 0005 não é óbvio. Recomendação da IA: mover, salvo razão de conceito. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_comida-fora-de-casa#p01 REVISAR **aceita**. IA: Não há como decidir célula a célula sem uma regra: hoje a mesma despesa (refrigerante tomado na rua) muda de grupo conforme a edição. Duas opções coerentes: (A) tudo do quadro de comida fora em 16104 (ou num grupo novo 'Alimentação fora do domicílio' dividido em refeição e lanche/bebida), o que dá uma série de 'comer fora' comparável; (B) tudo por produto, o que soma comer fora a comer em casa em cada produto. A IA recomenda (A), porque o questionário separa o quadro em todas as edições e porque o IBGE publica alimentação fora do domicílio à parte. É decisão estrutural (REGRA, possivelmente CRIAR), por isso fica para o humano (ADR 0005). Humano (claude-ia (ADR 0005)): —

### 7. Carnes

#### 07101 — Alcatra
7.1 Carnes bovinas de primeira · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 2 · 2017: 4 (padrão 11111)
- Decisão 2026-10-16_claude-v3_alimentos-cocos-farinhas-panif-carnes#p16 MOVER **aceita** (07103 → 07101). IA: Outlier pontual: os mesmos produtos estão em 07101 em todas as outras edições em que aparecem (pelo menos 3); só em 2017 a célula está em 07103, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 07101) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —

#### 07102 — Carne moída
7.1 Carnes bovinas de primeira · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 2 · 2017: 2 (padrão 11111)
- Decisão 2026-10-16_claude-v3_alimentos-cocos-farinhas-panif-carnes#p13 MOVER **aceita** (07102 → 07203). IA: Outlier pontual: os mesmos produtos estão em 07203 em todas as outras edições em que aparecem (pelo menos 4); só em 2002 a célula está em 07102, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 07203) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —

#### 07103 — Carne não especificada
7.1 Carnes bovinas de primeira · status **ativo** · criado em base
Células por ano: 1987: 2 · 1995: 1 · 2002: 6 · 2008: 5 · 2017: 7 (padrão 11111)
- Decisão 2026-10-16_claude-v3_alimentos-cocos-farinhas-panif-carnes#p08 MOVER **aceita** (07103 → 07208). IA: Outlier pontual: os mesmos produtos estão em 07208 em todas as outras edições em que aparecem (pelo menos 3); só em 1995 a célula está em 07103, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 07208) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_alimentos-cocos-farinhas-panif-carnes#p16 MOVER **aceita** (07103 → 07101). IA: Outlier pontual: os mesmos produtos estão em 07101 em todas as outras edições em que aparecem (pelo menos 3); só em 2017 a célula está em 07103, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 07101) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —

#### 07104 — Chã-de-dentro
7.1 Carnes bovinas de primeira · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 3 · 2017: 3 (padrão 11111)

#### 07105 — Contrafilé
7.1 Carnes bovinas de primeira · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 1 · 2017: 1 (padrão 11111)

#### 07106 — Filé e filé mignon; Filé mignon
7.1 Carnes bovinas de primeira · status **ativo** · criado em base
Células por ano: 1987: 2 · 1995: 1 · 2002: 1 · 2008: 2 · 2017: 2 (padrão 11111)

#### 07107 — Lagarto comum
7.1 Carnes bovinas de primeira · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 2 · 2008: 4 · 2017: 4 (padrão 11111)

#### 07108 — Lagarto redondo
7.1 Carnes bovinas de primeira · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 0 · 2008: 1 · 2017: 1 (padrão 11011)

#### 07109 — Patinho
7.1 Carnes bovinas de primeira · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 2 · 2008: 1 · 2017: 1 (padrão 11111)

#### 07201 — Acém
7.2 Carnes bovinas de segunda · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 1 · 2017: 1 (padrão 11111)

#### 07203 — Carne moída
7.2 Carnes bovinas de segunda · status **ativo** · criado em base
Células por ano: 1987: 2 · 1995: 2 · 2002: 1 · 2008: 2 · 2017: 2 (padrão 11111)
- Decisão 2026-10-16_claude-v3_alimentos-cocos-farinhas-panif-carnes#p13 MOVER **aceita** (07102 → 07203). IA: Outlier pontual: os mesmos produtos estão em 07203 em todas as outras edições em que aparecem (pelo menos 4); só em 2002 a célula está em 07102, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 07203) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —

#### 07204 — Costela
7.2 Carnes bovinas de segunda · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 1 · 2017: 1 (padrão 11111)

#### 07205 — Músculo
7.2 Carnes bovinas de segunda · status **ativo** · criado em base
Células por ano: 1987: 2 · 1995: 1 · 2002: 1 · 2008: 3 · 2017: 3 (padrão 11111)
- Decisão 2026-10-16_claude-v3_alimentos-cocos-farinhas-panif-carnes#p02 MOVER **aceita** (07208 → 07205). IA: Outlier pontual: os mesmos produtos estão em 07205 em todas as outras edições em que aparecem (pelo menos 3); só em 1987 a célula está em 07208, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 07205) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —

#### 07206 — Pá
7.2 Carnes bovinas de segunda · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 1 · 2017: 1 (padrão 11111)

#### 07207 — Peito
7.2 Carnes bovinas de segunda · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 1 · 2017: 1 (padrão 11111)

#### 07208 — Outros Capa de filé; Carne não especificada; Carne de hambúrger; Carne de sol; Carne moída não especificada; Mocotó; Outras; Carne-seca
7.2 Carnes bovinas de segunda · status **ativo** · criado em base
Células por ano: 1987: 18 · 1995: 15 · 2002: 33 · 2008: 26 · 2017: 31 (padrão 11111)
- Decisão 2026-10-16_claude-v3_alimentos-bebidas-outros#p16 REVISAR **aceita**. IA: Os mesmos produtos estão em 16103 nas duas outras edições em que aparecem; em 2002 estão em 07208. Duas edições contra uma, sem segunda fonte (IBGE neutro ou ausente, sem revisão manual): pela ADR 0005 não é óbvio. Recomendação da IA: mover, salvo razão de conceito. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_alimentos-cocos-farinhas-panif-carnes#p02 MOVER **aceita** (07208 → 07205). IA: Outlier pontual: os mesmos produtos estão em 07205 em todas as outras edições em que aparecem (pelo menos 3); só em 1987 a célula está em 07208, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 07205) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_alimentos-cocos-farinhas-panif-carnes#p03 MOVER **aceita** (07506 → 07208). IA: Outlier pontual: os mesmos produtos estão em 07208 em todas as outras edições em que aparecem (pelo menos 3); só em 1987 a célula está em 07506, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 07208) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_alimentos-cocos-farinhas-panif-carnes#p07 MOVER **aceita** (08101 → 07208). IA: Outlier pontual: os mesmos produtos estão em 07208 em todas as outras edições em que aparecem (pelo menos 3); só em 1987 a célula está em 08101, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 07208) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_alimentos-cocos-farinhas-panif-carnes#p08 MOVER **aceita** (07103 → 07208). IA: Outlier pontual: os mesmos produtos estão em 07208 em todas as outras edições em que aparecem (pelo menos 3); só em 1995 a célula está em 07103, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 07208) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_alimentos-cocos-farinhas-panif-carnes#p09 MOVER **aceita** (07208 → 07602). IA: Outlier pontual: os mesmos produtos estão em 07602 em todas as outras edições em que aparecem (pelo menos 3); só em 1995 a célula está em 07208, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 07602) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_alimentos-cocos-farinhas-panif-carnes#p15 MOVER **aceita** (16104 → 07208). IA: Outlier pontual: os mesmos produtos estão em 07208 em todas as outras edições em que aparecem (pelo menos 3); só em 2002 a célula está em 16104, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 07208) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_alimentos-cocos-farinhas-panif-carnes#p21 REVISAR **aceita**. IA: Os mesmos produtos estão em 07103 nas duas outras edições em que aparecem; em 2002 estão em 07208. Duas edições contra uma, sem segunda fonte (IBGE neutro ou ausente, sem revisão manual): pela ADR 0005 não é óbvio. Recomendação da IA: mover, salvo razão de conceito. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_alimentos-cocos-farinhas-panif-carnes#p22 REVISAR **aceita**. IA: Os mesmos produtos estão em 07205 nas duas outras edições em que aparecem; em 2002 estão em 07208. Duas edições contra uma, sem segunda fonte (IBGE neutro ou ausente, sem revisão manual): pela ADR 0005 não é óbvio. Recomendação da IA: mover, salvo razão de conceito. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_alimentos-cocos-farinhas-panif-carnes#p23 REVISAR **aceita**. IA: Os mesmos produtos estão em 07403 nas duas outras edições em que aparecem; em 2002 estão em 07208. Duas edições contra uma, sem segunda fonte (IBGE neutro ou ausente, sem revisão manual): pela ADR 0005 não é óbvio. Recomendação da IA: mover, salvo razão de conceito. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_alimentos-cocos-farinhas-panif-carnes#p24 REVISAR **aceita**. IA: Os mesmos produtos estão em 07506 nas duas outras edições em que aparecem; em 2002 estão em 07208. Duas edições contra uma, sem segunda fonte (IBGE neutro ou ausente, sem revisão manual): pela ADR 0005 não é óbvio. Recomendação da IA: mover, salvo razão de conceito. Humano (claude-ia (ADR 0005)): —

#### 07401 — Carré
7.4 Carnes suínas com osso e sem osso · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 1 · 2017: 1 (padrão 11111)

#### 07402 — Costela
7.4 Carnes suínas com osso e sem osso · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 3 · 2008: 4 · 2017: 6 (padrão 11111)

#### 07403 — Lombo
7.4 Carnes suínas com osso e sem osso · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 3 · 2008: 4 · 2017: 5 (padrão 11111)

#### 07404 — Pernil
7.4 Carnes suínas com osso e sem osso · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 1 · 2017: 2 (padrão 11111)

#### 07405 — Porco eviscerado; Outras
7.4 Carnes suínas com osso e sem osso · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 2 · 2008: 6 · 2017: 8 (padrão 11111)

#### 07501 — Mortadela
7.5 Carnes suínas outras · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 2 · 2002: 2 · 2008: 3 · 2017: 3 (padrão 11111)
- Decisão 2026-10-16_claude-v3_alimentos-cocos-farinhas-panif-carnes#p11 MOVER **aceita** (16103 → 07501). IA: Outlier pontual: os mesmos produtos estão em 07501 em todas as outras edições em que aparecem (pelo menos 3); só em 1995 a célula está em 16103, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 07501) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —

#### 07502 — Presunto
7.5 Carnes suínas outras · status **ativo** · criado em base
Células por ano: 1987: 2 · 1995: 1 · 2002: 2 · 2008: 7 · 2017: 9 (padrão 11111)
- Decisão 2026-10-16_claude-v3_alimentos-cocos-farinhas-panif-carnes#p04 MOVER **aceita** (07506 → 07502). IA: Outlier pontual: os mesmos produtos estão em 07502 em todas as outras edições em que aparecem (pelo menos 3); só em 1987 a célula está em 07506, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 07502) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —

#### 07503 — Salsicha; Salsicha comum
7.5 Carnes suínas outras · status **ativo** · criado em base
Células por ano: 1987: 2 · 1995: 2 · 2002: 2 · 2008: 4 · 2017: 4 (padrão 11111)

#### 07504 — Toucinho fresco; Toucinho defumado; Toucinho
7.5 Carnes suínas outras · status **ativo** · criado em base
Células por ano: 1987: 3 · 1995: 3 · 2002: 3 · 2008: 3 · 2017: 3 (padrão 11111)

#### 07506 — Outras; Cane salgada não especificada; Costela de porco salgada; Paio; Pé de porco salgado; Salame
7.5 Carnes suínas outras · status **ativo** · criado em base
Células por ano: 1987: 22 · 1995: 23 · 2002: 19 · 2008: 28 · 2017: 37 (padrão 11111)
- Decisão 2026-10-16_claude-v3_alimentos-cocos-farinhas-panif-carnes#p03 MOVER **aceita** (07506 → 07208). IA: Outlier pontual: os mesmos produtos estão em 07208 em todas as outras edições em que aparecem (pelo menos 3); só em 1987 a célula está em 07506, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 07208) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_alimentos-cocos-farinhas-panif-carnes#p04 MOVER **aceita** (07506 → 07502). IA: Outlier pontual: os mesmos produtos estão em 07502 em todas as outras edições em que aparecem (pelo menos 3); só em 1987 a célula está em 07506, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 07502) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_alimentos-cocos-farinhas-panif-carnes#p05 MOVER **aceita** (07506 → 07601). IA: Outlier pontual: os mesmos produtos estão em 07601 em todas as outras edições em que aparecem (pelo menos 3); só em 1987 a célula está em 07506, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 07601) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_alimentos-cocos-farinhas-panif-carnes#p06 MOVER **aceita** (07506 → 07602). IA: Outlier pontual: os mesmos produtos estão em 07602 em todas as outras edições em que aparecem (pelo menos 3); só em 1987 a célula está em 07506, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 07602) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_alimentos-cocos-farinhas-panif-carnes#p10 MOVER **aceita** (07506 → 07602). IA: Outlier pontual: os mesmos produtos estão em 07602 em todas as outras edições em que aparecem (pelo menos 3); só em 1995 a célula está em 07506, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 07602) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_alimentos-cocos-farinhas-panif-carnes#p12 MOVER **aceita** (16103 → 07506). IA: Outlier pontual: os mesmos produtos estão em 07506 em todas as outras edições em que aparecem (pelo menos 3); só em 1995 a célula está em 16103, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 07506) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_alimentos-cocos-farinhas-panif-carnes#p25 REVISAR **aceita**. IA: Os mesmos produtos estão em 07602 nas duas outras edições em que aparecem; em 2002 estão em 07506. Duas edições contra uma, sem segunda fonte (IBGE neutro ou ausente, sem revisão manual): pela ADR 0005 não é óbvio. Recomendação da IA: mover, salvo razão de conceito. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_alimentos-visceras-a-oleos#p16 REVISAR **aceita**. IA: Os mesmos produtos estão em 08103 nas duas outras edições em que aparecem; em 2002 estão em 07506. Duas edições contra uma, sem segunda fonte (IBGE neutro ou ausente, sem revisão manual): pela ADR 0005 não é óbvio. Recomendação da IA: mover, salvo razão de conceito. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_alimentos-visceras-a-oleos#p17 REVISAR **aceita**. IA: Os mesmos produtos estão em 10107 nas duas outras edições em que aparecem; em 2002 estão em 07506. Duas edições contra uma, sem segunda fonte (IBGE neutro ou ausente, sem revisão manual): pela ADR 0005 não é óbvio. Recomendação da IA: mover, salvo razão de conceito. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_comida-fora-de-casa#p01 REVISAR **aceita**. IA: Não há como decidir célula a célula sem uma regra: hoje a mesma despesa (refrigerante tomado na rua) muda de grupo conforme a edição. Duas opções coerentes: (A) tudo do quadro de comida fora em 16104 (ou num grupo novo 'Alimentação fora do domicílio' dividido em refeição e lanche/bebida), o que dá uma série de 'comer fora' comparável; (B) tudo por produto, o que soma comer fora a comer em casa em cada produto. A IA recomenda (A), porque o questionário separa o quadro em todas as edições e porque o IBGE publica alimentação fora do domicílio à parte. É decisão estrutural (REGRA, possivelmente CRIAR), por isso fica para o humano (ADR 0005). Humano (claude-ia (ADR 0005)): —

#### 07601 — Linguiça
7.6 Carnes de outros animais · status **ativo** · criado em base
Células por ano: 1987: 6 · 1995: 4 · 2002: 3 · 2008: 2 · 2017: 2 (padrão 11111)
- Decisão 2026-10-16_claude-v3_alimentos-cocos-farinhas-panif-carnes#p05 MOVER **aceita** (07506 → 07601). IA: Outlier pontual: os mesmos produtos estão em 07601 em todas as outras edições em que aparecem (pelo menos 3); só em 1987 a célula está em 07506, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 07601) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —

#### 07602 — Outras; Carne de cabrito; Carne de carneiro
7.6 Carnes de outros animais · status **ativo** · criado em base
Células por ano: 1987: 21 · 1995: 9 · 2002: 22 · 2008: 16 · 2017: 18 (padrão 11111)
- Decisão 2026-10-16_claude-v3_alimentos-cocos-farinhas-panif-carnes#p06 MOVER **aceita** (07506 → 07602). IA: Outlier pontual: os mesmos produtos estão em 07602 em todas as outras edições em que aparecem (pelo menos 3); só em 1987 a célula está em 07506, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 07602) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_alimentos-cocos-farinhas-panif-carnes#p09 MOVER **aceita** (07208 → 07602). IA: Outlier pontual: os mesmos produtos estão em 07602 em todas as outras edições em que aparecem (pelo menos 3); só em 1995 a célula está em 07208, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 07602) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_alimentos-cocos-farinhas-panif-carnes#p10 MOVER **aceita** (07506 → 07602). IA: Outlier pontual: os mesmos produtos estão em 07602 em todas as outras edições em que aparecem (pelo menos 3); só em 1995 a célula está em 07506, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 07602) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_alimentos-cocos-farinhas-panif-carnes#p26 REVISAR **aceita**. IA: Os mesmos produtos estão em 07402 nas duas outras edições em que aparecem; em 2002 estão em 07602. Duas edições contra uma, sem segunda fonte (IBGE neutro ou ausente, sem revisão manual): pela ADR 0005 não é óbvio. Recomendação da IA: mover, salvo razão de conceito. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_alimentos-cocos-farinhas-panif-carnes#p27 REVISAR **aceita**. IA: Os mesmos produtos estão em 07404 nas duas outras edições em que aparecem; em 2002 estão em 07602. Duas edições contra uma, sem segunda fonte (IBGE neutro ou ausente, sem revisão manual): pela ADR 0005 não é óbvio. Recomendação da IA: mover, salvo razão de conceito. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_alimentos-visceras-a-oleos#p04 MOVER **aceita** (07602 → 10107). IA: Outlier pontual: os mesmos produtos estão em 10107 em todas as outras edições em que aparecem (pelo menos 3); só em 1995 a célula está em 07602, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 10107) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_alimentos-visceras-a-oleos#p18 REVISAR **aceita**. IA: Os mesmos produtos estão em 08104 nas duas outras edições em que aparecem; em 2002 estão em 07602. Duas edições contra uma, sem segunda fonte (IBGE neutro ou ausente, sem revisão manual): pela ADR 0005 não é óbvio. Recomendação da IA: mover, salvo razão de conceito. Humano (claude-ia (ADR 0005)): —

### 8. Vísceras

#### 08101 — Bovina Fígado
8.1 Vísceras · status **ativo** · criado em base
Células por ano: 1987: 3 · 1995: 3 · 2002: 3 · 2008: 3 · 2017: 4 (padrão 11111)
- Decisão 2026-10-16_claude-v3_alimentos-cocos-farinhas-panif-carnes#p07 MOVER **aceita** (08101 → 07208). IA: Outlier pontual: os mesmos produtos estão em 07208 em todas as outras edições em que aparecem (pelo menos 3); só em 1987 a célula está em 08101, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 07208) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —

#### 08102 — Bovina Outras; Bucho; Língua
8.1 Vísceras · status **ativo** · criado em base
Células por ano: 1987: 14 · 1995: 15 · 2002: 16 · 2008: 16 · 2017: 17 (padrão 11111)
- Decisão 2026-10-16_claude-v3_alimentos-cocos-farinhas-panif-carnes#p28 REVISAR **aceita**. IA: Os mesmos produtos estão em 07208 nas duas outras edições em que aparecem; em 2002 estão em 08102. Duas edições contra uma, sem segunda fonte (IBGE neutro ou ausente, sem revisão manual): pela ADR 0005 não é óbvio. Recomendação da IA: mover, salvo razão de conceito. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_alimentos-visceras-a-oleos#p09 MOVER **aceita** (16103 → 08102). IA: Outlier pontual: os mesmos produtos estão em 08102 em todas as outras edições em que aparecem (pelo menos 3); só em 1995 a célula está em 16103, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 08102) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —

#### 08103 — Vísceras suínas
8.1 Vísceras · status **ativo** · criado em base
Células por ano: 1987: 19 · 1995: 21 · 2002: 24 · 2008: 15 · 2017: 15 (padrão 11111)
- Decisão 2026-10-16_claude-v3_alimentos-cocos-farinhas-panif-carnes#p29 REVISAR **aceita**. IA: Os mesmos produtos estão em 07103 nas duas outras edições em que aparecem; em 2002 estão em 08103. Duas edições contra uma, sem segunda fonte (IBGE neutro ou ausente, sem revisão manual): pela ADR 0005 não é óbvio. Recomendação da IA: mover, salvo razão de conceito. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_alimentos-cocos-farinhas-panif-carnes#p30 REVISAR **aceita**. IA: Os mesmos produtos estão em 07506 nas duas outras edições em que aparecem; em 2002 estão em 08103. Duas edições contra uma, sem segunda fonte (IBGE neutro ou ausente, sem revisão manual): pela ADR 0005 não é óbvio. Recomendação da IA: mover, salvo razão de conceito. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_alimentos-visceras-a-oleos#p12 MOVER **aceita** (08103 → 08104). IA: Outlier pontual: os mesmos produtos estão em 08104 em todas as outras edições em que aparecem (pelo menos 4); só em 2002 a célula está em 08103, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 08104) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_alimentos-visceras-a-oleos#p19 REVISAR **aceita**. IA: Os mesmos produtos estão em 08104 nas duas outras edições em que aparecem; em 2002 estão em 08103. Duas edições contra uma, sem segunda fonte (IBGE neutro ou ausente, sem revisão manual): pela ADR 0005 não é óbvio. Recomendação da IA: mover, salvo razão de conceito. Humano (claude-ia (ADR 0005)): —

#### 08104 — Outras vísceras
8.1 Vísceras · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 15 · 2008: 17 · 2017: 18 (padrão 11111)
- Decisão 2026-10-16_claude-v3_alimentos-cocos-farinhas-panif-carnes#p31 REVISAR **aceita**. IA: Os mesmos produtos estão em 07506 nas duas outras edições em que aparecem; em 2002 estão em 08104. Duas edições contra uma, sem segunda fonte (IBGE neutro ou ausente, sem revisão manual): pela ADR 0005 não é óbvio. Recomendação da IA: mover, salvo razão de conceito. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_alimentos-visceras-a-oleos#p12 MOVER **aceita** (08103 → 08104). IA: Outlier pontual: os mesmos produtos estão em 08104 em todas as outras edições em que aparecem (pelo menos 4); só em 2002 a célula está em 08103, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 08104) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_alimentos-visceras-a-oleos#p20 REVISAR **aceita**. IA: Os mesmos produtos estão em 08102 nas duas outras edições em que aparecem; em 2002 estão em 08104. Duas edições contra uma, sem segunda fonte (IBGE neutro ou ausente, sem revisão manual): pela ADR 0005 não é óbvio. Recomendação da IA: mover, salvo razão de conceito. Humano (claude-ia (ADR 0005)): —

### 9. Pescados

#### 09101 — Bacalhau
9.1 Pescados de água salgada · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 1 · 2017: 1 (padrão 11111)

#### 09102 — Camarão fresco
9.1 Pescados de água salgada · status **ativo** · criado em base
Células por ano: 1987: 5 · 1995: 3 · 2002: 6 · 2008: 7 · 2017: 8 (padrão 11111)

#### 09103 — Corvina fresca
9.1 Pescados de água salgada · status **ativo** · criado em base
Células por ano: 1987: 3 · 1995: 4 · 2002: 7 · 2008: 7 · 2017: 7 (padrão 11111)
- Decisão 2026-10-16_claude-v3_alimentos-visceras-a-oleos#p05 MOVER **aceita** (09109 → 09103). IA: Outlier pontual: os mesmos produtos estão em 09103 em todas as outras edições em que aparecem (pelo menos 3); só em 1995 a célula está em 09109, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 09103) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —

#### 09104 — Pescada em filé fresco
9.1 Pescados de água salgada · status **ativo** · criado em base
Células por ano: 1987: 6 · 1995: 5 · 2002: 7 · 2008: 8 · 2017: 8 (padrão 11111)
- Decisão 2026-10-16_claude-v3_alimentos-visceras-a-oleos#p01 MOVER **aceita** (09109 → 09104). IA: Outlier pontual: os mesmos produtos estão em 09104 em todas as outras edições em que aparecem (pelo menos 3); só em 1987 a célula está em 09109, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 09104) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —

#### 09107 — Sardinha em conserva
9.1 Pescados de água salgada · status **ativo** · criado em base
Células por ano: 1987: 4 · 1995: 4 · 2002: 1 · 2008: 2 · 2017: 3 (padrão 11111)

#### 09108 — Sardinha fresca
9.1 Pescados de água salgada · status **ativo** · criado em base
Células por ano: 1987: 3 · 1995: 3 · 2002: 11 · 2008: 11 · 2017: 11 (padrão 11111)

#### 09109 — Outros; Anchova fresca; Bagre fresco; Cação fresco; Meluza em filé congelado; Merluza em filé fresco; Parati fresco; Pescada em filé congelado; Tainha fresca; Outros pescados em filé congelado; Outros pescados em filé fresco; Outros pescados frescos; Outros pescados salgados
9.1 Pescados de água salgada · status **ativo** · criado em base
Células por ano: 1987: 407 · 1995: 395 · 2002: 356 · 2008: 356 · 2017: 361 (padrão 11111)
- Decisão 2026-10-16_claude-v3_alimentos-visceras-a-oleos#p01 MOVER **aceita** (09109 → 09104). IA: Outlier pontual: os mesmos produtos estão em 09104 em todas as outras edições em que aparecem (pelo menos 3); só em 1987 a célula está em 09109, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 09104) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_alimentos-visceras-a-oleos#p05 MOVER **aceita** (09109 → 09103). IA: Outlier pontual: os mesmos produtos estão em 09103 em todas as outras edições em que aparecem (pelo menos 3); só em 1995 a célula está em 09109, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 09103) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_alimentos-visceras-a-oleos#p10 MOVER **aceita** (16103 → 09109). IA: Outlier pontual: os mesmos produtos estão em 09109 em todas as outras edições em que aparecem (pelo menos 3); só em 1995 a célula está em 16103, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 09109) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —

#### 09201 — Pescados de água doce; Acará fresca; Acari fresco; Anujá fresco; Curimatã fresco; Dourada fresca; Jaraqui fresco; Lambari fresco; Mapará fresco; Piau fresco; Surubim fresco; Tambaqui fresco; Tilápia fresca; Traíra fresca; Tucunaré fresco; Outros pescados em filé congelado; Outros pescados em filé fresco; Outros pescados frescos; Outros pescados salgados; Pescados não especificados; Peixe em filé congelado; Peixe em filé fresco; Peixe fresco; Peixe salgado
9.2 Pescados de água doce e congelados · status **ativo** · criado em base
Células por ano: 1987: 261 · 1995: 256 · 2002: 271 · 2008: 275 · 2017: 276 (padrão 11111)

### 10. Aves e ovos

#### 10101 — Asa de frango; Asa de galinha
10.1 Aves · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 2 · 2017: 2 (padrão 11111)

#### 10102 — Carne de frango não especificada; Carne não especificada de galinha
10.1 Aves · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 7 · 2008: 12 · 2017: 14 (padrão 11111)
- Decisão 2026-10-16_claude-v3_alimentos-visceras-a-oleos#p13 MOVER **aceita** (10107 → 10102). IA: Outlier pontual: os mesmos produtos estão em 10102 em todas as outras edições em que aparecem (pelo menos 3); só em 2002 a célula está em 10107, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 10102) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —

#### 10103 — Coxa de frango; Coxa de galinha
10.1 Aves · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 2 · 2017: 2 (padrão 11111)

#### 10104 — Frango abatido (inteiro); Frango abatido
10.1 Aves · status **ativo** · criado em base
Células por ano: 1987: 3 · 1995: 2 · 2002: 2 · 2008: 5 · 2017: 5 (padrão 11111)

#### 10105 — Frango vivo
10.1 Aves · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 1 · 2017: 1 (padrão 11111)

#### 10106 — Peito de frango; Peito de galinha
10.1 Aves · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 3 · 2017: 3 (padrão 11111)

#### 10107 — Outras; Dorso de frango; Miúdos de frango; Outras carnes de frango; Pato inteiro ou em cortes; Peru abatido; Peru em cortes
10.1 Aves · status **ativo** · criado em base
Células por ano: 1987: 32 · 1995: 27 · 2002: 43 · 2008: 48 · 2017: 53 (padrão 11111)
- Decisão 2026-10-16_claude-v3_alimentos-bebidas-outros#p17 REVISAR **aceita**. IA: Os mesmos produtos estão em 16103 nas duas outras edições em que aparecem; em 2002 estão em 10107. Duas edições contra uma, sem segunda fonte (IBGE neutro ou ausente, sem revisão manual): pela ADR 0005 não é óbvio. Recomendação da IA: mover, salvo razão de conceito. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_alimentos-visceras-a-oleos#p04 MOVER **aceita** (07602 → 10107). IA: Outlier pontual: os mesmos produtos estão em 10107 em todas as outras edições em que aparecem (pelo menos 3); só em 1995 a célula está em 07602, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 10107) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_alimentos-visceras-a-oleos#p11 MOVER **aceita** (16103 → 10107). IA: Outlier pontual: os mesmos produtos estão em 10107 em todas as outras edições em que aparecem (pelo menos 3); só em 1995 a célula está em 16103, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 10107) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_alimentos-visceras-a-oleos#p13 MOVER **aceita** (10107 → 10102). IA: Outlier pontual: os mesmos produtos estão em 10102 em todas as outras edições em que aparecem (pelo menos 3); só em 2002 a célula está em 10107, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 10102) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_alimentos-visceras-a-oleos#p21 REVISAR **aceita**. IA: Os mesmos produtos estão em 10101 nas duas outras edições em que aparecem; em 2002 estão em 10107. Duas edições contra uma, sem segunda fonte (IBGE neutro ou ausente, sem revisão manual): pela ADR 0005 não é óbvio. Recomendação da IA: mover, salvo razão de conceito. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_alimentos-visceras-a-oleos#p22 REVISAR **aceita**. IA: Os mesmos produtos estão em 10102 nas duas outras edições em que aparecem; em 2002 estão em 10107. Duas edições contra uma, sem segunda fonte (IBGE neutro ou ausente, sem revisão manual): pela ADR 0005 não é óbvio. Recomendação da IA: mover, salvo razão de conceito. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_alimentos-visceras-a-oleos#p23 REVISAR **aceita**. IA: Os mesmos produtos estão em 10202 nas duas outras edições em que aparecem; em 2002 estão em 10107. Duas edições contra uma, sem segunda fonte (IBGE neutro ou ausente, sem revisão manual): pela ADR 0005 não é óbvio. Recomendação da IA: mover, salvo razão de conceito. Humano (claude-ia (ADR 0005)): —

#### 10201 — Ovo de galinha
10.2 Ovos · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 2 · 2017: 2 (padrão 11111)

#### 10202 — Outros
10.2 Ovos · status **ativo** · criado em base
Células por ano: 1987: 3 · 1995: 3 · 2002: 2 · 2008: 8 · 2017: 8 (padrão 11111)

### 11. Laticínios

#### 11101 — Creme de leite; Creme de leite em conserva
11.1 Leite e creme de leite · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 2 · 2008: 6 · 2017: 7 (padrão 11111)

#### 11102 — Leite condensado
11.1 Leite e creme de leite · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 3 · 2017: 4 (padrão 11111)

#### 11103 — Leite de vaca fresco
11.1 Leite e creme de leite · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 6 · 2017: 5 (padrão 11111)
- Decisão 2026-10-16_claude-v3_comida-fora-de-casa#p01 REVISAR **aceita**. IA: Não há como decidir célula a célula sem uma regra: hoje a mesma despesa (refrigerante tomado na rua) muda de grupo conforme a edição. Duas opções coerentes: (A) tudo do quadro de comida fora em 16104 (ou num grupo novo 'Alimentação fora do domicílio' dividido em refeição e lanche/bebida), o que dá uma série de 'comer fora' comparável; (B) tudo por produto, o que soma comer fora a comer em casa em cada produto. A IA recomenda (A), porque o questionário separa o quadro em todas as edições e porque o IBGE publica alimentação fora do domicílio à parte. É decisão estrutural (REGRA, possivelmente CRIAR), por isso fica para o humano (ADR 0005). Humano (claude-ia (ADR 0005)): —

#### 11104 — Leite de vaca pasteurizado
11.1 Leite e creme de leite · status **ativo** · criado em base
Células por ano: 1987: 2 · 1995: 1 · 2002: 1 · 2008: 5 · 2017: 6 (padrão 11111)

#### 11105 — Leite em pó integral; Leite em pó desengordurado; Leite em pó não especificado
11.1 Leite e creme de leite · status **ativo** · criado em base
Células por ano: 1987: 3 · 1995: 3 · 2002: 3 · 2008: 5 · 2017: 12 (padrão 11111)

#### 11106 — Outros
11.1 Leite e creme de leite · status **ativo** · criado em base
Células por ano: 1987: 10 · 1995: 7 · 2002: 9 · 2008: 14 · 2017: 12 (padrão 11111)
- Decisão 2026-10-16_claude-v3_alimentos-visceras-a-oleos#p06 MOVER **aceita** (11106 → 11204). IA: Outlier pontual: os mesmos produtos estão em 11204 em todas as outras edições em que aparecem (pelo menos 3); só em 1995 a célula está em 11106, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 11204) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_comida-fora-de-casa#p01 REVISAR **aceita**. IA: Não há como decidir célula a célula sem uma regra: hoje a mesma despesa (refrigerante tomado na rua) muda de grupo conforme a edição. Duas opções coerentes: (A) tudo do quadro de comida fora em 16104 (ou num grupo novo 'Alimentação fora do domicílio' dividido em refeição e lanche/bebida), o que dá uma série de 'comer fora' comparável; (B) tudo por produto, o que soma comer fora a comer em casa em cada produto. A IA recomenda (A), porque o questionário separa o quadro em todas as edições e porque o IBGE publica alimentação fora do domicílio à parte. É decisão estrutural (REGRA, possivelmente CRIAR), por isso fica para o humano (ADR 0005). Humano (claude-ia (ADR 0005)): —

#### 11201 — Queijo minas
11.2 Queijos e requeijão · status **ativo** · criado em base
Células por ano: 1987: 2 · 1995: 1 · 2002: 1 · 2008: 5 · 2017: 4 (padrão 11111)
- Decisão 2026-10-16_claude-v3_comida-fora-de-casa#p01 REVISAR **aceita**. IA: Não há como decidir célula a célula sem uma regra: hoje a mesma despesa (refrigerante tomado na rua) muda de grupo conforme a edição. Duas opções coerentes: (A) tudo do quadro de comida fora em 16104 (ou num grupo novo 'Alimentação fora do domicílio' dividido em refeição e lanche/bebida), o que dá uma série de 'comer fora' comparável; (B) tudo por produto, o que soma comer fora a comer em casa em cada produto. A IA recomenda (A), porque o questionário separa o quadro em todas as edições e porque o IBGE publica alimentação fora do domicílio à parte. É decisão estrutural (REGRA, possivelmente CRIAR), por isso fica para o humano (ADR 0005). Humano (claude-ia (ADR 0005)): —

#### 11202 — Queijo mozarela
11.2 Queijos e requeijão · status **ativo** · criado em base
Células por ano: 1987: 2 · 1995: 2 · 2002: 1 · 2008: 3 · 2017: 3 (padrão 11111)
- Decisão 2026-10-16_claude-v3_comida-fora-de-casa#p01 REVISAR **aceita**. IA: Não há como decidir célula a célula sem uma regra: hoje a mesma despesa (refrigerante tomado na rua) muda de grupo conforme a edição. Duas opções coerentes: (A) tudo do quadro de comida fora em 16104 (ou num grupo novo 'Alimentação fora do domicílio' dividido em refeição e lanche/bebida), o que dá uma série de 'comer fora' comparável; (B) tudo por produto, o que soma comer fora a comer em casa em cada produto. A IA recomenda (A), porque o questionário separa o quadro em todas as edições e porque o IBGE publica alimentação fora do domicílio à parte. É decisão estrutural (REGRA, possivelmente CRIAR), por isso fica para o humano (ADR 0005). Humano (claude-ia (ADR 0005)): —

#### 11203 — Queijo prato
11.2 Queijos e requeijão · status **ativo** · criado em base
Células por ano: 1987: 2 · 1995: 1 · 2002: 1 · 2008: 3 · 2017: 3 (padrão 11111)
- Decisão 2026-10-16_claude-v3_alimentos-visceras-a-oleos#p02 MOVER **aceita** (11204 → 11203). IA: Outlier pontual: os mesmos produtos estão em 11203 em todas as outras edições em que aparecem (pelo menos 3); só em 1987 a célula está em 11204, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 11203) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_comida-fora-de-casa#p01 REVISAR **aceita**. IA: Não há como decidir célula a célula sem uma regra: hoje a mesma despesa (refrigerante tomado na rua) muda de grupo conforme a edição. Duas opções coerentes: (A) tudo do quadro de comida fora em 16104 (ou num grupo novo 'Alimentação fora do domicílio' dividido em refeição e lanche/bebida), o que dá uma série de 'comer fora' comparável; (B) tudo por produto, o que soma comer fora a comer em casa em cada produto. A IA recomenda (A), porque o questionário separa o quadro em todas as edições e porque o IBGE publica alimentação fora do domicílio à parte. É decisão estrutural (REGRA, possivelmente CRIAR), por isso fica para o humano (ADR 0005). Humano (claude-ia (ADR 0005)): —

#### 11204 — Outros queijos; Queijo não especificado; Queijo parmezão
11.2 Queijos e requeijão · status **ativo** · criado em base
Células por ano: 1987: 15 · 1995: 12 · 2002: 10 · 2008: 25 · 2017: 35 (padrão 11111)
- Decisão 2026-10-16_claude-v3_alimentos-visceras-a-oleos#p02 MOVER **aceita** (11204 → 11203). IA: Outlier pontual: os mesmos produtos estão em 11203 em todas as outras edições em que aparecem (pelo menos 3); só em 1987 a célula está em 11204, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 11203) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_alimentos-visceras-a-oleos#p03 MOVER **aceita** (11204 → 11205). IA: Outlier pontual: os mesmos produtos estão em 11205 em todas as outras edições em que aparecem (pelo menos 3); só em 1987 a célula está em 11204, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 11205) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_alimentos-visceras-a-oleos#p06 MOVER **aceita** (11106 → 11204). IA: Outlier pontual: os mesmos produtos estão em 11204 em todas as outras edições em que aparecem (pelo menos 3); só em 1995 a célula está em 11106, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 11204) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_comida-fora-de-casa#p01 REVISAR **aceita**. IA: Não há como decidir célula a célula sem uma regra: hoje a mesma despesa (refrigerante tomado na rua) muda de grupo conforme a edição. Duas opções coerentes: (A) tudo do quadro de comida fora em 16104 (ou num grupo novo 'Alimentação fora do domicílio' dividido em refeição e lanche/bebida), o que dá uma série de 'comer fora' comparável; (B) tudo por produto, o que soma comer fora a comer em casa em cada produto. A IA recomenda (A), porque o questionário separa o quadro em todas as edições e porque o IBGE publica alimentação fora do domicílio à parte. É decisão estrutural (REGRA, possivelmente CRIAR), por isso fica para o humano (ADR 0005). Humano (claude-ia (ADR 0005)): —

#### 11205 — Requeijão
11.2 Queijos e requeijão · status **ativo** · criado em base
Células por ano: 1987: 2 · 1995: 1 · 2002: 1 · 2008: 2 · 2017: 3 (padrão 11111)
- Decisão 2026-10-16_claude-v3_alimentos-visceras-a-oleos#p03 MOVER **aceita** (11204 → 11205). IA: Outlier pontual: os mesmos produtos estão em 11205 em todas as outras edições em que aparecem (pelo menos 3); só em 1987 a célula está em 11204, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 11205) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —

#### 11301 — Iogurte
11.3 Outros laticínios · status **ativo** · criado em base
Células por ano: 1987: 2 · 1995: 2 · 2002: 2 · 2008: 9 · 2017: 9 (padrão 11111)
- Decisão 2026-10-16_claude-v3_comida-fora-de-casa#p01 REVISAR **aceita**. IA: Não há como decidir célula a célula sem uma regra: hoje a mesma despesa (refrigerante tomado na rua) muda de grupo conforme a edição. Duas opções coerentes: (A) tudo do quadro de comida fora em 16104 (ou num grupo novo 'Alimentação fora do domicílio' dividido em refeição e lanche/bebida), o que dá uma série de 'comer fora' comparável; (B) tudo por produto, o que soma comer fora a comer em casa em cada produto. A IA recomenda (A), porque o questionário separa o quadro em todas as edições e porque o IBGE publica alimentação fora do domicílio à parte. É decisão estrutural (REGRA, possivelmente CRIAR), por isso fica para o humano (ADR 0005). Humano (claude-ia (ADR 0005)): —

#### 11302 — Leite fermentado
11.3 Outros laticínios · status **ativo** · criado em base
Células por ano: 1987: 3 · 1995: 3 · 2002: 2 · 2008: 4 · 2017: 3 (padrão 11111)
- Decisão 2026-10-16_claude-v3_comida-fora-de-casa#p01 REVISAR **aceita**. IA: Não há como decidir célula a célula sem uma regra: hoje a mesma despesa (refrigerante tomado na rua) muda de grupo conforme a edição. Duas opções coerentes: (A) tudo do quadro de comida fora em 16104 (ou num grupo novo 'Alimentação fora do domicílio' dividido em refeição e lanche/bebida), o que dá uma série de 'comer fora' comparável; (B) tudo por produto, o que soma comer fora a comer em casa em cada produto. A IA recomenda (A), porque o questionário separa o quadro em todas as edições e porque o IBGE publica alimentação fora do domicílio à parte. É decisão estrutural (REGRA, possivelmente CRIAR), por isso fica para o humano (ADR 0005). Humano (claude-ia (ADR 0005)): —

#### 11303 — Manteiga
11.3 Outros laticínios · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 2 · 2017: 3 (padrão 11111)

#### 11304 — Outros
11.3 Outros laticínios · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 2 · 2002: 3 · 2008: 6 · 2017: 10 (padrão 11111)
- Decisão 2026-10-16_claude-v3_comida-fora-de-casa#p01 REVISAR **aceita**. IA: Não há como decidir célula a célula sem uma regra: hoje a mesma despesa (refrigerante tomado na rua) muda de grupo conforme a edição. Duas opções coerentes: (A) tudo do quadro de comida fora em 16104 (ou num grupo novo 'Alimentação fora do domicílio' dividido em refeição e lanche/bebida), o que dá uma série de 'comer fora' comparável; (B) tudo por produto, o que soma comer fora a comer em casa em cada produto. A IA recomenda (A), porque o questionário separa o quadro em todas as edições e porque o IBGE publica alimentação fora do domicílio à parte. É decisão estrutural (REGRA, possivelmente CRIAR), por isso fica para o humano (ADR 0005). Humano (claude-ia (ADR 0005)): —

### 12. Açúcares e produtos de confeitaria

#### 12101 — Açúcar cristal
12.1 Açúcares, doces e produtos de confeitaria · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 2 · 2008: 4 · 2017: 4 (padrão 11111)

#### 12102 — Açúcar refinado; Açúcar não especificado; Açúcar demerara
12.1 Açúcares, doces e produtos de confeitaria · status **ativo** · criado em base
Células por ano: 1987: 3 · 1995: 2 · 2002: 2 · 2008: 4 · 2017: 4 (padrão 11111)

#### 12103 — Outros
12.1 Açúcares, doces e produtos de confeitaria · status **ativo** · criado em base
Células por ano: 1987: 3 · 1995: 3 · 2002: 11 · 2008: 21 · 2017: 20 (padrão 11111)
- Decisão 2026-10-16_claude-v3_comida-fora-de-casa#p01 REVISAR **aceita**. IA: Não há como decidir célula a célula sem uma regra: hoje a mesma despesa (refrigerante tomado na rua) muda de grupo conforme a edição. Duas opções coerentes: (A) tudo do quadro de comida fora em 16104 (ou num grupo novo 'Alimentação fora do domicílio' dividido em refeição e lanche/bebida), o que dá uma série de 'comer fora' comparável; (B) tudo por produto, o que soma comer fora a comer em casa em cada produto. A IA recomenda (A), porque o questionário separa o quadro em todas as edições e porque o IBGE publica alimentação fora do domicílio à parte. É decisão estrutural (REGRA, possivelmente CRIAR), por isso fica para o humano (ADR 0005). Humano (claude-ia (ADR 0005)): —

#### 12201 — Doce a base de leite
12.2 Doces e derivados · status **ativo** · criado em base
Células por ano: 1987: 13 · 1995: 13 · 2002: 10 · 2008: 19 · 2017: 22 (padrão 11111)

#### 12202 — Doce de fruta
12.2 Doces e derivados · status **ativo** · criado em base
Células por ano: 1987: 5 · 1995: 5 · 2002: 7 · 2008: 14 · 2017: 17 (padrão 11111)
- Decisão 2026-10-16_claude-v3_comida-fora-de-casa#p01 REVISAR **aceita**. IA: Não há como decidir célula a célula sem uma regra: hoje a mesma despesa (refrigerante tomado na rua) muda de grupo conforme a edição. Duas opções coerentes: (A) tudo do quadro de comida fora em 16104 (ou num grupo novo 'Alimentação fora do domicílio' dividido em refeição e lanche/bebida), o que dá uma série de 'comer fora' comparável; (B) tudo por produto, o que soma comer fora a comer em casa em cada produto. A IA recomenda (A), porque o questionário separa o quadro em todas as edições e porque o IBGE publica alimentação fora do domicílio à parte. É decisão estrutural (REGRA, possivelmente CRIAR), por isso fica para o humano (ADR 0005). Humano (claude-ia (ADR 0005)): —

#### 12203 — Sorvete
12.2 Doces e derivados · status **ativo** · criado em base
Células por ano: 1987: 3 · 1995: 3 · 2002: 2 · 2008: 8 · 2017: 11 (padrão 11111)
- Decisão 2026-10-16_claude-v3_comida-fora-de-casa#p01 REVISAR **aceita**. IA: Não há como decidir célula a célula sem uma regra: hoje a mesma despesa (refrigerante tomado na rua) muda de grupo conforme a edição. Duas opções coerentes: (A) tudo do quadro de comida fora em 16104 (ou num grupo novo 'Alimentação fora do domicílio' dividido em refeição e lanche/bebida), o que dá uma série de 'comer fora' comparável; (B) tudo por produto, o que soma comer fora a comer em casa em cada produto. A IA recomenda (A), porque o questionário separa o quadro em todas as edições e porque o IBGE publica alimentação fora do domicílio à parte. É decisão estrutural (REGRA, possivelmente CRIAR), por isso fica para o humano (ADR 0005). Humano (claude-ia (ADR 0005)): —

#### 12204 — Outros; Rapadura; Bombom; Chiclete; Chocolate em tablete
12.2 Doces e derivados · status **ativo** · criado em base
Células por ano: 1987: 27 · 1995: 30 · 2002: 44 · 2008: 74 · 2017: 74 (padrão 11111)
- Decisão 2026-10-16_claude-v3_alimentos-cocos-farinhas-panif-carnes#p32 REVISAR **aceita**. IA: Os mesmos produtos estão em 06201 nas duas outras edições em que aparecem; em 2002 estão em 12204. Duas edições contra uma, sem segunda fonte (IBGE neutro ou ausente, sem revisão manual): pela ADR 0005 não é óbvio. Recomendação da IA: mover, salvo razão de conceito. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_alimentos-cocos-farinhas-panif-carnes#p33 REVISAR **aceita**. IA: Os mesmos produtos estão em 06303 nas duas outras edições em que aparecem; em 2002 estão em 12204. Duas edições contra uma, sem segunda fonte (IBGE neutro ou ausente, sem revisão manual): pela ADR 0005 não é óbvio. Recomendação da IA: mover, salvo razão de conceito. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_alimentos-visceras-a-oleos#p07 MOVER **aceita** (12302 → 12204). IA: Outlier pontual: os mesmos produtos estão em 12204 em todas as outras edições em que aparecem (pelo menos 3); só em 1995 a célula está em 12302, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 12204) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_alimentos-visceras-a-oleos#p14 MOVER **aceita** (12204 → 12302). IA: Outlier pontual: os mesmos produtos estão em 12302 em todas as outras edições em que aparecem (pelo menos 3); só em 2002 a célula está em 12204, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 12302) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_comida-fora-de-casa#p01 REVISAR **aceita**. IA: Não há como decidir célula a célula sem uma regra: hoje a mesma despesa (refrigerante tomado na rua) muda de grupo conforme a edição. Duas opções coerentes: (A) tudo do quadro de comida fora em 16104 (ou num grupo novo 'Alimentação fora do domicílio' dividido em refeição e lanche/bebida), o que dá uma série de 'comer fora' comparável; (B) tudo por produto, o que soma comer fora a comer em casa em cada produto. A IA recomenda (A), porque o questionário separa o quadro em todas as edições e porque o IBGE publica alimentação fora do domicílio à parte. É decisão estrutural (REGRA, possivelmente CRIAR), por isso fica para o humano (ADR 0005). Humano (claude-ia (ADR 0005)): —

#### 12205 — Pamonha
12.2 Doces e derivados · status **ativo** · criado em base
Células por ano: 1987: 2 · 1995: 2 · 2002: 2 · 2008: 2 · 2017: 2 (padrão 11111)
- Decisão 2026-10-16_claude-v3_comida-fora-de-casa#p01 REVISAR **aceita**. IA: Não há como decidir célula a célula sem uma regra: hoje a mesma despesa (refrigerante tomado na rua) muda de grupo conforme a edição. Duas opções coerentes: (A) tudo do quadro de comida fora em 16104 (ou num grupo novo 'Alimentação fora do domicílio' dividido em refeição e lanche/bebida), o que dá uma série de 'comer fora' comparável; (B) tudo por produto, o que soma comer fora a comer em casa em cada produto. A IA recomenda (A), porque o questionário separa o quadro em todas as edições e porque o IBGE publica alimentação fora do domicílio à parte. É decisão estrutural (REGRA, possivelmente CRIAR), por isso fica para o humano (ADR 0005). Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_pendencias-validacao-e-criar#p34 REVISAR **aceita**. IA: Criar grupo é decisão estrutural (ADR + aprovação de outro membro). A IA conferiu que as células existem nas cinco edições, condição da R2 para manter a distinção; falta decidir se a granularidade vale um grupo próprio. Humano (claude-ia (ADR 0005)): —

#### 12301 — Chocolate em pó
12.3 Outros açucares e produtos de confeitaria · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 1 · 2017: 1 (padrão 11111)

#### 12302 — Outros; Polpa de fruta; Gelatina; Mel de abelha
12.3 Outros açucares e produtos de confeitaria · status **ativo** · criado em base
Células por ano: 1987: 3 · 1995: 4 · 2002: 4 · 2008: 13 · 2017: 15 (padrão 11111)
- Decisão 2026-10-16_claude-v3_alimentos-visceras-a-oleos#p07 MOVER **aceita** (12302 → 12204). IA: Outlier pontual: os mesmos produtos estão em 12204 em todas as outras edições em que aparecem (pelo menos 3); só em 1995 a célula está em 12302, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 12204) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_alimentos-visceras-a-oleos#p14 MOVER **aceita** (12204 → 12302). IA: Outlier pontual: os mesmos produtos estão em 12302 em todas as outras edições em que aparecem (pelo menos 3); só em 2002 a célula está em 12204, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 12302) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_comida-fora-de-casa#p01 REVISAR **aceita**. IA: Não há como decidir célula a célula sem uma regra: hoje a mesma despesa (refrigerante tomado na rua) muda de grupo conforme a edição. Duas opções coerentes: (A) tudo do quadro de comida fora em 16104 (ou num grupo novo 'Alimentação fora do domicílio' dividido em refeição e lanche/bebida), o que dá uma série de 'comer fora' comparável; (B) tudo por produto, o que soma comer fora a comer em casa em cada produto. A IA recomenda (A), porque o questionário separa o quadro em todas as edições e porque o IBGE publica alimentação fora do domicílio à parte. É decisão estrutural (REGRA, possivelmente CRIAR), por isso fica para o humano (ADR 0005). Humano (claude-ia (ADR 0005)): —

#### 12303 — Mel de abelha
12.3 Outros açucares e produtos de confeitaria · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 2 · 2017: 2 (padrão 11111)
- Decisão 2026-10-16_claude-v3_pendencias-validacao-e-criar#p35 REVISAR **aceita**. IA: Criar grupo é decisão estrutural (ADR + aprovação de outro membro). A IA conferiu que as células existem nas cinco edições, condição da R2 para manter a distinção; falta decidir se a granularidade vale um grupo próprio. Humano (claude-ia (ADR 0005)): —

#### 12304 — Melado de cana
12.3 Outros açucares e produtos de confeitaria · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 1 · 2017: 1 (padrão 11111)
- Decisão 2026-10-16_claude-v3_pendencias-validacao-e-criar#p36 REVISAR **aceita**. IA: Criar grupo é decisão estrutural (ADR + aprovação de outro membro). A IA conferiu que as células existem nas cinco edições, condição da R2 para manter a distinção; falta decidir se a granularidade vale um grupo próprio. Humano (claude-ia (ADR 0005)): —

#### 12305 — Gelatina
12.3 Outros açucares e produtos de confeitaria · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 4 · 2017: 5 (padrão 11111)
- Decisão 2026-10-16_claude-v3_comida-fora-de-casa#p01 REVISAR **aceita**. IA: Não há como decidir célula a célula sem uma regra: hoje a mesma despesa (refrigerante tomado na rua) muda de grupo conforme a edição. Duas opções coerentes: (A) tudo do quadro de comida fora em 16104 (ou num grupo novo 'Alimentação fora do domicílio' dividido em refeição e lanche/bebida), o que dá uma série de 'comer fora' comparável; (B) tudo por produto, o que soma comer fora a comer em casa em cada produto. A IA recomenda (A), porque o questionário separa o quadro em todas as edições e porque o IBGE publica alimentação fora do domicílio à parte. É decisão estrutural (REGRA, possivelmente CRIAR), por isso fica para o humano (ADR 0005). Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_pendencias-validacao-e-criar#p34 REVISAR **aceita**. IA: Criar grupo é decisão estrutural (ADR + aprovação de outro membro). A IA conferiu que as células existem nas cinco edições, condição da R2 para manter a distinção; falta decidir se a granularidade vale um grupo próprio. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_pendencias-validacao-e-criar#p37 REVISAR **aceita**. IA: Criar grupo é decisão estrutural (ADR + aprovação de outro membro). A IA conferiu que as células existem nas cinco edições, condição da R2 para manter a distinção; falta decidir se a granularidade vale um grupo próprio. Humano (claude-ia (ADR 0005)): —

### 13. Sais e condimentos

#### 13101 — Sal grosso
13.1 Sais · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 1 · 2017: 1 (padrão 11111)

#### 13102 — Sal refinado
13.1 Sais · status **ativo** · criado em base
Células por ano: 1987: 2 · 1995: 1 · 2002: 2 · 2008: 3 · 2017: 3 (padrão 11111)

#### 13103 — Outros
13.1 Sais · status **ativo** · criado em base
Células por ano: 1987: 2 · 1995: 2 · 2002: 4 · 2008: 4 · 2017: 7 (padrão 11111)

#### 13201 — Caldo de carne em tablete
13.2 Condimentos · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 1 · 2017: 1 (padrão 11111)

#### 13202 — Caldo de galinha em tablete
13.2 Condimentos · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 1 · 2017: 1 (padrão 11111)

#### 13203 — Fermento
13.2 Condimentos · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 1 · 2017: 1 (padrão 11111)

#### 13204 — Maionese
13.2 Condimentos · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 2 · 2017: 2 (padrão 11111)

#### 13205 — Massa de tomate
13.2 Condimentos · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 1 · 2017: 1 (padrão 11111)

#### 13206 — Molho de tomate
13.2 Condimentos · status **ativo** · criado em base
Células por ano: 1987: 2 · 1995: 2 · 2002: 3 · 2008: 4 · 2017: 4 (padrão 11111)

#### 13207 — Tempero misto
13.2 Condimentos · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 4 · 2008: 10 · 2017: 10 (padrão 11111)
- Decisão 2026-10-16_claude-v3_alimentos-visceras-a-oleos#p15 MOVER **aceita** (13207 → 13210). IA: Outlier pontual: os mesmos produtos estão em 13210 em todas as outras edições em que aparecem (pelo menos 4); só em 2002 a célula está em 13207, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 13210) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —

#### 13208 — Vinagre de álcool
13.2 Condimentos · status **ativo** · criado em base
Células por ano: 1987: 2 · 1995: 2 · 2002: 1 · 2008: 2 · 2017: 2 (padrão 11111)

#### 13209 — Vinagre de vinho
13.2 Condimentos · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 1 · 2017: 1 (padrão 11111)

#### 13210 — Outros; Vinagre não especificado; Coco ralado; Outros caldos em tablete; Colorau; Leite de coco
13.2 Condimentos · status **ativo** · criado em base
Células por ano: 1987: 46 · 1995: 59 · 2002: 68 · 2008: 100 · 2017: 122 (padrão 11111)
- Decisão 2026-10-16_claude-v3_alimentos-cereais-hortalicas-frutas#p02 MOVER **aceita** (13210 → 02212). IA: Outlier pontual: os mesmos produtos estão em 02212 em todas as outras edições em que aparecem (pelo menos 3); só em 1987 a célula está em 13210, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 02212) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_alimentos-cereais-hortalicas-frutas#p05 MOVER **aceita** (13210 → 02212). IA: Outlier pontual: os mesmos produtos estão em 02212 em todas as outras edições em que aparecem (pelo menos 3); só em 1995 a célula está em 13210, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 02212) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_alimentos-visceras-a-oleos#p15 MOVER **aceita** (13207 → 13210). IA: Outlier pontual: os mesmos produtos estão em 13210 em todas as outras edições em que aparecem (pelo menos 4); só em 2002 a célula está em 13207, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 13210) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —

### 14. Óleos e gorduras

#### 14101 — Azeite de oliva
14.1 Óleos · status **ativo** · criado em base
Células por ano: 1987: 2 · 1995: 1 · 2002: 1 · 2008: 2 · 2017: 3 (padrão 11111)

#### 14102 — Óleo de milho
14.1 Óleos · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 1 · 2017: 1 (padrão 11111)

#### 14103 — Óleo de soja
14.1 Óleos · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 2 · 2017: 2 (padrão 11111)

#### 14104 — Óleo não especificado; Óleo de girassol; Óleo de canola x. xOutros
14.1 Óleos · status **ativo** · criado em base
Células por ano: 1987: 15 · 1995: 16 · 2002: 23 · 2008: 26 · 2017: 26 (padrão 11111)
- Decisão 2026-10-16_claude-v3_alimentos-visceras-a-oleos#p08 MOVER **aceita** (14104 → 14202). IA: Outlier pontual: os mesmos produtos estão em 14202 em todas as outras edições em que aparecem (pelo menos 3); só em 1995 a célula está em 14104, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 14202) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_habitacao-servicos#p19 REVISAR **aceita**. IA: Os mesmos produtos estão em 32002 nas duas outras edições em que aparecem; em 2002 estão em 14104. Duas edições contra uma, sem segunda fonte (IBGE neutro ou ausente, sem revisão manual): pela ADR 0005 não é óbvio. Recomendação da IA: mover, salvo razão de conceito. Humano (claude-ia (ADR 0005)): —

#### 14201 — Margarina vegetal
14.2 Gorduras · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 2 · 2008: 4 · 2017: 5 (padrão 11111)

#### 14202 — Outras; Banha de porco
14.2 Gorduras · status **ativo** · criado em base
Células por ano: 1987: 9 · 1995: 10 · 2002: 11 · 2008: 11 · 2017: 11 (padrão 11111)
- Decisão 2026-10-16_claude-v3_alimentos-visceras-a-oleos#p08 MOVER **aceita** (14104 → 14202). IA: Outlier pontual: os mesmos produtos estão em 14202 em todas as outras edições em que aparecem (pelo menos 3); só em 1995 a célula está em 14104, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 14202) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —

### 15. Bebidas e infusões

#### 15101 — Outras aguardentes; Aguardente de cana
15.1 Bebidas alcoólicas · status **ativo** · criado em base
Células por ano: 1987: 5 · 1995: 7 · 2002: 7 · 2008: 15 · 2017: 15 (padrão 11111)
- Decisão 2026-10-16_claude-v3_alimentos-bebidas-outros#p01 MOVER **aceita** (15101 → 15104). IA: Outlier pontual: os mesmos produtos estão em 15104 em todas as outras edições em que aparecem (pelo menos 4); só em 1987 a célula está em 15101, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 15104) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_alimentos-bebidas-outros#p02 MOVER **aceita** (15104 → 15101). IA: Outlier pontual: os mesmos produtos estão em 15101 em todas as outras edições em que aparecem (pelo menos 4); só em 1987 a célula está em 15104, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 15101) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_alimentos-bebidas-outros#p06 MOVER **aceita** (15101 → 15206). IA: Outlier pontual: os mesmos produtos estão em 15206 em todas as outras edições em que aparecem (pelo menos 4); só em 1995 a célula está em 15101, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 15206) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_alimentos-bebidas-outros#p15 MOVER **aceita** (15101 → 15104). IA: Outlier pontual: os mesmos produtos estão em 15104 em todas as outras edições em que aparecem (pelo menos 3); só em 2002 a célula está em 15101, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 15104) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_alimentos-bebidas-outros#p18 REVISAR **aceita**. IA: Os mesmos produtos estão em 15208 nas duas outras edições em que aparecem; em 1995 estão em 15101. Duas edições contra uma, sem segunda fonte (IBGE neutro ou ausente, sem revisão manual): pela ADR 0005 não é óbvio. Recomendação da IA: mover, salvo razão de conceito. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_comida-fora-de-casa#p01 REVISAR **aceita**. IA: Não há como decidir célula a célula sem uma regra: hoje a mesma despesa (refrigerante tomado na rua) muda de grupo conforme a edição. Duas opções coerentes: (A) tudo do quadro de comida fora em 16104 (ou num grupo novo 'Alimentação fora do domicílio' dividido em refeição e lanche/bebida), o que dá uma série de 'comer fora' comparável; (B) tudo por produto, o que soma comer fora a comer em casa em cada produto. A IA recomenda (A), porque o questionário separa o quadro em todas as edições e porque o IBGE publica alimentação fora do domicílio à parte. É decisão estrutural (REGRA, possivelmente CRIAR), por isso fica para o humano (ADR 0005). Humano (claude-ia (ADR 0005)): —

#### 15102 — Cerveja
15.1 Bebidas alcoólicas · status **ativo** · criado em base
Células por ano: 1987: 6 · 1995: 5 · 2002: 6 · 2008: 10 · 2017: 9 (padrão 11111)
- Decisão 2026-10-16_claude-v3_alimentos-bebidas-outros#p03 MOVER **aceita** (15104 → 15102). IA: Outlier pontual: os mesmos produtos estão em 15102 em todas as outras edições em que aparecem (pelo menos 3); só em 1987 a célula está em 15104, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 15102) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_alimentos-bebidas-outros#p07 MOVER **aceita** (15102 → 15206). IA: Outlier pontual: os mesmos produtos estão em 15206 em todas as outras edições em que aparecem (pelo menos 4); só em 1995 a célula está em 15102, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 15206) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_alimentos-bebidas-outros#p08 MOVER **aceita** (15102 → 15402). IA: Outlier pontual: os mesmos produtos estão em 15402 em todas as outras edições em que aparecem (pelo menos 4); só em 1995 a célula está em 15102, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 15402) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_comida-fora-de-casa#p01 REVISAR **aceita**. IA: Não há como decidir célula a célula sem uma regra: hoje a mesma despesa (refrigerante tomado na rua) muda de grupo conforme a edição. Duas opções coerentes: (A) tudo do quadro de comida fora em 16104 (ou num grupo novo 'Alimentação fora do domicílio' dividido em refeição e lanche/bebida), o que dá uma série de 'comer fora' comparável; (B) tudo por produto, o que soma comer fora a comer em casa em cada produto. A IA recomenda (A), porque o questionário separa o quadro em todas as edições e porque o IBGE publica alimentação fora do domicílio à parte. É decisão estrutural (REGRA, possivelmente CRIAR), por isso fica para o humano (ADR 0005). Humano (claude-ia (ADR 0005)): —

#### 15103 — Vinho
15.1 Bebidas alcoólicas · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 4 · 2017: 4 (padrão 11111)
- Decisão 2026-10-16_claude-v3_alimentos-bebidas-outros#p09 MOVER **aceita** (15104 → 15103). IA: Outlier pontual: os mesmos produtos estão em 15103 em todas as outras edições em que aparecem (pelo menos 4); só em 1995 a célula está em 15104, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 15103) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_comida-fora-de-casa#p01 REVISAR **aceita**. IA: Não há como decidir célula a célula sem uma regra: hoje a mesma despesa (refrigerante tomado na rua) muda de grupo conforme a edição. Duas opções coerentes: (A) tudo do quadro de comida fora em 16104 (ou num grupo novo 'Alimentação fora do domicílio' dividido em refeição e lanche/bebida), o que dá uma série de 'comer fora' comparável; (B) tudo por produto, o que soma comer fora a comer em casa em cada produto. A IA recomenda (A), porque o questionário separa o quadro em todas as edições e porque o IBGE publica alimentação fora do domicílio à parte. É decisão estrutural (REGRA, possivelmente CRIAR), por isso fica para o humano (ADR 0005). Humano (claude-ia (ADR 0005)): —

#### 15104 — Outras
15.1 Bebidas alcoólicas · status **ativo** · criado em base
Células por ano: 1987: 20 · 1995: 30 · 2002: 24 · 2008: 31 · 2017: 33 (padrão 11111)
- Decisão 2026-10-16_claude-v3_alimentos-bebidas-outros#p01 MOVER **aceita** (15101 → 15104). IA: Outlier pontual: os mesmos produtos estão em 15104 em todas as outras edições em que aparecem (pelo menos 4); só em 1987 a célula está em 15101, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 15104) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_alimentos-bebidas-outros#p02 MOVER **aceita** (15104 → 15101). IA: Outlier pontual: os mesmos produtos estão em 15101 em todas as outras edições em que aparecem (pelo menos 4); só em 1987 a célula está em 15104, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 15101) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_alimentos-bebidas-outros#p03 MOVER **aceita** (15104 → 15102). IA: Outlier pontual: os mesmos produtos estão em 15102 em todas as outras edições em que aparecem (pelo menos 3); só em 1987 a célula está em 15104, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 15102) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_alimentos-bebidas-outros#p09 MOVER **aceita** (15104 → 15103). IA: Outlier pontual: os mesmos produtos estão em 15103 em todas as outras edições em que aparecem (pelo menos 4); só em 1995 a célula está em 15104, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 15103) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_alimentos-bebidas-outros#p10 MOVER **aceita** (15104 → 15206). IA: Outlier pontual: os mesmos produtos estão em 15206 em todas as outras edições em que aparecem (pelo menos 3); só em 1995 a célula está em 15104, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 15206) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_alimentos-bebidas-outros#p11 MOVER **aceita** (15104 → 15208). IA: Outlier pontual: os mesmos produtos estão em 15208 em todas as outras edições em que aparecem (pelo menos 3); só em 1995 a célula está em 15104, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 15208) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_alimentos-bebidas-outros#p12 MOVER **aceita** (15104 → 15402). IA: Outlier pontual: os mesmos produtos estão em 15402 em todas as outras edições em que aparecem (pelo menos 4); só em 1995 a célula está em 15104, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 15402) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_alimentos-bebidas-outros#p15 MOVER **aceita** (15101 → 15104). IA: Outlier pontual: os mesmos produtos estão em 15104 em todas as outras edições em que aparecem (pelo menos 3); só em 2002 a célula está em 15101, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 15104) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_comida-fora-de-casa#p01 REVISAR **aceita**. IA: Não há como decidir célula a célula sem uma regra: hoje a mesma despesa (refrigerante tomado na rua) muda de grupo conforme a edição. Duas opções coerentes: (A) tudo do quadro de comida fora em 16104 (ou num grupo novo 'Alimentação fora do domicílio' dividido em refeição e lanche/bebida), o que dá uma série de 'comer fora' comparável; (B) tudo por produto, o que soma comer fora a comer em casa em cada produto. A IA recomenda (A), porque o questionário separa o quadro em todas as edições e porque o IBGE publica alimentação fora do domicílio à parte. É decisão estrutural (REGRA, possivelmente CRIAR), por isso fica para o humano (ADR 0005). Humano (claude-ia (ADR 0005)): —

#### 15201 — Água mineral
15.2 Bebidas não alcoólicas · status **ativo** · criado em base
Células por ano: 1987: 4 · 1995: 4 · 2002: 6 · 2008: 4 · 2017: 4 (padrão 11111)
- Decisão 2026-10-16_claude-v3_comida-fora-de-casa#p01 REVISAR **aceita**. IA: Não há como decidir célula a célula sem uma regra: hoje a mesma despesa (refrigerante tomado na rua) muda de grupo conforme a edição. Duas opções coerentes: (A) tudo do quadro de comida fora em 16104 (ou num grupo novo 'Alimentação fora do domicílio' dividido em refeição e lanche/bebida), o que dá uma série de 'comer fora' comparável; (B) tudo por produto, o que soma comer fora a comer em casa em cada produto. A IA recomenda (A), porque o questionário separa o quadro em todas as edições e porque o IBGE publica alimentação fora do domicílio à parte. É decisão estrutural (REGRA, possivelmente CRIAR), por isso fica para o humano (ADR 0005). Humano (claude-ia (ADR 0005)): —

#### 15202 — Refrigerante de cola
15.2 Bebidas não alcoólicas · status **ativo** · criado em base
Células por ano: 1987: 4 · 1995: 3 · 2002: 1 · 2008: 7 · 2017: 4 (padrão 11111)
- Decisão 2026-10-16_claude-v3_comida-fora-de-casa#p01 REVISAR **aceita**. IA: Não há como decidir célula a célula sem uma regra: hoje a mesma despesa (refrigerante tomado na rua) muda de grupo conforme a edição. Duas opções coerentes: (A) tudo do quadro de comida fora em 16104 (ou num grupo novo 'Alimentação fora do domicílio' dividido em refeição e lanche/bebida), o que dá uma série de 'comer fora' comparável; (B) tudo por produto, o que soma comer fora a comer em casa em cada produto. A IA recomenda (A), porque o questionário separa o quadro em todas as edições e porque o IBGE publica alimentação fora do domicílio à parte. É decisão estrutural (REGRA, possivelmente CRIAR), por isso fica para o humano (ADR 0005). Humano (claude-ia (ADR 0005)): —

#### 15203 — Refrigerante de guaraná
15.2 Bebidas não alcoólicas · status **ativo** · criado em base
Células por ano: 1987: 2 · 1995: 2 · 2002: 2 · 2008: 5 · 2017: 3 (padrão 11111)
- Decisão 2026-10-16_claude-v3_comida-fora-de-casa#p01 REVISAR **aceita**. IA: Não há como decidir célula a célula sem uma regra: hoje a mesma despesa (refrigerante tomado na rua) muda de grupo conforme a edição. Duas opções coerentes: (A) tudo do quadro de comida fora em 16104 (ou num grupo novo 'Alimentação fora do domicílio' dividido em refeição e lanche/bebida), o que dá uma série de 'comer fora' comparável; (B) tudo por produto, o que soma comer fora a comer em casa em cada produto. A IA recomenda (A), porque o questionário separa o quadro em todas as edições e porque o IBGE publica alimentação fora do domicílio à parte. É decisão estrutural (REGRA, possivelmente CRIAR), por isso fica para o humano (ADR 0005). Humano (claude-ia (ADR 0005)): —

#### 15204 — Refrigerante de laranja
15.2 Bebidas não alcoólicas · status **ativo** · criado em base
Células por ano: 1987: 3 · 1995: 3 · 2002: 1 · 2008: 4 · 2017: 2 (padrão 11111)
- Decisão 2026-10-16_claude-v3_comida-fora-de-casa#p01 REVISAR **aceita**. IA: Não há como decidir célula a célula sem uma regra: hoje a mesma despesa (refrigerante tomado na rua) muda de grupo conforme a edição. Duas opções coerentes: (A) tudo do quadro de comida fora em 16104 (ou num grupo novo 'Alimentação fora do domicílio' dividido em refeição e lanche/bebida), o que dá uma série de 'comer fora' comparável; (B) tudo por produto, o que soma comer fora a comer em casa em cada produto. A IA recomenda (A), porque o questionário separa o quadro em todas as edições e porque o IBGE publica alimentação fora do domicílio à parte. É decisão estrutural (REGRA, possivelmente CRIAR), por isso fica para o humano (ADR 0005). Humano (claude-ia (ADR 0005)): —

#### 15205 — Refrigerante de limão
15.2 Bebidas não alcoólicas · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 2 · 2008: 6 · 2017: 4 (padrão 11111)
- Decisão 2026-10-16_claude-v3_comida-fora-de-casa#p01 REVISAR **aceita**. IA: Não há como decidir célula a célula sem uma regra: hoje a mesma despesa (refrigerante tomado na rua) muda de grupo conforme a edição. Duas opções coerentes: (A) tudo do quadro de comida fora em 16104 (ou num grupo novo 'Alimentação fora do domicílio' dividido em refeição e lanche/bebida), o que dá uma série de 'comer fora' comparável; (B) tudo por produto, o que soma comer fora a comer em casa em cada produto. A IA recomenda (A), porque o questionário separa o quadro em todas as edições e porque o IBGE publica alimentação fora do domicílio à parte. É decisão estrutural (REGRA, possivelmente CRIAR), por isso fica para o humano (ADR 0005). Humano (claude-ia (ADR 0005)): —

#### 15206 — Outros refrigerantes; Refrigerante não especificado; Refrigerante de maçã; Refrigerante de uva; Bebida energética
15.2 Bebidas não alcoólicas · status **ativo** · criado em base
Células por ano: 1987: 22 · 1995: 22 · 2002: 28 · 2008: 69 · 2017: 68 (padrão 11111)
- Decisão 2026-10-16_claude-v3_alimentos-bebidas-outros#p06 MOVER **aceita** (15101 → 15206). IA: Outlier pontual: os mesmos produtos estão em 15206 em todas as outras edições em que aparecem (pelo menos 4); só em 1995 a célula está em 15101, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 15206) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_alimentos-bebidas-outros#p07 MOVER **aceita** (15102 → 15206). IA: Outlier pontual: os mesmos produtos estão em 15206 em todas as outras edições em que aparecem (pelo menos 4); só em 1995 a célula está em 15102, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 15206) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_alimentos-bebidas-outros#p10 MOVER **aceita** (15104 → 15206). IA: Outlier pontual: os mesmos produtos estão em 15206 em todas as outras edições em que aparecem (pelo menos 3); só em 1995 a célula está em 15104, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 15206) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_comida-fora-de-casa#p01 REVISAR **aceita**. IA: Não há como decidir célula a célula sem uma regra: hoje a mesma despesa (refrigerante tomado na rua) muda de grupo conforme a edição. Duas opções coerentes: (A) tudo do quadro de comida fora em 16104 (ou num grupo novo 'Alimentação fora do domicílio' dividido em refeição e lanche/bebida), o que dá uma série de 'comer fora' comparável; (B) tudo por produto, o que soma comer fora a comer em casa em cada produto. A IA recomenda (A), porque o questionário separa o quadro em todas as edições e porque o IBGE publica alimentação fora do domicílio à parte. É decisão estrutural (REGRA, possivelmente CRIAR), por isso fica para o humano (ADR 0005). Humano (claude-ia (ADR 0005)): —

#### 15207 — Suco de fruta em pó
15.2 Bebidas não alcoólicas · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 3 · 2017: 3 (padrão 11111)

#### 15208 — Suco de fruta envasado
15.2 Bebidas não alcoólicas · status **ativo** · criado em base
Células por ano: 1987: 5 · 1995: 5 · 2002: 8 · 2008: 28 · 2017: 28 (padrão 11111)
- Decisão 2026-10-16_claude-v3_alimentos-bebidas-outros#p11 MOVER **aceita** (15104 → 15208). IA: Outlier pontual: os mesmos produtos estão em 15208 em todas as outras edições em que aparecem (pelo menos 3); só em 1995 a célula está em 15104, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 15208) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_comida-fora-de-casa#p01 REVISAR **aceita**. IA: Não há como decidir célula a célula sem uma regra: hoje a mesma despesa (refrigerante tomado na rua) muda de grupo conforme a edição. Duas opções coerentes: (A) tudo do quadro de comida fora em 16104 (ou num grupo novo 'Alimentação fora do domicílio' dividido em refeição e lanche/bebida), o que dá uma série de 'comer fora' comparável; (B) tudo por produto, o que soma comer fora a comer em casa em cada produto. A IA recomenda (A), porque o questionário separa o quadro em todas as edições e porque o IBGE publica alimentação fora do domicílio à parte. É decisão estrutural (REGRA, possivelmente CRIAR), por isso fica para o humano (ADR 0005). Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_pendencias-formulario#p01 MANTER **aceita**. IA: As sugestões do formulário já estão aplicadas no estado do repositório. Nada a mudar. Humano (claude-ia (ADR 0005)): —

#### 15209 — Outras
15.2 Bebidas não alcoólicas · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 2 · 2002: 8 · 2008: 8 · 2017: 14 (padrão 11111)
- Decisão 2026-10-16_claude-v3_alimentos-bebidas-outros#p19 REVISAR **aceita**. IA: Os mesmos produtos estão em 15208 nas duas outras edições em que aparecem; em 2002 estão em 15209. Duas edições contra uma, sem segunda fonte (IBGE neutro ou ausente, sem revisão manual): pela ADR 0005 não é óbvio. Recomendação da IA: mover, salvo razão de conceito. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_comida-fora-de-casa#p01 REVISAR **aceita**. IA: Não há como decidir célula a célula sem uma regra: hoje a mesma despesa (refrigerante tomado na rua) muda de grupo conforme a edição. Duas opções coerentes: (A) tudo do quadro de comida fora em 16104 (ou num grupo novo 'Alimentação fora do domicílio' dividido em refeição e lanche/bebida), o que dá uma série de 'comer fora' comparável; (B) tudo por produto, o que soma comer fora a comer em casa em cada produto. A IA recomenda (A), porque o questionário separa o quadro em todas as edições e porque o IBGE publica alimentação fora do domicílio à parte. É decisão estrutural (REGRA, possivelmente CRIAR), por isso fica para o humano (ADR 0005). Humano (claude-ia (ADR 0005)): —

#### 15210 — Agua de coco
15.2 Bebidas não alcoólicas · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 1 · 2017: 1 (padrão 11111)
- Decisão 2026-10-16_claude-v3_pendencias-validacao-e-criar#p30 REVISAR **aceita**. IA: Criar grupo é decisão estrutural (ADR + aprovação de outro membro). A IA conferiu que as células existem nas cinco edições, condição da R2 para manter a distinção; falta decidir se a granularidade vale um grupo próprio. Humano (claude-ia (ADR 0005)): —

#### 15211 — Caldo de cana
15.2 Bebidas não alcoólicas · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 1 · 2017: 1 (padrão 11111)
- Decisão 2026-10-16_claude-v3_pendencias-validacao-e-criar#p31 REVISAR **aceita**. IA: Criar grupo é decisão estrutural (ADR + aprovação de outro membro). A IA conferiu que as células existem nas cinco edições, condição da R2 para manter a distinção; falta decidir se a granularidade vale um grupo próprio. Humano (claude-ia (ADR 0005)): —

#### 15212 — Chocolate engarrafado ou encartonado
15.2 Bebidas não alcoólicas · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 2 · 2002: 1 · 2008: 3 · 2017: 3 (padrão 11111)
- Decisão 2026-10-16_claude-v3_comida-fora-de-casa#p01 REVISAR **aceita**. IA: Não há como decidir célula a célula sem uma regra: hoje a mesma despesa (refrigerante tomado na rua) muda de grupo conforme a edição. Duas opções coerentes: (A) tudo do quadro de comida fora em 16104 (ou num grupo novo 'Alimentação fora do domicílio' dividido em refeição e lanche/bebida), o que dá uma série de 'comer fora' comparável; (B) tudo por produto, o que soma comer fora a comer em casa em cada produto. A IA recomenda (A), porque o questionário separa o quadro em todas as edições e porque o IBGE publica alimentação fora do domicílio à parte. É decisão estrutural (REGRA, possivelmente CRIAR), por isso fica para o humano (ADR 0005). Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_pendencias-validacao-e-criar#p32 REVISAR **aceita**. IA: Criar grupo é decisão estrutural (ADR + aprovação de outro membro). A IA conferiu que as células existem nas cinco edições, condição da R2 para manter a distinção; falta decidir se a granularidade vale um grupo próprio. Humano (claude-ia (ADR 0005)): —

#### 15301 — Café moído
15.3 Cafés · status **ativo** · criado em base
Células por ano: 1987: 2 · 1995: 1 · 2002: 2 · 2008: 7 · 2017: 3 (padrão 11111)
- Decisão 2026-10-16_claude-v3_comida-fora-de-casa#p01 REVISAR **aceita**. IA: Não há como decidir célula a célula sem uma regra: hoje a mesma despesa (refrigerante tomado na rua) muda de grupo conforme a edição. Duas opções coerentes: (A) tudo do quadro de comida fora em 16104 (ou num grupo novo 'Alimentação fora do domicílio' dividido em refeição e lanche/bebida), o que dá uma série de 'comer fora' comparável; (B) tudo por produto, o que soma comer fora a comer em casa em cada produto. A IA recomenda (A), porque o questionário separa o quadro em todas as edições e porque o IBGE publica alimentação fora do domicílio à parte. É decisão estrutural (REGRA, possivelmente CRIAR), por isso fica para o humano (ADR 0005). Humano (claude-ia (ADR 0005)): —

#### 15302 — Café solúvel
15.3 Cafés · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 4 · 2008: 9 · 2017: 10 (padrão 11111)

#### 15303 — Outros
15.3 Cafés · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 2 · 2002: 0 · 2008: 0 · 2017: 2 (padrão 11001)
- Decisão 2026-10-16_claude-v3_comida-fora-de-casa#p01 REVISAR **aceita**. IA: Não há como decidir célula a célula sem uma regra: hoje a mesma despesa (refrigerante tomado na rua) muda de grupo conforme a edição. Duas opções coerentes: (A) tudo do quadro de comida fora em 16104 (ou num grupo novo 'Alimentação fora do domicílio' dividido em refeição e lanche/bebida), o que dá uma série de 'comer fora' comparável; (B) tudo por produto, o que soma comer fora a comer em casa em cada produto. A IA recomenda (A), porque o questionário separa o quadro em todas as edições e porque o IBGE publica alimentação fora do domicílio à parte. É decisão estrutural (REGRA, possivelmente CRIAR), por isso fica para o humano (ADR 0005). Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_pendencias-formulario#p14 REVISAR **aceita**. IA: Depende da regra da comida fora de casa (onda comida-fora-de-casa da v3). Humano (claude-ia (ADR 0005)): —

#### 15304 — Café em grão
15.3 Cafés · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 1 · 2017: 1 (padrão 11111)
- Decisão 2026-10-16_claude-v3_pendencias-validacao-e-criar#p33 REVISAR **aceita**. IA: Criar grupo é decisão estrutural (ADR + aprovação de outro membro). A IA conferiu que as células existem nas cinco edições, condição da R2 para manter a distinção; falta decidir se a granularidade vale um grupo próprio. Humano (claude-ia (ADR 0005)): —

#### 15401 — Chá-mate
15.4 Chás · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 7 · 2017: 5 (padrão 11111)
- Decisão 2026-10-16_claude-v3_comida-fora-de-casa#p01 REVISAR **aceita**. IA: Não há como decidir célula a célula sem uma regra: hoje a mesma despesa (refrigerante tomado na rua) muda de grupo conforme a edição. Duas opções coerentes: (A) tudo do quadro de comida fora em 16104 (ou num grupo novo 'Alimentação fora do domicílio' dividido em refeição e lanche/bebida), o que dá uma série de 'comer fora' comparável; (B) tudo por produto, o que soma comer fora a comer em casa em cada produto. A IA recomenda (A), porque o questionário separa o quadro em todas as edições e porque o IBGE publica alimentação fora do domicílio à parte. É decisão estrutural (REGRA, possivelmente CRIAR), por isso fica para o humano (ADR 0005). Humano (claude-ia (ADR 0005)): —

#### 15402 — Outros; Chá preto
15.4 Chás · status **ativo** · criado em base
Células por ano: 1987: 43 · 1995: 10 · 2002: 15 · 2008: 29 · 2017: 46 (padrão 11111)
- Decisão 2026-10-16_claude-v3_alimentos-bebidas-outros#p08 MOVER **aceita** (15102 → 15402). IA: Outlier pontual: os mesmos produtos estão em 15402 em todas as outras edições em que aparecem (pelo menos 4); só em 1995 a célula está em 15102, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 15402) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_alimentos-bebidas-outros#p12 MOVER **aceita** (15104 → 15402). IA: Outlier pontual: os mesmos produtos estão em 15402 em todas as outras edições em que aparecem (pelo menos 4); só em 1995 a célula está em 15104, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 15402) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_comida-fora-de-casa#p01 REVISAR **aceita**. IA: Não há como decidir célula a célula sem uma regra: hoje a mesma despesa (refrigerante tomado na rua) muda de grupo conforme a edição. Duas opções coerentes: (A) tudo do quadro de comida fora em 16104 (ou num grupo novo 'Alimentação fora do domicílio' dividido em refeição e lanche/bebida), o que dá uma série de 'comer fora' comparável; (B) tudo por produto, o que soma comer fora a comer em casa em cada produto. A IA recomenda (A), porque o questionário separa o quadro em todas as edições e porque o IBGE publica alimentação fora do domicílio à parte. É decisão estrutural (REGRA, possivelmente CRIAR), por isso fica para o humano (ADR 0005). Humano (claude-ia (ADR 0005)): —

### (sem nível 1)

#### 16016 — Outros
 · status **ativo** · criado em base
Células por ano: 1987: 0 · 1995: 0 · 2002: 1 · 2008: 0 · 2017: 0 (padrão 00100)
- Decisão 2026-10-16_claude-v3_alimentos-cereais-hortalicas-frutas#p11 REVISAR **aceita**. IA: Os mesmos produtos estão em 01199 nas duas outras edições em que aparecem; em 2002 estão em 16016. Duas edições contra uma, sem segunda fonte (IBGE neutro ou ausente, sem revisão manual): pela ADR 0005 não é óbvio. Recomendação da IA: mover, salvo razão de conceito. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_pendencias-validacao-e-criar#p28 REVISAR **aceita**. IA: As outras edições não confirmam com clareza nem o grupo atual nem o da planilha antiga. Recomendação da IA: 01199 Outros, o grupo mais frequente nas outras edições. Humano (claude-ia (ADR 0005)): —

### 16. Outros produtos

#### 16101 — Frango assado ou defumado
16.1 Outros produtos · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 0 · 2002: 0 · 2008: 0 · 2017: 0 (padrão 10000)
- Decisão 2026-10-16_claude-v3_alimentos-bebidas-outros#p13 MOVER **aceita** (16101 → 16104). IA: Outlier pontual: os mesmos produtos estão em 16104 em todas as outras edições em que aparecem (pelo menos 3); só em 1995 a célula está em 16101, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 16104) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —

#### 16102 — Massa; Massa preparada
16.1 Outros produtos · status **ativo** · criado em base
Células por ano: 1987: 2 · 1995: 2 · 2002: 2 · 2008: 1 · 2017: 0 (padrão 11110)
- Decisão 2026-10-16_claude-v3_alimentos-cocos-farinhas-panif-carnes#p14 MOVER **aceita** (16102 → 05303). IA: Outlier pontual: os mesmos produtos estão em 05303 em todas as outras edições em que aparecem (pelo menos 3); só em 2002 a célula está em 16102, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 05303) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_comida-fora-de-casa#p01 REVISAR **aceita**. IA: Não há como decidir célula a célula sem uma regra: hoje a mesma despesa (refrigerante tomado na rua) muda de grupo conforme a edição. Duas opções coerentes: (A) tudo do quadro de comida fora em 16104 (ou num grupo novo 'Alimentação fora do domicílio' dividido em refeição e lanche/bebida), o que dá uma série de 'comer fora' comparável; (B) tudo por produto, o que soma comer fora a comer em casa em cada produto. A IA recomenda (A), porque o questionário separa o quadro em todas as edições e porque o IBGE publica alimentação fora do domicílio à parte. É decisão estrutural (REGRA, possivelmente CRIAR), por isso fica para o humano (ADR 0005). Humano (claude-ia (ADR 0005)): —

#### 16103 — Outros produtos
16.1 Outros produtos · status **ativo** · criado em base
Células por ano: 1987: 30 · 1995: 17 · 2002: 22 · 2008: 28 · 2017: 33 (padrão 11111)
- Decisão 2026-10-16_claude-v3_alimentos-bebidas-outros#p04 MOVER **aceita** (16103 → 16104). IA: Outlier pontual: os mesmos produtos estão em 16104 em todas as outras edições em que aparecem (pelo menos 3); só em 1987 a célula está em 16103, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 16104) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_alimentos-bebidas-outros#p14 MOVER **aceita** (16103 → 16104). IA: Outlier pontual: os mesmos produtos estão em 16104 em todas as outras edições em que aparecem (pelo menos 3); só em 1995 a célula está em 16103, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 16104) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_alimentos-cereais-hortalicas-frutas#p06 MOVER **aceita** (16103 → 02212). IA: Outlier pontual: os mesmos produtos estão em 02212 em todas as outras edições em que aparecem (pelo menos 3); só em 1995 a célula está em 16103, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 02212) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_alimentos-cereais-hortalicas-frutas#p12 REVISAR **aceita**. IA: Os mesmos produtos estão em 01299 nas duas outras edições em que aparecem; em 2002 estão em 16103. Duas edições contra uma, sem segunda fonte (IBGE neutro ou ausente, sem revisão manual): pela ADR 0005 não é óbvio. Recomendação da IA: mover, salvo razão de conceito. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_alimentos-cocos-farinhas-panif-carnes#p11 MOVER **aceita** (16103 → 07501). IA: Outlier pontual: os mesmos produtos estão em 07501 em todas as outras edições em que aparecem (pelo menos 3); só em 1995 a célula está em 16103, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 07501) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_alimentos-cocos-farinhas-panif-carnes#p12 MOVER **aceita** (16103 → 07506). IA: Outlier pontual: os mesmos produtos estão em 07506 em todas as outras edições em que aparecem (pelo menos 3); só em 1995 a célula está em 16103, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 07506) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_alimentos-cocos-farinhas-panif-carnes#p34 REVISAR **aceita**. IA: Os mesmos produtos estão em 05104 nas duas outras edições em que aparecem; em 2008 estão em 16103. Duas edições contra uma, sem segunda fonte (IBGE neutro ou ausente, sem revisão manual): pela ADR 0005 não é óbvio. Recomendação da IA: mover, salvo razão de conceito. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_alimentos-visceras-a-oleos#p09 MOVER **aceita** (16103 → 08102). IA: Outlier pontual: os mesmos produtos estão em 08102 em todas as outras edições em que aparecem (pelo menos 3); só em 1995 a célula está em 16103, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 08102) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_alimentos-visceras-a-oleos#p10 MOVER **aceita** (16103 → 09109). IA: Outlier pontual: os mesmos produtos estão em 09109 em todas as outras edições em que aparecem (pelo menos 3); só em 1995 a célula está em 16103, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 09109) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_alimentos-visceras-a-oleos#p11 MOVER **aceita** (16103 → 10107). IA: Outlier pontual: os mesmos produtos estão em 10107 em todas as outras edições em que aparecem (pelo menos 3); só em 1995 a célula está em 16103, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 10107) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_comida-fora-de-casa#p01 REVISAR **aceita**. IA: Não há como decidir célula a célula sem uma regra: hoje a mesma despesa (refrigerante tomado na rua) muda de grupo conforme a edição. Duas opções coerentes: (A) tudo do quadro de comida fora em 16104 (ou num grupo novo 'Alimentação fora do domicílio' dividido em refeição e lanche/bebida), o que dá uma série de 'comer fora' comparável; (B) tudo por produto, o que soma comer fora a comer em casa em cada produto. A IA recomenda (A), porque o questionário separa o quadro em todas as edições e porque o IBGE publica alimentação fora do domicílio à parte. É decisão estrutural (REGRA, possivelmente CRIAR), por isso fica para o humano (ADR 0005). Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_vestuario-transporte-higiene-saude#p11 MOVER **aceita** (16103 → 35004). IA: Outlier pontual: os mesmos produtos estão em 35004 em todas as outras edições em que aparecem (pelo menos 4); só em 2017 a célula está em 16103, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 35004) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —

#### 16104 — Refeição; Refeição pronta
16.1 Outros produtos · status **ativo** · criado em base
Células por ano: 1987: 23 · 1995: 44 · 2002: 76 · 2008: 129 · 2017: 242 (padrão 11111)
- Decisão 2026-10-16_claude-v3_alimentos-bebidas-outros#p04 MOVER **aceita** (16103 → 16104). IA: Outlier pontual: os mesmos produtos estão em 16104 em todas as outras edições em que aparecem (pelo menos 3); só em 1987 a célula está em 16103, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 16104) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_alimentos-bebidas-outros#p13 MOVER **aceita** (16101 → 16104). IA: Outlier pontual: os mesmos produtos estão em 16104 em todas as outras edições em que aparecem (pelo menos 3); só em 1995 a célula está em 16101, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 16104) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_alimentos-bebidas-outros#p14 MOVER **aceita** (16103 → 16104). IA: Outlier pontual: os mesmos produtos estão em 16104 em todas as outras edições em que aparecem (pelo menos 3); só em 1995 a célula está em 16103, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 16104) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_alimentos-cocos-farinhas-panif-carnes#p15 MOVER **aceita** (16104 → 07208). IA: Outlier pontual: os mesmos produtos estão em 07208 em todas as outras edições em que aparecem (pelo menos 3); só em 2002 a célula está em 16104, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 07208) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_comida-fora-de-casa#p01 REVISAR **aceita**. IA: Não há como decidir célula a célula sem uma regra: hoje a mesma despesa (refrigerante tomado na rua) muda de grupo conforme a edição. Duas opções coerentes: (A) tudo do quadro de comida fora em 16104 (ou num grupo novo 'Alimentação fora do domicílio' dividido em refeição e lanche/bebida), o que dá uma série de 'comer fora' comparável; (B) tudo por produto, o que soma comer fora a comer em casa em cada produto. A IA recomenda (A), porque o questionário separa o quadro em todas as edições e porque o IBGE publica alimentação fora do domicílio à parte. É decisão estrutural (REGRA, possivelmente CRIAR), por isso fica para o humano (ADR 0005). Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_recreacao-cultura#p07 MOVER **aceita** (16104 → 38006). IA: Outlier pontual: os mesmos produtos estão em 38006 em todas as outras edições em que aparecem (pelo menos 4); só em 2002 a célula está em 16104, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 38006) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —

#### 16105 — Salgadinho
16.1 Outros produtos · status **ativo** · criado em base
Células por ano: 1987: 2 · 1995: 2 · 2002: 3 · 2008: 4 · 2017: 5 (padrão 11111)
- Decisão 2026-10-16_claude-v3_comida-fora-de-casa#p01 REVISAR **aceita**. IA: Não há como decidir célula a célula sem uma regra: hoje a mesma despesa (refrigerante tomado na rua) muda de grupo conforme a edição. Duas opções coerentes: (A) tudo do quadro de comida fora em 16104 (ou num grupo novo 'Alimentação fora do domicílio' dividido em refeição e lanche/bebida), o que dá uma série de 'comer fora' comparável; (B) tudo por produto, o que soma comer fora a comer em casa em cada produto. A IA recomenda (A), porque o questionário separa o quadro em todas as edições e porque o IBGE publica alimentação fora do domicílio à parte. É decisão estrutural (REGRA, possivelmente CRIAR), por isso fica para o humano (ADR 0005). Humano (claude-ia (ADR 0005)): —

#### 16106 — Mistura para bolo; Mistura industrial para bolo
16.1 Outros produtos · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 2 · 2002: 2 · 2008: 2 · 2017: 2 (padrão 11111)
- Decisão 2026-10-16_claude-v3_alimentos-bebidas-outros#p05 MOVER **aceita** (06104 → 16106). IA: Outlier pontual: os mesmos produtos estão em 16106 em todas as outras edições em que aparecem (pelo menos 3); só em 1995 a célula está em 06104, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 16106) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —

#### 16107 — Aspargo em conserva
16.1 Outros produtos · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 1 · 2017: 1 (padrão 11111)

#### 16108 — Cenoura em conserva
16.1 Outros produtos · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 1 · 2017: 1 (padrão 11111)

#### 16109 — Repolho em conserva, cucrute
16.1 Outros produtos · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 1 · 2017: 1 (padrão 11111)

#### 16110 — Tomate em lata
16.1 Outros produtos · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 1 · 2017: 1 (padrão 11111)

#### 16111 — Palmito em conserva
16.1 Outros produtos · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 1 · 2017: 1 (padrão 11111)

#### 16112 — Cogumelo em conserva
16.1 Outros produtos · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 1 · 2017: 1 (padrão 11111)

### 31. Servicos_e_taxas

#### 31001 — Aluguel
Servicos_e_taxas · status **ativo** · criado em base
Células por ano: 1987: 4 · 1995: 4 · 2002: 5 · 2008: 4 · 2017: 5 (padrão 11111)
- Decisão 2026-10-16_claude-v3_habitacao-servicos#p36 MOVER **aceita** (31007;40006;41006 → 31001). IA: Mesma despesa espalhada por três grupos; 2002/2008 e o IBGE concordam em Aluguel. Duas fontes ⇒ ALTA. Humano (claude-ia (ADR 0005)): —

#### 31002 — Energia eletrica
Servicos_e_taxas · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 1 · 2017: 2 (padrão 11111)

#### 31003 — Telefonia
Servicos_e_taxas · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 3 · 2002: 4 · 2008: 8 · 2017: 9 (padrão 11111)
- Decisão 2026-10-16_claude-v3_pendencias-formulario#p09 REVISAR **aceita**. IA: Conflita com a reorganização proposta para a telefonia (31003). Decidir junto. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_recreacao-cultura#p18 REVISAR **aceita**. IA: Não há outlier: o serviço muda de grupo em todas as edições (38002, 31003, 38005, 38002). A distinção serviço × aparelho é observável nos cinco anos (R2) e é a do IBGE, então a IA recomenda: serviço e pacotes com celular em 31003 Telefonia (1995:715, 1995:1309 aluguel de telefone móvel, 1995:1697 linha telefônica móvel, 2008:28023, 2008:28024, 2017:44001, 44002, 44003, 6010, 6011, 6016); aparelhos e acessórios ficam em 38002. Como é reorganização de série (e 31003 hoje junta fixo e móvel), a decisão é humana (ADR 0005). Humano (claude-ia (ADR 0005)): —

#### 31005 — Gas domestico
Servicos_e_taxas · status **ativo** · criado em base
Células por ano: 1987: 3 · 1995: 3 · 2002: 2 · 2008: 2 · 2017: 2 (padrão 11111)
- Decisão 2026-10-16_claude-v3_1995-copia-de-1987#p02 REVISAR **aceita**. IA: O padrão confirma a suspeita da pendência q3. O histórico dessas células vem de palavra-chave (descrições diferem), o que não basta para mover pela ADR 0005. Recomendação da IA: revisar a lista com o questionário de 1995 aberto; os casos evidentes acima podem ir para o grupo das edições seguintes. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_habitacao-servicos#p20 REVISAR **aceita**. IA: Os mesmos produtos estão em 32001 nas duas outras edições em que aparecem; em 1987 estão em 31005. Duas edições contra uma, sem segunda fonte (IBGE neutro ou ausente, sem revisão manual): pela ADR 0005 não é óbvio. Recomendação da IA: mover, salvo razão de conceito. Humano (claude-ia (ADR 0005)): —

#### 31006 — Agua e esgoto
Servicos_e_taxas · status **ativo** · criado em base
Células por ano: 1987: 2 · 1995: 2 · 2002: 1 · 2008: 1 · 2017: 1 (padrão 11111)

#### 31007 — Outros servicos etc
Servicos_e_taxas · status **ativo** · criado em base
Células por ano: 1987: 13 · 1995: 30 · 2002: 32 · 2008: 36 · 2017: 39 (padrão 11111)
- Decisão 2026-10-16_claude-v3_1995-copia-de-1987#p01 MANTER **aceita**. IA: A coincidência de grupo com 1987 não é erro quando as edições seguintes confirmam. Nada a mudar. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_educacao-despesas-diversas#p07 MOVER **aceita** (31007 → 40002). IA: Outlier pontual: os mesmos produtos estão em 40002 em todas as outras edições em que aparecem (pelo menos 3); só em 1995 a célula está em 31007, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 40002) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_educacao-despesas-diversas#p19 REVISAR **aceita**. IA: Os mesmos produtos estão em 40002 nas duas outras edições em que aparecem; em 1995 estão em 31007. Duas edições contra uma, sem segunda fonte (IBGE neutro ou ausente, sem revisão manual): pela ADR 0005 não é óbvio. Recomendação da IA: mover, salvo razão de conceito. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_habitacao-servicos#p18 MOVER **aceita** (42001 → 31007). IA: Outlier pontual: os mesmos produtos estão em 31007 em todas as outras edições em que aparecem (pelo menos 2); só em 2017 a célula está em 42001, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 31007) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_habitacao-servicos#p21 REVISAR **aceita**. IA: Os mesmos produtos estão em 32001 nas duas outras edições em que aparecem; em 2002 estão em 31007. Duas edições contra uma, sem segunda fonte (IBGE neutro ou ausente, sem revisão manual): pela ADR 0005 não é óbvio. Recomendação da IA: mover, salvo razão de conceito. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_habitacao-servicos#p34 MOVER **aceita** (40006;41006 → 31007). IA: Quebra de série: o mesmo gasto (condomínio do domicílio principal) está em três grupos diferentes ao longo das edições, e em 2008/2017 cai fora do consumo. Estrutura dos códigos (célula do domicílio principal, mesmo quadro de aluguel e taxas), anos 1995/2002 e o tradutor do IBGE convergem: 31007. Duas fontes independentes ⇒ ALTA (ADR 0005). Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_habitacao-servicos#p35 MOVER **aceita** (31007;32001 → 41001). IA: Três edições unânimes e o IBGE concordam: imposto é outra despesa corrente, não manutenção do lar nem serviço. Os dois anos antigos estão cada um num grupo diferente, sinal de deslize e não de critério. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_habitacao-servicos#p36 MOVER **aceita** (31007;40006;41006 → 31001). IA: Mesma despesa espalhada por três grupos; 2002/2008 e o IBGE concordam em Aluguel. Duas fontes ⇒ ALTA. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_pendencias-formulario#p03 MOVER **aceita** (31007 → 32001). IA: Combustível doméstico não é serviço: o repositório (2002) e o IBGE (2008) o põem em manutenção do lar, e a sugestão humana do formulário converge. Duas fontes além da sugestão ⇒ ALTA. Ficam de fora os agregados (1987:798, 1995:798) e 1995:909 (manutenção de utensílios), sem par. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_pendencias-formulario#p08 MOVER **aceita** (42001 → 31007). IA: Taxa não é aquisição de imóvel (deslocamento de 2017 no quadro 12). 2008 e a sugestão humana dizem 31007; o IBGE confirma Habitação (linha água e esgoto, que pode ser discutida depois). Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_pendencias-formulario#p15 REVISAR **aceita**. IA: Agregado mistura os itens do quadro (serviços públicos e combustíveis) e o 909 é conserto: sem par para decidir. Recomendação da IA: agregados acompanham o item dominante do quadro em valor (decidir com os microdados); 909 em 32005 Consertos. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_vestuario-transporte-higiene-saude#p10 MOVER **aceita** (31007 → 34001). IA: Outlier pontual: os mesmos produtos estão em 34001 em todas as outras edições em que aparecem (pelo menos 2); só em 2008 a célula está em 31007, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 34001) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —

### 32. Habitacao

#### 32001 — Manutencao do lar
Habitacao · status **ativo** · criado em base
Células por ano: 1987: 34 · 1995: 108 · 2002: 142 · 2008: 121 · 2017: 100 (padrão 11111)
- Decisão 2026-10-16_claude-v3_1995-copia-de-1987#p01 MANTER **aceita**. IA: A coincidência de grupo com 1987 não é erro quando as edições seguintes confirmam. Nada a mudar. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_1995-copia-de-1987#p02 REVISAR **aceita**. IA: O padrão confirma a suspeita da pendência q3. O histórico dessas células vem de palavra-chave (descrições diferem), o que não basta para mover pela ADR 0005. Recomendação da IA: revisar a lista com o questionário de 1995 aberto; os casos evidentes acima podem ir para o grupo das edições seguintes. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_cynthia-folha-32#p11 REVISAR **aceita**. IA: A revisão manual aponta outlier pontual, mas o detector não o confirmou: a célula tem itens sem histórico ou de outro conceito, ou o histórico não é unânime (R1). Precisa olhar a célula inteira. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_cynthia-folha-32#p18 REVISAR **aceita**. IA: A revisão manual aponta outlier pontual, mas o detector não o confirmou: a célula tem itens sem histórico ou de outro conceito, ou o histórico não é unânime (R1). Precisa olhar a célula inteira. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_educacao-despesas-diversas#p28 REVISAR **aceita**. IA: As outras edições põem os mesmos produtos em 40006, mas o tradutor do IBGE confirma o grupo atual (32001) em 2008. Fontes discordantes (CONSTITUICAO, hierarquia de evidência): decidir qual convenção vale para a série. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_habitacao-servicos#p08 MOVER **aceita** (32001 → 32002). IA: Outlier pontual: os mesmos produtos estão em 32002 em todas as outras edições em que aparecem (pelo menos 4); só em 2017 a célula está em 32001, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 32002) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_habitacao-servicos#p31 REVISAR **aceita**. IA: As outras edições põem os mesmos produtos em 32003, mas o tradutor do IBGE confirma o grupo atual (32001) em 2008. Fontes discordantes (CONSTITUICAO, hierarquia de evidência): decidir qual convenção vale para a série. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_habitacao-servicos#p35 MOVER **aceita** (31007;32001 → 41001). IA: Três edições unânimes e o IBGE concordam: imposto é outra despesa corrente, não manutenção do lar nem serviço. Os dois anos antigos estão cada um num grupo diferente, sinal de deslize e não de critério. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_nao-consumo#p18 REVISAR **aceita**. IA: Os mesmos nomes de produto estão em 41002 nas outras edições, mas a célula está em 32001, de outro domínio (consumo, outras despesas, rendimentos ou inventário). Mesmo nome não garante mesma despesa (ex.: item de inventário de bens duráveis × compra; 'empregado' como rendimento × serviço doméstico). Sem confirmação do IBGE, a decisão é humana. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_nao-consumo#p19 REVISAR **aceita**. IA: Os mesmos nomes de produto estão em 42002 nas outras edições, mas a célula está em 32001, de outro domínio (consumo, outras despesas, rendimentos ou inventário). Mesmo nome não garante mesma despesa (ex.: item de inventário de bens duráveis × compra; 'empregado' como rendimento × serviço doméstico). Sem confirmação do IBGE, a decisão é humana. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_pendencias-formulario#p03 MOVER **aceita** (31007 → 32001). IA: Combustível doméstico não é serviço: o repositório (2002) e o IBGE (2008) o põem em manutenção do lar, e a sugestão humana do formulário converge. Duas fontes além da sugestão ⇒ ALTA. Ficam de fora os agregados (1987:798, 1995:798) e 1995:909 (manutenção de utensílios), sem par. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_pendencias-formulario#p05 MOVER **aceita** (43002 → 32001). IA: Vidro não é prestação de imóvel: o erro de código copiado é inequívoco. O destino 32001 segue a sugestão humana e 2002/2008; a alternativa 42002 faz parte da questão reforma × manutenção (pendência 2026-09-11_arthurwelle#q1), que fica aberta. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_pendencias-formulario#p13 REVISAR **aceita**. IA: Faz parte da questão reforma × manutenção do lar (pendência 2026-09-11_arthurwelle#q1, R1 em 1987), que precisa de regra antes de mover células. Humano (claude-ia (ADR 0005)): —

#### 32002 — Artigos de limpeza
Habitacao · status **ativo** · criado em base
Células por ano: 1987: 42 · 1995: 43 · 2002: 62 · 2008: 57 · 2017: 62 (padrão 11111)
- Decisão 2026-10-16_claude-v3_1995-copia-de-1987#p01 MANTER **aceita**. IA: A coincidência de grupo com 1987 não é erro quando as edições seguintes confirmam. Nada a mudar. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_cynthia-folha-32#p01 REVISAR **aceita**. IA: A revisão manual aponta outlier pontual, mas o detector não o confirmou: a célula tem itens sem histórico ou de outro conceito, ou o histórico não é unânime (R1). Precisa olhar a célula inteira. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_cynthia-folha-32#p06 MANTER **aceita**. IA: As células da ação já estão no destino proposto pela revisão manual (a planilha do Drive estava defasada). Nada a mudar. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_cynthia-folha-32#p17 MANTER **aceita**. IA: As células da ação já estão no destino proposto pela revisão manual (a planilha do Drive estava defasada). Nada a mudar. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_habitacao-servicos#p03 MOVER **aceita** (32003 → 32002). IA: Outlier pontual: os mesmos produtos estão em 32002 em todas as outras edições em que aparecem (pelo menos 3); só em 1995 a célula está em 32003, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 32002) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_habitacao-servicos#p05 MOVER **aceita** (32002 → 32003). IA: Outlier pontual: os mesmos produtos estão em 32003 em todas as outras edições em que aparecem (pelo menos 3); só em 2002 a célula está em 32002, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 32003) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_habitacao-servicos#p07 MOVER **aceita** (32003 → 32002). IA: Outlier pontual: os mesmos produtos estão em 32002 em todas as outras edições em que aparecem (pelo menos 2); só em 2008 a célula está em 32003, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 32002) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_habitacao-servicos#p08 MOVER **aceita** (32001 → 32002). IA: Outlier pontual: os mesmos produtos estão em 32002 em todas as outras edições em que aparecem (pelo menos 4); só em 2017 a célula está em 32001, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 32002) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_habitacao-servicos#p09 MOVER **aceita** (32003 → 32002). IA: Outlier pontual: os mesmos produtos estão em 32002 em todas as outras edições em que aparecem (pelo menos 4); só em 2017 a célula está em 32003, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 32002) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_vestuario-transporte-higiene-saude#p04 MOVER **aceita** (32002 → 33004). IA: Outlier pontual: os mesmos produtos estão em 33004 em todas as outras edições em que aparecem (pelo menos 3); só em 1995 a célula está em 32002, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 33004) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —

#### 32003 — Mobiliarios e artigos do lar
Habitacao · status **ativo** · criado em base
Células por ano: 1987: 270 · 1995: 281 · 2002: 331 · 2008: 332 · 2017: 434 (padrão 11111)
- Decisão 2026-10-16_claude-v3_1995-copia-de-1987#p01 MANTER **aceita**. IA: A coincidência de grupo com 1987 não é erro quando as edições seguintes confirmam. Nada a mudar. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_1995-copia-de-1987#p02 REVISAR **aceita**. IA: O padrão confirma a suspeita da pendência q3. O histórico dessas células vem de palavra-chave (descrições diferem), o que não basta para mover pela ADR 0005. Recomendação da IA: revisar a lista com o questionário de 1995 aberto; os casos evidentes acima podem ir para o grupo das edições seguintes. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_2017-quadros-deslocados#p02 MOVER **aceita** (38005 → 32003). IA: Mesmo padrão do quadro 16 de 2017; outras edições e IBGE concordam em 32003. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_2017-quadros-deslocados#p03 MOVER **aceita** (32003 → 33006). IA: Em 2017 o quadro 37 tem itens trocados entre 33006 e 32003 (ver também a proposta do enchimento). As outras edições e o IBGE concordam em 33006: duas fontes ⇒ ALTA. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_2017-quadros-deslocados#p04 MOVER **aceita** (33006 → 32003). IA: O par simétrico da troca de linhas do quadro 37 de 2017. Três edições e o IBGE concordam. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_2017-quadros-deslocados#p06 REVISAR **aceita**. IA: Em 2017 o quadro 37 ganhou itens novos e linhas trocadas; sem par nas outras edições, o destino depende de critério (tecido para o lar é armarinho ou artigo do lar? artesanato é recreação?). Recomendação da IA: tecidos, couro e entretela em 33006 (IBGE); artesanato junto, em 38005, como o IBGE. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_cynthia-folha-32#p02 REVISAR **aceita**. IA: A revisão manual aponta outlier pontual, mas o detector não o confirmou: a célula tem itens sem histórico ou de outro conceito, ou o histórico não é unânime (R1). Precisa olhar a célula inteira. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_cynthia-folha-32#p03 REVISAR **aceita**. IA: A revisão manual aponta outlier pontual, mas o detector não o confirmou: a célula tem itens sem histórico ou de outro conceito, ou o histórico não é unânime (R1). Precisa olhar a célula inteira. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_cynthia-folha-32#p05 REVISAR **aceita**. IA: A revisão manual aponta outlier pontual, mas o detector não o confirmou: a célula tem itens sem histórico ou de outro conceito, ou o histórico não é unânime (R1). Precisa olhar a célula inteira. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_cynthia-folha-32#p10 MANTER **aceita**. IA: As células da ação já estão no destino proposto pela revisão manual (a planilha do Drive estava defasada). Nada a mudar. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_cynthia-folha-32#p12 MANTER **aceita**. IA: As células da ação já estão no destino proposto pela revisão manual (a planilha do Drive estava defasada). Nada a mudar. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_cynthia-folha-32#p19 MANTER **aceita**. IA: As células da ação já estão no destino proposto pela revisão manual (a planilha do Drive estava defasada). Nada a mudar. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_cynthia-folha-32#p20 REVISAR **aceita**. IA: A revisão manual aponta outlier pontual, mas o detector não o confirmou: a célula tem itens sem histórico ou de outro conceito, ou o histórico não é unânime (R1). Precisa olhar a célula inteira. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_educacao-despesas-diversas#p10 MOVER **aceita** (32003 → 40006). IA: Outlier pontual: os mesmos produtos estão em 40006 em todas as outras edições em que aparecem (pelo menos 2); só em 2017 a célula está em 32003, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 40006) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_habitacao-servicos#p01 MOVER **aceita** (32004 → 32003). IA: Outlier pontual: os mesmos produtos estão em 32003 em todas as outras edições em que aparecem (pelo menos 3); só em 1987 a célula está em 32004, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 32003) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_habitacao-servicos#p02 MOVER **aceita** (40006 → 32003). IA: Outlier pontual: os mesmos produtos estão em 32003 em todas as outras edições em que aparecem (pelo menos 4); só em 1987 a célula está em 40006, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 32003) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_habitacao-servicos#p03 MOVER **aceita** (32003 → 32002). IA: Outlier pontual: os mesmos produtos estão em 32002 em todas as outras edições em que aparecem (pelo menos 3); só em 1995 a célula está em 32003, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 32002) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_habitacao-servicos#p04 MOVER **aceita** (32003 → 32004). IA: Outlier pontual: os mesmos produtos estão em 32004 em todas as outras edições em que aparecem (pelo menos 3); só em 1995 a célula está em 32003, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 32004) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_habitacao-servicos#p05 MOVER **aceita** (32002 → 32003). IA: Outlier pontual: os mesmos produtos estão em 32003 em todas as outras edições em que aparecem (pelo menos 3); só em 2002 a célula está em 32002, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 32003) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_habitacao-servicos#p06 MOVER **aceita** (32005 → 32003). IA: Outlier pontual: os mesmos produtos estão em 32003 em todas as outras edições em que aparecem (pelo menos 4); só em 2002 a célula está em 32005, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 32003) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_habitacao-servicos#p07 MOVER **aceita** (32003 → 32002). IA: Outlier pontual: os mesmos produtos estão em 32002 em todas as outras edições em que aparecem (pelo menos 2); só em 2008 a célula está em 32003, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 32002) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_habitacao-servicos#p09 MOVER **aceita** (32003 → 32002). IA: Outlier pontual: os mesmos produtos estão em 32002 em todas as outras edições em que aparecem (pelo menos 4); só em 2017 a célula está em 32003, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 32002) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_habitacao-servicos#p10 MOVER **aceita** (32003 → 32004). IA: Outlier pontual: os mesmos produtos estão em 32004 em todas as outras edições em que aparecem (pelo menos 2); só em 2017 a célula está em 32003, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 32004) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_habitacao-servicos#p11 MOVER **aceita** (32004 → 32003). IA: Outlier pontual: os mesmos produtos estão em 32003 em todas as outras edições em que aparecem (pelo menos 4); só em 2017 a célula está em 32004, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 32003) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_habitacao-servicos#p12 MOVER **aceita** (37005 → 32003). IA: Outlier pontual: os mesmos produtos estão em 32003 em todas as outras edições em que aparecem (pelo menos 3); só em 2017 a célula está em 37005, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 32003) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_habitacao-servicos#p14 MOVER **aceita** (38005 → 32003). IA: Outlier pontual: os mesmos produtos estão em 32003 em todas as outras edições em que aparecem (pelo menos 2); só em 2017 a célula está em 38005, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 32003) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_habitacao-servicos#p16 MOVER **aceita** (40006 → 32003). IA: Outlier pontual: os mesmos produtos estão em 32003 em todas as outras edições em que aparecem (pelo menos 4); só em 2017 a célula está em 40006, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 32003) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_habitacao-servicos#p22 REVISAR **aceita**. IA: Os mesmos produtos estão em 32002 nas duas outras edições em que aparecem; em 1995 estão em 32003. Duas edições contra uma, sem segunda fonte (IBGE neutro ou ausente, sem revisão manual): pela ADR 0005 não é óbvio. Recomendação da IA: mover, salvo razão de conceito. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_habitacao-servicos#p23 REVISAR **aceita**. IA: Os mesmos produtos estão em 32004 nas duas outras edições em que aparecem; em 1995 estão em 32003. Duas edições contra uma, sem segunda fonte (IBGE neutro ou ausente, sem revisão manual): pela ADR 0005 não é óbvio. Recomendação da IA: mover, salvo razão de conceito. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_habitacao-servicos#p32 REVISAR **aceita**. IA: As outras edições põem os mesmos produtos em 32004, mas o tradutor do IBGE confirma o grupo atual (32003) em 2017. Fontes discordantes (CONSTITUICAO, hierarquia de evidência): decidir qual convenção vale para a série. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_recreacao-cultura#p08 MOVER **aceita** (32003 → 38005). IA: Outlier pontual: os mesmos produtos estão em 38005 em todas as outras edições em que aparecem (pelo menos 2); só em 2017 a célula está em 32003, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 38005) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_vestuario-transporte-higiene-saude#p05 MOVER **aceita** (32003 → 33006). IA: Outlier pontual: os mesmos produtos estão em 33006 em todas as outras edições em que aparecem (pelo menos 3); só em 1995 a célula está em 32003, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 33006) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_vestuario-transporte-higiene-saude#p07 MOVER **aceita** (32003 → 39001). IA: Outlier pontual: os mesmos produtos estão em 39001 em todas as outras edições em que aparecem (pelo menos 4); só em 2002 a célula está em 32003, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 39001) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_vestuario-transporte-higiene-saude#p12 MOVER **aceita** (32003 → 33006). IA: Outlier pontual: os mesmos produtos estão em 33006 em todas as outras edições em que aparecem (pelo menos 3); só em 2017 a célula está em 32003, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 33006) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_vestuario-transporte-higiene-saude#p22 REVISAR **aceita**. IA: Os mesmos produtos estão em 33006 nas duas outras edições em que aparecem; em 1995 estão em 32003. Duas edições contra uma, sem segunda fonte (IBGE neutro ou ausente, sem revisão manual): pela ADR 0005 não é óbvio. Recomendação da IA: mover, salvo razão de conceito. Humano (claude-ia (ADR 0005)): —

#### 32004 — Eletrodomesticos
Habitacao · status **ativo** · criado em base
Células por ano: 1987: 104 · 1995: 123 · 2002: 149 · 2008: 152 · 2017: 132 (padrão 11111)
- Decisão 2026-10-16_claude-v3_1995-copia-de-1987#p01 MANTER **aceita**. IA: A coincidência de grupo com 1987 não é erro quando as edições seguintes confirmam. Nada a mudar. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_1995-copia-de-1987#p02 REVISAR **aceita**. IA: O padrão confirma a suspeita da pendência q3. O histórico dessas células vem de palavra-chave (descrições diferem), o que não basta para mover pela ADR 0005. Recomendação da IA: revisar a lista com o questionário de 1995 aberto; os casos evidentes acima podem ir para o grupo das edições seguintes. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_2017-quadros-deslocados#p01 MOVER **aceita** (38005 → 32004). IA: Utensílio doméstico em recreação só em 2017, no bloco do quadro 16 que a aba de 2017 deslocou. Outras edições e IBGE concordam no grupo: duas fontes ⇒ ALTA (ADR 0005). Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_cynthia-folha-38#p07 MANTER **aceita**. IA: As células da ação já estão no destino proposto pela revisão manual (a planilha do Drive estava defasada). Nada a mudar. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_habitacao-servicos#p01 MOVER **aceita** (32004 → 32003). IA: Outlier pontual: os mesmos produtos estão em 32003 em todas as outras edições em que aparecem (pelo menos 3); só em 1987 a célula está em 32004, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 32003) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_habitacao-servicos#p04 MOVER **aceita** (32003 → 32004). IA: Outlier pontual: os mesmos produtos estão em 32004 em todas as outras edições em que aparecem (pelo menos 3); só em 1995 a célula está em 32003, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 32004) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_habitacao-servicos#p10 MOVER **aceita** (32003 → 32004). IA: Outlier pontual: os mesmos produtos estão em 32004 em todas as outras edições em que aparecem (pelo menos 2); só em 2017 a célula está em 32003, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 32004) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_habitacao-servicos#p11 MOVER **aceita** (32004 → 32003). IA: Outlier pontual: os mesmos produtos estão em 32003 em todas as outras edições em que aparecem (pelo menos 4); só em 2017 a célula está em 32004, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 32003) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_habitacao-servicos#p13 MOVER **aceita** (38001 → 32004). IA: Outlier pontual: os mesmos produtos estão em 32004 em todas as outras edições em que aparecem (pelo menos 4); só em 2017 a célula está em 38001, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 32004) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_habitacao-servicos#p15 MOVER **aceita** (38005 → 32004). IA: Outlier pontual: os mesmos produtos estão em 32004 em todas as outras edições em que aparecem (pelo menos 4); só em 2017 a célula está em 38005, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 32004) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_habitacao-servicos#p17 MOVER **aceita** (40006 → 32004). IA: Outlier pontual: os mesmos produtos estão em 32004 em todas as outras edições em que aparecem (pelo menos 4); só em 2017 a célula está em 40006, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 32004) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_nao-consumo#p07 MOVER **aceita** (32004 → 42003). IA: Outlier pontual: os mesmos produtos estão em 42003 em todas as outras edições em que aparecem (pelo menos 2); só em 2017 a célula está em 32004, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 42003) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_recreacao-cultura#p04 MOVER **aceita** (32004 → 38002). IA: Outlier pontual: os mesmos produtos estão em 38002 em todas as outras edições em que aparecem (pelo menos 3); só em 1995 a célula está em 32004, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 38002) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_recreacao-cultura#p18 REVISAR **aceita**. IA: Não há outlier: o serviço muda de grupo em todas as edições (38002, 31003, 38005, 38002). A distinção serviço × aparelho é observável nos cinco anos (R2) e é a do IBGE, então a IA recomenda: serviço e pacotes com celular em 31003 Telefonia (1995:715, 1995:1309 aluguel de telefone móvel, 1995:1697 linha telefônica móvel, 2008:28023, 2008:28024, 2017:44001, 44002, 44003, 6010, 6011, 6016); aparelhos e acessórios ficam em 38002. Como é reorganização de série (e 31003 hoje junta fixo e móvel), a decisão é humana (ADR 0005). Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_vestuario-transporte-higiene-saude#p08 MOVER **aceita** (32004 → 35002). IA: Outlier pontual: os mesmos produtos estão em 35002 em todas as outras edições em que aparecem (pelo menos 2); só em 2002 a célula está em 32004, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 35002) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_vestuario-transporte-higiene-saude#p31 REVISAR **aceita**. IA: As outras edições põem os mesmos produtos em 34004, mas o tradutor do IBGE confirma o grupo atual (32004) em 2017. Fontes discordantes (CONSTITUICAO, hierarquia de evidência): decidir qual convenção vale para a série. Humano (claude-ia (ADR 0005)): —

#### 32005 — Consertos de artigos do lar
Habitacao · status **ativo** · criado em base
Células por ano: 1987: 17 · 1995: 67 · 2002: 80 · 2008: 157 · 2017: 227 (padrão 11111)
- Decisão 2026-10-16_claude-v3_2017-quadros-deslocados#p07 REVISAR **aceita**. IA: Aluguel não é conserto. 2002 e o IBGE (2008 e 2017) põem aluguel de aparelhos em despesas diversas. Recomendação da IA: 40006; só uma edição tem par, por isso não é óbvio pela ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_habitacao-servicos#p06 MOVER **aceita** (32005 → 32003). IA: Outlier pontual: os mesmos produtos estão em 32003 em todas as outras edições em que aparecem (pelo menos 4); só em 2002 a célula está em 32005, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 32003) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_habitacao-servicos#p24 REVISAR **aceita**. IA: Os mesmos produtos estão em 32003 nas duas outras edições em que aparecem; em 2002 estão em 32005. Duas edições contra uma, sem segunda fonte (IBGE neutro ou ausente, sem revisão manual): pela ADR 0005 não é óbvio. Recomendação da IA: mover, salvo razão de conceito. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_pendencias-validacao-e-criar#p26 REVISAR **aceita**. IA: As outras edições não confirmam com clareza nem o grupo atual nem o da planilha antiga. Recomendação da IA: 39005 Outras servicos pessoais, o grupo mais frequente nas outras edições. Humano (claude-ia (ADR 0005)): —

### 33. Vestuario

#### 33001 — Roupa de homem
Vestuario · status **ativo** · criado em base
Células por ano: 1987: 34 · 1995: 39 · 2002: 40 · 2008: 34 · 2017: 31 (padrão 11111)

#### 33002 — Roupa de mulher
Vestuario · status **ativo** · criado em base
Células por ano: 1987: 46 · 1995: 54 · 2002: 61 · 2008: 60 · 2017: 48 (padrão 11111)

#### 33003 — Roupa de crianca
Vestuario · status **ativo** · criado em base
Células por ano: 1987: 38 · 1995: 53 · 2002: 53 · 2008: 49 · 2017: 55 (padrão 11111)
- Decisão 2026-10-16_claude-v3_vestuario-transporte-higiene-saude#p32 REVISAR **aceita**. IA: As outras edições põem os mesmos produtos em 33001, mas o tradutor do IBGE confirma o grupo atual (33003) em 2008. Fontes discordantes (CONSTITUICAO, hierarquia de evidência): decidir qual convenção vale para a série. Humano (claude-ia (ADR 0005)): —

#### 33004 — Calcados e apetrechos
Vestuario · status **ativo** · criado em base
Células por ano: 1987: 41 · 1995: 40 · 2002: 50 · 2008: 70 · 2017: 52 (padrão 11111)
- Decisão 2026-10-16_claude-v3_cynthia-folha-32#p08 MANTER **aceita**. IA: As células da ação já estão no destino proposto pela revisão manual (a planilha do Drive estava defasada). Nada a mudar. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_educacao-despesas-diversas#p11 MOVER **aceita** (33004 → 40006). IA: Outlier pontual: os mesmos produtos estão em 40006 em todas as outras edições em que aparecem (pelo menos 4); só em 2017 a célula está em 33004, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 40006) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_educacao-despesas-diversas#p20 REVISAR **aceita**. IA: Os mesmos produtos estão em 40006 nas duas outras edições em que aparecem; em 2017 estão em 33004. Duas edições contra uma, sem segunda fonte (IBGE neutro ou ausente, sem revisão manual): pela ADR 0005 não é óbvio. Recomendação da IA: mover, salvo razão de conceito. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_vestuario-transporte-higiene-saude#p01 MOVER **aceita** (33004 → 33006). IA: Outlier pontual: os mesmos produtos estão em 33006 em todas as outras edições em que aparecem (pelo menos 3); só em 1987 a célula está em 33004, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 33006) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_vestuario-transporte-higiene-saude#p04 MOVER **aceita** (32002 → 33004). IA: Outlier pontual: os mesmos produtos estão em 33004 em todas as outras edições em que aparecem (pelo menos 3); só em 1995 a célula está em 32002, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 33004) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_vestuario-transporte-higiene-saude#p13 MOVER **aceita** (33004 → 33005). IA: Outlier pontual: os mesmos produtos estão em 33005 em todas as outras edições em que aparecem (pelo menos 2); só em 2017 a célula está em 33004, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 33005) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_vestuario-transporte-higiene-saude#p33 REVISAR **aceita**. IA: As outras edições põem os mesmos produtos em 39001, mas o tradutor do IBGE confirma o grupo atual (33004) em 2008. Fontes discordantes (CONSTITUICAO, hierarquia de evidência): decidir qual convenção vale para a série. Humano (claude-ia (ADR 0005)): —

#### 33005 — Joias e bijuterias
Vestuario · status **ativo** · criado em base
Células por ano: 1987: 12 · 1995: 14 · 2002: 12 · 2008: 12 · 2017: 10 (padrão 11111)
- Decisão 2026-10-16_claude-v3_vestuario-transporte-higiene-saude#p13 MOVER **aceita** (33004 → 33005). IA: Outlier pontual: os mesmos produtos estão em 33005 em todas as outras edições em que aparecem (pelo menos 2); só em 2017 a célula está em 33004, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 33005) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —

#### 33006 — Tecidos e armarinhos
Vestuario · status **ativo** · criado em base
Células por ano: 1987: 14 · 1995: 13 · 2002: 25 · 2008: 25 · 2017: 16 (padrão 11111)
- Decisão 2026-10-16_claude-v3_2017-quadros-deslocados#p03 MOVER **aceita** (32003 → 33006). IA: Em 2017 o quadro 37 tem itens trocados entre 33006 e 32003 (ver também a proposta do enchimento). As outras edições e o IBGE concordam em 33006: duas fontes ⇒ ALTA. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_2017-quadros-deslocados#p04 MOVER **aceita** (33006 → 32003). IA: O par simétrico da troca de linhas do quadro 37 de 2017. Três edições e o IBGE concordam. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_2017-quadros-deslocados#p06 REVISAR **aceita**. IA: Em 2017 o quadro 37 ganhou itens novos e linhas trocadas; sem par nas outras edições, o destino depende de critério (tecido para o lar é armarinho ou artigo do lar? artesanato é recreação?). Recomendação da IA: tecidos, couro e entretela em 33006 (IBGE); artesanato junto, em 38005, como o IBGE. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_cynthia-folha-32#p07 MANTER **aceita**. IA: As células da ação já estão no destino proposto pela revisão manual (a planilha do Drive estava defasada). Nada a mudar. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_cynthia-folha-32#p21 REVISAR **aceita**. IA: A revisão manual propõe adotar a classificação mais recente (taxonomia que amadureceu). É escolha de critério para a série, não erro: decisão humana. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_cynthia-folha-32#p22 MANTER **aceita**. IA: As células da ação já estão no destino proposto pela revisão manual (a planilha do Drive estava defasada). Nada a mudar. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_vestuario-transporte-higiene-saude#p01 MOVER **aceita** (33004 → 33006). IA: Outlier pontual: os mesmos produtos estão em 33006 em todas as outras edições em que aparecem (pelo menos 3); só em 1987 a célula está em 33004, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 33006) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_vestuario-transporte-higiene-saude#p03 MOVER **aceita** (40006 → 33006). IA: Outlier pontual: os mesmos produtos estão em 33006 em todas as outras edições em que aparecem (pelo menos 3); só em 1987 a célula está em 40006, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 33006) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_vestuario-transporte-higiene-saude#p05 MOVER **aceita** (32003 → 33006). IA: Outlier pontual: os mesmos produtos estão em 33006 em todas as outras edições em que aparecem (pelo menos 3); só em 1995 a célula está em 32003, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 33006) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_vestuario-transporte-higiene-saude#p12 MOVER **aceita** (32003 → 33006). IA: Outlier pontual: os mesmos produtos estão em 33006 em todas as outras edições em que aparecem (pelo menos 3); só em 2017 a célula está em 32003, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 33006) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —

### 34. Transporte

#### 34001 — Urbano
Transporte · status **ativo** · criado em base
Células por ano: 1987: 12 · 1995: 20 · 2002: 25 · 2008: 17 · 2017: 20 (padrão 11111)
- Decisão 2026-10-16_claude-v3_cynthia-folha-38#p02 REVISAR **aceita**. IA: A revisão manual aponta outlier pontual, mas o detector não o confirmou: a célula tem itens sem histórico ou de outro conceito, ou o histórico não é unânime (R1). Precisa olhar a célula inteira. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_vestuario-transporte-higiene-saude#p10 MOVER **aceita** (31007 → 34001). IA: Outlier pontual: os mesmos produtos estão em 34001 em todas as outras edições em que aparecem (pelo menos 2); só em 2008 a célula está em 31007, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 34001) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_vestuario-transporte-higiene-saude#p21 MOVER **aceita** (41006 → 34001). IA: Outlier pontual: os mesmos produtos estão em 34001 em todas as outras edições em que aparecem (pelo menos 3); só em 2017 a célula está em 41006, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 34001) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —

#### 34002 — Gasolina para veiculo proprio
Transporte · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 2 · 2008: 2 · 2017: 2 (padrão 11111)

#### 34003 — Alcool para veiculo proprio
Transporte · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 1 · 2017: 1 (padrão 11111)

#### 34004 — Manutencao de veiculo proprio
Transporte · status **ativo** · criado em base
Células por ano: 1987: 42 · 1995: 38 · 2002: 38 · 2008: 21 · 2017: 70 (padrão 11111)
- Decisão 2026-10-16_claude-v3_1995-copia-de-1987#p01 MANTER **aceita**. IA: A coincidência de grupo com 1987 não é erro quando as edições seguintes confirmam. Nada a mudar. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_1995-copia-de-1987#p02 REVISAR **aceita**. IA: O padrão confirma a suspeita da pendência q3. O histórico dessas células vem de palavra-chave (descrições diferem), o que não basta para mover pela ADR 0005. Recomendação da IA: revisar a lista com o questionário de 1995 aberto; os casos evidentes acima podem ir para o grupo das edições seguintes. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_vestuario-transporte-higiene-saude#p06 MOVER **aceita** (34007 → 34004). IA: Outlier pontual: os mesmos produtos estão em 34004 em todas as outras edições em que aparecem (pelo menos 3); só em 1995 a célula está em 34007, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 34004) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_vestuario-transporte-higiene-saude#p14 MOVER **aceita** (34007 → 34004). IA: Outlier pontual: os mesmos produtos estão em 34004 em todas as outras edições em que aparecem (pelo menos 2); só em 2017 a célula está em 34007, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 34004) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_vestuario-transporte-higiene-saude#p23 REVISAR **aceita**. IA: Os mesmos produtos estão em 34007 nas duas outras edições em que aparecem; em 1995, 2002 estão em 34004. Duas edições contra uma, sem segunda fonte (IBGE neutro ou ausente, sem revisão manual): pela ADR 0005 não é óbvio. Recomendação da IA: mover, salvo razão de conceito. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_vestuario-transporte-higiene-saude#p24 REVISAR **aceita**. IA: Os mesmos produtos estão em 35002 nas duas outras edições em que aparecem; em 2002 estão em 34004. Duas edições contra uma, sem segunda fonte (IBGE neutro ou ausente, sem revisão manual): pela ADR 0005 não é óbvio. Recomendação da IA: mover, salvo razão de conceito. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_vestuario-transporte-higiene-saude#p38 REVISAR **aceita**. IA: Duas edições antigas contra três recentes, os dois grupos dentro de Transporte. Recomendação da IA: 34007 nos cinco anos (é o que o IBGE faz; seguro não é manutenção). Escolha de critério, não deslize. Humano (claude-ia (ADR 0005)): —

#### 34005 — Aquisicao de veiculos
Transporte · status **ativo** · criado em base
Células por ano: 1987: 14 · 1995: 21 · 2002: 21 · 2008: 24 · 2017: 26 (padrão 11111)
- Decisão 2026-10-16_claude-v3_1995-copia-de-1987#p01 MANTER **aceita**. IA: A coincidência de grupo com 1987 não é erro quando as edições seguintes confirmam. Nada a mudar. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_nao-consumo#p20 REVISAR **aceita**. IA: Os mesmos nomes de produto estão em 88888 nas outras edições, mas a célula está em 34005, de outro domínio (consumo, outras despesas, rendimentos ou inventário). Mesmo nome não garante mesma despesa (ex.: item de inventário de bens duráveis × compra; 'empregado' como rendimento × serviço doméstico). Sem confirmação do IBGE, a decisão é humana. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_vestuario-transporte-higiene-saude#p19 MOVER **aceita** (41001 → 34005). IA: Outlier pontual: os mesmos produtos estão em 34005 em todas as outras edições em que aparecem (pelo menos 3); só em 2017 a célula está em 41001, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 34005) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_vestuario-transporte-higiene-saude#p34 REVISAR **aceita**. IA: As outras edições põem os mesmos produtos em 34001, mas o tradutor do IBGE confirma o grupo atual (34005) em 2017. Fontes discordantes (CONSTITUICAO, hierarquia de evidência): decidir qual convenção vale para a série. Humano (claude-ia (ADR 0005)): —

#### 34006 — Viagens
Transporte · status **ativo** · criado em base
Células por ano: 1987: 0 · 1995: 0 · 2002: 0 · 2008: 0 · 2017: 0 (padrão 00000)

#### 34007 — Outros transporte
Transporte · status **ativo** · criado em base
Células por ano: 1987: 2 · 1995: 12 · 2002: 10 · 2008: 11 · 2017: 13 (padrão 11111)
- Decisão 2026-10-16_claude-v3_1995-copia-de-1987#p02 REVISAR **aceita**. IA: O padrão confirma a suspeita da pendência q3. O histórico dessas células vem de palavra-chave (descrições diferem), o que não basta para mover pela ADR 0005. Recomendação da IA: revisar a lista com o questionário de 1995 aberto; os casos evidentes acima podem ir para o grupo das edições seguintes. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_educacao-despesas-diversas#p01 MOVER **aceita** (34007 → 37006). IA: Outlier pontual: os mesmos produtos estão em 37006 em todas as outras edições em que aparecem (pelo menos 4); só em 1987 a célula está em 34007, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 37006) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_nao-consumo#p08 MOVER **aceita** (34007 → 41001). IA: Outlier pontual: os mesmos produtos estão em 41001 em todas as outras edições em que aparecem (pelo menos 2); só em 2017 a célula está em 34007, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 41001) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_vestuario-transporte-higiene-saude#p06 MOVER **aceita** (34007 → 34004). IA: Outlier pontual: os mesmos produtos estão em 34004 em todas as outras edições em que aparecem (pelo menos 3); só em 1995 a célula está em 34007, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 34004) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_vestuario-transporte-higiene-saude#p14 MOVER **aceita** (34007 → 34004). IA: Outlier pontual: os mesmos produtos estão em 34004 em todas as outras edições em que aparecem (pelo menos 2); só em 2017 a célula está em 34007, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 34004) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_vestuario-transporte-higiene-saude#p20 MOVER **aceita** (41001 → 34007). IA: Outlier pontual: os mesmos produtos estão em 34007 em todas as outras edições em que aparecem (pelo menos 3); só em 2017 a célula está em 41001, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 34007) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_vestuario-transporte-higiene-saude#p35 REVISAR **aceita**. IA: As outras edições põem os mesmos produtos em 34004, mas o tradutor do IBGE confirma o grupo atual (34007) em 2008. Fontes discordantes (CONSTITUICAO, hierarquia de evidência): decidir qual convenção vale para a série. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_vestuario-transporte-higiene-saude#p37 MOVER **aceita** (41001 → 34007). IA: Em 2017 o seguro obrigatório sai do consumo sem mudança de conceito na POF; as duas edições anteriores e o IBGE de 2017 concordam em Transporte/Outras. Duas fontes ⇒ ALTA (ADR 0005). Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_vestuario-transporte-higiene-saude#p38 REVISAR **aceita**. IA: Duas edições antigas contra três recentes, os dois grupos dentro de Transporte. Recomendação da IA: 34007 nos cinco anos (é o que o IBGE faz; seguro não é manutenção). Escolha de critério, não deslize. Humano (claude-ia (ADR 0005)): —

#### 34008 — Bicicleta
Transporte · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 1 · 2017: 1 (padrão 11111)

#### 34009 — Estacionamento e vaga cativa de estacionamento
Transporte · status **ativo** · criado em base
Células por ano: 1987: 3 · 1995: 3 · 2002: 3 · 2008: 3 · 2017: 2 (padrão 11111)

#### 34010 — Oleo diesel
Transporte · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 1 · 2017: 1 (padrão 11111)

#### 34011 — Pedagio
Transporte · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 1 · 2017: 1 (padrão 11111)

### 35. Higiene_e_cuidados_pessoais

#### 35001 — Perfume
Higiene_e_cuidados_pessoais · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 1 · 2017: 1 (padrão 11111)

#### 35002 — Produtos para cabelo
Higiene_e_cuidados_pessoais · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 3 · 2008: 2 · 2017: 1 (padrão 11111)
- Decisão 2026-10-16_claude-v3_cynthia-folha-32#p16 MANTER **aceita**. IA: As células da ação já estão no destino proposto pela revisão manual (a planilha do Drive estava defasada). Nada a mudar. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_vestuario-transporte-higiene-saude#p08 MOVER **aceita** (32004 → 35002). IA: Outlier pontual: os mesmos produtos estão em 35002 em todas as outras edições em que aparecem (pelo menos 2); só em 2002 a célula está em 32004, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 35002) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —

#### 35003 — Sabonete
Higiene_e_cuidados_pessoais · status **ativo** · criado em base
Células por ano: 1987: 2 · 1995: 2 · 2002: 3 · 2008: 1 · 2017: 1 (padrão 11111)
- Decisão 2026-10-16_claude-v3_vestuario-transporte-higiene-saude#p09 MOVER **aceita** (35004 → 35003). IA: Outlier pontual: os mesmos produtos estão em 35003 em todas as outras edições em que aparecem (pelo menos 4); só em 2002 a célula está em 35004, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 35003) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —

#### 35004 — Produtos de uso pessoal
Higiene_e_cuidados_pessoais · status **ativo** · criado em base
Células por ano: 1987: 32 · 1995: 35 · 2002: 45 · 2008: 40 · 2017: 30 (padrão 11111)
- Decisão 2026-10-16_claude-v3_educacao-despesas-diversas#p12 MOVER **aceita** (35004 → 40006). IA: Outlier pontual: os mesmos produtos estão em 40006 em todas as outras edições em que aparecem (pelo menos 4); só em 2017 a célula está em 35004, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 40006) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_pendencias-validacao-e-criar#p12 REVISAR **aceita**. IA: As outras edições não confirmam com clareza nem o grupo atual nem o da planilha antiga. Recomendação da IA: 35004 Produtos de uso pessoal, o grupo mais frequente nas outras edições. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_pendencias-validacao-e-criar#p17 MANTER **aceita**. IA: A mudança da planilha v2026 para a base (lá 36001, hoje 35004) é a classificação que as outras edições usam para os mesmos produtos (7 de 7 ocorrências): correção legítima. Nada a mudar. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_vestuario-transporte-higiene-saude#p09 MOVER **aceita** (35004 → 35003). IA: Outlier pontual: os mesmos produtos estão em 35003 em todas as outras edições em que aparecem (pelo menos 4); só em 2002 a célula está em 35004, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 35003) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_vestuario-transporte-higiene-saude#p11 MOVER **aceita** (16103 → 35004). IA: Outlier pontual: os mesmos produtos estão em 35004 em todas as outras edições em que aparecem (pelo menos 4); só em 2017 a célula está em 16103, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 35004) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_vestuario-transporte-higiene-saude#p15 MOVER **aceita** (35004 → 36009). IA: Outlier pontual: os mesmos produtos estão em 36009 em todas as outras edições em que aparecem (pelo menos 2); só em 2017 a célula está em 35004, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 36009) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —

#### 35005 — Creme dental e fio dental
Higiene_e_cuidados_pessoais · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 1 · 2017: 2 (padrão 11111)

#### 35006 — Fralda descartável infantil
Higiene_e_cuidados_pessoais · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 1 · 2017: 1 (padrão 11111)

### 36. Assistencia_a_saude

#### 36001 — Remedios
Assistencia_a_saude · status **ativo** · criado em base
Células por ano: 1987: 4 · 1995: 37 · 2002: 92 · 2008: 48 · 2017: 74 (padrão 11111)
- Decisão 2026-10-16_claude-v3_1995-copia-de-1987#p01 MANTER **aceita**. IA: A coincidência de grupo com 1987 não é erro quando as edições seguintes confirmam. Nada a mudar. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_1995-copia-de-1987#p02 REVISAR **aceita**. IA: O padrão confirma a suspeita da pendência q3. O histórico dessas células vem de palavra-chave (descrições diferem), o que não basta para mover pela ADR 0005. Recomendação da IA: revisar a lista com o questionário de 1995 aberto; os casos evidentes acima podem ir para o grupo das edições seguintes. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_vestuario-transporte-higiene-saude#p16 MOVER **aceita** (36001 → 36009). IA: Outlier pontual: os mesmos produtos estão em 36009 em todas as outras edições em que aparecem (pelo menos 3); só em 2017 a célula está em 36001, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 36009) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_vestuario-transporte-higiene-saude#p25 REVISAR **aceita**. IA: Os mesmos produtos estão em 35004 nas duas outras edições em que aparecem; em 2002 estão em 36001. Duas edições contra uma, sem segunda fonte (IBGE neutro ou ausente, sem revisão manual): pela ADR 0005 não é óbvio. Recomendação da IA: mover, salvo razão de conceito. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_vestuario-transporte-higiene-saude#p26 REVISAR **aceita**. IA: Os mesmos produtos estão em 36009 nas duas outras edições em que aparecem; em 2002 estão em 36001. Duas edições contra uma, sem segunda fonte (IBGE neutro ou ausente, sem revisão manual): pela ADR 0005 não é óbvio. Recomendação da IA: mover, salvo razão de conceito. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_vestuario-transporte-higiene-saude#p36 REVISAR **aceita**. IA: As outras edições põem os mesmos produtos em 36009, mas o tradutor do IBGE confirma o grupo atual (36001) em 2008. Fontes discordantes (CONSTITUICAO, hierarquia de evidência): decidir qual convenção vale para a série. Humano (claude-ia (ADR 0005)): —

#### 36002 — Plano Seguro saude
Assistencia_a_saude · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 4 · 2002: 3 · 2008: 5 · 2017: 5 (padrão 11111)
- Decisão 2026-09-11_arthurwelle_cirurgia#p16 MOVER **aceita** (36010 → 36002). IA: Mensalidade de clínica é pagamento recorrente por assistência, classificado com planos nos três anos em que aparece antes de 2017. Humano (arthur): —
- Decisão 2026-09-11_arthurwelle_cirurgia#p23 REVISAR **aceita**. IA: O erro não é pontual do quadro 42: se o PROCV deslocou linhas, o mesmo padrão deve aparecer em outros quadros de 2017. Vale uma onda global só para 2017, comparando cada célula com a de 2008 pela tabela compara2008-17. Humano (arthur): —

#### 36003 — Consulta e tratamento dentario
Assistencia_a_saude · status **ativo** · criado em base
Células por ano: 1987: 2 · 1995: 2 · 2002: 3 · 2008: 2 · 2017: 2 (padrão 11111)
- Decisão 2026-09-11_arthurwelle_cirurgia#p12 MOVER **aceita** (36004 → 36003). IA: Consulta com dentista e tratamento dentário formam o grupo 36003 em todos os anos anteriores. Humano (arthur): —
- Decisão 2026-09-11_arthurwelle_cirurgia#p23 REVISAR **aceita**. IA: O erro não é pontual do quadro 42: se o PROCV deslocou linhas, o mesmo padrão deve aparecer em outros quadros de 2017. Vale uma onda global só para 2017, comparando cada célula com a de 2008 pela tabela compara2008-17. Humano (arthur): —

#### 36004 — Consulta medica
Assistencia_a_saude · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 2 · 2002: 14 · 2008: 4 · 2017: 39 (padrão 11111)
- Regra 2026-09-11_arthurwelle_cirurgia#r3 (excecao_r1, ativa): Em 2002:42046 o item consulta médica nutricionista não propaga a R1: a célula segue o conceito dominante (consulta médica) e o nutricionista fica registrado como contaminação.
- Regra 2026-09-11_arthurwelle_cirurgia#r4 (excecao_r1, ativa): Em 2002:42008 os itens de exame ginecológico/pré-natal/preventivo e de exame oftalmológico não propagam a R1: a célula segue o conceito dominante (exames de laboratório) e eles ficam registrados como contaminação.
- Decisão 2026-09-11_arthurwelle_cirurgia#p09 MOVER **aceita** (36004 → 36005). IA: São profissionais não médicos cujo atendimento a POF trata como tratamento em todos os anos anteriores. Mantê-los em consulta médica quebra a série dos dois grupos em 2017. Humano (arthur): —
- Decisão 2026-09-11_arthurwelle_cirurgia#p12 MOVER **aceita** (36004 → 36003). IA: Consulta com dentista e tratamento dentário formam o grupo 36003 em todos os anos anteriores. Humano (arthur): —
- Decisão 2026-09-11_arthurwelle_cirurgia#p18 MOVER **aceita** (36008 → 36004). IA: Pela R1 o conceito de exame ginecológico/preventivo pertence ao bloco da consulta, porque em dois anos não dá para separá-lo dela. Consequência: as células com código próprio também vão para lá. Humano (arthur): —
- Decisão 2026-09-11_arthurwelle_cirurgia#p19 MOVER **aceita** (36008 → 36004). IA: É consulta médica com especialista, como as demais 40 células de consulta de 2017. Humano (arthur): —

#### 36005 — Tratamento ambulatorial
Assistencia_a_saude · status **ativo** · criado em base
Células por ano: 1987: 3 · 1995: 3 · 2002: 8 · 2008: 13 · 2017: 15 (padrão 11111)
- Regra 2026-09-11_arthurwelle_cirurgia#r1 (excecao_r1, ativa): Em 2002:42015 o item implante de cabelo não propaga a R1: a célula segue o conceito dominante (outros tratamentos) e o implante fica registrado como contaminação.
- Regra 2026-09-11_arthurwelle_cirurgia#r2 (excecao_r1, ativa): Em 2002:42016 o item instrumentador cirúrgico não propaga a R1: a célula segue o conceito dominante (enfermagem) e o instrumentador fica registrado como contaminação.
- Regra 2026-09-11_arthurwelle_cirurgia#r3 (excecao_r1, ativa): Em 2002:42046 o item consulta médica nutricionista não propaga a R1: a célula segue o conceito dominante (consulta médica) e o nutricionista fica registrado como contaminação.
- Decisão 2026-09-11_arthurwelle_cirurgia#p05 MOVER **aceita** (36005 → 36006). IA: É a única célula de cirurgia de 2017 e está em tratamento ambulatorial, o que deixa 36006 vazio em 2017 e quebra a série (R4). Todos os anos anteriores têm a célula equivalente em 36006. Humano (arthur): —
- Decisão 2026-09-11_arthurwelle_cirurgia#p06 MOVER **aceita** (36005 → 36006). IA: A distinção laser x cirurgia não é observável em 2008 nem em 2017, então não pode existir na harmonização (R1). Diferente das quatro exceções, esta junção se repete em duas edições: é como a POF passou a medir, não um acidente de 2002. Humano (arthur): —
- Decisão 2026-09-11_arthurwelle_cirurgia#p08 MOVER **aceita** (36010 → 36005). IA: Enfermeira e tratamento de enfermagem são inseparáveis em 2008, então a harmonização não pode separá-los (R1). O grupo de destino é o dos tratamentos, onde o conceito já está na maior parte dos anos. Humano (arthur): —
- Decisão 2026-09-11_arthurwelle_cirurgia#p09 MOVER **aceita** (36004 → 36005). IA: São profissionais não médicos cujo atendimento a POF trata como tratamento em todos os anos anteriores. Mantê-los em consulta médica quebra a série dos dois grupos em 2017. Humano (arthur): —
- Decisão 2026-09-11_arthurwelle_cirurgia#p10 MOVER **aceita** (36005;36010 → 36009). IA: Mesmo produto, mesmo grupo nos quatro anos anteriores; a mudança em 2017 não tem justificativa nas classificações originais. Humano (arthur): —
- Decisão 2026-09-11_arthurwelle_cirurgia#p13 MOVER **aceita** (36005 → 36010). IA: Remoção por ambulância está em outras assistências nos quatro anos anteriores. Humano (arthur): —
- Decisão 2026-09-11_arthurwelle_cirurgia#p14 MOVER **aceita** (36005 → 36010). IA: Mesmo conjunto de itens, em 36010 nos quatro anos anteriores. Humano (arthur): —
- Decisão 2026-09-11_arthurwelle_cirurgia#p15 MOVER **aceita** (36005 → 36010). IA: Três anos contra dois, e a mudança não vem de mudança na POF: o item de 2008 ainda traz SANGUE HUMANO. Mover os dois anos recentes custa menos do que mover três anos (R8). Humano (arthur): —
- Decisão 2026-09-11_arthurwelle_cirurgia#p17 MOVER **aceita** (36008 → 36005). IA: Hemodiálise é tratamento, não exame, e está em 36005 nos dois anos anteriores em que aparece. Humano (arthur): —
- Decisão 2026-09-11_arthurwelle_cirurgia#p22 MANTER **aceita**. IA: Foram examinadas e a classificação atual é a mais granular compatível com os cinco anos. Nada a mudar (R8). Humano (arthur): —
- Decisão 2026-09-11_arthurwelle_cirurgia#p23 REVISAR **aceita**. IA: O erro não é pontual do quadro 42: se o PROCV deslocou linhas, o mesmo padrão deve aparecer em outros quadros de 2017. Vale uma onda global só para 2017, comparando cada célula com a de 2008 pela tabela compara2008-17. Humano (arthur): —

#### 36006 — Servicos de cirurgia
Assistencia_a_saude · status **ativo** · criado em base
Células por ano: 1987: 3 · 1995: 3 · 2002: 3 · 2008: 1 · 2017: 1 (padrão 11111)
- Regra 2026-09-11_arthurwelle_cirurgia#r1 (excecao_r1, ativa): Em 2002:42015 o item implante de cabelo não propaga a R1: a célula segue o conceito dominante (outros tratamentos) e o implante fica registrado como contaminação.
- Regra 2026-09-11_arthurwelle_cirurgia#r2 (excecao_r1, ativa): Em 2002:42016 o item instrumentador cirúrgico não propaga a R1: a célula segue o conceito dominante (enfermagem) e o instrumentador fica registrado como contaminação.
- Decisão 2026-09-11_arthurwelle_cirurgia#p05 MOVER **aceita** (36005 → 36006). IA: É a única célula de cirurgia de 2017 e está em tratamento ambulatorial, o que deixa 36006 vazio em 2017 e quebra a série (R4). Todos os anos anteriores têm a célula equivalente em 36006. Humano (arthur): —
- Decisão 2026-09-11_arthurwelle_cirurgia#p06 MOVER **aceita** (36005 → 36006). IA: A distinção laser x cirurgia não é observável em 2008 nem em 2017, então não pode existir na harmonização (R1). Diferente das quatro exceções, esta junção se repete em duas edições: é como a POF passou a medir, não um acidente de 2002. Humano (arthur): —
- Decisão 2026-09-11_arthurwelle_cirurgia#p07 MOVER **aceita** (36009 → 36006). IA: Mesma situação do laser: em 2008 não dá para separar fotografia de cirurgia, então a distinção não pode existir na harmonização. Em 2017 o item deixa de aparecer. Humano (arthur): —
- Decisão 2026-09-11_arthurwelle_cirurgia#p20 MOVER **aceita** (36006 → 36009). IA: São produtos de farmácia, não serviço de cirurgia. O destino é o grupo em que os mesmos itens estão nos anos intermediários. Humano (arthur): —
- Decisão 2026-09-11_arthurwelle_cirurgia#p21 MOVER **aceita** (36006 → 36010). IA: Mesmos produtos, mesmo grupo dos anos intermediários. Observação para uma onda futura: 36010 (outras assistências à saúde) é um destino estranho para produtos de bebê, mas mudá-lo exige rever os cinco anos. Humano (arthur): —
- Decisão 2026-09-11_arthurwelle_cirurgia#p22 MANTER **aceita**. IA: Foram examinadas e a classificação atual é a mais granular compatível com os cinco anos. Nada a mudar (R8). Humano (arthur): —
- Decisão 2026-09-11_arthurwelle_cirurgia#p23 REVISAR **aceita**. IA: O erro não é pontual do quadro 42: se o PROCV deslocou linhas, o mesmo padrão deve aparecer em outros quadros de 2017. Vale uma onda global só para 2017, comparando cada célula com a de 2008 pela tabela compara2008-17. Humano (arthur): —

#### 36007 — Hospitalizacao
Assistencia_a_saude · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 1 · 2017: 1 (padrão 11111)

#### 36008 — Exames diversos
Assistencia_a_saude · status **ativo** · criado em base
Células por ano: 1987: 4 · 1995: 6 · 2002: 6 · 2008: 9 · 2017: 24 (padrão 11111)
- Regra 2026-09-11_arthurwelle_cirurgia#r4 (excecao_r1, ativa): Em 2002:42008 os itens de exame ginecológico/pré-natal/preventivo e de exame oftalmológico não propagam a R1: a célula segue o conceito dominante (exames de laboratório) e eles ficam registrados como contaminação.
- Decisão 2026-09-11_arthurwelle_cirurgia#p17 MOVER **aceita** (36008 → 36005). IA: Hemodiálise é tratamento, não exame, e está em 36005 nos dois anos anteriores em que aparece. Humano (arthur): —
- Decisão 2026-09-11_arthurwelle_cirurgia#p18 MOVER **aceita** (36008 → 36004). IA: Pela R1 o conceito de exame ginecológico/preventivo pertence ao bloco da consulta, porque em dois anos não dá para separá-lo dela. Consequência: as células com código próprio também vão para lá. Humano (arthur): —
- Decisão 2026-09-11_arthurwelle_cirurgia#p19 MOVER **aceita** (36008 → 36004). IA: É consulta médica com especialista, como as demais 40 células de consulta de 2017. Humano (arthur): —

#### 36009 — Material de tratamento
Assistencia_a_saude · status **ativo** · criado em base
Células por ano: 1987: 11 · 1995: 32 · 2002: 38 · 2008: 14 · 2017: 22 (padrão 11111)
- Decisão 2026-09-11_arthurwelle_cirurgia#p07 MOVER **aceita** (36009 → 36006). IA: Mesma situação do laser: em 2008 não dá para separar fotografia de cirurgia, então a distinção não pode existir na harmonização. Em 2017 o item deixa de aparecer. Humano (arthur): —
- Decisão 2026-09-11_arthurwelle_cirurgia#p10 MOVER **aceita** (36005;36010 → 36009). IA: Mesmo produto, mesmo grupo nos quatro anos anteriores; a mudança em 2017 não tem justificativa nas classificações originais. Humano (arthur): —
- Decisão 2026-09-11_arthurwelle_cirurgia#p11 MOVER **aceita** (36010 → 36009). IA: Mesma lista de produtos dos anos anteriores, em outro grupo só em 2017. Humano (arthur): —
- Decisão 2026-09-11_arthurwelle_cirurgia#p20 MOVER **aceita** (36006 → 36009). IA: São produtos de farmácia, não serviço de cirurgia. O destino é o grupo em que os mesmos itens estão nos anos intermediários. Humano (arthur): —
- Decisão 2026-09-11_arthurwelle_cirurgia#p23 REVISAR **aceita**. IA: O erro não é pontual do quadro 42: se o PROCV deslocou linhas, o mesmo padrão deve aparecer em outros quadros de 2017. Vale uma onda global só para 2017, comparando cada célula com a de 2008 pela tabela compara2008-17. Humano (arthur): —
- Decisão 2026-10-16_claude-v3_pendencias-formulario#p02 MANTER **aceita**. IA: Pendência resolvida por decisão anterior desta v3. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_pendencias-validacao-e-criar#p01 REVISAR **aceita**. IA: As outras edições não confirmam com clareza nem o grupo atual nem o da planilha antiga. Recomendação da IA: 36009 Material de tratamento, o grupo mais frequente nas outras edições. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_pendencias-validacao-e-criar#p08 REVISAR **aceita**. IA: As outras edições não confirmam com clareza nem o grupo atual nem o da planilha antiga. Recomendação da IA: 36009 Material de tratamento, o grupo mais frequente nas outras edições. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_pendencias-validacao-e-criar#p29 REVISAR **aceita**. IA: As outras edições não confirmam com clareza nem o grupo atual nem o da planilha antiga. Recomendação da IA: 36009 Material de tratamento, o grupo mais frequente nas outras edições. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_vestuario-transporte-higiene-saude#p02 MOVER **aceita** (36010 → 36009). IA: Outlier pontual: os mesmos produtos estão em 36009 em todas as outras edições em que aparecem (pelo menos 4); só em 1987 a célula está em 36010, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 36009) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_vestuario-transporte-higiene-saude#p15 MOVER **aceita** (35004 → 36009). IA: Outlier pontual: os mesmos produtos estão em 36009 em todas as outras edições em que aparecem (pelo menos 2); só em 2017 a célula está em 35004, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 36009) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_vestuario-transporte-higiene-saude#p16 MOVER **aceita** (36001 → 36009). IA: Outlier pontual: os mesmos produtos estão em 36009 em todas as outras edições em que aparecem (pelo menos 3); só em 2017 a célula está em 36001, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 36009) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_vestuario-transporte-higiene-saude#p17 MOVER **aceita** (36009 → 36010). IA: Outlier pontual: os mesmos produtos estão em 36010 em todas as outras edições em que aparecem (pelo menos 3); só em 2017 a célula está em 36009, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 36010) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —

#### 36010 — Outras assistencia saude
Assistencia_a_saude · status **ativo** · criado em base
Células por ano: 1987: 15 · 1995: 15 · 2002: 13 · 2008: 13 · 2017: 12 (padrão 11111)
- Regra 2026-09-11_arthurwelle_cirurgia#r2 (excecao_r1, ativa): Em 2002:42016 o item instrumentador cirúrgico não propaga a R1: a célula segue o conceito dominante (enfermagem) e o instrumentador fica registrado como contaminação.
- Decisão 2026-09-11_arthurwelle_cirurgia#p08 MOVER **aceita** (36010 → 36005). IA: Enfermeira e tratamento de enfermagem são inseparáveis em 2008, então a harmonização não pode separá-los (R1). O grupo de destino é o dos tratamentos, onde o conceito já está na maior parte dos anos. Humano (arthur): —
- Decisão 2026-09-11_arthurwelle_cirurgia#p10 MOVER **aceita** (36005;36010 → 36009). IA: Mesmo produto, mesmo grupo nos quatro anos anteriores; a mudança em 2017 não tem justificativa nas classificações originais. Humano (arthur): —
- Decisão 2026-09-11_arthurwelle_cirurgia#p11 MOVER **aceita** (36010 → 36009). IA: Mesma lista de produtos dos anos anteriores, em outro grupo só em 2017. Humano (arthur): —
- Decisão 2026-09-11_arthurwelle_cirurgia#p13 MOVER **aceita** (36005 → 36010). IA: Remoção por ambulância está em outras assistências nos quatro anos anteriores. Humano (arthur): —
- Decisão 2026-09-11_arthurwelle_cirurgia#p14 MOVER **aceita** (36005 → 36010). IA: Mesmo conjunto de itens, em 36010 nos quatro anos anteriores. Humano (arthur): —
- Decisão 2026-09-11_arthurwelle_cirurgia#p15 MOVER **aceita** (36005 → 36010). IA: Três anos contra dois, e a mudança não vem de mudança na POF: o item de 2008 ainda traz SANGUE HUMANO. Mover os dois anos recentes custa menos do que mover três anos (R8). Humano (arthur): —
- Decisão 2026-09-11_arthurwelle_cirurgia#p16 MOVER **aceita** (36010 → 36002). IA: Mensalidade de clínica é pagamento recorrente por assistência, classificado com planos nos três anos em que aparece antes de 2017. Humano (arthur): —
- Decisão 2026-09-11_arthurwelle_cirurgia#p21 MOVER **aceita** (36006 → 36010). IA: Mesmos produtos, mesmo grupo dos anos intermediários. Observação para uma onda futura: 36010 (outras assistências à saúde) é um destino estranho para produtos de bebê, mas mudá-lo exige rever os cinco anos. Humano (arthur): —
- Decisão 2026-09-11_arthurwelle_cirurgia#p23 REVISAR **aceita**. IA: O erro não é pontual do quadro 42: se o PROCV deslocou linhas, o mesmo padrão deve aparecer em outros quadros de 2017. Vale uma onda global só para 2017, comparando cada célula com a de 2008 pela tabela compara2008-17. Humano (arthur): —
- Decisão 2026-10-16_claude-v3_pendencias-validacao-e-criar#p01 REVISAR **aceita**. IA: As outras edições não confirmam com clareza nem o grupo atual nem o da planilha antiga. Recomendação da IA: 36009 Material de tratamento, o grupo mais frequente nas outras edições. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_pendencias-validacao-e-criar#p08 REVISAR **aceita**. IA: As outras edições não confirmam com clareza nem o grupo atual nem o da planilha antiga. Recomendação da IA: 36009 Material de tratamento, o grupo mais frequente nas outras edições. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_vestuario-transporte-higiene-saude#p02 MOVER **aceita** (36010 → 36009). IA: Outlier pontual: os mesmos produtos estão em 36009 em todas as outras edições em que aparecem (pelo menos 4); só em 1987 a célula está em 36010, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 36009) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_vestuario-transporte-higiene-saude#p17 MOVER **aceita** (36009 → 36010). IA: Outlier pontual: os mesmos produtos estão em 36010 em todas as outras edições em que aparecem (pelo menos 3); só em 2017 a célula está em 36009, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 36010) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —

### 37. Educacao

#### 37001 — Cursos regulares
Educacao · status **ativo** · criado em base
Células por ano: 1987: 4 · 1995: 4 · 2002: 4 · 2008: 3 · 2017: 36 (padrão 11111)
- Decisão 2026-10-16_claude-v3_cynthia-folha-37#p08 REVISAR **aceita**. IA: A revisão manual aponta outlier pontual, mas o detector não o confirmou: a célula tem itens sem histórico ou de outro conceito, ou o histórico não é unânime (R1). Precisa olhar a célula inteira. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_educacao-despesas-diversas#p02 MOVER **aceita** (37001 → 37006). IA: Outlier pontual: os mesmos produtos estão em 37006 em todas as outras edições em que aparecem (pelo menos 3); só em 1987 a célula está em 37001, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 37006) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_educacao-despesas-diversas#p08 MOVER **aceita** (37003 → 37001). IA: Outlier pontual: os mesmos produtos estão em 37001 em todas as outras edições em que aparecem (pelo menos 4); só em 1995 a célula está em 37003, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 37001) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_educacao-despesas-diversas#p21 REVISAR **aceita**. IA: Os mesmos produtos estão em 37003 nas duas outras edições em que aparecem; em 2017 estão em 37001. Duas edições contra uma, sem segunda fonte (IBGE neutro ou ausente, sem revisão manual): pela ADR 0005 não é óbvio. Recomendação da IA: mover, salvo razão de conceito. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_educacao-despesas-diversas#p22 REVISAR **aceita**. IA: Os mesmos produtos estão em 37004 nas duas outras edições em que aparecem; em 1987 estão em 37001. Duas edições contra uma, sem segunda fonte (IBGE neutro ou ausente, sem revisão manual): pela ADR 0005 não é óbvio. Recomendação da IA: mover, salvo razão de conceito. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_educacao-despesas-diversas#p23 REVISAR **aceita**. IA: Os mesmos produtos estão em 37006 nas duas outras edições em que aparecem; em 1995 estão em 37001. Duas edições contra uma, sem segunda fonte (IBGE neutro ou ausente, sem revisão manual): pela ADR 0005 não é óbvio. Recomendação da IA: mover, salvo razão de conceito. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_pendencias-validacao-e-criar#p19 MANTER **aceita**. IA: A mudança da planilha v2026 para a base (lá 34004, hoje 37001) é a classificação que as outras edições usam para os mesmos produtos (12 de 16 ocorrências): correção legítima. Nada a mudar. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_pendencias-validacao-e-criar#p25 REVISAR **aceita**. IA: As outras edições não confirmam com clareza nem o grupo atual nem o da planilha antiga. Recomendação da IA: 37005 Artigos escolares, o grupo mais frequente nas outras edições. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_pendencias-validacao-e-criar#p27 REVISAR **aceita**. IA: As outras edições não confirmam com clareza nem o grupo atual nem o da planilha antiga. Recomendação da IA: 34007 Outros transporte, o grupo mais frequente nas outras edições. Humano (claude-ia (ADR 0005)): —

#### 37002 — Curso superior
Educacao · status **ativo** · criado em base
Células por ano: 1987: 4 · 1995: 2 · 2002: 3 · 2008: 4 · 2017: 7 (padrão 11111)
- Decisão 2026-10-16_claude-v3_cynthia-folha-37#p03 REVISAR **aceita**. IA: A revisão manual move por analogia com itens parecidos, sem o mesmo produto em outras edições. Evidência de nível 5 (descrição): decisão humana. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_educacao-despesas-diversas#p03 MOVER **aceita** (37002 → 37005). IA: Outlier pontual: os mesmos produtos estão em 37005 em todas as outras edições em que aparecem (pelo menos 2); só em 1987 a célula está em 37002, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 37005) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_pendencias-validacao-e-criar#p11 REVISAR **aceita**. IA: As outras edições não confirmam com clareza nem o grupo atual nem o da planilha antiga. Recomendação da IA: 37003 Outros cursos, o grupo mais frequente nas outras edições. Humano (claude-ia (ADR 0005)): —

#### 37003 — Outros cursos
Educacao · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 17 · 2002: 20 · 2008: 55 · 2017: 64 (padrão 11111)
- Decisão 2026-10-16_claude-v3_cynthia-folha-37#p02 REVISAR **aceita**. IA: A revisão manual propõe adotar a classificação mais recente (taxonomia que amadureceu). É escolha de critério para a série, não erro: decisão humana. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_cynthia-folha-37#p04 REVISAR **aceita**. IA: Ação da revisão manual sem tipo identificado; decisão humana. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_cynthia-folha-37#p06 REVISAR **aceita**. IA: Ação da revisão manual sem tipo identificado; decisão humana. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_cynthia-folha-37#p07 REVISAR **aceita**. IA: Ação da revisão manual sem tipo identificado; decisão humana. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_cynthia-folha-37#p10 REVISAR **aceita**. IA: Ação da revisão manual sem tipo identificado; decisão humana. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_cynthia-folha-38#p15 REVISAR **aceita**. IA: A revisão manual aponta outlier pontual, mas o detector não o confirmou: a célula tem itens sem histórico ou de outro conceito, ou o histórico não é unânime (R1). Precisa olhar a célula inteira. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_educacao-despesas-diversas#p08 MOVER **aceita** (37003 → 37001). IA: Outlier pontual: os mesmos produtos estão em 37001 em todas as outras edições em que aparecem (pelo menos 4); só em 1995 a célula está em 37003, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 37001) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_educacao-despesas-diversas#p14 MOVER **aceita** (37006 → 37003). IA: Outlier pontual: os mesmos produtos estão em 37003 em todas as outras edições em que aparecem (pelo menos 2); só em 2017 a célula está em 37006, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 37003) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_recreacao-cultura#p13 REVISAR **aceita**. IA: As outras edições põem os mesmos produtos em 38004, mas o tradutor do IBGE confirma o grupo atual (37003) em 2017. Fontes discordantes (CONSTITUICAO, hierarquia de evidência): decidir qual convenção vale para a série. Humano (claude-ia (ADR 0005)): —

#### 37004 — Livros e revistas tecnicas
Educacao · status **ativo** · criado em base
Células por ano: 1987: 0 · 1995: 4 · 2002: 4 · 2008: 4 · 2017: 1 (padrão 01111)
- Decisão 2026-10-16_claude-v3_recreacao-cultura#p01 MOVER **aceita** (37004 → 38003). IA: Outlier pontual: os mesmos produtos estão em 38003 em todas as outras edições em que aparecem (pelo menos 2); só em 1987 a célula está em 37004, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 38003) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_recreacao-cultura#p05 MOVER **aceita** (37004 → 38004). IA: Outlier pontual: os mesmos produtos estão em 38004 em todas as outras edições em que aparecem (pelo menos 2); só em 1995 a célula está em 37004, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 38004) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —

#### 37005 — Artigos escolares
Educacao · status **ativo** · criado em base
Células por ano: 1987: 7 · 1995: 21 · 2002: 16 · 2008: 8 · 2017: 68 (padrão 11111)
- Decisão 2026-10-16_claude-v3_cynthia-folha-37#p09 MANTER **aceita**. IA: As células da ação já estão no destino proposto pela revisão manual (a planilha do Drive estava defasada). Nada a mudar. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_educacao-despesas-diversas#p03 MOVER **aceita** (37002 → 37005). IA: Outlier pontual: os mesmos produtos estão em 37005 em todas as outras edições em que aparecem (pelo menos 2); só em 1987 a célula está em 37002, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 37005) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_educacao-despesas-diversas#p04 MOVER **aceita** (37006 → 37005). IA: Outlier pontual: os mesmos produtos estão em 37005 em todas as outras edições em que aparecem (pelo menos 3); só em 1987 a célula está em 37006, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 37005) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_educacao-despesas-diversas#p05 MOVER **aceita** (38004 → 37005). IA: Outlier pontual: os mesmos produtos estão em 37005 em todas as outras edições em que aparecem (pelo menos 3); só em 1987 a célula está em 38004, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 37005) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_educacao-despesas-diversas#p09 MOVER **aceita** (37005 → 37006). IA: Outlier pontual: os mesmos produtos estão em 37006 em todas as outras edições em que aparecem (pelo menos 3); só em 1995 a célula está em 37005, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 37006) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_educacao-despesas-diversas#p13 MOVER **aceita** (37005 → 40006). IA: Outlier pontual: os mesmos produtos estão em 40006 em todas as outras edições em que aparecem (pelo menos 2); só em 2017 a célula está em 37005, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 40006) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_educacao-despesas-diversas#p24 REVISAR **aceita**. IA: Os mesmos produtos estão em 37006 nas duas outras edições em que aparecem; em 1995 estão em 37005. Duas edições contra uma, sem segunda fonte (IBGE neutro ou ausente, sem revisão manual): pela ADR 0005 não é óbvio. Recomendação da IA: mover, salvo razão de conceito. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_habitacao-servicos#p12 MOVER **aceita** (37005 → 32003). IA: Outlier pontual: os mesmos produtos estão em 32003 em todas as outras edições em que aparecem (pelo menos 3); só em 2017 a célula está em 37005, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 32003) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —

#### 37006 — Outras educacao
Educacao · status **ativo** · criado em base
Células por ano: 1987: 15 · 1995: 12 · 2002: 23 · 2008: 24 · 2017: 26 (padrão 11111)
- Decisão 2026-10-16_claude-v3_educacao-despesas-diversas#p01 MOVER **aceita** (34007 → 37006). IA: Outlier pontual: os mesmos produtos estão em 37006 em todas as outras edições em que aparecem (pelo menos 4); só em 1987 a célula está em 34007, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 37006) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_educacao-despesas-diversas#p02 MOVER **aceita** (37001 → 37006). IA: Outlier pontual: os mesmos produtos estão em 37006 em todas as outras edições em que aparecem (pelo menos 3); só em 1987 a célula está em 37001, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 37006) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_educacao-despesas-diversas#p04 MOVER **aceita** (37006 → 37005). IA: Outlier pontual: os mesmos produtos estão em 37005 em todas as outras edições em que aparecem (pelo menos 3); só em 1987 a célula está em 37006, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 37005) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_educacao-despesas-diversas#p09 MOVER **aceita** (37005 → 37006). IA: Outlier pontual: os mesmos produtos estão em 37006 em todas as outras edições em que aparecem (pelo menos 3); só em 1995 a célula está em 37005, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 37006) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_educacao-despesas-diversas#p14 MOVER **aceita** (37006 → 37003). IA: Outlier pontual: os mesmos produtos estão em 37003 em todas as outras edições em que aparecem (pelo menos 2); só em 2017 a célula está em 37006, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 37003) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_educacao-despesas-diversas#p29 REVISAR **aceita**. IA: As outras edições põem os mesmos produtos em 37003, mas o tradutor do IBGE confirma o grupo atual (37006) em 2008. Fontes discordantes (CONSTITUICAO, hierarquia de evidência): decidir qual convenção vale para a série. Humano (claude-ia (ADR 0005)): —

### 38. Recreacao_e_cultura

#### 38001 — Brinquedos e jogos
Recreacao_e_cultura · status **ativo** · criado em base
Células por ano: 1987: 7 · 1995: 8 · 2002: 7 · 2008: 3 · 2017: 56 (padrão 11111)
- Decisão 2026-10-16_claude-v3_cynthia-folha-38#p04 REVISAR **aceita**. IA: A revisão manual aponta outlier pontual, mas o detector não o confirmou: a célula tem itens sem histórico ou de outro conceito, ou o histórico não é unânime (R1). Precisa olhar a célula inteira. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_cynthia-folha-38#p06 REVISAR **aceita**. IA: A revisão manual aponta outlier pontual, mas o detector não o confirmou: a célula tem itens sem histórico ou de outro conceito, ou o histórico não é unânime (R1). Precisa olhar a célula inteira. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_educacao-despesas-diversas#p15 MOVER **aceita** (38001 → 40006). IA: Outlier pontual: os mesmos produtos estão em 40006 em todas as outras edições em que aparecem (pelo menos 3); só em 2017 a célula está em 38001, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 40006) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_habitacao-servicos#p13 MOVER **aceita** (38001 → 32004). IA: Outlier pontual: os mesmos produtos estão em 32004 em todas as outras edições em que aparecem (pelo menos 4); só em 2017 a célula está em 38001, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 32004) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_habitacao-servicos#p25 REVISAR **aceita**. IA: Os mesmos produtos estão em 32004 nas duas outras edições em que aparecem; em 2017 estão em 38001. Duas edições contra uma, sem segunda fonte (IBGE neutro ou ausente, sem revisão manual): pela ADR 0005 não é óbvio. Recomendação da IA: mover, salvo razão de conceito. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_recreacao-cultura#p14 REVISAR **aceita**. IA: As outras edições põem os mesmos produtos em 38005, mas o tradutor do IBGE confirma o grupo atual (38001) em 2017. Fontes discordantes (CONSTITUICAO, hierarquia de evidência): decidir qual convenção vale para a série. Humano (claude-ia (ADR 0005)): —

#### 38002 — Celular e acessorios
Recreacao_e_cultura · status **ativo** · criado em base
Células por ano: 1987: 0 · 1995: 3 · 2002: 4 · 2008: 4 · 2017: 11 (padrão 01111)
- Decisão 2026-10-16_claude-v3_cynthia-folha-38#p18 MANTER **aceita**. IA: As células da ação já estão no destino proposto pela revisão manual (a planilha do Drive estava defasada). Nada a mudar. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_recreacao-cultura#p04 MOVER **aceita** (32004 → 38002). IA: Outlier pontual: os mesmos produtos estão em 38002 em todas as outras edições em que aparecem (pelo menos 3); só em 1995 a célula está em 32004, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 38002) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_recreacao-cultura#p18 REVISAR **aceita**. IA: Não há outlier: o serviço muda de grupo em todas as edições (38002, 31003, 38005, 38002). A distinção serviço × aparelho é observável nos cinco anos (R2) e é a do IBGE, então a IA recomenda: serviço e pacotes com celular em 31003 Telefonia (1995:715, 1995:1309 aluguel de telefone móvel, 1995:1697 linha telefônica móvel, 2008:28023, 2008:28024, 2017:44001, 44002, 44003, 6010, 6011, 6016); aparelhos e acessórios ficam em 38002. Como é reorganização de série (e 31003 hoje junta fixo e móvel), a decisão é humana (ADR 0005). Humano (claude-ia (ADR 0005)): —

#### 38003 — Periodicos livros e revistas
Recreacao_e_cultura · status **ativo** · criado em base
Células por ano: 1987: 6 · 1995: 6 · 2002: 6 · 2008: 22 · 2017: 24 (padrão 11111)
- Decisão 2026-10-16_claude-v3_1995-copia-de-1987#p01 MANTER **aceita**. IA: A coincidência de grupo com 1987 não é erro quando as edições seguintes confirmam. Nada a mudar. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_recreacao-cultura#p01 MOVER **aceita** (37004 → 38003). IA: Outlier pontual: os mesmos produtos estão em 38003 em todas as outras edições em que aparecem (pelo menos 2); só em 1987 a célula está em 37004, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 38003) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_recreacao-cultura#p06 MOVER **aceita** (38003 → 38004). IA: Outlier pontual: os mesmos produtos estão em 38004 em todas as outras edições em que aparecem (pelo menos 2); só em 1995 a célula está em 38003, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 38004) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_recreacao-cultura#p09 MOVER **aceita** (38003 → 38005). IA: Outlier pontual: os mesmos produtos estão em 38005 em todas as outras edições em que aparecem (pelo menos 3); só em 2017 a célula está em 38003, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 38005) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —

#### 38004 — Diversoes e esportes
Recreacao_e_cultura · status **ativo** · criado em base
Células por ano: 1987: 36 · 1995: 57 · 2002: 63 · 2008: 43 · 2017: 37 (padrão 11111)
- Decisão 2026-10-16_claude-v3_1995-copia-de-1987#p01 MANTER **aceita**. IA: A coincidência de grupo com 1987 não é erro quando as edições seguintes confirmam. Nada a mudar. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_1995-copia-de-1987#p02 REVISAR **aceita**. IA: O padrão confirma a suspeita da pendência q3. O histórico dessas células vem de palavra-chave (descrições diferem), o que não basta para mover pela ADR 0005. Recomendação da IA: revisar a lista com o questionário de 1995 aberto; os casos evidentes acima podem ir para o grupo das edições seguintes. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_cynthia-folha-32#p13 MANTER **aceita**. IA: As células da ação já estão no destino proposto pela revisão manual (a planilha do Drive estava defasada). Nada a mudar. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_cynthia-folha-38#p05 REVISAR **aceita**. IA: A revisão manual aponta outlier pontual, mas o detector não o confirmou: a célula tem itens sem histórico ou de outro conceito, ou o histórico não é unânime (R1). Precisa olhar a célula inteira. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_cynthia-folha-38#p08 REVISAR **aceita**. IA: A revisão manual move por analogia com itens parecidos, sem o mesmo produto em outras edições. Evidência de nível 5 (descrição): decisão humana. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_cynthia-folha-38#p10 REVISAR **aceita**. IA: A revisão manual aponta outlier pontual, mas o detector não o confirmou: a célula tem itens sem histórico ou de outro conceito, ou o histórico não é unânime (R1). Precisa olhar a célula inteira. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_cynthia-folha-38#p12 REVISAR **aceita**. IA: A revisão manual propõe adotar a classificação mais recente (taxonomia que amadureceu). É escolha de critério para a série, não erro: decisão humana. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_cynthia-folha-38#p13 MANTER **aceita**. IA: As células da ação já estão no destino proposto pela revisão manual (a planilha do Drive estava defasada). Nada a mudar. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_cynthia-folha-38#p14 REVISAR **aceita**. IA: A revisão manual aponta outlier pontual, mas o detector não o confirmou: a célula tem itens sem histórico ou de outro conceito, ou o histórico não é unânime (R1). Precisa olhar a célula inteira. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_cynthia-folha-38#p16 MANTER **aceita**. IA: As células da ação já estão no destino proposto pela revisão manual (a planilha do Drive estava defasada). Nada a mudar. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_cynthia-folha-38#p19 MANTER **aceita**. IA: As células da ação já estão no destino proposto pela revisão manual (a planilha do Drive estava defasada). Nada a mudar. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_educacao-despesas-diversas#p05 MOVER **aceita** (38004 → 37005). IA: Outlier pontual: os mesmos produtos estão em 37005 em todas as outras edições em que aparecem (pelo menos 3); só em 1987 a célula está em 38004, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 37005) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_pendencias-validacao-e-criar#p10 MANTER **aceita**. IA: A mudança da planilha v2026 para a base (lá 37005, hoje 38004) é a classificação que as outras edições usam para os mesmos produtos (6 de 6 ocorrências): correção legítima. Nada a mudar. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_pendencias-validacao-e-criar#p18 MANTER **aceita**. IA: A mudança da planilha v2026 para a base (lá 38003, hoje 38004) é a classificação que as outras edições usam para os mesmos produtos (4 de 5 ocorrências): correção legítima. Nada a mudar. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_recreacao-cultura#p02 MOVER **aceita** (38005 → 38004). IA: Outlier pontual: os mesmos produtos estão em 38004 em todas as outras edições em que aparecem (pelo menos 2); só em 1987 a célula está em 38005, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 38004) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_recreacao-cultura#p03 MOVER **aceita** (40006 → 38004). IA: Outlier pontual: os mesmos produtos estão em 38004 em todas as outras edições em que aparecem (pelo menos 2); só em 1987 a célula está em 40006, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 38004) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_recreacao-cultura#p05 MOVER **aceita** (37004 → 38004). IA: Outlier pontual: os mesmos produtos estão em 38004 em todas as outras edições em que aparecem (pelo menos 2); só em 1995 a célula está em 37004, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 38004) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_recreacao-cultura#p06 MOVER **aceita** (38003 → 38004). IA: Outlier pontual: os mesmos produtos estão em 38004 em todas as outras edições em que aparecem (pelo menos 2); só em 1995 a célula está em 38003, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 38004) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_recreacao-cultura#p10 MOVER **aceita** (38005 → 38004). IA: Outlier pontual: os mesmos produtos estão em 38004 em todas as outras edições em que aparecem (pelo menos 3); só em 2017 a célula está em 38005, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 38004) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_recreacao-cultura#p11 MOVER **aceita** (40003 → 38004). IA: Outlier pontual: os mesmos produtos estão em 38004 em todas as outras edições em que aparecem (pelo menos 2); só em 2017 a célula está em 40003, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 38004) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —

#### 38005 — Outras recreacao etc
Recreacao_e_cultura · status **ativo** · criado em base
Células por ano: 1987: 29 · 1995: 27 · 2002: 42 · 2008: 89 · 2017: 71 (padrão 11111)
- Decisão 2026-10-16_claude-v3_2017-quadros-deslocados#p01 MOVER **aceita** (38005 → 32004). IA: Utensílio doméstico em recreação só em 2017, no bloco do quadro 16 que a aba de 2017 deslocou. Outras edições e IBGE concordam no grupo: duas fontes ⇒ ALTA (ADR 0005). Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_2017-quadros-deslocados#p02 MOVER **aceita** (38005 → 32003). IA: Mesmo padrão do quadro 16 de 2017; outras edições e IBGE concordam em 32003. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_2017-quadros-deslocados#p05 REVISAR **aceita**. IA: Estão fora do lugar (recreação), mas o destino fino não é unânime nas outras edições. Recomendação da IA: seguir a linha do IBGE 2017 (32003 Mobiliário para quase todos; COFRE em 40006, como 2002/2008 e o IBGE, apesar da revisão manual). Decisão humana porque o subgrupo de destino varia. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_cynthia-folha-32#p14 REVISAR **aceita**. IA: A revisão manual aponta outlier pontual, mas o detector não o confirmou: a célula tem itens sem histórico ou de outro conceito, ou o histórico não é unânime (R1). Precisa olhar a célula inteira. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_cynthia-folha-38#p01 REVISAR **aceita**. IA: A revisão manual aponta outlier pontual, mas o detector não o confirmou: a célula tem itens sem histórico ou de outro conceito, ou o histórico não é unânime (R1). Precisa olhar a célula inteira. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_cynthia-folha-38#p02 REVISAR **aceita**. IA: A revisão manual aponta outlier pontual, mas o detector não o confirmou: a célula tem itens sem histórico ou de outro conceito, ou o histórico não é unânime (R1). Precisa olhar a célula inteira. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_cynthia-folha-38#p03 REVISAR **aceita**. IA: A revisão manual aponta outlier pontual, mas o detector não o confirmou: a célula tem itens sem histórico ou de outro conceito, ou o histórico não é unânime (R1). Precisa olhar a célula inteira. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_cynthia-folha-38#p05 REVISAR **aceita**. IA: A revisão manual aponta outlier pontual, mas o detector não o confirmou: a célula tem itens sem histórico ou de outro conceito, ou o histórico não é unânime (R1). Precisa olhar a célula inteira. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_cynthia-folha-38#p09 REVISAR **aceita**. IA: A revisão manual propõe adotar a classificação mais recente (taxonomia que amadureceu). É escolha de critério para a série, não erro: decisão humana. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_cynthia-folha-38#p11 REVISAR **aceita**. IA: A revisão manual aponta outlier pontual, mas o detector não o confirmou: a célula tem itens sem histórico ou de outro conceito, ou o histórico não é unânime (R1). Precisa olhar a célula inteira. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_cynthia-folha-38#p20 REVISAR **aceita**. IA: A revisão manual aponta outlier pontual, mas o detector não o confirmou: a célula tem itens sem histórico ou de outro conceito, ou o histórico não é unânime (R1). Precisa olhar a célula inteira. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_educacao-despesas-diversas#p25 REVISAR **aceita**. IA: Os mesmos produtos estão em 37005 nas duas outras edições em que aparecem; em 2017 estão em 38005. Duas edições contra uma, sem segunda fonte (IBGE neutro ou ausente, sem revisão manual): pela ADR 0005 não é óbvio. Recomendação da IA: mover, salvo razão de conceito. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_habitacao-servicos#p14 MOVER **aceita** (38005 → 32003). IA: Outlier pontual: os mesmos produtos estão em 32003 em todas as outras edições em que aparecem (pelo menos 2); só em 2017 a célula está em 38005, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 32003) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_habitacao-servicos#p15 MOVER **aceita** (38005 → 32004). IA: Outlier pontual: os mesmos produtos estão em 32004 em todas as outras edições em que aparecem (pelo menos 4); só em 2017 a célula está em 38005, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 32004) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_pendencias-validacao-e-criar#p09 REVISAR **aceita**. IA: As outras edições não confirmam com clareza nem o grupo atual nem o da planilha antiga. Recomendação da IA: 38005 Outras recreacao etc, o grupo mais frequente nas outras edições. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_recreacao-cultura#p02 MOVER **aceita** (38005 → 38004). IA: Outlier pontual: os mesmos produtos estão em 38004 em todas as outras edições em que aparecem (pelo menos 2); só em 1987 a célula está em 38005, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 38004) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_recreacao-cultura#p08 MOVER **aceita** (32003 → 38005). IA: Outlier pontual: os mesmos produtos estão em 38005 em todas as outras edições em que aparecem (pelo menos 2); só em 2017 a célula está em 32003, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 38005) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_recreacao-cultura#p09 MOVER **aceita** (38003 → 38005). IA: Outlier pontual: os mesmos produtos estão em 38005 em todas as outras edições em que aparecem (pelo menos 3); só em 2017 a célula está em 38003, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 38005) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_recreacao-cultura#p10 MOVER **aceita** (38005 → 38004). IA: Outlier pontual: os mesmos produtos estão em 38004 em todas as outras edições em que aparecem (pelo menos 3); só em 2017 a célula está em 38005, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 38004) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_recreacao-cultura#p12 REVISAR **aceita**. IA: Os mesmos produtos estão em 38004 nas duas outras edições em que aparecem; em 2017 estão em 38005. Duas edições contra uma, sem segunda fonte (IBGE neutro ou ausente, sem revisão manual): pela ADR 0005 não é óbvio. Recomendação da IA: mover, salvo razão de conceito. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_recreacao-cultura#p15 REVISAR **aceita**. IA: As outras edições põem os mesmos produtos em 38001, mas o tradutor do IBGE confirma o grupo atual (38005) em 2008. Fontes discordantes (CONSTITUICAO, hierarquia de evidência): decidir qual convenção vale para a série. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_recreacao-cultura#p16 REVISAR **aceita**. IA: As outras edições põem os mesmos produtos em 38004, mas o tradutor do IBGE confirma o grupo atual (38005) em 2008. Fontes discordantes (CONSTITUICAO, hierarquia de evidência): decidir qual convenção vale para a série. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_recreacao-cultura#p18 REVISAR **aceita**. IA: Não há outlier: o serviço muda de grupo em todas as edições (38002, 31003, 38005, 38002). A distinção serviço × aparelho é observável nos cinco anos (R2) e é a do IBGE, então a IA recomenda: serviço e pacotes com celular em 31003 Telefonia (1995:715, 1995:1309 aluguel de telefone móvel, 1995:1697 linha telefônica móvel, 2008:28023, 2008:28024, 2017:44001, 44002, 44003, 6010, 6011, 6016); aparelhos e acessórios ficam em 38002. Como é reorganização de série (e 31003 hoje junta fixo e móvel), a decisão é humana (ADR 0005). Humano (claude-ia (ADR 0005)): —

#### 38006 — Gastos com viagens
Recreacao_e_cultura · status **ativo** · criado em base
Células por ano: 1987: 21 · 1995: 26 · 2002: 31 · 2008: 41 · 2017: 72 (padrão 11111)
- Decisão 2026-10-16_claude-v3_cynthia-folha-38#p02 REVISAR **aceita**. IA: A revisão manual aponta outlier pontual, mas o detector não o confirmou: a célula tem itens sem histórico ou de outro conceito, ou o histórico não é unânime (R1). Precisa olhar a célula inteira. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_cynthia-folha-38#p06 REVISAR **aceita**. IA: A revisão manual aponta outlier pontual, mas o detector não o confirmou: a célula tem itens sem histórico ou de outro conceito, ou o histórico não é unânime (R1). Precisa olhar a célula inteira. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_pendencias-validacao-e-criar#p04 REVISAR **aceita**. IA: As outras edições não confirmam com clareza nem o grupo atual nem o da planilha antiga. Recomendação da IA: 32004 Eletrodomesticos, o grupo mais frequente nas outras edições. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_recreacao-cultura#p07 MOVER **aceita** (16104 → 38006). IA: Outlier pontual: os mesmos produtos estão em 38006 em todas as outras edições em que aparecem (pelo menos 4); só em 2002 a célula está em 16104, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 38006) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_vestuario-transporte-higiene-saude#p27 REVISAR **aceita**. IA: Os mesmos produtos estão em 34007 nas duas outras edições em que aparecem; em 2002 estão em 38006. Duas edições contra uma, sem segunda fonte (IBGE neutro ou ausente, sem revisão manual): pela ADR 0005 não é óbvio. Recomendação da IA: mover, salvo razão de conceito. Humano (claude-ia (ADR 0005)): —

### 39. Servicos_pessoais

#### 39001 — Fumo
Servicos_pessoais · status **ativo** · criado em base
Células por ano: 1987: 20 · 1995: 22 · 2002: 22 · 2008: 23 · 2017: 26 (padrão 11111)
- Decisão 2026-10-16_claude-v3_1995-copia-de-1987#p02 REVISAR **aceita**. IA: O padrão confirma a suspeita da pendência q3. O histórico dessas células vem de palavra-chave (descrições diferem), o que não basta para mover pela ADR 0005. Recomendação da IA: revisar a lista com o questionário de 1995 aberto; os casos evidentes acima podem ir para o grupo das edições seguintes. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_educacao-despesas-diversas#p30 REVISAR **aceita**. IA: As outras edições põem os mesmos produtos em 40006, mas o tradutor do IBGE confirma o grupo atual (39001) em 2008. Fontes discordantes (CONSTITUICAO, hierarquia de evidência): decidir qual convenção vale para a série. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_vestuario-transporte-higiene-saude#p07 MOVER **aceita** (32003 → 39001). IA: Outlier pontual: os mesmos produtos estão em 39001 em todas as outras edições em que aparecem (pelo menos 4); só em 2002 a célula está em 32003, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 39001) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —

#### 39002 — Cabeleireiro
Servicos_pessoais · status **ativo** · criado em base
Células por ano: 1987: 3 · 1995: 3 · 2002: 5 · 2008: 5 · 2017: 2 (padrão 11111)

#### 39003 — Manicuro e pedicuro
Servicos_pessoais · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 1 · 2017: 3 (padrão 11111)
- Decisão 2026-10-16_claude-v3_vestuario-transporte-higiene-saude#p28 REVISAR **aceita**. IA: Os mesmos produtos estão em 39002 nas duas outras edições em que aparecem; em 2017 estão em 39003. Duas edições contra uma, sem segunda fonte (IBGE neutro ou ausente, sem revisão manual): pela ADR 0005 não é óbvio. Recomendação da IA: mover, salvo razão de conceito. Humano (claude-ia (ADR 0005)): —

#### 39004 — Consertos de artigos pessoais
Servicos_pessoais · status **ativo** · criado em base
Células por ano: 1987: 13 · 1995: 19 · 2002: 21 · 2008: 22 · 2017: 13 (padrão 11111)
- Decisão 2026-10-16_claude-v3_vestuario-transporte-higiene-saude#p18 MOVER **aceita** (39004 → 39005). IA: Outlier pontual: os mesmos produtos estão em 39005 em todas as outras edições em que aparecem (pelo menos 2); só em 2017 a célula está em 39004, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 39005) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —

#### 39005 — Outras servicos pessoais
Servicos_pessoais · status **ativo** · criado em base
Células por ano: 1987: 11 · 1995: 19 · 2002: 24 · 2008: 25 · 2017: 28 (padrão 11111)
- Decisão 2026-10-16_claude-v3_1995-copia-de-1987#p01 MANTER **aceita**. IA: A coincidência de grupo com 1987 não é erro quando as edições seguintes confirmam. Nada a mudar. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_educacao-despesas-diversas#p16 MOVER **aceita** (39005 → 40006). IA: Outlier pontual: os mesmos produtos estão em 40006 em todas as outras edições em que aparecem (pelo menos 3); só em 2017 a célula está em 39005, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 40006) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_vestuario-transporte-higiene-saude#p18 MOVER **aceita** (39004 → 39005). IA: Outlier pontual: os mesmos produtos estão em 39005 em todas as outras edições em que aparecem (pelo menos 2); só em 2017 a célula está em 39004, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 39005) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —

### 40. Despesas_diversas

#### 40001 — Jogos e apostas
Despesas_diversas · status **ativo** · criado em base
Células por ano: 1987: 12 · 1995: 17 · 2002: 22 · 2008: 25 · 2017: 33 (padrão 11111)

#### 40002 — Comunicacao
Despesas_diversas · status **ativo** · criado em base
Células por ano: 1987: 4 · 1995: 1 · 2002: 6 · 2008: 6 · 2017: 8 (padrão 11111)
- Decisão 2026-10-16_claude-v3_educacao-despesas-diversas#p07 MOVER **aceita** (31007 → 40002). IA: Outlier pontual: os mesmos produtos estão em 40002 em todas as outras edições em que aparecem (pelo menos 3); só em 1995 a célula está em 31007, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 40002) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —

#### 40003 — Cerimonias e festas
Despesas_diversas · status **ativo** · criado em base
Células por ano: 1987: 12 · 1995: 12 · 2002: 17 · 2008: 17 · 2017: 28 (padrão 11111)
- Decisão 2026-10-16_claude-v3_1995-copia-de-1987#p01 MANTER **aceita**. IA: A coincidência de grupo com 1987 não é erro quando as edições seguintes confirmam. Nada a mudar. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_educacao-despesas-diversas#p31 REVISAR **aceita**. IA: As outras edições põem os mesmos produtos em 40004, mas o tradutor do IBGE confirma o grupo atual (40003) em 2008. Fontes discordantes (CONSTITUICAO, hierarquia de evidência): decidir qual convenção vale para a série. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_habitacao-servicos#p37 REVISAR **aceita**. IA: Série partida em dois critérios. Não é deslize de um ano: é decisão de onde fica gasto com jazigo (investimento em imóvel ou cerimônia/serviço funerário). Recomendação da IA: 40003 nos cinco anos, porque é taxa recorrente, não reforma; mas é escolha de conceito. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_recreacao-cultura#p11 MOVER **aceita** (40003 → 38004). IA: Outlier pontual: os mesmos produtos estão em 38004 em todas as outras edições em que aparecem (pelo menos 2); só em 2017 a célula está em 40003, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 38004) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —

#### 40004 — Servicos profissionais
Despesas_diversas · status **ativo** · criado em base
Células por ano: 1987: 15 · 1995: 20 · 2002: 20 · 2008: 20 · 2017: 7 (padrão 11111)
- Decisão 2026-10-16_claude-v3_1995-copia-de-1987#p01 MANTER **aceita**. IA: A coincidência de grupo com 1987 não é erro quando as edições seguintes confirmam. Nada a mudar. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_educacao-despesas-diversas#p06 MOVER **aceita** (40006 → 40004). IA: Outlier pontual: os mesmos produtos estão em 40004 em todas as outras edições em que aparecem (pelo menos 3); só em 1987 a célula está em 40006, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 40004) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_educacao-despesas-diversas#p17 MOVER **aceita** (40006 → 40004). IA: Outlier pontual: os mesmos produtos estão em 40004 em todas as outras edições em que aparecem (pelo menos 4); só em 2017 a célula está em 40006, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 40004) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —

#### 40005 — Imoveis de uso ocasional
Despesas_diversas · status **ativo** · criado em base
Células por ano: 1987: 16 · 1995: 18 · 2002: 15 · 2008: 19 · 2017: 26 (padrão 11111)
- Decisão 2026-10-16_claude-v3_2017-quadros-deslocados#p08 REVISAR **aceita**. IA: Aluguel não é aquisição (deslocamento típico de 2017). Recomendação da IA: aluguel e garagem para 40005; impostos de outros imóveis para 41001 (como o IPTU do domicílio); clube conforme o IBGE. Só 2008 tem par, por isso fica para decisão humana. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_nao-consumo#p21 REVISAR **aceita**. IA: Os mesmos nomes de produto estão em 42002 nas outras edições, mas a célula está em 40005, de outro domínio (consumo, outras despesas, rendimentos ou inventário). Mesmo nome não garante mesma despesa (ex.: item de inventário de bens duráveis × compra; 'empregado' como rendimento × serviço doméstico). Sem confirmação do IBGE, a decisão é humana. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_nao-consumo#p26 REVISAR **aceita**. IA: Comprar imóvel é investimento (aumento do ativo), não consumo; o próprio repositório trata assim a compra do domicílio principal. Para outros imóveis o critério é consistente nas quatro edições, então não é deslize de um ano: é uma decisão de taxonomia (40005 'uso ocasional' incluiria a compra de casa de veraneio?). Recomendação da IA: 42001 para todas as células listadas, como o domicílio principal e o IBGE; manter em 40005 só aluguel, condomínio, IPTU e contas de outros imóveis. Humano (claude-ia (ADR 0005)): —

#### 40006 — Outras despesas diversas
Despesas_diversas · status **ativo** · criado em base
Células por ano: 1987: 65 · 1995: 63 · 2002: 61 · 2008: 79 · 2017: 67 (padrão 11111)
- Decisão 2026-10-16_claude-v3_1995-copia-de-1987#p01 MANTER **aceita**. IA: A coincidência de grupo com 1987 não é erro quando as edições seguintes confirmam. Nada a mudar. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_1995-copia-de-1987#p02 REVISAR **aceita**. IA: O padrão confirma a suspeita da pendência q3. O histórico dessas células vem de palavra-chave (descrições diferem), o que não basta para mover pela ADR 0005. Recomendação da IA: revisar a lista com o questionário de 1995 aberto; os casos evidentes acima podem ir para o grupo das edições seguintes. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_2017-quadros-deslocados#p05 REVISAR **aceita**. IA: Estão fora do lugar (recreação), mas o destino fino não é unânime nas outras edições. Recomendação da IA: seguir a linha do IBGE 2017 (32003 Mobiliário para quase todos; COFRE em 40006, como 2002/2008 e o IBGE, apesar da revisão manual). Decisão humana porque o subgrupo de destino varia. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_2017-quadros-deslocados#p06 REVISAR **aceita**. IA: Em 2017 o quadro 37 ganhou itens novos e linhas trocadas; sem par nas outras edições, o destino depende de critério (tecido para o lar é armarinho ou artigo do lar? artesanato é recreação?). Recomendação da IA: tecidos, couro e entretela em 33006 (IBGE); artesanato junto, em 38005, como o IBGE. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_cynthia-folha-32#p15 REVISAR **aceita**. IA: A revisão manual propõe adotar a classificação mais recente (taxonomia que amadureceu). É escolha de critério para a série, não erro: decisão humana. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_cynthia-folha-400006#p01 REVISAR **aceita**. IA: Ação da revisão manual sem tipo identificado; decisão humana. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_cynthia-folha-400006#p02 REVISAR **aceita**. IA: A revisão manual aponta outlier pontual, mas o detector não o confirmou: a célula tem itens sem histórico ou de outro conceito, ou o histórico não é unânime (R1). Precisa olhar a célula inteira. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_cynthia-folha-400006#p03 REVISAR **aceita**. IA: A revisão manual propõe adotar a classificação mais recente (taxonomia que amadureceu). É escolha de critério para a série, não erro: decisão humana. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_cynthia-folha-400006#p04 REVISAR **aceita**. IA: A revisão manual aponta outlier pontual, mas o detector não o confirmou: a célula tem itens sem histórico ou de outro conceito, ou o histórico não é unânime (R1). Precisa olhar a célula inteira. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_cynthia-folha-400006#p05 REVISAR **aceita**. IA: A revisão manual move por analogia com itens parecidos, sem o mesmo produto em outras edições. Evidência de nível 5 (descrição): decisão humana. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_cynthia-folha-400006#p06 REVISAR **aceita**. IA: A revisão manual move por analogia com itens parecidos, sem o mesmo produto em outras edições. Evidência de nível 5 (descrição): decisão humana. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_cynthia-folha-400006#p07 REVISAR **aceita**. IA: A revisão manual aponta outlier pontual, mas o detector não o confirmou: a célula tem itens sem histórico ou de outro conceito, ou o histórico não é unânime (R1). Precisa olhar a célula inteira. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_cynthia-folha-400006#p08 REVISAR **aceita**. IA: A revisão manual aponta outlier pontual, mas o detector não o confirmou: a célula tem itens sem histórico ou de outro conceito, ou o histórico não é unânime (R1). Precisa olhar a célula inteira. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_cynthia-folha-400006#p11 REVISAR **aceita**. IA: A revisão manual move por analogia com itens parecidos, sem o mesmo produto em outras edições. Evidência de nível 5 (descrição): decisão humana. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_cynthia-folha-400006#p12 REVISAR **aceita**. IA: A revisão manual propõe adotar a classificação mais recente (taxonomia que amadureceu). É escolha de critério para a série, não erro: decisão humana. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_cynthia-folha-400006#p13 REVISAR **aceita**. IA: A revisão manual propõe adotar a classificação mais recente (taxonomia que amadureceu). É escolha de critério para a série, não erro: decisão humana. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_cynthia-folha-400006#p14 REVISAR **aceita**. IA: Ação da revisão manual sem tipo identificado; decisão humana. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_cynthia-folha-400006#p15 REVISAR **aceita**. IA: Ação da revisão manual sem tipo identificado; decisão humana. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_cynthia-folha-400006#p16 REVISAR **aceita**. IA: A revisão manual move por analogia com itens parecidos, sem o mesmo produto em outras edições. Evidência de nível 5 (descrição): decisão humana. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_cynthia-folha-400006#p17 REVISAR **aceita**. IA: A revisão manual propõe adotar a classificação mais recente (taxonomia que amadureceu). É escolha de critério para a série, não erro: decisão humana. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_cynthia-folha-400006#p18 REVISAR **aceita**. IA: A revisão manual propõe adotar a classificação mais recente (taxonomia que amadureceu). É escolha de critério para a série, não erro: decisão humana. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_cynthia-folha-400006#p19 REVISAR **aceita**. IA: Ação da revisão manual sem tipo identificado; decisão humana. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_cynthia-folha-400006#p20 REVISAR **aceita**. IA: Ação da revisão manual sem tipo identificado; decisão humana. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_cynthia-folha-400006#p21 REVISAR **aceita**. IA: Ação da revisão manual sem tipo identificado; decisão humana. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_cynthia-folha-400006#p22 REVISAR **aceita**. IA: Ação da revisão manual sem tipo identificado; decisão humana. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_educacao-despesas-diversas#p06 MOVER **aceita** (40006 → 40004). IA: Outlier pontual: os mesmos produtos estão em 40004 em todas as outras edições em que aparecem (pelo menos 3); só em 1987 a célula está em 40006, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 40004) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_educacao-despesas-diversas#p10 MOVER **aceita** (32003 → 40006). IA: Outlier pontual: os mesmos produtos estão em 40006 em todas as outras edições em que aparecem (pelo menos 2); só em 2017 a célula está em 32003, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 40006) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_educacao-despesas-diversas#p11 MOVER **aceita** (33004 → 40006). IA: Outlier pontual: os mesmos produtos estão em 40006 em todas as outras edições em que aparecem (pelo menos 4); só em 2017 a célula está em 33004, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 40006) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_educacao-despesas-diversas#p12 MOVER **aceita** (35004 → 40006). IA: Outlier pontual: os mesmos produtos estão em 40006 em todas as outras edições em que aparecem (pelo menos 4); só em 2017 a célula está em 35004, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 40006) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_educacao-despesas-diversas#p13 MOVER **aceita** (37005 → 40006). IA: Outlier pontual: os mesmos produtos estão em 40006 em todas as outras edições em que aparecem (pelo menos 2); só em 2017 a célula está em 37005, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 40006) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_educacao-despesas-diversas#p15 MOVER **aceita** (38001 → 40006). IA: Outlier pontual: os mesmos produtos estão em 40006 em todas as outras edições em que aparecem (pelo menos 3); só em 2017 a célula está em 38001, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 40006) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_educacao-despesas-diversas#p16 MOVER **aceita** (39005 → 40006). IA: Outlier pontual: os mesmos produtos estão em 40006 em todas as outras edições em que aparecem (pelo menos 3); só em 2017 a célula está em 39005, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 40006) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_educacao-despesas-diversas#p17 MOVER **aceita** (40006 → 40004). IA: Outlier pontual: os mesmos produtos estão em 40004 em todas as outras edições em que aparecem (pelo menos 4); só em 2017 a célula está em 40006, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 40004) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_educacao-despesas-diversas#p18 MOVER **aceita** (42002 → 40006). IA: Outlier pontual: os mesmos produtos estão em 40006 em todas as outras edições em que aparecem (pelo menos 2); só em 2017 a célula está em 42002, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 40006) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_educacao-despesas-diversas#p32 REVISAR **aceita**. IA: As outras edições põem os mesmos produtos em 37006, mas o tradutor do IBGE confirma o grupo atual (40006) em 2017. Fontes discordantes (CONSTITUICAO, hierarquia de evidência): decidir qual convenção vale para a série. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_habitacao-servicos#p02 MOVER **aceita** (40006 → 32003). IA: Outlier pontual: os mesmos produtos estão em 32003 em todas as outras edições em que aparecem (pelo menos 4); só em 1987 a célula está em 40006, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 32003) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_habitacao-servicos#p16 MOVER **aceita** (40006 → 32003). IA: Outlier pontual: os mesmos produtos estão em 32003 em todas as outras edições em que aparecem (pelo menos 4); só em 2017 a célula está em 40006, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 32003) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_habitacao-servicos#p17 MOVER **aceita** (40006 → 32004). IA: Outlier pontual: os mesmos produtos estão em 32004 em todas as outras edições em que aparecem (pelo menos 4); só em 2017 a célula está em 40006, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 32004) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_habitacao-servicos#p26 REVISAR **aceita**. IA: Os mesmos produtos estão em 31007 nas duas outras edições em que aparecem; em 2002 estão em 40006. Duas edições contra uma, sem segunda fonte (IBGE neutro ou ausente, sem revisão manual): pela ADR 0005 não é óbvio. Recomendação da IA: mover, salvo razão de conceito. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_habitacao-servicos#p34 MOVER **aceita** (40006;41006 → 31007). IA: Quebra de série: o mesmo gasto (condomínio do domicílio principal) está em três grupos diferentes ao longo das edições, e em 2008/2017 cai fora do consumo. Estrutura dos códigos (célula do domicílio principal, mesmo quadro de aluguel e taxas), anos 1995/2002 e o tradutor do IBGE convergem: 31007. Duas fontes independentes ⇒ ALTA (ADR 0005). Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_habitacao-servicos#p36 MOVER **aceita** (31007;40006;41006 → 31001). IA: Mesma despesa espalhada por três grupos; 2002/2008 e o IBGE concordam em Aluguel. Duas fontes ⇒ ALTA. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_nao-consumo#p09 MOVER **aceita** (40006 → 41006). IA: Outlier pontual: os mesmos produtos estão em 41006 em todas as outras edições em que aparecem (pelo menos 4); só em 2017 a célula está em 40006, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 41006) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_recreacao-cultura#p03 MOVER **aceita** (40006 → 38004). IA: Outlier pontual: os mesmos produtos estão em 38004 em todas as outras edições em que aparecem (pelo menos 2); só em 1987 a célula está em 40006, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 38004) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_recreacao-cultura#p17 REVISAR **aceita**. IA: As outras edições põem os mesmos produtos em 38005, mas o tradutor do IBGE confirma o grupo atual (40006) em 2017. Fontes discordantes (CONSTITUICAO, hierarquia de evidência): decidir qual convenção vale para a série. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_recreacao-cultura#p18 REVISAR **aceita**. IA: Não há outlier: o serviço muda de grupo em todas as edições (38002, 31003, 38005, 38002). A distinção serviço × aparelho é observável nos cinco anos (R2) e é a do IBGE, então a IA recomenda: serviço e pacotes com celular em 31003 Telefonia (1995:715, 1995:1309 aluguel de telefone móvel, 1995:1697 linha telefônica móvel, 2008:28023, 2008:28024, 2017:44001, 44002, 44003, 6010, 6011, 6016); aparelhos e acessórios ficam em 38002. Como é reorganização de série (e 31003 hoje junta fixo e móvel), a decisão é humana (ADR 0005). Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_vestuario-transporte-higiene-saude#p03 MOVER **aceita** (40006 → 33006). IA: Outlier pontual: os mesmos produtos estão em 33006 em todas as outras edições em que aparecem (pelo menos 3); só em 1987 a célula está em 40006, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 33006) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_vestuario-transporte-higiene-saude#p29 REVISAR **aceita**. IA: Os mesmos produtos estão em 33004 nas duas outras edições em que aparecem; em 1987 estão em 40006. Duas edições contra uma, sem segunda fonte (IBGE neutro ou ausente, sem revisão manual): pela ADR 0005 não é óbvio. Recomendação da IA: mover, salvo razão de conceito. Humano (claude-ia (ADR 0005)): —

### 41. Outras_despesas_correntes

#### 41001 — Impostos
Outras_despesas_correntes · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 41 · 2002: 17 · 2008: 76 · 2017: 18 (padrão 11111)
- Decisão 2026-10-16_claude-v3_habitacao-servicos#p35 MOVER **aceita** (31007;32001 → 41001). IA: Três edições unânimes e o IBGE concordam: imposto é outra despesa corrente, não manutenção do lar nem serviço. Os dois anos antigos estão cada um num grupo diferente, sinal de deslize e não de critério. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_nao-consumo#p08 MOVER **aceita** (34007 → 41001). IA: Outlier pontual: os mesmos produtos estão em 41001 em todas as outras edições em que aparecem (pelo menos 2); só em 2017 a célula está em 34007, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 41001) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_nao-consumo#p22 REVISAR **aceita**. IA: Os mesmos nomes de produto estão em 46001 nas outras edições, mas a célula está em 41001, de outro domínio (consumo, outras despesas, rendimentos ou inventário). Mesmo nome não garante mesma despesa (ex.: item de inventário de bens duráveis × compra; 'empregado' como rendimento × serviço doméstico). Sem confirmação do IBGE, a decisão é humana. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_nao-consumo#p23 REVISAR **aceita**. IA: Os mesmos nomes de produto estão em 47003 nas outras edições, mas a célula está em 41001, de outro domínio (consumo, outras despesas, rendimentos ou inventário). Mesmo nome não garante mesma despesa (ex.: item de inventário de bens duráveis × compra; 'empregado' como rendimento × serviço doméstico). Sem confirmação do IBGE, a decisão é humana. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_vestuario-transporte-higiene-saude#p19 MOVER **aceita** (41001 → 34005). IA: Outlier pontual: os mesmos produtos estão em 34005 em todas as outras edições em que aparecem (pelo menos 3); só em 2017 a célula está em 41001, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 34005) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_vestuario-transporte-higiene-saude#p20 MOVER **aceita** (41001 → 34007). IA: Outlier pontual: os mesmos produtos estão em 34007 em todas as outras edições em que aparecem (pelo menos 3); só em 2017 a célula está em 41001, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 34007) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_vestuario-transporte-higiene-saude#p37 MOVER **aceita** (41001 → 34007). IA: Em 2017 o seguro obrigatório sai do consumo sem mudança de conceito na POF; as duas edições anteriores e o IBGE de 2017 concordam em Transporte/Outras. Duas fontes ⇒ ALTA (ADR 0005). Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_vestuario-transporte-higiene-saude#p39 REVISAR **aceita**. IA: O agregado reúne itens do quadro sem detalhamento (seguro, documentação, taxas). O IBGE o põe em Transporte nas duas edições. Fontes discordantes (repositório consistente × IBGE): decisão humana; recomendação da IA: 34007, como o IBGE. Humano (claude-ia (ADR 0005)): —

#### 41002 — Contribuicoes trabalhistas
Outras_despesas_correntes · status **ativo** · criado em base
Células por ano: 1987: 3 · 1995: 51 · 2002: 4 · 2008: 44 · 2017: 3 (padrão 11111)
- Decisão 2026-10-16_claude-v3_nao-consumo#p10 MOVER **aceita** (41006 → 41002). IA: Outlier pontual: os mesmos produtos estão em 41002 em todas as outras edições em que aparecem (pelo menos 4); só em 2017 a célula está em 41006, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 41002) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —

#### 41003 — Servicos bancarios
Outras_despesas_correntes · status **ativo** · criado em base
Células por ano: 1987: 4 · 1995: 10 · 2002: 12 · 2008: 17 · 2017: 16 (padrão 11111)

#### 41004 — Pensoes mesadas e doacoes
Outras_despesas_correntes · status **ativo** · criado em base
Células por ano: 1987: 7 · 1995: 11 · 2002: 10 · 2008: 11 · 2017: 9 (padrão 11111)
- Decisão 2026-10-16_claude-v3_nao-consumo#p11 MOVER **aceita** (41006 → 41004). IA: Outlier pontual: os mesmos produtos estão em 41004 em todas as outras edições em que aparecem (pelo menos 2); só em 2017 a célula está em 41006, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 41004) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —

#### 41005 — Previdencia privada
Outras_despesas_correntes · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 3 · 2008: 1 · 2017: 1 (padrão 11111)

#### 41006 — Outras despesas
Outras_despesas_correntes · status **ativo** · criado em base
Células por ano: 1987: 9 · 1995: 13 · 2002: 22 · 2008: 82 · 2017: 19 (padrão 11111)
- Decisão 2026-10-16_claude-v3_educacao-despesas-diversas#p26 REVISAR **aceita**. IA: Os mesmos nomes de produto estão em 40006 nas outras edições, mas a célula está em 41006, de outro domínio (consumo, outras despesas, rendimentos ou inventário). Mesmo nome não garante mesma despesa (ex.: item de inventário de bens duráveis × compra; 'empregado' como rendimento × serviço doméstico). Sem confirmação do IBGE, a decisão é humana. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_habitacao-servicos#p34 MOVER **aceita** (40006;41006 → 31007). IA: Quebra de série: o mesmo gasto (condomínio do domicílio principal) está em três grupos diferentes ao longo das edições, e em 2008/2017 cai fora do consumo. Estrutura dos códigos (célula do domicílio principal, mesmo quadro de aluguel e taxas), anos 1995/2002 e o tradutor do IBGE convergem: 31007. Duas fontes independentes ⇒ ALTA (ADR 0005). Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_habitacao-servicos#p36 MOVER **aceita** (31007;40006;41006 → 31001). IA: Mesma despesa espalhada por três grupos; 2002/2008 e o IBGE concordam em Aluguel. Duas fontes ⇒ ALTA. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_nao-consumo#p09 MOVER **aceita** (40006 → 41006). IA: Outlier pontual: os mesmos produtos estão em 41006 em todas as outras edições em que aparecem (pelo menos 4); só em 2017 a célula está em 40006, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 41006) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_nao-consumo#p10 MOVER **aceita** (41006 → 41002). IA: Outlier pontual: os mesmos produtos estão em 41002 em todas as outras edições em que aparecem (pelo menos 4); só em 2017 a célula está em 41006, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 41002) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_nao-consumo#p11 MOVER **aceita** (41006 → 41004). IA: Outlier pontual: os mesmos produtos estão em 41004 em todas as outras edições em que aparecem (pelo menos 2); só em 2017 a célula está em 41006, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 41004) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_nao-consumo#p12 MOVER **aceita** (41006 → 42003). IA: Outlier pontual: os mesmos produtos estão em 42003 em todas as outras edições em que aparecem (pelo menos 3); só em 2017 a célula está em 41006, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 42003) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_nao-consumo#p13 MOVER **aceita** (41006 → 43001). IA: Outlier pontual: os mesmos produtos estão em 43001 em todas as outras edições em que aparecem (pelo menos 4); só em 2017 a célula está em 41006, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 43001) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_nao-consumo#p24 REVISAR **aceita**. IA: As outras edições põem os mesmos produtos em 41004, mas o tradutor do IBGE confirma o grupo atual (41006) em 2017. Fontes discordantes (CONSTITUICAO, hierarquia de evidência): decidir qual convenção vale para a série. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_nao-consumo#p26 REVISAR **aceita**. IA: Comprar imóvel é investimento (aumento do ativo), não consumo; o próprio repositório trata assim a compra do domicílio principal. Para outros imóveis o critério é consistente nas quatro edições, então não é deslize de um ano: é uma decisão de taxonomia (40005 'uso ocasional' incluiria a compra de casa de veraneio?). Recomendação da IA: 42001 para todas as células listadas, como o domicílio principal e o IBGE; manter em 40005 só aluguel, condomínio, IPTU e contas de outros imóveis. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_pendencias-formulario#p12 REVISAR **aceita**. IA: Série coerente e IBGE concordam com o estado atual. Recomendação da IA: manter (rejeitar a sugestão), salvo razão de conceito. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_vestuario-transporte-higiene-saude#p21 MOVER **aceita** (41006 → 34001). IA: Outlier pontual: os mesmos produtos estão em 34001 em todas as outras edições em que aparecem (pelo menos 3); só em 2017 a célula está em 41006, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 34001) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —

### 42. Aumento_do_ativo

#### 42001 — Imovel aquisicao
Aumento_do_ativo · status **ativo** · criado em base
Células por ano: 1987: 3 · 1995: 10 · 2002: 7 · 2008: 11 · 2017: 6 (padrão 11111)
- Decisão 2026-10-16_claude-v3_1995-copia-de-1987#p02 REVISAR **aceita**. IA: O padrão confirma a suspeita da pendência q3. O histórico dessas células vem de palavra-chave (descrições diferem), o que não basta para mover pela ADR 0005. Recomendação da IA: revisar a lista com o questionário de 1995 aberto; os casos evidentes acima podem ir para o grupo das edições seguintes. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_2017-quadros-deslocados#p08 REVISAR **aceita**. IA: Aluguel não é aquisição (deslocamento típico de 2017). Recomendação da IA: aluguel e garagem para 40005; impostos de outros imóveis para 41001 (como o IPTU do domicílio); clube conforme o IBGE. Só 2008 tem par, por isso fica para decisão humana. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_cynthia-folha-32#p09 REVISAR **aceita**. IA: A revisão manual aponta outlier pontual, mas o detector não o confirmou: a célula tem itens sem histórico ou de outro conceito, ou o histórico não é unânime (R1). Precisa olhar a célula inteira. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_habitacao-servicos#p18 MOVER **aceita** (42001 → 31007). IA: Outlier pontual: os mesmos produtos estão em 31007 em todas as outras edições em que aparecem (pelo menos 2); só em 2017 a célula está em 42001, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 31007) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_habitacao-servicos#p27 REVISAR **aceita**. IA: Os mesmos nomes de produto estão em 32005 nas outras edições, mas a célula está em 42001, de outro domínio (consumo, outras despesas, rendimentos ou inventário). Mesmo nome não garante mesma despesa (ex.: item de inventário de bens duráveis × compra; 'empregado' como rendimento × serviço doméstico). Sem confirmação do IBGE, a decisão é humana. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_nao-consumo#p26 REVISAR **aceita**. IA: Comprar imóvel é investimento (aumento do ativo), não consumo; o próprio repositório trata assim a compra do domicílio principal. Para outros imóveis o critério é consistente nas quatro edições, então não é deslize de um ano: é uma decisão de taxonomia (40005 'uso ocasional' incluiria a compra de casa de veraneio?). Recomendação da IA: 42001 para todas as células listadas, como o domicílio principal e o IBGE; manter em 40005 só aluguel, condomínio, IPTU e contas de outros imóveis. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_pendencias-formulario#p04 MOVER **aceita** (42001 → 43002). IA: Outlier pontual de 1995 com descrição diferente (o detector não casou); 1987, 2002, o IBGE e o formulário concordam. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_pendencias-formulario#p08 MOVER **aceita** (42001 → 31007). IA: Taxa não é aquisição de imóvel (deslocamento de 2017 no quadro 12). 2008 e a sugestão humana dizem 31007; o IBGE confirma Habitação (linha água e esgoto, que pode ser discutida depois). Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_pendencias-formulario#p10 REVISAR **aceita**. IA: Duas fontes humanas discordam. Recomendação da IA: 32005 (três edições + Cynthia); a v3 não aplicou porque a mudança cruza de 'outras despesas' para consumo sem o IBGE. Humano (claude-ia (ADR 0005)): —

#### 42002 — Imovel reforma
Aumento_do_ativo · status **ativo** · criado em base
Células por ano: 1987: 73 · 1995: 11 · 2002: 77 · 2008: 86 · 2017: 103 (padrão 11111)
- Decisão 2026-10-16_claude-v3_cynthia-folha-32#p04 REVISAR **aceita**. IA: A revisão manual aponta outlier pontual, mas o detector não o confirmou: a célula tem itens sem histórico ou de outro conceito, ou o histórico não é unânime (R1). Precisa olhar a célula inteira. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_cynthia-folha-400006#p03 REVISAR **aceita**. IA: A revisão manual propõe adotar a classificação mais recente (taxonomia que amadureceu). É escolha de critério para a série, não erro: decisão humana. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_educacao-despesas-diversas#p18 MOVER **aceita** (42002 → 40006). IA: Outlier pontual: os mesmos produtos estão em 40006 em todas as outras edições em que aparecem (pelo menos 2); só em 2017 a célula está em 42002, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 40006) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_educacao-despesas-diversas#p27 REVISAR **aceita**. IA: Os mesmos nomes de produto estão em 40003 nas outras edições, mas a célula está em 42002, de outro domínio (consumo, outras despesas, rendimentos ou inventário). Mesmo nome não garante mesma despesa (ex.: item de inventário de bens duráveis × compra; 'empregado' como rendimento × serviço doméstico). Sem confirmação do IBGE, a decisão é humana. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_educacao-despesas-diversas#p33 REVISAR **aceita**. IA: As outras edições põem os mesmos produtos em 40006, mas o tradutor do IBGE confirma o grupo atual (42002) em 2008. Fontes discordantes (CONSTITUICAO, hierarquia de evidência): decidir qual convenção vale para a série. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_habitacao-servicos#p33 REVISAR **aceita**. IA: As outras edições põem os mesmos produtos em 32003, mas o tradutor do IBGE confirma o grupo atual (42002) em 2008. Fontes discordantes (CONSTITUICAO, hierarquia de evidência): decidir qual convenção vale para a série. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_habitacao-servicos#p37 REVISAR **aceita**. IA: Série partida em dois critérios. Não é deslize de um ano: é decisão de onde fica gasto com jazigo (investimento em imóvel ou cerimônia/serviço funerário). Recomendação da IA: 40003 nos cinco anos, porque é taxa recorrente, não reforma; mas é escolha de conceito. Humano (claude-ia (ADR 0005)): —

#### 42003 — Outros investimentos
Aumento_do_ativo · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 2 · 2002: 8 · 2008: 7 · 2017: 3 (padrão 11111)
- Decisão 2026-10-16_claude-v3_nao-consumo#p07 MOVER **aceita** (32004 → 42003). IA: Outlier pontual: os mesmos produtos estão em 42003 em todas as outras edições em que aparecem (pelo menos 2); só em 2017 a célula está em 32004, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 42003) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_nao-consumo#p12 MOVER **aceita** (41006 → 42003). IA: Outlier pontual: os mesmos produtos estão em 42003 em todas as outras edições em que aparecem (pelo menos 3); só em 2017 a célula está em 41006, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 42003) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_pendencias-formulario#p11 REVISAR **aceita**. IA: A sugestão humana contraria o IBGE; o próprio repositório está dividido entre os anos. Recomendação da IA: manter 42003 (direito de linha é ativo, como o IBGE) e levar 1995 e 2017 para 42003, para a série ficar coerente. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_vestuario-transporte-higiene-saude#p30 REVISAR **aceita**. IA: Os mesmos nomes de produto estão em 33005 nas outras edições, mas a célula está em 42003, de outro domínio (consumo, outras despesas, rendimentos ou inventário). Mesmo nome não garante mesma despesa (ex.: item de inventário de bens duráveis × compra; 'empregado' como rendimento × serviço doméstico). Sem confirmação do IBGE, a decisão é humana. Humano (claude-ia (ADR 0005)): —

### 43. Diminuicao_do_passivo

#### 43001 — Emprestimo e carne
Diminuicao_do_passivo · status **ativo** · criado em base
Células por ano: 1987: 4 · 1995: 4 · 2002: 4 · 2008: 5 · 2017: 4 (padrão 11111)
- Decisão 2026-10-16_claude-v3_1995-copia-de-1987#p02 REVISAR **aceita**. IA: O padrão confirma a suspeita da pendência q3. O histórico dessas células vem de palavra-chave (descrições diferem), o que não basta para mover pela ADR 0005. Recomendação da IA: revisar a lista com o questionário de 1995 aberto; os casos evidentes acima podem ir para o grupo das edições seguintes. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_nao-consumo#p13 MOVER **aceita** (41006 → 43001). IA: Outlier pontual: os mesmos produtos estão em 43001 em todas as outras edições em que aparecem (pelo menos 4); só em 2017 a célula está em 41006, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 43001) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —

#### 43002 — Prestacao de imovel
Diminuicao_do_passivo · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 2 · 2008: 2 · 2017: 2 (padrão 11111)
- Decisão 2026-10-16_claude-v3_pendencias-formulario#p04 MOVER **aceita** (42001 → 43002). IA: Outlier pontual de 1995 com descrição diferente (o detector não casou); 1987, 2002, o IBGE e o formulário concordam. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_pendencias-formulario#p05 MOVER **aceita** (43002 → 32001). IA: Vidro não é prestação de imóvel: o erro de código copiado é inequívoco. O destino 32001 segue a sugestão humana e 2002/2008; a alternativa 42002 faz parte da questão reforma × manutenção (pendência 2026-09-11_arthurwelle#q1), que fica aberta. Humano (claude-ia (ADR 0005)): —

### 44. Rendimento_do_trabalho

#### 44001 — Empregado
Rendimento_do_trabalho · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 5 · 2002: 14 · 2008: 26 · 2017: 8 (padrão 11111)
- Decisão 2026-10-16_claude-v3_habitacao-servicos#p28 REVISAR **aceita**. IA: Os mesmos nomes de produto estão em 32001 nas outras edições, mas a célula está em 44001, de outro domínio (consumo, outras despesas, rendimentos ou inventário). Mesmo nome não garante mesma despesa (ex.: item de inventário de bens duráveis × compra; 'empregado' como rendimento × serviço doméstico). Sem confirmação do IBGE, a decisão é humana. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_nao-consumo#p03 MOVER **aceita** (44001 → 47004). IA: Outlier pontual: os mesmos produtos estão em 47004 em todas as outras edições em que aparecem (pelo menos 3); só em 2008 a célula está em 44001, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 47004) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_nao-consumo#p15 REVISAR **aceita**. IA: Os mesmos produtos estão em 45005 nas duas outras edições em que aparecem; em 2008 estão em 44001. Duas edições contra uma, sem segunda fonte (IBGE neutro ou ausente, sem revisão manual): pela ADR 0005 não é óbvio. Recomendação da IA: mover, salvo razão de conceito. Humano (claude-ia (ADR 0005)): —

#### 44002 — Empregador
Rendimento_do_trabalho · status **ativo** · criado em base
Células por ano: 1987: 2 · 1995: 1 · 2002: 1 · 2008: 2 · 2017: 2 (padrão 11111)

#### 44003 — Conta propria
Rendimento_do_trabalho · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 2 · 2002: 1 · 2008: 1 · 2017: 1 (padrão 11111)

#### 44004 — Trabalho Nao remunerado
Rendimento_do_trabalho · status **ativo** · criado em base
Células por ano: 1987: 0 · 1995: 0 · 2002: 4 · 2008: 3 · 2017: 1 (padrão 00111)

### 45. Transferencia

#### 45001 — Aposentadoria prev publica
Transferencia · status **ativo** · criado em base
Células por ano: 1987: 2 · 1995: 3 · 2002: 5 · 2008: 8 · 2017: 5 (padrão 11111)

#### 45002 — Aposentadoria prev privada
Transferencia · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 2 · 2002: 3 · 2008: 5 · 2017: 1 (padrão 11111)

#### 45003 — Bolsa de estudo
Transferencia · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 1 · 2017: 1 (padrão 11111)
- Decisão 2026-10-16_claude-v3_nao-consumo#p04 MOVER **aceita** (45005 → 45003). IA: Outlier pontual: os mesmos produtos estão em 45003 em todas as outras edições em que aparecem (pelo menos 4); só em 2008 a célula está em 45005, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 45003) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —

#### 45004 — Pensao aliment mesada doacao
Transferencia · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 5 · 2017: 3 (padrão 11111)

#### 45005 — Transferencias transitorias
Transferencia · status **ativo** · criado em base
Células por ano: 1987: 10 · 1995: 14 · 2002: 21 · 2008: 25 · 2017: 9 (padrão 11111)
- Decisão 2026-10-16_claude-v3_nao-consumo#p01 MOVER **aceita** (47004 → 45005). IA: Outlier pontual: os mesmos produtos estão em 45005 em todas as outras edições em que aparecem (pelo menos 3); só em 1987 a célula está em 47004, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 45005) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_nao-consumo#p04 MOVER **aceita** (45005 → 45003). IA: Outlier pontual: os mesmos produtos estão em 45003 em todas as outras edições em que aparecem (pelo menos 4); só em 2008 a célula está em 45005, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 45003) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_nao-consumo#p14 MOVER **aceita** (47004 → 45005). IA: Outlier pontual: os mesmos produtos estão em 45005 em todas as outras edições em que aparecem (pelo menos 4); só em 2017 a célula está em 47004, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 45005) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —

### 46. Rendimento_de_aluguel

#### 46001 — Aluguel de bens imoveis
Rendimento_de_aluguel · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 1 · 2017: 1 (padrão 11111)
- Decisão 2026-10-16_claude-v3_pendencias-formulario#p06 MOVER **aceita** (46001 → 46002). IA: A própria descrição diz bens móveis; 2002, 2017 e a sugestão humana concordam. O grupo 46001 mantém os aluguéis de imóveis. Humano (claude-ia (ADR 0005)): —

#### 46002 — Aluguel de bens moveis
Rendimento_de_aluguel · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 1 · 2002: 1 · 2008: 1 · 2017: 1 (padrão 11111)
- Decisão 2026-10-16_claude-v3_pendencias-formulario#p06 MOVER **aceita** (46001 → 46002). IA: A própria descrição diz bens móveis; 2002, 2017 e a sugestão humana concordam. O grupo 46001 mantém os aluguéis de imóveis. Humano (claude-ia (ADR 0005)): —

### 47. Outros_rendimentos

#### 47001 — Vendas esporadicas
Outros_rendimentos · status **ativo** · criado em base
Células por ano: 1987: 0 · 1995: 10 · 2002: 10 · 2008: 10 · 2017: 7 (padrão 01111)
- Decisão 2026-10-16_claude-v3_nao-consumo#p05 MOVER **aceita** (47004 → 47001). IA: Outlier pontual: os mesmos produtos estão em 47001 em todas as outras edições em que aparecem (pelo menos 3); só em 2008 a célula está em 47004, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 47001) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —

#### 47002 — Emprestimos
Outros_rendimentos · status **ativo** · criado em base
Células por ano: 1987: 1 · 1995: 3 · 2002: 3 · 2008: 1 · 2017: 1 (padrão 11111)
- Decisão 2026-10-16_claude-v3_nao-consumo#p02 MOVER **aceita** (47004 → 47002). IA: Outlier pontual: os mesmos produtos estão em 47002 em todas as outras edições em que aparecem (pelo menos 3); só em 1987 a célula está em 47004, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 47002) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —

#### 47003 — Aplicacoes de capital
Outros_rendimentos · status **ativo** · criado em base
Células por ano: 1987: 10 · 1995: 3 · 2002: 11 · 2008: 10 · 2017: 11 (padrão 11111)
- Decisão 2026-10-16_claude-v3_nao-consumo#p06 MOVER **aceita** (47004 → 47003). IA: Outlier pontual: os mesmos produtos estão em 47003 em todas as outras edições em que aparecem (pelo menos 3); só em 2008 a célula está em 47004, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 47003) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —

#### 47004 — Outros renda
Outros_rendimentos · status **ativo** · criado em base
Células por ano: 1987: 30 · 1995: 23 · 2002: 15 · 2008: 19 · 2017: 65 (padrão 11111)
- Decisão 2026-10-16_claude-v3_1995-copia-de-1987#p01 MANTER **aceita**. IA: A coincidência de grupo com 1987 não é erro quando as edições seguintes confirmam. Nada a mudar. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_1995-copia-de-1987#p02 REVISAR **aceita**. IA: O padrão confirma a suspeita da pendência q3. O histórico dessas células vem de palavra-chave (descrições diferem), o que não basta para mover pela ADR 0005. Recomendação da IA: revisar a lista com o questionário de 1995 aberto; os casos evidentes acima podem ir para o grupo das edições seguintes. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_nao-consumo#p01 MOVER **aceita** (47004 → 45005). IA: Outlier pontual: os mesmos produtos estão em 45005 em todas as outras edições em que aparecem (pelo menos 3); só em 1987 a célula está em 47004, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 45005) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_nao-consumo#p02 MOVER **aceita** (47004 → 47002). IA: Outlier pontual: os mesmos produtos estão em 47002 em todas as outras edições em que aparecem (pelo menos 3); só em 1987 a célula está em 47004, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 47002) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_nao-consumo#p03 MOVER **aceita** (44001 → 47004). IA: Outlier pontual: os mesmos produtos estão em 47004 em todas as outras edições em que aparecem (pelo menos 3); só em 2008 a célula está em 44001, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 47004) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_nao-consumo#p05 MOVER **aceita** (47004 → 47001). IA: Outlier pontual: os mesmos produtos estão em 47001 em todas as outras edições em que aparecem (pelo menos 3); só em 2008 a célula está em 47004, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 47001) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_nao-consumo#p06 MOVER **aceita** (47004 → 47003). IA: Outlier pontual: os mesmos produtos estão em 47003 em todas as outras edições em que aparecem (pelo menos 3); só em 2008 a célula está em 47004, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 47003) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_nao-consumo#p14 MOVER **aceita** (47004 → 45005). IA: Outlier pontual: os mesmos produtos estão em 45005 em todas as outras edições em que aparecem (pelo menos 4); só em 2017 a célula está em 47004, sem nenhum item desse grupo em outro ano. Mover a célula inteira respeita a R1 (todos os itens com histórico apontam para 45005) e recompõe a série do grupo (R4/R6). Critério de óbvio da ADR 0005. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_nao-consumo#p16 REVISAR **aceita**. IA: Os mesmos produtos estão em 44001 nas duas outras edições em que aparecem; em 1995 estão em 47004. Duas edições contra uma, sem segunda fonte (IBGE neutro ou ausente, sem revisão manual): pela ADR 0005 não é óbvio. Recomendação da IA: mover, salvo razão de conceito. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_nao-consumo#p17 REVISAR **aceita**. IA: Os mesmos produtos estão em 45005 nas duas outras edições em que aparecem; em 1995 estão em 47004. Duas edições contra uma, sem segunda fonte (IBGE neutro ou ausente, sem revisão manual): pela ADR 0005 não é óbvio. Recomendação da IA: mover, salvo razão de conceito. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_nao-consumo#p25 REVISAR **aceita**. IA: As outras edições põem os mesmos produtos em 44001, mas o tradutor do IBGE confirma o grupo atual (47004) em 2017. Fontes discordantes (CONSTITUICAO, hierarquia de evidência): decidir qual convenção vale para a série. Humano (claude-ia (ADR 0005)): —

### 88. Inventário

#### 88888 — Inventário
Inventário · status **ativo** · criado em base
Células por ano: 1987: 28 · 1995: 33 · 2002: 33 · 2008: 32 · 2017: 32 (padrão 11111)
- Decisão 2026-10-16_claude-v3_habitacao-servicos#p29 REVISAR **aceita**. IA: Os mesmos nomes de produto estão em 32003 nas outras edições, mas a célula está em 88888, de outro domínio (consumo, outras despesas, rendimentos ou inventário). Mesmo nome não garante mesma despesa (ex.: item de inventário de bens duráveis × compra; 'empregado' como rendimento × serviço doméstico). Sem confirmação do IBGE, a decisão é humana. Humano (claude-ia (ADR 0005)): —
- Decisão 2026-10-16_claude-v3_habitacao-servicos#p30 REVISAR **aceita**. IA: Os mesmos nomes de produto estão em 32004 nas outras edições, mas a célula está em 88888, de outro domínio (consumo, outras despesas, rendimentos ou inventário). Mesmo nome não garante mesma despesa (ex.: item de inventário de bens duráveis × compra; 'empregado' como rendimento × serviço doméstico). Sem confirmação do IBGE, a decisão é humana. Humano (claude-ia (ADR 0005)): —
