# Escola Madison para Android — testes

[**Baixar o APK para Android**](https://github.com/MarcosBarrosMB/madison-android-testes/releases/download/teste-2026-10-21/Madison-teste-2026-10-21.apk)

Versão **0.1.8** · Android 8.0 ou mais recente · aproximadamente 15 MB · processadores de 32 e 64 bits.

## Instalação e atualização

1. Abra o link no celular Android e baixe o arquivo `.apk` novamente.
2. Abra o arquivo e toque em **Instalar** ou **Atualizar**. Se solicitado, permita a instalação por essa fonte.
3. Abra o **Escola Madison** e entre com sua conta institucional. Se já usa o iPhone, utilize a mesma conta.

Se o app já estiver instalado, instale por cima para manter os dados locais. Não é necessário desinstalar.

## Escola Madison 0.1.8

- Alarmes de atividade passam a usar o mecanismo de despertador do Android, separado dos avisos de preparação.
- O disparo mantém o processador acordado por poucos segundos para concluir a validação e apresentar o alerta, mesmo com a tela apagada.
- Menos processamento ao disparar; uma validação lenta não registra o alarme como entregue antes da publicação, e falhas temporárias recebem tentativas limitadas.
- Corrigidas referências de áudio que podiam deixar de funcionar após atualizar o APK. Preferências de som, canais silenciados e escolhas de vibração são preservados.
- A restauração dos horários após reiniciar ou atualizar o app usa trabalho persistente em segundo plano. A sincronização também conclui a publicação dos avisos antes de encerrar.
- Orientação sobre atividade em segundo plano nas configurações de alarmes de aparelhos Samsung.

Instale sobre a versão anterior, sem desinstalar. Abra o app uma vez depois de atualizar e confira as opções em **Notificações e alarmes**. Em aparelhos Samsung, permita atividade em segundo plano e retire a Escola Madison dos aplicativos suspensos nas configurações de bateria.

Lembretes da rotina já programados usam os dados locais, inclusive sem internet, respeitando a validade da autorização da conta. Novos avisos da escola precisam chegar pela sincronização; o Android pode adiar essa busca em economia de bateria. Fechar o app ou bloquear a tela é diferente de usar **Forçar parada** nas configurações, ou desligar completamente o celular.

Validação em emuladores Android 9 e Android 17; o Galaxy J4+ físico ainda precisa ser retestado. Nenhuma alteração nas telas de reuniões.

## Integridade do arquivo

Assinatura de desenvolvimento verificada, igual à versão anterior. Atualizado em **21/10/2026**.

SHA-256:

```
f8042d5346be5feeab48e00330d660a36e6b5b1cd6888aa4e01d9d0777035ecb
```
