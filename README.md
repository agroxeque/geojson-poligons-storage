# GeoJSON Storage

Repositório para armazenamento de arquivos GeoJSON gerados a partir de KML.

## Estrutura
- `/geojson` - Diretório onde os arquivos GeoJSON são armazenados

## Formato dos Arquivos
Os arquivos GeoJSON seguem o padrão:
- Nome: `polygon_YYYYMMDD_HHMMSS.geojson`
- Estrutura: GeoJSON Feature com geometria do tipo Polygon

## Acesso aos Arquivos
Os arquivos podem ser acessados diretamente via URL raw do GitHub:
`https://raw.githubusercontent.com/[usuario]/[repositorio]/main/geojson/[nome_arquivo]`