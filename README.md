# 🕯️ Helena Coelho — Landing Page

**Site ao vivo:** https://helanatscoelho.github.io/helena-coelho-lp/

> Gestora · Empreendedora · Missionária

---

## 📁 Estrutura do Repositório

```
helena-coelho-lp/
├── index.html          ← A Landing Page completa
├── assets/
│   └── images/         ← Coloque suas fotos aqui
└── README.md           ← Este guia
```

---

## ✏️ Como Editar

### 1. Trocar ou adicionar sua foto

1. Vá em **Add file → Upload files**
2. Crie a pasta `assets/images/` e suba sua foto (ex: `helena-hero.jpg`)
3. Abra o `index.html` e encontre o comentário:
   ```html
   <!-- FOTO: descomente e coloque o caminho da sua imagem -->
   <!-- <img src="assets/images/helena-hero.jpg" alt="Helena Coelho"> -->
   ```
4. Remova os `<!--` e `-->` para ativar a foto

---

### 2. Atualizar a Agenda de Missão (mensal)

Abra o `index.html` e encontre o bloco com o comentário:
```html
<!-- EDITE OS EVENTOS AQUI MENSALMENTE -->
```

Cada evento tem este formato — copie e cole para adicionar novos:
```html
<div class="event-card">
  <div class="event-date">
    <div class="day">15</div>       <!-- dia -->
    <div class="month">Jun</div>    <!-- mês -->
  </div>
  <div class="event-info">
    <div class="event-name">Nome do Evento</div>
    <div class="event-local">📍 Cidade – Estado</div>
  </div>
  <span class="event-badge confirmado">Confirmado</span>
</div>
```

Para evento "em breve", use: `<span class="event-badge">Em breve</span>`

---

### 3. Alterar textos

Abra o `index.html` diretamente no GitHub:
- Clique no arquivo `index.html`
- Clique no **ícone de lápis** (editar)
- Faça as alterações no texto entre as tags HTML
- Clique em **"Confirmar alterações"**

Principais seções para editar:
| O que editar | Onde encontrar no HTML |
|---|---|
| Título Hero | `<h1 class="hero-title">` |
| Descrição principal | `<p class="hero-desc">` |
| Texto "Sobre" | seção `id="sobre"` |
| Os 3 pilares | seção `id="identidade"` |
| Agenda de missão | seção `id="agenda"` |
| Links de contato | seção `id="contato"` |
| Email de contato | `href="mailto:seuemail@email.com"` |

---

### 4. Adicionar novos links de contato

Encontre este bloco na seção `id="contato"`:
```html
<!-- ADICIONE MAIS LINKS AQUI -->
```

E adicione:
```html
<a href="https://seulink.com" target="_blank" class="link-card">
  <span class="licon">🔗</span> Nome do Link
</a>
```

---

### 5. Subir novas fotos

1. No repositório, clique em **Add file → Upload files**
2. Arraste suas imagens para a pasta `assets/images/`
3. Clique em **Commit changes**
4. No `index.html`, referencie com: `src="assets/images/nome-da-foto.jpg"`

---

## 🌐 Publicação

O site é publicado automaticamente no GitHub Pages toda vez que você salvar mudanças no `index.html`.

**URL do site:** `https://helanatscoelho.github.io/helena-coelho-lp/`

Após cada edição, aguarde ~1 minuto para o site atualizar.

---

## 🎨 Paleta de Cores

| Nome | Código Hex | Uso |
|---|---|---|
| Marrom Café | `#5C3D2E` | Cor principal, títulos |
| Bege | `#F5EFE6` | Fundos de seção |
| Areia | `#E8DDD0` | Bordas e elementos leves |
| Verde Oliva | `#6B7C5C` | Destaques em itálico |
| Dourado | `#C9A84C` | Acentos, labels, botões especiais |
| Off-white | `#FAF7F4` | Fundo geral |

---

*Gestora · Empreendedora · Missionária — @euhelenacoelhots*
