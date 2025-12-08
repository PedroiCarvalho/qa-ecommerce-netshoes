Casos de Teste – Netshoes (Busca, Filtros, PDP e Carrinho)

Data: coloque o dia de hoje
Responsável: Pedro Carvalho
Sistema: Netshoes
URL: https://www.netshoes.com.br

🧪 CT-001 – Validar busca com termo válido

Pré-condições:
– Acessar homepage da Netshoes

Passos:

Digitar “tênis” na barra de busca

Pressionar Enter

Analisar a lista de produtos retornada

Resultado Esperado:
– Produtos relacionados ao termo “tênis” devem ser exibidos
– Página deve carregar sem erros

🧪 CT-002 – Validar busca com termo inválido

Passos:

Digitar “asdfg123” na busca

Pressionar Enter

Resultado Esperado:
– Sistema deve exibir mensagem apropriada (“nenhum resultado”)
– Não deve quebrar layout
– Não deve retornar produtos incoerentes

🧪 CT-003 – Validar aplicação de filtro por preço

Passos:

Realizar busca por “tênis”

Abrir filtros → Preço

Selecionar faixa R$ 100 – R$ 200

Resultado Esperado:
– Lista deve atualizar somente com produtos dentro da faixa
– Total de produtos deve ser recalculado
– Filtro deve ser exibido como ativo

🧪 CT-004 – Validar cálculo de frete na PDP

Passos:

Abrir um produto qualquer

Inserir CEP válido para frete

Clicar em “Calcular”

Resultado Esperado:
– Frete deve ser exibido corretamente
– O preço não deve sumir
– Botões devem continuar funcionais

🧪 CT-005 – Validar inclusão do item no carrinho

Passos:

Abrir um produto

Selecionar numeração (se aplicável)

Clicar em “Adicionar ao carrinho”

Abrir carrinho

Resultado Esperado:
– Item deve aparecer no carrinho
– Quantidade = 1
– Frete deve atualizar ao inserir CEP
– Não deve ocorrer erro visual ou técnico
