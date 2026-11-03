# Escola Madison para Android

[**Baixar o APK atualizado para Android**](https://github.com/MarcosBarrosMB/madison-android-testes/releases/latest/download/Madison-Android.apk)

Versão **0.2.0 (14)** · Android 8.0 ou posterior · aproximadamente 15 MB · processadores de 32 e 64 bits.

## Instalação e atualização

1. Abra o link no celular Android e baixe o arquivo `.apk`.
2. Abra o arquivo e toque em **Instalar** ou **Atualizar**. Se solicitado, permita a instalação por essa fonte.
3. Abra o **Escola Madison** e entre com a mesma conta institucional usada no iPhone ou Mac.

Instale por cima da versão anterior para preservar a conta e os dados locais. Não é necessário desinstalar.

## Nesta atualização

- Reuniões como última opção da Rotina e em Áreas, com pautas por tipo, histórico de resoluções e atas.
- Agendamento sem término previsto, exclusão de reuniões marcadas, aviso dez minutos antes e alarme no início para os participantes autorizados, conforme as permissões do aparelho.
- Gravação pelo aparelho que marcou a reunião, controle na notificação e ata automática ao encerrar. O áudio é apagado após confirmar a ata salva; não é guardado no servidor Madison.
- Ata editável, com as alterações incluídas no PDF.
- GPT Madison ao lado de Registrar entrada: texto com resposta progressiva e conversa por voz GPT-Live. O assistente segue as permissões da conta.
- Consentimento antes de enviar dados à OpenAI; histórico criptografado somente no aparelho, separado por conta.
- Widget GPT Madison e controles rápidos para GPT e ponto.

A chave da OpenAI permanece no servidor institucional. Os usuários autorizados não precisam de uma chave própria. O uso da API é cobrado separadamente da assinatura ChatGPT.

## Validação e distribuição

406 testes JVM sem falhas, Lint concluído, testes nativos no Android 13 e captura nativa por 76 segundos com tela bloqueada. Transcrição e ata controladas nos testes verificam recuperação e exclusão após confirmação do banco. A fala real e a voz em aparelhos Android físicos ainda precisam de conferência no aparelho.

APK universal Release/R8, sem depuração, com a mesma assinatura de teste das versões anteriores. Distribuição direta pelo GitHub; não publicado na Play Store.

[Notas completas da versão](https://github.com/MarcosBarrosMB/madison-android-testes/releases/tag/android-0.2.0-2026-11-03) · [Versão anterior 0.1.12](https://github.com/MarcosBarrosMB/madison-android-testes/releases/tag/teste-2026-10-21)

## Integridade

SHA-256 do APK 0.2.0:

```
fa279c6566567a6d50a19aa78a55db42ceae6a432b87fd7c861bd66a24f2a9d1
```
