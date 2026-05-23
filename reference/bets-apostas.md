# Apostas Esportivas e Cassino Online (Bets) — IRPF 2026

## Marco regulatório

**Lei nº 14.790/2023** — regulamentou o mercado de apostas de quota fixa no Brasil. Para o ciclo IRPF 2026, a Receita Federal criou:
- Códigos específicos em "Bens e Direitos".
- Faixa de isenção anual.
- Distinção entre plataformas autorizadas e offshore.

## Os dois domínios fiscais (não confundir!)

A skill deve sempre tratar **separadamente**:

1. **Patrimônio** (saldo na carteira da bet em 31/12/2025) → "Bens e Direitos".
2. **Rendimentos** (prêmios líquidos auferidos durante 2025) → "Rendimentos Sujeitos à Tributação Exclusiva" OU "Rendimentos Tributáveis" (depende da plataforma).

## 1. Declaração patrimonial — Saldos em carteira

### Regra (corrigida — fonte: contabeis.com.br + Receita Federal)
Se o saldo na **carteira virtual da bet** em **31/12/2025 às 23:59** for **superior a R$ 140,00**, é **obrigatório declarar** o bem individualmente.

> **Esclarecimento**: o limite de **R$ 140** é o threshold padrão para declaração de **qualquer** saldo em conta/aplicação financeira (incluindo carteiras de bets). Não confundir com **R$ 800.000** que é o limite **total de bens e direitos** que aciona a obrigatoriedade de entrega da DAA inteira (ver `obrigatoriedade.md`).
>
> **Quando a regra do R$ 140 importa**:
> - Se você está declarando IRPF (já obrigado por outro critério: salário > R$ 35.584, etc), deve declarar **TODA** carteira de bets > R$ 140 individualmente.
> - Se você não está obrigado a declarar (renda baixa), saldos < R$ 140 podem ser omitidos.

### Como declarar
- Ficha: **Bens e Direitos**.
- Grupo: **06 — Depósitos e Aplicações**.
- Código: **02** (campo específico criado em 2026 para apostas).
- Descrição: nome da plataforma + CNPJ.
- Situação em 31/12/2024: saldo no ano anterior (zero se nova).
- Situação em 31/12/2025: saldo na data, conforme extrato/comprovante.

### Distinção crítica de CNPJ
- **Plataforma autorizada (nacional)**: usa CNPJ brasileiro registrado no Ministério da Fazenda.
- **Plataforma offshore**: pode não ter CNPJ — usar identificador da empresa, país de origem, descrição completa.

## 2. Tributação de prêmios

### Tipo de tributação: DEFINITIVA / EXCLUSIVA

- O imposto **não** vira crédito para abater outros impostos.
- **Não** é restituível.
- Lançar na ficha "Rendimentos Sujeitos à Tributação Exclusiva/Definitiva", Tipo de Rendimento **"13 — Prêmios líquidos obtidos em loterias de apostas de quota fixa — Lei nº 14.790/2023"**.

### Apuração — ANUAL, POR NATUREZA DE APOSTA

**Fonte autoritativa**: Perguntão IRPF 2026, pergunta 318; art. 31 da Lei nº 14.790/2023.

A apuração do prêmio líquido é **anual** (não por evento), e separada por **natureza**:

1. **Eventos reais de temática esportiva** (futebol, basquete, etc).
2. **Eventos virtuais de jogos on-line** (cassino, slots, etc).
3. **Fantasy sport**.

**Algoritmo oficial** (passos do Perguntão 2026):

1. Para cada **agente operador** (plataforma) e cada **natureza** de aposta, somar ganhos e subtrair perdas no ano (incluindo todas as marcas comerciais do operador).
2. Para cada **natureza**, somar os resultados de **todos os operadores** — obtendo o **resultado líquido anual por natureza**.
3. **Prêmio líquido total** = soma apenas dos **resultados positivos por natureza** (resultados negativos em uma natureza **NÃO compensam** ganhos em outra).
4. Subtrair a primeira faixa da tabela progressiva anual (R$ 28.467,20 em 2025).
5. Aplicar 15% sobre o excedente.

> **Exemplo do Perguntão**: João ganhou R$ 62.000 em eventos reais somando 2 operadores, e teve **perda** líquida de R$ 39.000 em eventos virtuais. Prêmio líquido = R$ 62.000 (perda em virtual não abate). Imposto = (62.000 − 28.467,20) × 15% = **R$ 5.029,92**.

**Implicações práticas**:
- ✅ Perdas DENTRO da mesma natureza compensam ganhos da mesma natureza, no ANO inteiro.
- ❌ Perdas em **eventos virtuais** NÃO compensam ganhos em **eventos reais** (nem vice-versa).
- ❌ Perdas em fantasy sport NÃO compensam ganhos em apostas esportivas.

### Quem paga e quando

**Quem apura**: o **próprio apostador** (não a plataforma).

**Quando**:
- A plataforma envia o **ComprovaBet** até o último dia útil de **fevereiro/2026** (com os resultados de 2025).
- O contribuinte usa o **aplicativo específico da RFB** em https://www.gov.br/receitafederal/pt-br/centrais-de-conteudo/formularios/impostos/pagamento-aposta-de-quota-fixa-e-fantasy-sport/aplicativo.html para apurar o imposto.
- Pagamento via **DARF** até o último dia útil de **abril/2026**.

**Não é retenção na fonte**: ao contrário de salário ou aplicações financeiras, a plataforma de bets **não retém** o imposto no pagamento dos prêmios — apenas fornece o ComprovaBet. O contribuinte calcula e paga.

### Faixa de isenção anual
- **R$ 28.467,20** em 2025 (primeira faixa da tabela progressiva **anual** — não mensal, não por evento).
- Aplica-se uma única vez, sobre o **prêmio líquido total** consolidado anual.

### Alíquota sobre o excedente
**15%** sobre o que exceder R$ 28.467,20 — apurada pelo apostador via aplicativo da RFB e paga via DARF próprio.

## Distinção decisiva: Plataforma Nacional vs Offshore

### Plataforma Nacional Autorizada
**Quem são**: empresas com licença do Ministério da Fazenda (lista oficial em https://www.gov.br/fazenda → SPA — Secretaria de Prêmios e Apostas). Exemplos atuais (sujeito a atualização): Bet365, Betano, Sportingbet, F12.bet, Esportes da Sorte, etc — **somente as licenciadas**.

**Responsabilidade fiscal**: a plataforma autorizada **fornece o ComprovaBet** ao contribuinte até último dia útil de fevereiro/2026. **O apostador** é quem apura e paga o DARF próprio até abril/2026 (não há retenção na fonte pela bet sobre os prêmios pagos ao apostador).

**Como declarar**:
- Ficha: **Rendimentos Sujeitos à Tributação Exclusiva/Definitiva**.
- Tipo de Rendimento: **"13 — Prêmios líquidos obtidos em loterias de apostas de quota fixa — Lei 14.790/2023"**.
- CNPJ: do agente operador (constante no ComprovaBet).
- Tipo de Beneficiário: Titular ou Dependente.
- Valor: prêmio líquido conforme apuração anual por natureza (passo 3 acima).

### Plataforma Offshore (não autorizada / internacional)
**Exemplos**: plataformas sem licença brasileira, sediadas em Curaçao, Malta, Gibraltar, etc.

**Responsabilidade fiscal**: **inverte** para a pessoa física do apostador. O apostador deveria ter:
1. Apurado mês a mês via **Carnê-Leão** (sistema do e-CAC).
2. Recolhido **DARF código 0190** até o último dia útil do mês seguinte.
3. Tabela progressiva mensal aplicada (não a faixa fixa de 15%).

> **A faixa de isenção de R$ 28.467,20 da Lei 14.790/2023 foi desenhada para plataformas autorizadas**. Para offshore, aplica-se a **tabela progressiva mensal de IRPF** sobre os ganhos como rendimento estrangeiro.

**Como declarar (offshore)**:
- Ficha: **Rendimentos Tributáveis Recebidos de Pessoa Física e do Exterior pelo Titular**.
- Discriminação: nome da plataforma, país, valores mensais.
- Carnê-Leão registrado (idealmente já pago durante 2025).

**Se o apostador NÃO recolheu DARF mensal durante 2025** (cenário muito comum):
1. Calcular o devido mês a mês com tabela progressiva.
2. Recolher **DARFs retroativos** (código 0190) com **multa de mora** + **juros SELIC**.
3. Multa de mora: 0,33% por dia até 20% máximo.
4. Juros: SELIC acumulada do mês seguinte ao vencimento até o pagamento.
5. Lançar na declaração com data correta (mês de recebimento) — programa calculará o que falta pagar no ajuste.

> **Alerta crítico**: a Receita Federal tem acordos de troca de informação fiscal com vários países. Plataformas em Curaçao, Malta, Gibraltar, Panamá compartilham dados via OECD. Ocultar é arriscado e a sanção pode ser de **150% do imposto devido + processo criminal por sonegação**.

## ComprovaBet

**Documento oficial** das plataformas autorizadas, equivalente ao informe de rendimentos.

Conteúdo:
- Total de apostas feitas no ano.
- Total de prêmios brutos recebidos.
- Total de apostas perdidas.
- IR retido pela plataforma.
- CNPJ e razão social.

A skill deve **exigir o ComprovaBet** antes de processar qualquer cálculo de bets nacionais. Se o usuário não tem, orientá-lo a:
1. Acessar a área do cliente da plataforma.
2. Procurar seção "Imposto de Renda" ou "Documentos Fiscais".
3. Baixar PDF do ComprovaBet 2025.

Para plataformas offshore, **não existe ComprovaBet**. Usar:
- Histórico de transações da carteira.
- Extratos bancários mostrando depósitos/saques.
- E-mails de confirmação de prêmios.

## Cálculo prático para apostadores frequentes

Pontos-chave:

- A isenção de R$ 28.467,20 é **anual**, não mensal e não por evento (Perguntão 318).
- A apuração é **anual por natureza**: ganhos e perdas dentro da **mesma natureza** (ex: ambos em eventos reais esportivos) se compensam ao longo do ano. Entre **naturezas diferentes**, perdas NÃO compensam.
- Se o apostador joga em **múltiplas plataformas**, somar **todas** por natureza antes de comparar com a faixa de isenção. Não há isenção por plataforma.
- **Ordem dos passos**: (1) apurar líquido por operador × natureza; (2) consolidar líquido por natureza somando operadores; (3) somar apenas naturezas com resultado positivo; (4) subtrair R$ 28.467,20; (5) aplicar 15%; (6) pagar DARF até último dia útil de abril/2026.

## Erros comuns

- ❌ Não declarar saldo de carteira virtual > R$ 140 quando obrigado a entregar a DAA → omissão patrimonial, risco de malha fina.
- ❌ Confundir prêmio bruto com prêmio líquido (líquido é após descontar a aposta).
- ❌ Tentar compensar perdas de cassino com ganhos esportivos — **não há compensação**.
- ❌ Ignorar plataforma offshore achando que "ninguém vai descobrir" — Banco Central reporta movimentações ao fisco.
- ❌ Lançar prêmios de plataforma autorizada como "Rendimentos Tributáveis" (em vez de "Tributação Exclusiva") — gera cobrança em duplicidade.
- ❌ Esquecer de incluir **freebets** e **bônus** convertidos em saldo real — tributáveis se virarem dinheiro.

## Sinalizadores de alerta para a IA

Se o usuário disser:
- "Ganhei muito em 2025 mas não declarei nada" → carregar este arquivo + **malha-fina-esocial.md** para entender riscos.
- "Aposto em [plataforma]" → verificar se está na lista do Ministério da Fazenda. Se não, é offshore.
- "Tenho R$ 1.500 parados na bet" → declarar em Bens (saldo > R$ 140 e contribuinte obrigado a entregar DAA).
- "Joguei muito mas perdi tudo" → não há nada a tributar (não há prêmio líquido), mas se houve **algum** prêmio durante o ano, pode haver retenção registrada que precisa ser declarada.

## Fontes oficiais para consulta

- **Lei nº 14.790, de 29/12/2023** — art. 31 (tributação definitiva).
- **Perguntão IRPF 2026, pergunta 318** — algoritmo de apuração anual por natureza, com exemplo detalhado.
- **Aplicativo da RFB** para cálculo: https://www.gov.br/receitafederal/pt-br/centrais-de-conteudo/formularios/impostos/pagamento-aposta-de-quota-fixa-e-fantasy-sport/aplicativo.html
- **Portaria SPA/MF** (lista de plataformas autorizadas — atualizada periodicamente).
- **Portal Gov.br** → Receita Federal → "Meu IR".
