# 🛒 Carrinho do Rancho

**Carrinho do Rancho** é um site leve e prático para auxiliar nas compras do mês, permitindo ao usuário marcar os itens que já pegou no mercado, separados por categorias. O projeto foi feito com foco em simplicidade e usabilidade, principalmente em dispositivos móveis.

---

## 📄 Páginas

### 1. `index.html` – Página Principal

A página principal contém:

- ✅ **Listas de compras organizadas por categorias** (alimentos, higiene, limpeza, etc.)
- 📌 **Checkboxes interativos** para marcar os itens adquiridos.
- 📱 **Layout responsivo**, ideal para celulares.
- 🧹 **Botão "Limpar Marcações"**, que redireciona para uma página de confirmação antes de limpar os dados.

### 2. `confirmacao.html` – Página de Confirmação

Essa página previne exclusões acidentais:

- ⚠️ Exibe **mensagem de confirmação**.
- 🔁 Botão **"Sim"**: limpa todos os itens marcados (via `localStorage`) e retorna à página principal.
- ❌ Botão **"Cancelar"**: volta para a página principal sem apagar nada.

---

## 💡 Tecnologias Utilizadas

- HTML5  
- CSS3  
- JavaScript Puro (Vanilla JS)  
- `localStorage` para salvar temporariamente os itens marcados

---

## 🚀 Como Usar

1. Abra `index.html` no navegador (preferencialmente no celular).
2. Marque os itens conforme for pegando no mercado.
3. Ao final, se quiser apagar tudo e recomeçar, clique em **"Limpar Marcações"**.
4. Confirme ou cancele na página seguinte.

---

## ☁️ Deploy (Hospedagem)

Você pode hospedar o site de forma gratuita no [GitHub Pages](https://pages.github.com/) ou serviços como Netlify e Vercel. Para GitHub Pages:

1. Faça o upload dos arquivos `index.html`, `confirmacao.html` e da pasta `css/` para um repositório.
2. Vá em **Settings > Pages** e selecione a branch com os arquivos.
3. Pronto! O site estará acessível por um link público.

---

## 📈 Melhorias Futuras

- 🔍 Barra de busca por item
- 📝 Permitir adicionar itens personalizados dinamicamente
- ☁️ Sincronização em nuvem com login
- 🖼️ Ícones ilustrativos por categoria
- 🎨 Tema claro/escuro com troca automática
- 🗂️ Filtragem por categoria ou prioridade

---

## 👨‍💻 Autor

- **João Lopes**  
  Bacharel em Ciência da Computação  
  Desenvolvedor apaixonado por praticidade, design simples e soluções que realmente ajudam no dia a dia.
