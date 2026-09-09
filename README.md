# Soli App — Instaladores

Aplicativo interno da Solivetti que reúne as automações da T.I. num lugar só:
abrir e acompanhar chamados do GLPI, avisos da equipe, renomeador de PDFs
escaneados e consulta de rendimento de insumos.

## Baixar

O instalador de cada versão está em **[Releases](../../releases)** — baixe o
`SoliApp-Setup-X.Y.Z.exe` da versão marcada como *Latest*.

Depois de instalado, **o próprio app se atualiza**: ele confere a versão logo
após o login e oferece a atualização quando há uma nova. Não é preciso voltar
aqui a cada versão.

## Conferir o download

Cada release traz um `SHA256SUMS.txt`. No PowerShell:

```powershell
Get-FileHash .\SoliApp-Setup-X.Y.Z.exe -Algorithm SHA256
```

O valor tem de bater com o do arquivo.

## Antes de instalar

O X da janela **esconde o app na bandeja** em vez de fechá-lo. Se o instalador
reclamar que o programa está em uso, saia pelo menu do ícone na bandeja
(perto do relógio) e instale de novo.

## Entrar

A senha é a mesma do GLPI — o app não guarda senha e pede a cada abertura.

## Sobre este repositório

Aqui ficam **somente os binários**. O código-fonte é privado.

Problema, dúvida ou sugestão: fale com a T.I.
