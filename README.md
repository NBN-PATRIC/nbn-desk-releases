# NBN Desk: versões para baixar

Acesso remoto da NBN Telecom, com servidor próprio. Quem está na máquina vê o pedido e aceita antes de qualquer acesso.
Este repositório só publica os executáveis; o código-fonte fica num repositório privado da NBN.

## Baixar

- [NBN-Desk-portatil.exe da última versão](https://github.com/NBN-PATRIC/nbn-desk-releases/releases/latest/download/NBN-Desk-portatil.exe)
  (é o mesmo arquivo do `NBN-Desk-x.y.z-<build>-portatil.exe` da [página da versão](../../releases/latest)).

O portátil roda sem instalar e sem administrador. Para deixar instalado com o mesmo ID, use o botão do cartão do ID
dentro do app.

O executável não tem certificado comercial de assinatura de código. Por isso o SmartScreen pode avisar
"O Windows protegeu o seu PC": clique em **Mais informações** e depois em **Executar assim mesmo**. Para conferir o
arquivo, compare o hash com o `SHA256SUMS.txt` da versão:

```powershell
Get-FileHash .\NBN-Desk-portatil.exe -Algorithm SHA256
```
