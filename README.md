# 💻 My Neovim Configuration 🚀

Bem-vindo ao meu setup do **Neovim**! 🌟 Este arquivo contém todos os detalhes das personalizações, plugins e configurações que estou utilizando para otimizar minha experiência de desenvolvimento. Vamos explorar o que torna este setup especial! 😎

---

## ✨ **Destaques do Setup**
- 🖼️ **Tema estiloso**: Horizon e suporte ao tema One Dark.
- 📁 **NERDTree customizado** com ícones incríveis.
- 🛠️ **Autocompletar poderoso** com CoC.
- 🔍 **Busca eficiente** com FZF.
- 🧑‍💻 **Suporte completo para Python e Go**, incluindo formatação automática e integração com ferramentas de linting.
- 📊 **Barra de status personalizada** com informações úteis e ícones.

---

## 🛠️ **Tecnologias e Plugins**
Aqui está a lista de tecnologias e plugins usados no setup:

### **Gerenciamento de Arquivos**
- 📁 [`NERDTree`](https://github.com/preservim/nerdtree): Navegador de arquivos e diretórios.
- 🎨 [`vim-devicons`](https://github.com/ryanoasis/vim-devicons): Adiciona ícones incríveis ao NERDTree.

### **Aparência**
- 🌌 [`onedark.nvim`](https://github.com/navarasu/onedark.nvim): Tema One Dark para Neovim.
- 🌅 [`doom-one.nvim`](https://github.com/NTBBloodbath/doom-one.nvim): Tema inspirado no Doom Emacs.
- 🖌️ [`nvim-web-devicons`](https://github.com/nvim-tree/nvim-web-devicons): Ícones para melhorar a aparência do Neovim.
- 📊 [`lualine.nvim`](https://github.com/nvim-lualine/lualine.nvim): Barra de status personalizável.

### **Autocompletar e Syntax Highlighting**
- 🤖 [`coc.nvim`](https://github.com/neoclide/coc.nvim): Motor de autocompletar baseado em LSP.
- 🖍️ [`vim-polyglot`](https://github.com/sheerun/vim-polyglot): Syntax highlighting para múltiplas linguagens.

### **Linguagens**
- 🐍 Python:
  - 🔧 [`Black`](https://github.com/psf/black): Formatação automática ao salvar.
  - ⚡ [`coc-pyright`](https://github.com/neoclide/coc.nvim): Suporte a linting e autocompletar.
- 🐹 Go:
  - 🚀 [`vim-go`](https://github.com/fatih/vim-go): Ferramentas completas para desenvolvimento Go.

### **Busca e Navegação**
- 🔍 [`fzf`](https://github.com/junegunn/fzf): Busca flutuante e rápida no Neovim.

---

## 📜 **Atalhos Principais**

Aqui estão alguns atalhos úteis que configuramos:

| Atalho         | Ação                                    |
|----------------|-----------------------------------------|
| **Ctrl + O**   | Alternar o NERDTree                    |
| **Ctrl + C**   | Fechar o NERDTree                      |
| **Ctrl + N**   | Mostrar arquivos e pastas ocultos       |
| **Ctrl + F**   | Localizar o arquivo atual no NERDTree   |
| **Leader + R** | Executar código Go                     |
| **Leader + B** | Compilar código Go                     |
| **Leader + T** | Testar código Go                       |

---

## 🛠️ **Como Configurar**

1. **Instale o Neovim**:
   ```bash
   brew install neovim
   ```

2. **Clone o Repositório Nerd Fonts** e instale uma fonte compatível:
   - Recomendo **Hack Nerd Font** ou **MesloLGS NF**:
     [Nerd Fonts GitHub](https://github.com/ryanoasis/nerd-fonts/releases/latest)

3. **Configure o Hyper (ou outro terminal)**:
   Adicione a fonte no arquivo `.hyper.js`:
   ```javascript
   fontFamily: '"Hack Nerd Font", monospace',
   ```

4. **Instale os Plugins no Neovim**:
   Abra o Neovim e execute:
   ```vim
   :PlugInstall
   :PlugUpdate
   ```

5. **Instale Dependências para Python e Go**:
   - Python:
     ```bash
     pip install black
     pip install python-lsp-server
     ```
   - Go:
     ```bash
     go install golang.org/x/tools/gopls@latest
     ```

---

## 🖼️ **Resultado Visual**

Aqui está uma prévia de como o Neovim está configurado: 🎉

![image](https://github.com/user-attachments/assets/d10f972d-7d37-46c0-b661-5270b701f711)
