### Zap

Antes do primeiro build LEIA ESSAS INSTRUÇÕES:

a) Abra o arquivo org.telegram.messenger.BuildVars.java e preencha as credenciais que devem ser geradas no liks que estão nos comentários do mesmo

b) no https://firebase.google.com/ (um dos links do passo anterior) é gerado o arquivo google-services.json, ele deve ser salvo dentro da pasta /TMessagesProj do projeto

c) Altero as ultimas linhas do values/strings.xml de acordo com o seu app (nome do app mensagem de boas vindas e etc...)

d) Substitua os arquivos ic_launcher.png nas pastas  /drawble pelo arquivo de seu app

e) Altere o build.grade de acordo com o reverse name do seu app (IMPORTANTE: é o mesmo reverse name que está no arquivo google-services.json

f) Gere sua chave de release e salve-a na pasta _signAPK como "release.keystore" e altere as credenciais de acordo no build.grande em "signingConfigs"