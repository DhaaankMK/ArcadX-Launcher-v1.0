# ArcadX Launcher — v1.0 (MVP)

> **⚠️ Status do Projeto: Em Desenvolvimento Ativo**
> O ArcadX Launcher é um projeto experimental em constante evolução. Esta versão representa o MVP (Minimum Viable Product) da base sólida do software, focada na arquitetura principal. Recursos adicionais e melhorias visuais estão sendo implementados de forma contínua.

---

ArcadX é um launcher customizado desenvolvido em Python para transformar o seu PC em um verdadeiro "console de mesa". Totalmente navegável por controle (joystick) ou teclado, ele traz uma experiência moderna inspirada no Steam Big Picture, unindo a praticidade do ambiente de PC com a imersão de uma interface de videogame.

Esta base inicial é estruturada em três pilares principais: **interface moderna**, **navegação por controle/teclado** e **execução segura de jogos**.

---

### Onde os dados do usuário ficam salvos

Como o ArcadX foi pensado para ser um **aplicativo de desktop instalado** (e não portátil), os dados gerados pelo usuário ficam isolados e seguros nos diretórios padrão do sistema operacional:

- **Windows**: `%APPDATA%\ArcadX\`
- **macOS**: `~/Library/Application Support/ArcadX/`
- **Linux**: `~/.config/ArcadX/`

Na primeira execução, o app copia os arquivos padrão de configuração para essa pasta de dados.

---

Desenvolvido por DhaaankMK
