# Sending session logs / Enviando logs

## English

On Windows:

1. After the problem occurs, note the approximate time and your time zone, the action you performed, and who was hosting. Capture the error message if one appears.
2. Press **Windows + R**, paste the path below, and press Enter:

   ```text
   %APPDATA%\songsofsyx\logs
   ```

3. Sort by **Date modified** and find the `syx-sovereigns-<number>.log` file for the affected game session. The number is a process identifier, not a player ID. Do not select solely by the largest number.
4. Include the matching `syx-sovereigns-<number>.previous.log` if it exists. This is the preceding part of a rotated log.
5. Copy the relevant files to a separate folder soon after the problem: older logs are eventually removed automatically. You may compress those copies into a ZIP. Name your attachment clearly, for example `host-2026-10-13.zip` or `guest-2026-10-13.zip`.
6. In the issue form's **Logs and screenshots** box, drag the files into the text area, wait for the upload to finish, and submit the report. You can also attach files in a later comment. Do not merely paste a file path from your computer: other people cannot open it.

For multiplayer issues, ask the host and affected guest to each send logs from the **same session**. Include approximate local time and time zone for each participant. Describe any missing logs rather than delaying the entire report.

If the normal folder is empty or unavailable, check the fallback location:

```text
%TEMP%\syx-sovereigns-logs
```

If neither location contains the logs, submit the report with that information. Include a screenshot or the exact error text if available. A log is diagnostic evidence and may not contain the full cause of every crash.

**Privacy:** this tracker is public. Review the contents before attaching them; logs can include player/account identifiers and local paths. Do not upload the whole game directory or unrequested save files.

## Português

1. Anote o horário aproximado e o fuso, o que estava fazendo e quem era o anfitrião. Capture a mensagem de erro, se houver.
2. Aperte **Windows + R**, cole `%APPDATA%\songsofsyx\logs` e pressione Enter.
3. Ordene por **Data de modificação** e procure o `syx-sovereigns-<número>.log` da sessão com problema. O número identifica o processo do jogo; não é a identificação do jogador nem indica qual arquivo é mais recente.
4. Inclua também o arquivo de mesmo número terminado em `.previous.log`, se existir. Ele contém a parte anterior do log.
5. Copie os arquivos logo após o problema, pois os mais antigos são removidos automaticamente. Pode compactar as cópias em ZIP. Identifique os anexos como anfitrião ou convidado.
6. Na aba **Issues**, abra um relato e arraste os arquivos para o campo **Logs and screenshots**. Espere o envio terminar antes de publicar. Também é possível anexá-los em um comentário posterior. Colar apenas o caminho do arquivo no computador não envia seu conteúdo.

Para problemas multiplayer, envie os logs do anfitrião e do convidado afetado **da mesma sessão**. Se só tiver um deles, informe qual está faltando; o outro jogador pode complementar depois. Inclua horário e fuso de cada participante.

Se a pasta normal estiver vazia ou indisponível, tente `%TEMP%\syx-sovereigns-logs`. Se não encontrar os logs, descreva isso no relato e inclua a mensagem de erro ou uma imagem, se possível.

**Os relatos e anexos são públicos.** Confira nomes, identificadores de conta e caminhos pessoais antes de enviar. Se ocultar informações pessoais, avise que o arquivo foi editado. Não envie a pasta inteira do jogo nem saves que não tenham sido solicitados.
