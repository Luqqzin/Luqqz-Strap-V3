<div align="center">

# ⚡ LuqqzStrap

**Bootstrapper e otimizador para Roblox** — gerencie FastFlags, presets de performance, contas e muito mais em uma interface moderna.

[![Release](https://img.shields.io/github/v/release/Luqqzin/Luqqz-Strap-V3?style=for-the-badge&color=6C5CE7&label=Vers%C3%A3o)](https://github.com/Luqqzin/Luqqz-Strap-V3/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/Luqqzin/Luqqz-Strap-V3/total?style=for-the-badge&color=00C896&label=Downloads)](https://github.com/Luqqzin/Luqqz-Strap-V3/releases)
[![Platform](https://img.shields.io/badge/Plataforma-Windows-0078D6?style=for-the-badge&logo=windows)](https://github.com/Luqqzin/Luqqz-Strap-V3/releases/latest)
[![License](https://img.shields.io/badge/Licen%C3%A7a-MIT-blue?style=for-the-badge)](LICENSE)

[📥 Baixar](#-download) • [✨ Funcionalidades](#-funcionalidades) • [🚀 Instalação](#-instalação) • [🛠️ Build](#️-build-a-partir-do-código) • [❓ FAQ](#-perguntas-frequentes)

</div>

---

## 📖 Sobre

**LuqqzStrap** é um bootstrapper alternativo para o Roblox: em vez de abrir o jogo direto pelo cliente padrão, ele te dá controle total sobre **FastFlags**, presets de gráficos/performance, múltiplas contas e várias ferramentas de conveniência — tudo isso sem precisar mexer manualmente em arquivos de configuração.

> ⚠️ Este projeto **não é afiliado, endossado ou patrocinado pela Roblox Corporation**. Use por sua conta e risco e sempre respeitando os Termos de Serviço do Roblox.

---

## ✨ Funcionalidades

- 🚩 **Gerenciador de FastFlags** — ative, desative e edite flags individualmente, com detecção automática de tipo (bool/int/float/string)
- 🎯 **Presets prontos** — perfis como *Ultra FPS*, *Competitivo (Zero Delay)* e *Qualidade Gráfica Máxima*, além de presets da comunidade
- 🔄 **Watchdog / aplicação em tempo real** — reaplica as flags automaticamente enquanto o Roblox está aberto
- 👥 **Múltiplas contas e multi-instância** — jogue com mais de uma conta ao mesmo tempo
- 💾 **Backup e restauração** — histórico de alterações e presets customizados salvos localmente
- 🖥️ **Integração com Discord** — Rich Presence e bot complementar
- 📊 **Logs e diagnóstico** — acompanhe tudo o que está sendo aplicado, com histórico de sessões
- ⌨️ **Atalhos de teclado (hotkeys)** e personalização de tema/UI

---

## 📥 Download

Baixe sempre a versão mais recente na página de **[Releases](https://github.com/Luqqzin/Luqqz-Strap-V3/releases/latest)** — não use o código-fonte cru como se fosse o instalador.

| Arquivo | Descrição |
|---|---|
| `LuqqzStrapSetup.exe` | Instalador oficial para Windows (recomendado) |

---

## 🚀 Instalação

1. Vá até a aba **[Releases](https://github.com/Luqqzin/Luqqz-Strap-V3/releases/latest)** deste repositório
2. Baixe o instalador `.exe` da versão mais recente
3. Execute o instalador e siga o assistente
4. Abra o LuqqzStrap e configure suas FastFlags/presets preferidos
5. Clique em **Aplicar no Roblox** e jogue normalmente

> O Windows Defender/SmartScreen pode alertar por ser um app pouco distribuído ainda — isso é esperado para instaladores sem certificado EV, não significa vírus.

---

## 🛠️ Build a partir do código

Pré-requisitos: **.NET 8 SDK**

```bash
git clone https://github.com/Luqqzin/Luqqz-Strap-V3-SRC.git
cd Luqqz-Strap-V3-SRC
dotnet restore
dotnet build -c Release
```

Para gerar o instalador Windows, use o script/`.iss` (Inno Setup) presente em `installer/`.

---

## 📁 Estrutura do projeto

```
├── src/
│   ├── LuqqzStrap/              # App principal (WPF, Windows)
│   ├── LuqqzStrap.Core/         # Lógica compartilhada (models, services)
│   ├── LuqqzStrap.UI.Avalonia/  # UI multiplataforma (em desenvolvimento)
│   └── LuqqzStrap.Platform.Linux/
├── backend/                     # Bot do Discord e serviço de IA
├── android/                     # App companion (em desenvolvimento)
├── installer/                   # Script do instalador (Inno Setup)
├── website/                     # Site e painel web
└── tests/                       # Testes automatizados
```

---

## ❓ Perguntas frequentes

**O LuqqzStrap é seguro?**
O projeto é open-source — qualquer pessoa pode auditar o código-fonte neste repositório.

**Preciso desinstalar o Bloxstrap/outro bootstrapper antes?**
Não é obrigatório, mas evite rodar dois bootstrappers apontando para a mesma instalação ao mesmo tempo.

**Onde reporto bugs ou sugiro features?**
Abra uma [Issue](https://github.com/Luqqzin/Luqqz-Strap-V3/issues) neste repositório.

---

## 🤝 Contribuindo

Pull requests são bem-vindos! Para mudanças grandes, abra uma Issue antes para discutirmos o que você quer alterar.

## 📄 Licença

Distribuído sob a licença MIT. Veja [`LICENSE`](LICENSE) para mais detalhes.

---

<div align="center">
Feito com 💜 por <a href="https://github.com/Luqqzin">Luqqzin</a>
</div>
