# GitHub Release Checklist

## Antes de publicar

1. Criar um repositorio vazio no GitHub.
2. Conectar este repo local ao `origin`.
3. Commitar apenas a documentacao e os metadados.
4. Nao commitar `release-assets/`.

## Assets para enviar em GitHub Releases

### Release principal

- `release-assets/manual-r3/FF12_PTBR_v1.8.0-r3.zip`

### Assets opcionais

- `release-assets/automatic-r1/FF12_PTBR_Installer_v1.8.0-r1.zip`
- `release-assets/automatic-r1/FF12_PTBR_Installer_v1.8.0-r1.exe`

## Ordem recomendada na pagina de release

1. `FF12_PTBR_v1.8.0-r3.zip` como arquivo principal
2. `FF12_PTBR_Installer_v1.8.0-r1.zip` como opcao alternativa
3. `FF12_PTBR_Installer_v1.8.0-r1.exe` apenas se quiser disponibilizar o executavel direto

## Observacao

A versao manual `r3` e a mais adequada para publicacao tecnica.  
A versao `r1` deve ser tratada como opcional por causa de reputacao/heuristica de antivirus.
