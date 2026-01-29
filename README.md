# GFTEAM - Centro de Treinamento de Jiu Jitsu

Site de apresentação para o centro de treinamento de jiu jitsu GFTEAM, desenvolvido em HTML, CSS e JavaScript puro.

## 📁 Estrutura do Projeto

```
gfteam-simple/
├── index.html          # Arquivo principal HTML
├── css/
│   └── styles.css      # Estilos CSS completos
├── js/
│   └── script.js       # JavaScript para interatividade
├── images/             # Pasta com imagens
│   ├── logo-gfteam.jpg
│   ├── hero-jiu-jitsu.jpg
│   ├── training-group.jpg
│   ├── belt-progression.jpg
│   ├── professor-nicolas.jpg
│   └── professor-bruno.jpg
└── README.md           # Este arquivo
```

## 🚀 Como Usar

### Opção 1: Abrir Diretamente no Navegador

1. Descompacte os arquivos
2. Clique duas vezes em `index.html`
3. O site abrirá no seu navegador padrão

### Opção 2: Usar um Servidor Local (Recomendado)

#### Com Python 3:
```bash
python -m http.server 8000
```
Acesse: `http://localhost:8000`

#### Com Python 2:
```bash
python -m SimpleHTTPServer 8000
```
Acesse: `http://localhost:8000`

#### Com Node.js (http-server):
```bash
npx http-server
```
Acesse: `http://localhost:8080`

#### Com PHP:
```bash
php -S localhost:8000
```
Acesse: `http://localhost:8000`

## 🎨 Design

- **Cores Principais:** Verde (#228B22) e Branco
- **Tipografia:** Montserrat (títulos) e Open Sans (corpo)
- **Estilo:** Modernismo Esportivo Minimalista
- **Características:** Linhas diagonais, cards com hover effects, animações suaves

## 📱 Responsividade

O site é totalmente responsivo e funciona perfeitamente em:
- Desktop
- Tablet
- Mobile

## 🔧 Personalização

### Alterar Cores

Abra `css/styles.css` e procure pela seção `:root`:

```css
:root {
    --primary-green: #228B22;
    --dark-green: #1a6b1a;
    /* ... outras cores ... */
}
```

### Alterar Informações de Contato

Abra `index.html` e procure pela seção `<!-- Footer -->`:

```html
<li>📞 (XX) XXXXX-XXXX</li>
<li>📧 contato@gfteam.com</li>
<li>📍 Rua [Endereço], [Cidade] - [Estado]</li>
```

### Adicionar Novo Professor

Na seção de Professores, copie o bloco de um professor e modifique:

```html
<div class="professor-card">
    <div class="professor-image">
        <img src="images/professor-novo.jpg" alt="Nome do Professor">
    </div>
    <div class="professor-info">
        <h3 class="professor-name">Nome do Professor</h3>
        <p class="professor-belt">Faixa Preta</p>
        <p class="professor-description">Descrição breve.</p>
    </div>
</div>
```

## 📝 Seções do Site

1. **Navegação** - Menu fixo no topo com logo e links
2. **Hero** - Seção de impacto com imagem e CTAs
3. **Sobre** - Apresentação da academia
4. **Aulas** - 3 tipos de aulas (Iniciantes, Intermediário, Avançado)
5. **Progressão** - Jornada das fitas de jiu jitsu
6. **Professores** - Cards com fotos e informações
7. **CTA** - Chamada para ação
8. **Footer** - Informações de contato e links

## 🎯 Funcionalidades

- ✅ Navegação suave (smooth scroll)
- ✅ Hover effects nos cards
- ✅ Animações de entrada
- ✅ Navbar com efeito de sombra ao scroll
- ✅ Totalmente responsivo
- ✅ Sem dependências externas (apenas Google Fonts)

## 📧 Próximos Passos

Para adicionar funcionalidades mais avançadas:

1. **Formulário de Agendamento** - Integrar com serviço de email
2. **Galeria de Fotos** - Adicionar mais imagens de treinamentos
3. **Blog** - Adicionar seção de artigos sobre jiu jitsu
4. **Integração com Redes Sociais** - Links para Instagram, Facebook, etc.
5. **Mapa de Localização** - Integrar Google Maps

## 📄 Licença

Este projeto é fornecido como está para uso pessoal e comercial.

## 👨‍💻 Desenvolvido por

Manus - Assistente de IA

---

**Versão:** 1.0.0  
**Data:** Janeiro 2026
