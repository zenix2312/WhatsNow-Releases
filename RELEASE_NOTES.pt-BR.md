# WhatsNow v0.5.0-beta.2 — Notas da versão

**Idioma:** [English](RELEASE_NOTES.md) | [Português (Brasil)](RELEASE_NOTES.pt-BR.md)

Versão beta experimental para Samsung Galaxy com recursos tecnicamente compatíveis de notificações na Now Bar.

## O que mudou

- Atualização da versão do módulo para `v0.5.0-beta.2` (`versionCode=57`).
- Atualização das referências de versão nos scripts de instalação e execução.
- Mantenedor/autor: `zenix2312`.
- Sem mudanças nos binários DEX/APK ou no comportamento principal das notificações em relação à beta.1.

## Funcionalidades

- Verificação de recursos do firmware, sem limitar a uma lista fixa de aparelhos.
- Adaptação de notificações do WhatsApp usando caminhos disponíveis no sistema.
- Agrupamento e expansão das conversas quando suportados.
- Verificações de segurança e diagnósticos na tela **Ação** do módulo.

## Limitações conhecidas

- A resposta diretamente dentro do cartão permanece desativada para preservar a estabilidade do SystemUI.
- Históricos com mensagens longas podem ser truncados.
- Há validação confirmada somente no Galaxy A07 / Android 16 / One UI 8.5 / KernelSU. Outros aparelhos ainda são experimentais.

## Instalação

Baixe `WhatsNow_v0.5.0-beta.2.zip` e o arquivo `.sha256` correspondente na [página v0.5.0-beta.2](https://github.com/zenix2312/WhatsNow-Releases/releases/tag/v0.5.0-beta.2). Confira a integridade e mantenha backup e método de recuperação.

**Distribuição:** o código-fonte original é privado. O módulo público inclui os binários e scripts necessários à instalação e execução. Consulte os [termos](TERMS.md).
