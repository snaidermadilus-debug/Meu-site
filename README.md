# Meu Site de Jogo 🎮

Este é um **site de jogo** desenvolvido para rodar no **Termux** no celular.  
Ele permite criar e interagir com um jogo simples diretamente no navegador do celular.  
O site usa **HTML, CSS e Python** (para rodar servidor local) e pode ser usado para estudo ou diversão.

              👇


 pkg update -y && pkg upgrade -y && \
 pkg install git python termux-api -y && \
 termux-setup-storage -y && \
 rm -rf Meu-site && \
 git clone https://github.com/snaidermadilus-debug/Meu-site.git && \
 cd Meu-site && \
 python -m http.server 8000


# Acessar no👇 navegador http://localhost:8000



---

## Funcionalidades do Site

- 🔹 **Exibe páginas de jogo** com títulos, textos e imagens.  
- 🔹 **Suporta interação do usuário**, como botões e formulários.  
- 🔹 🔗 **Navegação simples** entre telas do jogo (menu, regras, pontuação).  
- 🔹 🎨 **Design personalizável** com cores e estilo CSS.  
- 🔹 🌍 Pode ser aberto em qualquer navegador do celular via Termux.

---

## 1️⃣ Estrutura Termux + HTML

```bash
pkg update && pkg upgrade -y
pkg install nano -y
pkg install python -y
nano index.html
termux-open index.html
python -m http.server 8080
# Abra: http://localhost:8080


# Criar arquivo
nano index.html

# Rodar servidor local
python -m http.server 8000

# Acessar no navegador
http://localhost:8000

# Para qualquer pessoa baixar e executar tudo de uma vez no Termux

pkg update -y && pkg upgrade -y && \
pkg install git python vim termux-api -y && \
termux-setup-storage -y && \
git clone https://github.com/snaidermadilus-debug/Meu-site.git && \
cd Meu-site && \
python -m http.server 8080
