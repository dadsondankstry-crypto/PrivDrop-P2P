# 📂 PrivDrop P2P

Uma aplicação web progressiva (PWA) leve e segura para transferência de ficheiros ponto a ponto (P2P), inspirada no AirDrop, mas funciona em qualquer dispositivo com um navegador.

![Versão](https://img.shields.io/badge/version-2.0.0-blue)
![Licença](https://img.shields.io/badge/license-MIT-green)

## ✨ Funcionalidades

- **Transferência Direta (P2P):** Os ficheiros não passam por um servidor central; vão diretamente de um dispositivo para o outro via WebRTC.
- **Privacidade:** Sem registos, sem armazenamento na nuvem e totalmente anónimo.
- **PWA (Progressive Web App):** Pode ser instalado no teu telemóvel ou desktop para acesso rápido.
- **Conexão via QR Code:** Basta apontar a câmara para conectar os dois dispositivos instantaneamente.
- **Multifile:** Suporte para envio de múltiplos ficheiros em simultâneo.

## 🚀 Como usar

1.  Aceda ao site num dos dispositivos.
2.  No segundo dispositivo, aceda ao mesmo link ou utilize o botão **"Ler QR Code"** para ler o código gerado no primeiro ecrã.
3.  Uma vez conectados, selecione os ficheiros e clique em **"Enviar Arquivos"**.
4.  O destinatário receberá os ficheiros automaticamente através do navegador.

## 🛠️ Tecnologias Utilizadas

* **PeerJS:** Para facilitar a sinalização WebRTC.
* **QRCode.js:** Para geração dinâmica de códigos QR de conexão.
* **Html5-QRCode:** Para leitura de códigos QR via câmara.
* **Service Workers:** Para suporte offline e funcionalidade PWA.

## 📦 Instalação Local

Se quiseres correr o projeto localmente ou fazer alterações:

1. Clone o repositório:
   ```bash
   git clone [https://github.com/teu-utilizador/PrivDrop-PWA-v2.git](https://github.com/teu-utilizador/PrivDrop-PWA-v2.git)