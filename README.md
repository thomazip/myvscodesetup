# Minhas Configurações do VS Code

Este repositório armazena minhas configurações personalizadas do Visual Studio Code.

## Estrutura do Repositório

- `settings.json`: Contém minhas configurações principais e mais detalhadas do VS Code.
- `simple ver./settings.json`: Uma versão mais simplificada das minhas configurações, possivelmente para diferentes perfis ou necessidades.

## Configurações Principais (`settings.json`) 

`versão VSCODE`

Este arquivo contém uma personalização extensiva da interface do usuário e do comportamento do editor, incluindo:

- **Tema:** Bearded Theme Monokai Black
- **Interface do Usuário:**
  - Abas do editor: modo "single"
  - Barra de status: oculta
  - Minimapa: desabilitado
  - Breadcrumbs: desabilitados
  - Barra lateral: posicionada à direita
  - Ícones: Material Icon Theme (com setas do explorer ocultas)
  - Nível de zoom: 1
- **Estilo Customizado (custom-ui-style):** Diversas modificações CSS para refinar a aparência de notificações, widgets, barra de título, etc.
- **Fonte do Editor:** JetBrains Mono, tamanho 15, com ligatures habilitadas.
- **Comportamento do Editor:**
  - Salvamento automático: habilitado (após um pequeno atraso)
  - Formatador padrão: rvest.vs-code-prettier-eslint
  - Formatar ao salvar: habilitado
  - Rolagem suave: habilitada
  - Animação suave do cursor: habilitada
- **Outras Configurações:**
  - Desabilitadas recomendações de extensões.
  - Modo de atualização: nenhum.

## Configurações Simplificadas (`simple ver./settings.json`)

`versão VSCODE FORKs`

Esta versão oferece uma configuração mais leve, com foco em:

- **Tema:** Nord
- **Interface do Usuário:**
  - Barra lateral: posicionada à direita
  - Barra de atividades: posicionada no topo
  - Minimapa: desabilitado
  - Barra de status: oculta
  - Breadcrumbs: desabilitados
- **Fonte do Editor:** Cascadia Mono, tamanho 16, com ligatures habilitadas.
- **Comportamento do Editor:**
  - Salvamento automático: habilitado
  - Formatador padrão: esbenp.prettier-vscode (especificamente para JavaScript também)
  - Formatar ao salvar: habilitado
  - Rolagem suave: habilitada
- **Terminal:**
  - Fundo transparente
  - Aceleração de GPU desabilitada

![CleanShot 2025-05-06 at 20 50 46@2x](https://github.com/user-attachments/assets/7641dd0d-3d1d-46f7-942e-05cbb720b959)

    
## Como Usar

1.  Clone este repositório.
2.  Copie o conteúdo do `settings.json` desejado.
3.  No VS Code, abra suas configurações (JSON) através do Command Palette (Cmd/Ctrl + Shift + P) com `Preferences: Open User Settings (JSON)`.
4.  Cole o conteúdo copiado no seu arquivo `settings.json`.

**Observação:** `custom-ui-style`, Depende da extensão "Custom UI Style".
