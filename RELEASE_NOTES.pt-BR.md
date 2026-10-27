# WhatsNow v0.5.0-beta.1 — Notas da versão

**Idioma:** [English](RELEASE_NOTES.md) | [Português (Brasil)](RELEASE_NOTES.pt-BR.md)

Primeira versão beta pública para aparelhos Samsung Galaxy com recursos tecnicamente compatíveis de notificações na Now Bar.

## Recursos incluídos

- Verificação dos recursos disponíveis no firmware, sem limitar o suporte a uma lista fixa de modelos.
- Conversão de notificações do WhatsApp utilizando os caminhos do sistema disponíveis.
- Agrupamento e expansão de conversas quando houver suporte.
- Verificações de segurança em execução e diagnósticos na tela **Ação** do módulo.

## Limitações conhecidas

- Responder diretamente dentro do cartão permanece desativado para preservar a estabilidade do SystemUI.
- Históricos com muitas mensagens longas podem ficar truncados.
- A validação em dispositivo real foi confirmada apenas no Galaxy A07 / Android 16 / One UI 8.5 / KernelSU.

## Instalação

Baixe `WhatsNow_v0.5.0-beta.1.zip` e o `.sha256` correspondente na [release do GitHub](https://github.com/zenix2312/WhatsNow-Releases/releases/tag/v0.5.0-beta.1). Confira o checksum, instale por um gerenciador de módulos root compatível e mantenha um backup funcional e uma opção de recuperação.

**Distribuição:** o código-fonte é privado. O ZIP público contém componentes compilados e scripts necessários à instalação e execução, sem os arquivos Java ou ferramentas de compilação. Consulte os [termos](TERMS.md).
