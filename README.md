# Oferta MeLi

Três skills em português para preparar anúncios de produtos e kits no Mercado Livre Brasil.

## O que vem no repositório

| Skill | Entrega | Onde baixar |
| --- | --- | --- |
| `oferta-meli` | Galeria de 10 imagens quadradas de 1200 × 1200 px. Inclui capa, benefícios e escala, uso principal, detalhes, comparação factual e outra aplicação. As imagens 07–10 aprofundam detalhes ou mostram componentes do kit em uso. | [`SKILL.md`](SKILL.md) e [`agents/`](agents/) na raiz |
| `meli-title-optimizer` | Um título factual, sem marca, de 58 a 60 caracteres, baseado na linguagem de busca do Mercado Livre Brasil. | [Pacote de título e descrição](./skills-meli.zip?raw=true) |
| `meli-description` | Descrição comercial factual de 1.200 a 1.500 caracteres. Quando solicitado, salva o texto em `Descrição.txt`. | [Pacote de título e descrição](./skills-meli.zip?raw=true) |

O pacote inclui as duas pastas completas, com os scripts, testes e material de apoio do otimizador de títulos.

## Instalação

1. Baixe o repositório pelo menu **Code → Download ZIP** ou clone-o. Para instalar a skill de imagens, reúna `SKILL.md` e `agents/` em uma pasta chamada `oferta-meli`.
2. Extraia `skills-meli.zip` e mantenha as pastas `meli-title-optimizer` e `meli-description` com seus arquivos internos.
3. Coloque as pastas das skills que deseja usar no diretório de skills do seu ambiente. Para uso em um projeto Codex, use `.agents/skills/` na raiz do projeto.

## Como usar

- **Imagens** — “Use `$oferta-meli` para criar a galeria deste kit com base nas fotos anexadas e na lista de itens inclusos.” Requer uma ferramenta de geração e edição de imagens.
- **Título** — “Use `$meli-title-optimizer` para criar o título deste anúncio. Seguem o produto, as características confirmadas e os termos de busca.” Requer acesso à pesquisa na web.
- **Descrição** — “Use `$meli-description` para escrever a descrição deste anúncio com os benefícios confirmados, a ficha técnica e os itens inclusos. Salve em `Descrição.txt`.”

Para preparar o anúncio completo, peça as três entregas no mesmo pedido e indique os dados confirmados e as fotos reais do produto.

## Referência visual e revisão

A galeria de tipografia citada no `SKILL.md` pertence ao projeto original e é fornecida à parte. Você pode anexar sua própria referência de estilo e indicar que ela deve ser usada.

Antes de publicar, confira modelo, quantidade, dimensões, textos e encaixes. Use apenas características e vantagens demonstráveis.
