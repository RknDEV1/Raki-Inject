# Raki — customizações visuais

Esta cópia mantém a lógica nativa do projeto e adiciona uma seção nativa em SwiftUI para escolher fundos animados.

## Alterações

- Nome exibido do produto e da interface: **Raki**.
- Tela `SettingsView` com seção **Fundos animados**.
- Sete GIFs originais preservados em `ThreeOneOSFive/RakiBanners/`.
- Sete vídeos MP4 locais, sem áudio, usados para reprodução contínua e confiável na WebView/AVPlayer do iOS.
- Prévia grande, miniaturas animadas, seleção persistente com `@AppStorage` e reinício ao voltar ao app.
- Créditos e links do Telegram removidos da interface.
- Ícone Raki aplicado ao catálogo `AppIcon.appiconset`.

## Build

A pasta foi preparada para abrir no Xcode. O ambiente Linux usado para editar o repositório não possui Xcode/macOS, então a compilação e a assinatura precisam ser feitas em um Mac com o perfil de assinatura adequado.
