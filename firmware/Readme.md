1. Às vezes ocorre um erro ao compilar este ramo pela primeira vez. Por favor, feche o vscode e reabra, então a compilação será normal.
2. se você baixou da versão oficial Marlin bugfix-2.0.x. Modifique [aqui](https://github.com/bigtreetech/BIGTREETECH-SKR-PRO-V1.1/blob/9ae95e478c74dc1e5c7fec6d94e13c3bedf2169f/firmware/Marlin-SKR-Pro/platformio.ini#L34) de `TMCStepper@<1.0 .0` para `https://github.com/bigtreetech/TMCStepper`.
Isso ocorre porque o UART de tmc2208/2209 ainda não foi mesclado na versão oficial, use este método antes da mesclagem

Observação: se você deseja criar suas próprias regras de nomenclatura de versão, os nomes das pastas não devem exceder 64 caracteres.
arquivos de projeto marlin 2.0 em outras pastas, profundidade de aninhamento de pasta não pode exceder 3,
caso contrário, ao abrir o projeto de compilação do projeto, haverá erros de compilação inesperados!
Recomenda-se que o nome do arquivo não seja muito longo, quanto mais curto melhor.
A profundidade de aninhamento de arquivos não deve ser muito grande, quanto menos aninhamento, melhor.
