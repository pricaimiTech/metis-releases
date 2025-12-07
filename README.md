<div align="center">

# 🦉 MÉTIS
### Intelligence for Quality Engineering

**Repositório Oficial de Distribuição**

[![GitHub Release](https://img.shields.io/github/v/release/pricaimiTech/metis-releases?style=for-the-badge&color=blue)](https://github.com/pricaimiTech/metis-releases/releases/latest)
[![Platform](https://img.shields.io/badge/Plataforma-Windows%20%7C%20Mac%20%7C%20Linux-lightgrey?style=for-the-badge)](https://github.com/pricaimiTech/metis-releases/releases/latest)

</div>

---

## 📥 Onde Baixar?

Acesse a aba **[Releases](https://github.com/seu-usuario/metis-releases/releases/latest)** deste repositório para baixar a versão mais recente.

1. Clique em **Releases** no menu lateral (ou no link acima).
2. Na versão mais recente (ex: `v1.0.0`), vá em **Assets**.
3. Baixe o arquivo **`Metis-Installer-vX.X.X.zip`**.

---

## ⚙️ Instalação (Offline)

A Métis é distribuída como um pacote offline para garantir segurança e estabilidade.

### 🪟 Windows
1. Extraia o arquivo `.zip` baixado.
2. Clique com o botão direito no arquivo `instalar.bat`.
3. Selecione **"Executar como Administrador"**.
4. Aguarde a mensagem de sucesso.

### 🍎 macOS / 🐧 Linux
1. Extraia o arquivo `.zip`.
2. Abra o terminal na pasta extraída.
3. Execute os comandos:
   ```bash
   chmod +x instalar.sh
   sudo ./instalar.sh
   ```

## 🚀 Como Usar

Após instalar, o comando `metis` estará disponível globalmente no seu terminal.

### 1\. Inicializar em um Projeto

Vá até a pasta do seu projeto de QA/Dev e rode:

```bash
metis init
```

Você será guiado para escolher seu Agente de IA favorito:

  * **Cursor** (Gera `.cursorrules`)
  * **Claude Code** (Gera `CLAUDE.md`)
  * **VS Code Copilot** (Gera instruções GitHub Copilot)

### 2\. Executar Análises

Abra o chat da sua IDE e utilize os comandos da Métis:

  * **`/analise`**: Analisa o PRD em busca de riscos.
  * **`/estrategia`**: Cria o plano de testes.
  * **`/teste`**: Gera casos de teste detalhados.

-----

## ❓ Solução de Problemas

**Erro: "metis: command not found"**

  * Certifique-se de que rodou o instalador como Administrador/Sudo.
  * No Windows, tente reiniciar o terminal após a instalação.

**Erro: Permissão Negada**

  * Verifique se você tem permissão de escrita na pasta do Node.js ou use `sudo`.

-----
## LEGAL
<div align="center">
  <i>
Qualiters Club® é uma marca registrada.
Copyright © 2025 Qualiters Club. Todos os direitos reservados.</i>
  <br><br>
  <a href="https://github.com/pricaimiTech">
    <img src="https://img.shields.io/badge/Desenvolvido%20por-Qualiters%20Club-black?style=for-the-badge&logo=github" alt="Qualiters Club©">
  </a>
</div>
