# Terra-Nova — Construindo hoje e preservando o amanhã

Site institucional de uma construtora fictícia com foco em soluções sustentáveis, desenvolvido como **trabalho acadêmico**.
A proposta apresenta projetos residenciais, construção de casas e reformas, com planejamento, uso consciente de recursos e alternativas ecológicas.

> ⚠️ Projeto acadêmico: a empresa, a equipe e os serviços fazem parte de um planejamento de trabalho de faculdade. A imagem principal é uma ilustração conceitual e não representa obras realizadas.

## Seções do site

1. **Início** — apresentação e chamada principal
2. **Essência** — propósito da empresa
3. **Serviços** — projetos residenciais, construção de casas, reformas e acompanhamento
4. **Sustentabilidade** — solo-cimento, concreto de menor impacto, aproveitamento da chuva, conforto e energia, coberturas verdes e gestão de resíduos
5. **Equipe** — estrutura de responsabilidades proposta
6. **Contato** — WhatsApp, telefone e endereço de referência

## Tecnologias

- HTML5 semântico
- CSS3 (`style.css`)
- JavaScript puro (`script.js`) — menu mobile e interações
- Sem frameworks nem dependências externas

## Estrutura de arquivos

```
terra-nova/
├── index.html
├── style.css
├── script.js
├── logo-terra-nova.jpeg
├── hero.webp
├── equipe-1.webp
├── equipe-2.webp
├── equipe-3.webp
├── equipe-4.webp
└── README.md
```

## Como executar

Não há etapa de build. Basta:

1. Clonar o repositório
2. Abrir o `index.html` no navegador

Opcionalmente, para rodar com um servidor local:

```bash
python -m http.server 8000
```

Depois acesse `http://localhost:8000`.

## Acessibilidade e boas práticas

- Link "Pular para o conteúdo" no topo da página
- Textos alternativos descritivos nas imagens
- Navegação com `aria-label` e menu com `aria-expanded`
- Imagens com `width`/`height` definidos e `loading="lazy"` na seção de equipe
- Meta tags de descrição e `theme-color`

## Licença / uso

Material produzido para fins educacionais.
