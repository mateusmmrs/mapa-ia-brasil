# Dicionário de Dados — dataset_ia_brasil.csv

## Origem dos dados

| Coluna | Fonte | Descrição |
|--------|-------|-----------|
| sigla_uf | IBGE | Sigla da Unidade da Federação |
| uf | IBGE | Nome da UF |
| regiao | Derivado | Região geográfica (Norte, Nordeste, Sudeste, Sul, Centro-Oeste) |
| rebanho | IBGE/PPM Tab. 3939 | Efetivo do rebanho bovino (cabeças), ano mais recente |
| pct_femeas_inseminadas_corte | ASBIA INDEX 2022 | % de fêmeas em rebanhos de corte inseminadas |
| pct_femeas_inseminadas_leite | ASBIA INDEX 2022 | % de fêmeas em rebanhos leiteiros inseminadas |
| femeas_estimadas | Derivado | Estimativa de fêmeas (rebanho × 0.55) |
| femeas_inseminadas_est | Derivado | Fêmeas inseminadas estimadas (fêmeas × % corte) |
| femeas_nao_inseminadas | Derivado | Fêmeas que ainda usam monta natural |
| potencial_doses | Derivado | Doses adicionais se inseminasse 30% das restantes |

## Notas

- Os dados da ASBIA foram compilados manualmente de PDFs do INDEX ASBIA
- A proporção de 55% fêmeas sobre o rebanho total é uma aproximação zootécnica
- Os dados por UF são do INDEX ASBIA 2022 (último com dados estaduais completos)
- Valores de "potencial_doses" são cenário conservador (30% de conversão)
