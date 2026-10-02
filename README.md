# Eco em Foco

Site educativo sobre sustentabilidade, emissões de carbono e impacto social, desenvolvido como atividade acadêmica de Front-End.

## Identificação

- **Equipe:** Eco em Foco

- **Projeto:** Eco em Foco — sustentabilidade, carbono e impacto social

- **Integrante:** Larissa Penha Francisco

- **Curso:** Engenharia de Software

- **Instituição:** UNICID

- **Disciplina:** Atividade A2 — Front-End

- **Data:** 25/09/2026

## Sobre o projeto

O projeto aborda a relação entre emissões de carbono, mudanças climáticas, sustentabilidade e impacto social. O tema é relevante porque as escolhas de consumo, energia e mobilidade, assim como o uso dos recursos naturais, afetam o meio ambiente e a qualidade de vida das pessoas.

O site apresenta informações educativas em linguagem simples, incentiva atitudes responsáveis e destaca que a sustentabilidade também envolve inclusão, acessibilidade e participação social.

### Objetivos

**Objetivo geral:** criar um site educativo, acessível e responsivo sobre sustentabilidade, emissões de carbono e impacto social.

**Objetivos específicos:**

- Explicar conceitos ambientais de forma clara.

- Apresentar dados, tabelas, notícias e fontes de consulta.

- Divulgar projetos relacionados à sustentabilidade.

- Aplicar recursos de acessibilidade e navegação por teclado.

- Demonstrar conhecimentos de HTML5, CSS3 e organização de projetos Front-End.

### Público-alvo

O site é voltado a estudantes, professores e pessoas interessadas em meio ambiente, clima e responsabilidade social. O conteúdo considera usuários de diferentes idades e níveis de conhecimento técnico, incluindo pessoas com deficiência como público prioritário.

## Páginas do site

O site possui dez páginas navegáveis, com navegação principal compartilhada, além de formulário de contato, galeria, recursos multimídia e notícias.

| Arquivo | Conteúdo |
| --- | --- |
| `index.html` | Apresentação do projeto, resumo do tema e menu principal. |
| `Sobre.html` | História, missão, visão e valores. |
| `projetos.html` | Projetos de sustentabilidade e impacto social. |
| `impacto.html` | Dados, indicadores, tabelas e resultados. |
| `acessibilidade.html` | Medidas de inclusão para pessoas com deficiência. |
| `galeria.html` | Imagens com legendas, créditos e fontes. |
| `midia.html` | Vídeo, áudio e iframe. |
| `noticias.html` | Notícias, artigos e referências. |
| `contato.html` | Dados fictícios, integrantes e formulário validado. |
| `orcamento_hospedagem.html` | Comparação de opções de hospedagem e domínio. |

### Mapa do site

```
Início
├── Sobre
├── Projetos
├── Impacto
├── Acessibilidade
├── Galeria
├── Mídia
├── Notícias
├── Contato
└── Orçamento de hospedagem
```

Todas as páginas dão acesso ao menu principal e ao rodapé com links de navegação.

## Tecnologias e ferramentas

- HTML5 semântico.

- CSS3 com variáveis, layouts responsivos e media queries.

- Elementos nativos de mídia: `<video controls poster>`, `<audio controls>` e `<iframe>`.

- Validação nativa de formulários HTML5, com atributos como `required`, `type="email"`, `type="tel"`, `type="date"`, `type="number"` e `pattern`.

- Visual Studio Code.

- Microsoft Edge para testes locais.

- Verificações estruturais e visuais do projeto.

A navegação principal não depende de JavaScript.

## Requisitos não funcionais

- **Acessibilidade:** textos alternativos, contraste, foco visível, navegação por teclado, `lang="pt-BR"` e atributos ARIA quando necessários.

- **Sustentabilidade:** conteúdo educativo, imagens com fontes identificadas e proposta de hospedagem de baixo custo.

- **Responsividade:** adaptação a celulares, tablets e computadores.

- **Desempenho:** CSS compartilhado, estrutura simples e uso de imagens limitado ao necessário.

- **SEO básico:** títulos descritivos, meta descriptions e hierarquia adequada de headings.

- **Semântica:** uso de elementos como `header`, `nav`, `main`, `section`, `article` e `footer`, além de headings de `h1` a `h3`.

## Identidade visual e conteúdo

O tom de voz é educativo, direto e acolhedor. A paleta combina tons de verde, associados à natureza, e terracota, usado para destacar ações e elementos de chamada. O logotipo textual “eco em foco” aparece no cabeçalho e no rodapé.

Imagens e materiais externos têm créditos ou links para suas fontes nas páginas correspondentes. Os textos foram organizados para fins acadêmicos e educativos.

## Como executar

O projeto pode ser aberto diretamente no navegador ou servido localmente.

### Abrir diretamente

Abra o arquivo `index.html` no navegador.

### Usar um servidor local

Na pasta do projeto, execute:

```bash
python -m http.server 8000
```

Em seguida, acesse [http://localhost:8000](http://localhost:8000).

## Divisão de funções e cronograma

Como o projeto foi desenvolvido individualmente, todas as etapas foram realizadas por Larissa Penha Francisco.

| Etapa | Responsável | Resultado |
| --- | --- | --- |
| Planejamento e escopo | Larissa Penha Francisco | Definição do tema, do público e das páginas. |
| Estrutura HTML | Larissa Penha Francisco | Criação das dez páginas e da navegação. |
| Identidade visual e CSS | Larissa Penha Francisco | Paleta verde e terracota, layout responsivo e comentários didáticos. |
| Conteúdo e fontes | Larissa Penha Francisco | Textos, dados, créditos e referências. |
| Acessibilidade e formulário | Larissa Penha Francisco | Labels, textos alternativos, ARIA, foco e validação HTML5. |
| Testes e documentação | Larissa Penha Francisco | Revisão no navegador, documentação e arquivo compactado. |

## Riscos e restrições

- O projeto é estático e não possui banco de dados nem servidor para envio de formulários.

- Vídeos, áudios e imagens externos dependem de conexão com a internet.

- O prazo acadêmico limita a quantidade de testes automatizados.

- Caso o professor solicite evidências, recomenda-se validar o HTML com o serviço oficial do W3C antes da entrega final.

## Critérios de aceitação

O projeto é considerado pronto quando:

- As dez páginas podem ser acessadas pelo menu.

- O formulário apresenta validação HTML5 funcional.

- A página de mídia contém vídeo, áudio e iframe.

- As imagens têm texto alternativo e fontes identificadas.

- O layout funciona em diferentes tamanhos de tela.

- A navegação pode ser realizada pelo teclado.

- A documentação da pasta `docs/` está completa.

- O projeto está compactado no arquivo `equipe_eco_em_foco.zip`.

## Documentação da entrega

A pasta `docs/` contém:

- `README.md` — identificação, objetivos, escopo e instruções do projeto.

- `diario-de-bordo.md` — decisões, aprendizados e dificuldades.

- `orcamento-hospedagem.md` — estimativas de hospedagem e domínio.

- `evidencias-testes.md` — descrição das verificações realizadas.

## Orçamento de hospedagem e domínio

### Cenário considerado

Site institucional estático, sem banco de dados e sem integrações complexas.

### Comparativo de hospedagem

| Serviço | Tipo | Estimativa | Vantagens |
| --- | --- | --- | --- |
| GitHub Pages | Estática | R$ 0/mês | Gratuita, adequada para HTML e CSS e integrada ao GitHub. |
| Netlify | Estática | R$$ 0 a R$$ 30/mês | Publicação simples, HTTPS e integração contínua. |
| Hostinger | Compartilhada | R$$ 20 a R$$ 80/mês | Suporte a domínio próprio e painel de hospedagem. |

### Comparativo de domínios

| Extensão | Estimativa anual | Uso recomendado |
| --- | --- | --- |
| `.com.br` | R$$ 40 a R$$ 60/ano | Projeto brasileiro e público nacional. |
| `.site` | R$$ 20 a R$$ 80/ano | Site institucional ou projeto escolar. |
| `.org` | R$$ 60 a R$$ 120/ano | Organizações e projetos sociais ou ambientais. |

### Custos adicionais

- **Manutenção e atualização de conteúdo:** R$$ 0 a R$$ 200 por mês, dependendo da necessidade de suporte externo.

- **Certificado SSL:** geralmente incluído nos serviços atuais ou disponibilizado gratuitamente.

Os valores são estimativas para fins acadêmicos e podem variar conforme o plano, o fornecedor e as promoções vigentes.

### Recomendação

Para este projeto acadêmico, recomenda-se o GitHub Pages, por ser gratuito e suficiente para páginas HTML e CSS. Se for necessário um endereço personalizado, a extensão `.com.br` é adequada ao público brasileiro. O Netlify é uma alternativa para publicação rápida, enquanto a Hostinger oferece mais recursos caso o projeto cresça e precise de hospedagem compartilhada.

## Evidências de testes

### Verificações realizadas

- Navegação principal visível no topo das páginas.

- Logo e menu alinhados corretamente.

- Página inicial seguindo o mesmo padrão estrutural das demais páginas.

- Formulário de contato com labels e validação HTML5 nativa.

- Página de mídia com elementos de vídeo, áudio e iframe.

- Estrutura HTML semântica e recursos básicos de acessibilidade.

### Observações

- Os links e a navegação foram conferidos visualmente.

- A página de contato foi ajustada para remover o estado desativado do formulário.

- A página de mídia foi revisada para incluir mídias com controles nativos do navegador.

## Diário de bordo

### Etapa 1 — Planejamento

- Definição da identidade visual do projeto, com tons de verde e terracota.

- Organização do site em páginas temáticas.

- Priorização da organização visual e da acessibilidade.

### Etapa 2 — Construção do layout

- Criação de cabeçalho, navegação e rodapé compartilhados.

- Ajuste do alinhamento do logo à esquerda e do menu à direita.

- Busca por consistência visual entre as páginas.

### Etapa 3 — Conteúdo e acessibilidade

- Inclusão de textos educativos e explicativos.

- Adição de skip link e navegação por teclado.

- Revisão de contraste e foco visual.

### Etapa 4 — Validação e ajustes finais

- Correção do menu ativo e verificação de sua visibilidade no topo.

- Ajuste do formulário para usar a validação HTML5.

- Inclusão de elementos multimídia com controles nativos.

- Organização da documentação do projeto na pasta `docs/`.

## Entrega

O arquivo compactado para envio é `equipe_eco_em_foco.zip`. A entrega deve ser feita pelo Blackboard, acompanhada dos documentos adicionais solicitados pelo professor.