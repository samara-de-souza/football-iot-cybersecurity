# Risk Assessment — DREAD

Este artefato apresenta a avaliação de risco das vulnerabilidades
identificadas no ecossistema IoT analisado no TCC.

A análise utiliza o modelo DREAD, com cinco critérios pontuados de 1 a 3:

- **D — Damage:** dano potencial;
- **R — Reproducibility:** facilidade de reprodução;
- **E — Exploitability:** facilidade de exploração;
- **A — Affected Users:** usuários ou ativos afetados;
- **D — Discoverability:** facilidade de descoberta.

A soma dos cinco critérios resulta em uma pontuação de 5 a 15,
classificada da seguinte forma:

| Pontuação | Nível |
|---|---|
| 5–7 | Baixo |
| 8–11 | Médio |
| 12–15 | Crítico |

A matriz apresentada no artefato utiliza os resultados do DREAD para
posicionar as vulnerabilidades em uma escala de **Impacto × Probabilidade**.

Para o posicionamento:

- **Impacto (X)** = `(Dano + Afetados) / 2`
- **Probabilidade (Y)** = `(Reprodutibilidade + Explorabilidade) / 2`

Os valores são posteriormente normalizados para a escala de 1 a 4
utilizada na matriz.

As cinco vulnerabilidades avaliadas apresentaram pontuações DREAD entre
9 e 11, sendo classificadas como **risco médio**.

![Risk Matrix](../images/risk_matriz.png)