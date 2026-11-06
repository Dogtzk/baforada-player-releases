# Bafo Player

Player feito por dogtzk. Os nomes dos temas dentro do aplicativo continuam como estão.

## Downloads

[Baixar Windows 1.8.39](https://github.com/Dogtzk/baforada-player-releases/releases/download/v1.8.39/BafoPlayer-Setup-1.8.39.exe)

[Baixar APK Android 1.6.33](https://github.com/Dogtzk/baforada-player-releases/releases/download/v1.8.39/BafoPlayer-Android-1.6.33.apk)

## Atualizações

O player verifica novas versões pelo próprio aplicativo. Em Configurações, procure Atualizações, baixe e instale quando quiser. Conta, biblioteca, downloads e temas são preservados. No Android, o sistema pode pedir permissão para instalar o APK.

## Nesta versão

Windows 1.8.39 — Recuperação de buffering

A transferência de áudio progressivo agora tenta continuar do byte em que a conexão parou, com limite de tentativas, sem reiniciar a faixa inteira. A retomada verifica o intervalo e a identidade do arquivo para evitar áudio duplicado ou corrompido. Trocar de faixa cancela o pedido anterior.

Quando o buffer está vazio e o tempo deixa de avançar, o player tenta recuperar após 3 segundos e renovar a fonte após 8 segundos, em vez de esperar até 25 segundos. A pausa manual continua respeitada.

212 testes automatizados passaram, incluindo interrupção da conexão, retomada exata, cancelamento e limites de tentativas. Testes de áudio na versão empacotada verificam a continuação sem reiniciar a música. Conta, biblioteca, downloads e temas preservados.

A alteração é para PC. O Android permanece na versão 1.6.33, com o mesmo APK assinado da versão anterior.

## Compatibilidade

Os arquivos com o nome anterior BaforadaPlayer têm conteúdo idêntico e são mantidos para a atualização automática das versões antigas. Para uma instalação nova, use os links Bafo Player acima.

Este repositório contém apenas distribuição, instruções e imagens públicas dos temas. Senhas, bibliotecas pessoais e chaves privadas de publicação não são enviados.
