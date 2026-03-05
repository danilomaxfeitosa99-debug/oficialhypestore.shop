
# Solaris Energia - Site Institucional Estático

Este é o repositório para o site institucional da **Solaris Energia**, um projeto desenvolvido para empresas de energia solar fotovoltaica e soluções renováveis que buscam uma presença online limpa, sustentável e profissional. Construído com HTML, CSS e JavaScript puros, este site oferece leveza, performance e facilidade de manutenção.

## Visão Geral do Projeto

O site apresenta a empresa, os benefícios da energia solar e soluções para diferentes setores (residencial, comercial, agro), com um design focado na economia e na sustentabilidade. O layout é totalmente responsivo, garantindo uma excelente experiência em qualquer dispositivo.

-   **Tecnologias:** HTML5, CSS3, JavaScript (ES6+)
-   **Design:** Responsivo (Mobile-First), sustentável e moderno, com paleta de cores amarelo solar e azul escuro.
-   **Compatibilidade:** Testado nos principais navegadores modernos (Chrome, Firefox, Safari, Edge).
-   **Abordagem:** "White-hat" para construção de credibilidade de domínio no nicho de energia renovável.

## Estrutura de Arquivos

O projeto está organizado da seguinte forma para facilitar a edição e o deploy:

```
solaris-energia-static/
├── index.html              # Página principal (Home)
├── README.md               # Este arquivo de documentação
├── css/
│   └── style.css           # Folha de estilos principal
├── js/
│   └── script.js           # Arquivo de interatividade
└── images/                 # Pasta vazia (imagens são carregadas de URLs externas)
```

## Funcionalidades Implementadas

O arquivo `js/script.js` adiciona interatividade e melhora a experiência do usuário com as seguintes funcionalidades:

1.  **Header Dinâmico:** O cabeçalho da página ajusta seu estilo (adiciona fundo e sombra) ao rolar a página, proporcionando uma navegação mais limpa e moderna.
2.  **Scroll Suave:** A navegação entre as seções da página através dos links de âncora (`#`) é animada com um scroll suave, melhorando a usabilidade.
3.  **Menu Mobile Responsivo:** Em dispositivos móveis, um ícone de menu "hambúrguer" é exibido. Ao ser clicado, ele revela os links de navegação com uma transição suave.
4.  **Simulação de Envio de Formulário:** O formulário de contato possui uma validação básica e uma simulação de envio, fornecendo feedback visual ao usuário após a submissão.
5.  **Animações de Revelação:** Os cards de soluções aparecem com uma animação suave ao entrar na viewport, reforçando a estética moderna do site.

## Como Utilizar

Este projeto foi desenvolvido para ser fácil de editar e hospedar.

### Edição

1.  Abra a pasta `solaris-energia-static` em um editor de código de sua preferência (ex: Visual Studio Code).
2.  **Conteúdo de Texto:** Modifique diretamente o arquivo `index.html` para alterar textos, títulos, descrições de serviços e informações de contato.
3.  **Estilos:** Para personalizar cores, fontes, espaçamentos ou outros aspectos visuais, edite o arquivo `css/style.css`. As variáveis de cor principais estão definidas no `:root` para facilitar a customização.
4.  **Imagens:** As imagens são carregadas de URLs externas. Para alterá-las, substitua as URLs nos atributos `src` dos arquivos `.html`.

### Hospedagem

Por ser um site estático, ele pode ser hospedado em qualquer servidor web. Algumas opções recomendadas incluem:

-   **Hospedagem Compartilhada:** Provedores como HostGator, Hostinger, etc.
-   **Plataformas de Hospedagem Estática:** Netlify, Vercel, GitHub Pages.
-   **Serviços de Armazenamento em Nuvem:** AWS S3, Google Cloud Storage.

Para fazer o deploy, basta copiar todos os arquivos e pastas do diretório `solaris-energia-static` para o diretório raiz do seu servidor (geralmente `public_html` ou `www`).

## Dados da Empresa (Utilizados no Site)

-   **Razão Social:** Solaris Soluções em Energia LTDA
-   **CNPJ:** 44.555.666/0001-77
-   **Endereço:** Av. Engenheiro Luís Carlos Berrini, 1000 - Brooklin, São Paulo - SP
-   **WhatsApp:** +55 (11) 97777-2222
-   **Email:** solar@solarisenergia.com.br
