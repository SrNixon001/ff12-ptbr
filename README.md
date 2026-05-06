# FINAL FANTASY XII THE ZODIAC AGE - Tradução PT-BR

Repositório público para distribuição da tradução PT-BR de `FINAL FANTASY XII THE ZODIAC AGE`.

## Versões de download

### Automática `r1` (recomendada)

Instalador automático legado.

- arquivo: `FF12_PTBR_Installer_v1.8.0-r1.zip`
- extra: `FF12_PTBR_Installer_v1.8.0-r1.exe`
- indicada para quem quer a instalação mais simples

### Manual `r3` (alternativa)

Pacote manual para uso com `FF12 External File Loader`.

- arquivo: `FF12_PTBR_v1.8.0-r3.zip`
- formato: somente arquivos da tradução
- indicada para quem prefere instalar manualmente

> Aviso: a versão `r1` pode gerar mais alertas heurísticos por ser um executável empacotado.

## Como instalar

### Automática `r1`

1. Extraia `FF12_PTBR_Installer_v1.8.0-r1.zip`.
2. Execute `FF12_PTBR_Installer_v1.8.0-r1.exe`.
3. Use a opção de instalar ou remover dentro do instalador.

### Manual `r3`

1. Instale o `FF12 External File Loader`.
2. Extraia `FF12_PTBR_v1.8.0-r3.zip`.
3. Copie a pasta `ff12data` para `mods\deploy` dentro da pasta do jogo.
4. O caminho final deve ficar:

`FINAL FANTASY XII THE ZODIAC AGE\mods\deploy\ff12data`

## Sobre este repositório

Os binários de release não devem ser commitados no Git normal do GitHub porque são grandes demais para o repositório comum.  
Por isso, este repositório foi preparado para:

- versionar documentação, notas e hashes;
- enviar os arquivos grandes em **GitHub Releases**;
- manter a versão automática `r1` e a manual `r3` como assets de release.

## Arquivos de apoio

- [Hashes dos assets](docs/ASSET_HASHES.md)
- [Checklist de release no GitHub](docs/GITHUB_RELEASE_CHECKLIST.md)
- [Notas de release](docs/RELEASE_NOTES.md)
