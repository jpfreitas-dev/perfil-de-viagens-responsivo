# Travelgram - Perfil de Viagens Responsivo

O **Travelgram** é uma página de perfil de usuário focada em compartilhar experiências de viagens, desenvolvida como parte da trilha Full-stack da **Rocketseat**. O projeto simula uma rede social de fotografias, onde o grande desafio foi criar uma interface extremamente limpa, semântica e totalmente adaptável a qualquer dispositivo.

## 🛠️ Tecnologias e Metodologias

Este projeto foi construído utilizando as melhores práticas de desenvolvimento Front-end moderno:

- **HTML5 Semântico**: Uso de tags como `header`, `nav`, `main` e `footer` para garantir acessibilidade e uma estrutura de dados clara.
- **CSS Modular (@import)**: Organização do estilo em múltiplos arquivos específicos (`header.css`, `main.css`, `utility.css`, etc.), centralizados em um arquivo `index.css`. Isso facilita a manutenção e evita o crescimento desordenado do código.
- **Arquitetura de Variáveis (Custom Properties)**: Centralização de cores, fontes e espaçamentos no arquivo `global.css`, permitindo alterações de design em todo o projeto através de um único local.
- **Utility-First CSS**: Criação de classes utilitárias (como `.flex`, `.items-center`, `.gap-1`) para promover a reutilização de código e manter a consistência visual.

## Destaques da Responsividade

O foco principal do projeto foi a transição fluida entre mobile e desktop:

- **Flexbox Adaptável**: Uso de `flex-wrap: wrap` e `justify-content: center` na galeria para garantir que as imagens se reorganizem sozinhas conforme o tamanho da tela.
- **Cálculo de Grid no Desktop**: Em telas maiores que `80rem`, foi aplicada uma lógica de 4 colunas perfeitamente alinhadas com `gap: 24px`, garantindo a simetria visual.
- **Imagens Inteligentes**: Uso de `object-fit: cover` e `aspect-ratio: 1 / 1` para que todas as fotos de viagem permaneçam quadradas e sem distorção, independentemente da proporção original da imagem.
- **Navegação Dinâmica**: O menu superior adapta seus itens (escondendo ou exibindo textos e ícones) para priorizar o espaço em telas menores.

## 📂 Organização de Arquivos

```text
├── assets/          # Logos, ícones e imagens de viagem
├── styles/          # CSS separado por módulos
│   ├── global.css   # Variáveis e resets
│   ├── utility.css  # Classes utilitárias reutilizáveis
│   ├── header.css   # Estilos do perfil e cabeçalho
│   └── ...          # Outros módulos
└── index.html       # Estrutura principal
```

## Visualização
Você pode visualizar o projeto finalizado através do link abaixo:

🔗 [Visualizar Projeto Online (GitHub Pages)](https://jpfreitas-dev.github.io/perfil-de-viagens-responsivo/)
