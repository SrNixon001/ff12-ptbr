# Checklist de Release no GitHub

## Antes de publicar

1. Criar um repositório vazio no GitHub.
2. Conectar este repo local ao `origin`.
3. Commitar apenas a documentação e os metadados.
4. Não commitar `release-assets/`.

## Assets para enviar em GitHub Releases

### Release principal

- `release-assets/manual-r3/FF12_PTBR_v1.8.0-r3.zip`

### Assets opcionais

- `release-assets/automatic-r1/FF12_PTBR_Installer_v1.8.0-r1.zip`
- `release-assets/automatic-r1/FF12_PTBR_Installer_v1.8.0-r1.exe`

## Ordem recomendada na página de release

1. `FF12_PTBR_v1.8.0-r3.zip` como arquivo principal
2. `FF12_PTBR_Installer_v1.8.0-r1.zip` como opção alternativa
3. `FF12_PTBR_Installer_v1.8.0-r1.exe` apenas se quiser disponibilizar o executável direto

## Observação

A versão manual `r3` é a mais adequada para publicação técnica.  
A versão `r1` deve ser tratada como opcional por causa de reputação/heurística de antivírus.
