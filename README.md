# Note Plot — instaladores

Notas em texto puro (`.txt`) organizadas num canvas infinito. Windows e Linux.

Este repositório só guarda os instaladores, publicados automaticamente a cada versão. O código não fica aqui.

## Baixar

Na página de [Releases](https://github.com/rayterion/note-plot-releases/releases/latest):

| Sistema | Arquivo                        | Atualiza sozinho? |
| ------- | ------------------------------ | ----------------- |
| Windows | `note-plot-setup-<versão>.exe` | sim               |
| Linux   | `note-plot-<versão>.AppImage`  | sim               |
| Linux   | `note-plot_<versão>_amd64.deb` | não               |

- **Windows:** sem assinatura de código, o SmartScreen avisa na primeira instalação: **Mais informações → Executar assim mesmo**.
- **AppImage:** salve numa pasta sua (ex.: `~/Apps`), rode `chmod +x` no arquivo e abra. No Ubuntu 22.04+, instale a libfuse2 (`sudo apt install libfuse2t64` no 24.04).
- **.deb:** `sudo apt install ./note-plot_<versão>_amd64.deb`. Para atualizar, baixe e instale o `.deb` da versão nova.
