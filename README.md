# 💪 Projeto Academia - Landing Page

Uma landing page moderna e responsiva para academia, com foco em apresentar os serviços, treinos, planos e alimentação saudável.

## 📋 Descrição do Projeto

Este projeto é uma página web completa de uma academia, desenvolvida com HTML5 e CSS3. A aplicação possui múltiplas páginas, cada uma com um design consistente porém com paletas de cores diferentes, garantindo uma experiência visual única para cada seção.

### Páginas Incluídas

- **index.html** - Página inicial (Home)
- **sobre.html** - Informações sobre a academia
- **treino-masculino.html** - Programas de treino para homens
- **treino-feminino.html** - Programas de treino para mulheres
- **planos.html** - Planos de associação
- **alimentos-saudaveis.html** - Guia de alimentação saudável

## 🎨 Estrutura e Estilo

### Arquitetura de CSS

Todas as páginas compartilham a mesma estrutura e estilo base:
- **css/style.css** - Estilos principais e globais
- **css/style-treinos-masculinos.css** - Paleta de cores para treino masculino
- **css/style-treinos-femininos.css** - Paleta de cores para treino feminino
- **css/style-planos.css** - Paleta de cores para planos
- **css/style-alimentos.css** - Paleta de cores para alimentação
- **css/style-sobre.css** - Paleta de cores para sobre

### Design Responsivo

O projeto utiliza:
- Flexbox para layouts flexíveis
- Media queries para responsividade em diferentes dispositivos
- Paletas de cores customizadas para cada seção
- Transições suaves (0.2s linear)
- Tipografia consistente em todas as páginas

### Recursos Visuais

- Imagens de fundo temáticas
- Logo da academia
- Componentes visuais para cada seção
- Design moderno com fundo escuro

## 🚀 Como Rodar Localmente

### Requisitos

- Navegador web moderno (Chrome, Firefox, Edge, Safari)
- Nenhuma dependência externa necessária

### Passos para Executar

1. **Clone ou baixe o repositório:**
   ```bash
   git clone <url-do-repositorio>
   cd "Projeto academia"
   ```

2. **Abra o arquivo index.html no navegador:**
   - **Opção 1:** Duplo clique no arquivo `index.html`
   - **Opção 2:** Clique com botão direito no arquivo e selecione "Abrir com" → seu navegador preferido
   - **Opção 3:** Use um servidor local

3. **Usando um Servidor Local (Recomendado):**

   **Com Python 3:**
   ```bash
   python -m http.server 8000
   ```
   Acesse: `http://localhost:8000`

   **Com Python 2:**
   ```bash
   python -m SimpleHTTPServer 8000
   ```
   Acesse: `http://localhost:8000`

   **Com Node.js (http-server):**
   ```bash
   npx http-server
   ```
   Acesse: `http://localhost:8080`

   **Com Live Server (VS Code Extension):**
   - Instale a extensão "Live Server"
   - Clique com botão direito em `index.html`
   - Selecione "Open with Live Server"

## 📁 Estrutura de Arquivos

```
Projeto academia/
├── README.md                          # Este arquivo
├── index.html                         # Página inicial
├── sobre.html                         # Sobre a academia
├── treino-masculino.html              # Treinos para homens
├── treino-feminino.html               # Treinos para mulheres
├── planos.html                        # Planos de associação
├── alimentos-saudaveis.html          # Guia de alimentação
├── css/
│   ├── style.css                      # Estilos base
│   ├── style-treinos-masculinos.css   # Tema treino masculino
│   ├── style-treinos-femininos.css    # Tema treino feminino
│   ├── style-planos.css               # Tema planos
│   ├── style-alimentos.css            # Tema alimentação
│   └── style-sobre.css                # Tema sobre
├── images/
│   ├── Logo.png                       # Logo da academia
│   ├── Fundo-home.png                 # Imagem de fundo home
│   └── ...                            # Outras imagens
└── .git/                              # Controle de versão
```

## 🎯 Funcionalidades

✅ Navegação entre páginas
✅ Design responsivo para mobile e desktop
✅ Paletas de cores customizadas por seção
✅ Apresentação de treinos
✅ Planos de associação
✅ Guia de alimentação saudável
✅ Informações sobre a academia
✅ Seção de benefícios

## 💻 Tecnologias Utilizadas

- **HTML5** - Estrutura semântica
- **CSS3** - Estilização e responsividade
  - Flexbox
  - Media Queries
  - Transições
  - Gradientes lineares

## 📝 Notas Importantes

- O projeto não possui dependências externas
- Todo o conteúdo é estático
- As imagens estão organizadas na pasta `/images`
- Cada página tem seu próprio CSS de tema, permitindo fácil manutenção

## 🔄 Estrutura de Navegação

A navegação está presente em todas as páginas através da barra superior (navbar):
- **Inicio** - Retorna à página inicial
- **Sobre** - Informações da academia
- **Treinos** - Link para seção de treinos na página inicial
- **Planos** - Página de planos de associação

## 📱 Responsividade

O projeto é totalmente responsivo e funciona bem em:
- Dispositivos desktop
- Tablets
- Smartphones

## 👨‍💻 Autor

Euler Rocha dos Santos 

Projeto Academia - Landing Page

## 📄 Licença

Este projeto é fornecido como está. Sinta-se livre para usá-lo e modificá-lo conforme necessário.

---

**Nota:** Para melhor experiência, recomenda-se acessar o projeto através de um servidor local em vez de abrir diretamente o arquivo HTML.
