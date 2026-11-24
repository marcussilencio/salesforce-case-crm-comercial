# 00 — Estrutura do Case Final (PDF + publicações do LinkedIn)

**Objetivo:** provar na prática o que o perfil do LinkedIn afirma — é a resposta ao principal alerta do "teste do recrutador": *zero evidência prática*.
**Formato combinado:** PDF de **8 páginas** fixado em Destaques + carrossel resumido no feed.
**Público:** recrutador de Salesforce/BA que clica no perfil depois de uma candidatura — tem **2 minutos**.

---

## Estrutura das 8 páginas

| Página | Título sugerido | Conteúdo | Fonte (pasta Análise) | Status |
|---|---|---|---|---|
| 1 | **Capa** | "CRM comercial do zero no Salesforce — do problema de negócio ao dashboard" + nome da empresa fictícia, tempo de execução, selos (org Developer, 10 user stories, 2 flows) | — | ✅ **no PDF publicado 24/11** |
| 2 | **O problema** | Página do problema + critérios de sucesso | `01-pagina-do-problema.md` | ✅ texto pronto |
| 3 | **O processo** | Mapa das 6 etapas + as 3 decisões de modelagem | `02-mapa-do-processo.md` | ✅ texto pronto |
| 4 | **Requisitos** | 10 user stories + matriz de cobertura (mostrar 3–4 e dizer "10 no total") | `03-user-stories.md` | ✅ texto pronto |
| 5 | **Modelo de dados** | Tabela de objetos/campos + "por quê" (1 exemplo em destaque) | `04-modelo-de-dados.md` | ✅ texto pronto |
| 6 | **Configuração na prática** | Prints: estágios da Oportunidade, seção Diagnóstico no layout, regra de validação, produtos no price book, dados fictícios | — | ✅ **no PDF publicado 24/11** |
| 7 | **Automação, segurança e visão** | Prints: Flow do follow-up, Flow do Pedido de Vaga, perfis/hierarquia, dashboard | — | ✅ **no PDF publicado 24/11** |
| 8 | **Testes e aprendizados** | Resumo do plano de testes (27 testes), "o que aprendi" e "o que faria diferente" + CTA (perfil Trailblazer, busca de oportunidades) | `05-plano-de-testes.md` | ✅ texto pronto |

> Regra de ouro das páginas 6 e 7: **print + 1 frase explicando a decisão** — mostra raciocínio, não só cliques.

---

## Checklist de prints (Semana 2 e 3) → salve em `Prints/`

**Semana 2 (página 6):**
- [ ] Lista de estágios personalizada da Oportunidade
- [ ] Layout da Oportunidade com seção "Diagnóstico"
- [x] Uma regra de validação aberta no editor (VR_Diagnostico_Proposta, 09/11/2026)
- [ ] Produtos + Price Book com os 4 serviços
- [ ] ~20 contas/opportunities fictícias no funil (visão "Pipeline")
- [x] Picklist Motivo da perda completo (S2-14, 09/11/2026)

**Semana 3 (página 7):**
- [ ] Flow_FollowUp_Proposta (tela do fluxo)
- [ ] Flow_PedidoDeVaga_Ganho (tela do fluxo)
- [ ] Pedido de Vaga recém-criado pelo Flow
- [ ] Perfis: Executivo, Gestor e Selecionadora (base mínima + permission set)
- [ ] Hierarquia de papéis
- [ ] **User Licenses (Company Information): mostra as 4 licenças da org DE (3 usadas, 1 restante)** → evidência da restrição e da solução (rotação de perfis)
- [ ] Dashboard "Visão Comercial" completo
- [ ] Print comparativo: "antes" (Setup Home vazio, já salvo) × "depois"

---

## Publicação: em partes ou tudo de uma vez?

**Recomendação: híbrido — mas o case completo é o gate para candidaturas.**

1. **Primeiro monte o PDF completo** (páginas 1–8). É o que o recrutador clica e julga — um projeto pela metade ressalta exatamente o alerta "sem evidência prática".
2. **Alimente o perfil no caminho**, se quiser ritmo: 2 a 3 posts curtos de milestone durante as Semanas 2 e 3 (ex.: "montei meu primeiro Flow e o erro que me ensinou X", "por que 'motivo de perda obrigatório' é requisito de negócio, não burocracia"). Cada um é autocontido — não é "parte 1 do projeto".
3. **Post âncora único ao final:** carrossel no feed (8 slides = as 8 páginas) + PDF fixado em Destaques + texto de abertura contando a história de quem usou CRM por anos e agora o projeta.
4. **Só então** as candidaturas com link no perfil — ou, se a oportunidade aparecer antes, o PDF parcial já com páginas 1–5 + 1 print da Semana 2 funciona como versão "em andamento" honesta.

*Vantagem da abordagem híbrida:* o LinkedIn mostra constância (algoritmo e recrutadores notam cadência), E o recrutador encontra o entregável completo.

---

## Texto do post âncora (rascunho — SUPERADO: a versão final aprovada está em `03-textos-publicacao.md`)

> Usei CRM quase 8 anos do lado de quem vendia. Agora projetei um do zero.
>
> O problema: uma consultoria de RH fictícia controlava propostas em planilha e o gestor pedia o funil por mensagem.
>
> O que fiz na minha org Developer Edition:
>
> Mapeei o processo comercial em 6 etapas.
> Escrevi 10 user stories com critérios de aceite.
> Modelei objetos, campos e regras no Salesforce.
> Automatizei o follow-up de proposta e a abertura de vaga com Flow.
> Entreguei um dashboard para o gestor não precisar pedir mais planilha.
>
> O que aprendi: a parte difícil não é clicar. É decidir o que não fazer e saber defender por quê. Deixar coisas fora do escopo foi a decisão de Business Analyst que mais me marcou.
>
> O case completo está fixado no Destaque, em 8 páginas. Estou à disposição para oportunidades em Salesforce Administration e Business Analysis.
>
> #Salesforce #BusinessAnalysis #CRM #FlowBuilder

---

## Camada 2 — o que separa um portfólio bom de um que contrata

A pesquisa de mercado (Salesforce Ben, fev/2026; The Salesforce Monk, jul/2026; blog oficial Salesforce) mostra que o case em PDF é o **mínimo**. O que faz contratar é ter **três camadas**:

| Camada | Entrega | Por que |
|---|---|---|
| 1. Prova escrita | PDF de 8 páginas + carrossel | Mostra raciocínio de BA |
| 2. Prova em vídeo | **Vídeo nativo de 60–90s** no LinkedIn | "A forma mais eficaz de gerar confiança com um recrutador" (Salesforce Monk) |
| 3. Prova navegável | **Site de portfólio em Experience Cloud**, na mesma org | Prova que você sabe construir, não só descrever. É o link que vai no currículo. |

O site em Experience Cloud não é enfeite: ele **demonstra** Data Modeling, Experience Cloud, segurança e UI — quatro competências que o PDF só afirma. É o que Abdul Sultani e Jessica Mills fizeram para conseguir a primeira vaga (casos citados no blog da Salesforce).

**Estrutura mínima do site:** About Me · Projetos (Fera Recruiting + Job Application Tracker) · Vídeo · Contato · link do Trailblazer.

---

## Status geral do projeto

| Semana | Entrega | Status |
|---|---|---|
| 1 | Página do problema | ✅ |
| 1 | Mapa do processo | ✅ |
| 1 | 10 user stories | ✅ (revisadas 01/11) |
| 1 | Modelo de dados | ✅ **revisado 01/11** (correções técnicas aplicadas) |
| 1 | Plano de testes | ✅ (27 testes) |
| 1 | Estrutura do case | ✅ (este documento) |
| 1 | Post Parte 1 (carrossel de análise) | ✅ **publicado 13/11** |
| 2 | Configuração na org + dados fictícios | ✅ **concluído** |
| 3 | Flows, segurança, relatórios, testes, PDF | ✅ **concluído** (27 testes, PDF de 8 páginas) |
| 4 | Vídeo 3:10 + site Experience Cloud + post âncora | ✅ **concluído 24/11** — vídeo publicado 19/11, site no ar 18/11, **post âncora publicado 24/11 + Destaque montado** |
