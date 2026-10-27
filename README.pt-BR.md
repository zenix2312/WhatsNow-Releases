# WhatsNow

**Idioma:** [English](README.md) | [Português (Brasil)](README.pt-BR.md)

Notificações do WhatsApp na Samsung Now Bar em aparelhos Galaxy tecnicamente compatíveis.

**Beta mais recente:** [v0.5.0-beta.1](https://github.com/zenix2312/WhatsNow-Releases/releases/tag/v0.5.0-beta.1) · Mantenedor: **zenix2312**

[Baixar beta](https://github.com/zenix2312/WhatsNow-Releases/releases/tag/v0.5.0-beta.1) · [Notas da versão](RELEASE_NOTES.pt-BR.md) · [Termos de distribuição](TERMS.md)

## Sobre o projeto

WhatsNow é um módulo root que adapta notificações compatíveis do WhatsApp à Now Bar da Samsung, quando o firmware oferece os recursos necessários. A simples presença da Now Bar **não garante** que a integração seja compatível.

Este repositório público distribui o módulo compilado e a documentação. O código-fonte é mantido separadamente em um repositório privado; o WhatsNow **não é open source**.

## Compatibilidade

**Testado:** Samsung Galaxy A07, Android 16, One UI 8.5, KernelSU.

**Outros Samsung Galaxy:** suporte experimental. A compatibilidade depende dos recursos de notificações da Now Bar presentes no firmware e precisa ser validada em cada aparelho. O funcionamento em gerenciadores de módulos root diferentes do KernelSU ainda não foi confirmado.

## Instalação

1. Baixe o ZIP do módulo e o arquivo `.sha256` correspondente na [página da versão](https://github.com/zenix2312/WhatsNow-Releases/releases/tag/v0.5.0-beta.1).
2. Confira o checksum e mantenha um backup funcional e uma forma de recuperação.
3. Instale pelo gerenciador de módulos root compatível.
4. Consulte os diagnósticos em **Ação** e teste com notificações reais do WhatsApp.
5. Se o SystemUI apresentar instabilidade, desative o módulo e siga o procedimento de recuperação do aparelho.

## Limitações atuais

- A resposta diretamente no cartão da Now Bar permanece desativada por estabilidade.
- Históricos com muitas mensagens longas podem ficar truncados.
- A compatibilidade ampla entre aparelhos e versões de firmware ainda não foi confirmada.

## Relatar problemas

Informe modelo Samsung, versões do Android e da One UI, gerenciador de módulos e versão, passos para reproduzir, resultado esperado e resultado observado. Remova mensagens privadas, telefones, identificadores do aparelho e logs sensíveis antes de compartilhar.

## Distribuição

O código-fonte original é privado. O módulo disponibilizado contém binários compilados e scripts necessários para instalação e execução. Baixar o ZIP não autoriza distribuir versões modificadas ou com outra identidade. Consulte os [termos de distribuição](TERMS.md).

WhatsNow é um projeto independente, sem vínculo oficial com Samsung ou Meta. Os nomes e as marcas pertencem a seus respectivos titulares.
