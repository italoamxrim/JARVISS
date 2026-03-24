# JARVIS - Assistente Virtual para Ubuntu

JARVIS é um projeto simples no terminal para personalização do Linux Ubuntu.

<div align="center">
  <img width="415" height="581" alt="Captura de ecrã de 2026-03-24 20-17-40" src="https://github.com/user-attachments/assets/a3b4f036-6f86-481f-a21d-d6ec4e9fbd95" />
</div>

---

## 📋 Sobre o Projeto

JARVIS é um assistente virtual desenvolvido em **Shell Script** que traz uma experiência interativa e personalizada para o terminal do Ubuntu, com animações, cores e efeitos visuais.

---

## 🚀 Funcionalidades

- Interface colorida no terminal
- Animação de inicialização
- Efeitos de carregamento simulados
- Integração com FastFetch
- Sistema de autenticação visual

---

## 📦 Instalação

```bash
# Clone o repositório
git clone https://github.com/seu-usuario/jarvis.git

# Entre na pasta
cd jarvis

# Dê permissão de execução
chmod +x jarvis.sh
chmod +x animacao.sh

# Execute o assistente principal
./jarvis.sh

# Execute a animação
./animacao.sh

#!/bin/bash

# Limpa a tela
clear

# Cores personalizadas
VERDE="\033[0;32m"
AZUL="\033[0;34m"
CIANO="\033[0;36m"
ROXO="\033[0;35m"
RESET="\033[0m"

# Efeito de inicialização
echo -e "${AZUL}"
echo "╔════════════════════════════════════════╗"
echo "║     INICIALIZANDO SISTEMA AMXRIM       ║"
echo "╚════════════════════════════════════════╝"
echo -e "${RESET}"
sleep 1

# Carregamento de módulos
echo -e "${VERDE}[OK]${RESET} Carregando kernel modules..."
sleep 0.8
echo -e "${VERDE}[OK]${RESET} Inicializando interface gráfica..."
sleep 0.8
echo -e "${VERDE}[OK]${RESET} Conectando aos servidores..."
sleep 0.8
echo -e "${VERDE}[OK]${RESET} Estabelecendo conexão segura..."
sleep 0.8
echo -e "${CIANO}[INFO]${RESET} Verificando integridade do sistema..."
sleep 0.8
echo -e "${CIANO}[INFO]${RESET} Autenticando usuário: ${ROXO}amxrim${RESET}"
sleep 1

# Linha separadora
echo "----------------------------------------"
sleep 0.5

# Executa o fastfetch
fastfetch

# Mensagem final
echo ""
echo -e "${VERDE}Sistema ${ROXO}Amxrim${VERDE} carregado. Aguardando comandos, Comandante.${RESET}"
echo ""

#!/bin/bash
echo -e "\033[1;32m"
echo "=============================="
echo "  INICIALIZANDO SISTEMA AMXRIM"
echo "=============================="
echo -e "\033[0m"
for i in $(seq 1 500); do
    printf ":l%08d\n" $i
    sleep 0.01
done
echo -e "\n\033[1;32mSISTEMA PRONTO.\033[0m"
exec bash
```

📌 Status do Projeto

- Em desenvolvimento - Este projeto ainda está em melhoria e novas funcionalidades serão adicionadas em breve.

👤 Autor
Amxrim
