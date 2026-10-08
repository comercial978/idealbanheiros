# Decisões e premissas

## Decisões registradas

| ID | Decisão | Motivo |
|---|---|---|
| D-001 | Usar `idealbanheiros.com.br` como domínio de produção | Correção confirmada pelo cliente em 08/10/2026 |
| D-002 | Limitar a oferta à locação de banheiros químicos e contêineres | Posicionamento informado pelo cliente |
| D-003 | Usar Mais Módulos apenas como referência de organização | A Ideal não fabrica nem vende e deseja uma experiência mais sucinta |
| D-004 | Priorizar contato, mobile, conteúdo em texto, SEO e desempenho | São os maiores gargalos observados no site atual |
| D-005 | Manter o repositório `comercial978/idealbanheiros` como público | Visibilidade alterada por solicitação do cliente em 08/10/2026 para permitir acesso sem login |
| D-006 | Não incluir dados de pagamento na documentação técnica | Dados financeiros não são necessários para desenvolver o site |

## Premissas a validar

- Uberaba/MG é a localização principal da oferta, mas as demais cidades precisam ser confirmadas.
- Os dados de contato publicados atualmente são provisórios até validação formal.
- A Ideal fornecerá fotos próprias e autorização para uso.
- O formulário terá uma solução segura compatível com a hospedagem escolhida.
- Analytics e Search Console serão configurados somente com acessos fornecidos ou autorizados.
- A tecnologia de implementação será registrada depois da avaliação da hospedagem Microsoft.
- O prazo de 10 a 15 dias úteis começa após materiais essenciais e aprovações iniciais.

## Evidências do diagnóstico de 08/10/2026

- o menu principal não fica visível em viewport móvel de 390 px;
- links internos e fluxo de navegação precisam ser simplificados;
- o WhatsApp flutuante usa mensagem sem contexto de orçamento;
- o formulário publicado utiliza endpoint HTTP e campo de mensagem de linha única;
- informações institucionais e de produtos estão incorporadas em imagens;
- não há meta description, canonical ou Open Graph na página principal;
- imagens não declaram carregamento adiado e usam descrições alternativas genéricas;
- a página atual apresenta 25 imagens e demanda otimização de formatos, tamanhos e carregamento.

Essas evidências orientam prioridades, mas a implementação deverá repetir os testes no ambiente de homologação e em produção.
