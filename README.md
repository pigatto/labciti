# LabCITI — UTFPR

> **Laboratório de Computação, Inteligência e Tecnologia da Informação**  
> Universidade Tecnológica Federal do Paraná · Curitiba, PR

---

## 🌐 Site Institucional

Este repositório contém o código-fonte do site institucional do **LabCITI**, desenvolvido em HTML/CSS/JS puro, sem dependências externas (exceto Google Fonts), pronto para hospedagem estática via **GitHub Pages**.

---

## 🚀 Como publicar via GitHub Pages

1. **Clone o repositório** (ou faça upload do arquivo `index.html`):

```bash
git clone https://github.com/labciti-utfpr/labciti-utfpr.github.io
cd labciti-utfpr.github.io
```

2. **Renomeie o arquivo** para `index.html` (se necessário):

```bash
mv labciti-site.html index.html
```

3. **Faça o commit e push**:

```bash
git add index.html
git commit -m "feat: site institucional LabCITI"
git push origin main
```

4. **Ative o GitHub Pages**:
   - Acesse **Settings → Pages**
   - Em *Source*, selecione `main` branch e pasta `/` (root)
   - Salve — o site estará disponível em `https://labciti-utfpr.github.io`

---

## 📁 Estrutura

```
labciti-utfpr.github.io/
│
├── index.html          ← Site completo (single-file, sem dependências)
└── README.md           ← Este arquivo
```

> O site é **single-file**: todo o CSS e JavaScript está embutido no `index.html`. Para adicionar imagens reais da equipe ou logos, crie uma pasta `assets/` e substitua os avatares gerados por código.

---

## 🎨 Seções do site

| Seção | Conteúdo |
|---|---|
| **Hero** | Apresentação do laboratório, animações e estatísticas principais |
| **Sobre** | Histórico, missão e números de impacto |
| **Pesquisa** | 6 linhas de pesquisa com tags e descrições |
| **Publicações** | Seleção de artigos recentes (periódicos, conferências, workshops) |
| **Equipe** | Cards dos membros com link para Lattes |
| **Projetos** | Projetos em andamento e concluídos com fontes de financiamento |
| **Contato** | Formulário de contato e informações institucionais |

---

## ✏️ Como personalizar

Abra o `index.html` em qualquer editor de texto e localize as seções marcadas. Os principais pontos de edição:

### Dados da equipe
Busque por `team-card` e substitua os nomes, cargos e links Lattes:

```html
<div class="team-name">Prof. Dr. Rafael Silva</div>
<div class="team-role">Coordenador</div>
<div class="team-area">IA, Aprendizado Federado, Privacidade</div>
<a href="https://lattes.cnpq.br/SEU_ID" class="team-lattes">Lattes</a>
```

### Publicações
Busque por `pub-card` e atualize os metadados:

```html
<div class="pub-year">2024</div>
<div class="pub-type journal">Periódico</div>
<div class="pub-title">Título do artigo aqui</div>
<div class="pub-authors">Autor1, A.; Autor2, B.</div>
<div class="pub-venue">Nome do Periódico / Conferência, Ano</div>
```

### Contato e endereço
Busque por `contact-item` e atualize e-mail, endereço e links institucionais.

### Cores institucionais
As variáveis CSS estão no topo do `<style>`:

```css
:root {
  --utfpr-yellow: #F5C400;   /* Amarelo UTFPR */
  --utfpr-blue:   #003366;   /* Azul UTFPR    */
  --accent-teal:  #00C4A7;   /* Destaque verde */
  --accent-coral: #FF5C3A;   /* Destaque coral */
}
```

---

## 🛠️ Tecnologias utilizadas

- **HTML5** semântico com acessibilidade básica
- **CSS3** puro — Grid, Flexbox, variáveis CSS, animações e transitions
- **JavaScript** vanilla — IntersectionObserver para animações de scroll
- **Google Fonts** — [Syne](https://fonts.google.com/specimen/Syne) (display) + [DM Sans](https://fonts.google.com/specimen/DM+Sans) (corpo) + [JetBrains Mono](https://fonts.google.com/specimen/JetBrains+Mono) (código)
- **Zero dependências** de frameworks ou bibliotecas externas

---

## 📄 Licença

Este projeto está licenciado sob a [MIT License](LICENSE). Você pode usá-lo, modificar e redistribuir livremente com atribuição.

---

<div align="center">

**LabCITI · UTFPR · Curitiba, PR**  
[labciti.ct.utfpr.edu.br](https://labciti.ct.utfpr.edu.br) · [labciti@utfpr.edu.br](mailto:labciti@utfpr.edu.br)

</div>
