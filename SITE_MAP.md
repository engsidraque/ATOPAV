# Mapa do Site

| Prioridade | URL canônica | Intenção | CTA principal |
| --- | --- | --- | --- |
| P1 | `/` | Acompanhamento técnico e fiscalização de pavimentação | Consultar disponibilidade da obra |
| P1 | `/servicos` | Comparar escopos e escolher o serviço | Consultar disponibilidade |
| P1 | `/servicos/acompanhamento-tecnico-de-obras-ato` | ATO de pavimentação | Enviar dados da obra |
| P1 | `/servicos/fiscalizacao-de-obras` | Fiscalização de pavimentação | Enviar dados da obra |
| P1 | `/servicos/controle-tecnologico` | Acompanhamento e análise de controles e resultados | Enviar dados da obra |
| P1 | `/servicos/consultoria-em-pavimentacao` | Consultoria técnica com produto definido em proposta | Enviar dados da obra |
| P1 | `/responsavel-tecnico` | Formação e perfil profissional de Sidraque Firmino | Ver perfil no LinkedIn |
| P1 | `/experiencia-tecnica` | Experiências profissionais atribuídas aos respectivos vínculos | Consultar escopo |
| P1 | `/contato` | Triagem inicial da obra | Continuar no WhatsApp |
| P1 | `/a-atopav` | Identidade e modo de atuação | Conhecer o ATO |
| P1 | `/privacidade` | Informar o fluxo de dados do site | Página de contato |

## URLs Preservados

- As páginas de serviço já publicadas mantêm seus slugs atuais como canônicos.
- `/servicos/ato-pavimentacao` resolve para o serviço canônico `/servicos/acompanhamento-tecnico-de-obras-ato`.
- `/servicos/fiscalizacao-pavimentacao` resolve para `/servicos/fiscalizacao-de-obras`.
- `/servicos/controle-tecnologico-pavimentacao` resolve para `/servicos/controle-tecnologico`.
- `/servicos/consultoria-pavimentacao` resolve para `/servicos/consultoria-em-pavimentacao`.
- `/projetos` continua acessível durante a transição e usa `/experiencia-tecnica` como canonical. Não há redirecionamento HTTP configurado no projeto.
- `/areas-de-atuacao` permanece no roteador. `/conteudo-tecnico` e seus seis artigos antigos continuam acessíveis por link direto, mas usam `noindex,follow` e foram removidos do sitemap até autoria, revisão técnica e fontes serem confirmadas.

O sitemap lista somente URLs canônicos. A configuração de fallback e 404 para produção depende da hospedagem, ainda não identificada.

## Itens Não Criados

Não foram adicionadas páginas regionais por cidade, novos artigos, casos de obra, depoimentos, estudos ou métricas de desempenho.