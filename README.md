# Atlas Device Control

Sistema interno desktop web para controle operacional e administrativo de coletores Zebra TC21, TC22, TC8300 e impressoras logísticas.

## Objetivo
Controlar entrega, recebimento, rastreabilidade, manutenção, inventário, auditoria, QR Codes, etiquetas, ocorrências por turno, dashboard operacional e notificações automáticas por e-mail.

## Regras principais
- Banco de dados interno é a fonte oficial de verdade
- Excel serve apenas para importação inicial, importação controlada, exportação e backup
- Não armazenar histórico na tabela principal de dispositivos
- Usar logs centralizados em `system_logs`
- Usar exclusão lógica
- Toda alteração manual de status exige justificativa
- Coletores e Impressoras devem funcionar como módulos irmãos
- Interface desktop web, não mobile
- O sistema deve ser escalável desde a fundação

## Documentação
- `docs/visao-geral.md`
- `docs/requisitos-funcionais.md`
- `docs/regras-tecnicas.md`
- `docs/fases.md`
