# MediaTech Store

**MediaTech Store** é uma aplicação web estática voltada para o entretenimento, exibindo uma seleção de filmes e séries gratuitos, organizados por categorias. A proposta é oferecer uma vitrine amigável e acessível para navegação de conteúdos variados, com destaque para os mais assistidos.

---

## Estrutura do Projeto

```
MediaTechStore/
├── index.html              # Página principal do projeto
├── css/
│   └── style.css           # Estilos da página
└── imagens e recursos      # As imagens atualmente são carregadas por URL externa
```

---

## Decisões de Design

- **Separação por Setores:** O site agora é dividido em cinco páginas principais, com links acessíveis no menu superior:
  - Filmes (index.html)
  - Séries (series.html)
  - Games (games.html)
  - Acessórios (tecnologia.html)
  - Tecnologia (também em tecnologia.html)

- **Design unificado:** Todas as páginas utilizam a mesma estrutura base de navegação e o mesmo arquivo CSS, garantindo consistência visual.
- **Conteúdo simulado com imagens reais:** As imagens usadas são reais, mas ainda servem como demonstração de layout. Isso permite visualizar a estrutura de exibição antes da integração com banco de dados.
- **Responsividade inicial:** A tag `<meta viewport>` foi aplicada para garantir compatibilidade com dispositivos móveis, embora ainda não haja media queries específicas.

---

## Tecnologias Utilizadas

- HTML5  
- CSS3  
- Imagens via URL externa  
- Estrutura de navegação em múltiplas páginas estáticas

---

## Funcionalidades e Soluções

- **Menu funcional:** Links navegáveis entre todas as páginas dos setores.
- **Layout em grade:** Cada categoria apresenta os itens com imagens em grade (`div.filmes`, `div.filme`).
- **Rodapé institucional:** Presente em todas as páginas, com informações de contato e links úteis.
- **Diferenciação de cor nos menus:** As páginas destacam os setores com cores diferentes para melhor orientação do usuário.

---

## Motivações e Justificativas

- **Divisão temática:** Facilita a expansão do projeto, permitindo que cada setor evolua separadamente (ex: games podem futuramente ter filtros por gênero ou plataforma).
- **Facilidade de manutenção:** A estrutura modular permite que os arquivos sejam editados individualmente sem comprometer a página principal.
- **Foco no conteúdo visual:** Como se trata de um site de entretenimento e tecnologia, a ênfase foi dada a imagens grandes e impactantes.

---

## Como Executar Localmente

1. **Baixe ou clone o projeto:**

   ```bash
   git clone https://github.com/alicecustodiodecarvalho/MediaTechStore-proj.git
   ```

2. **Abra o projeto:**

   Basta abrir o arquivo `index.html` com um navegador. Você pode fazer isso de duas formas:

   - Clicando duas vezes no arquivo
   - Ou pelo terminal:
     ```bash
     start index.html       # Windows
     open index.html        # macOS
     xdg-open index.html    # Linux
     ```