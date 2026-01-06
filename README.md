# Sistema de Backup Automatizado

Este projeto demonstra a criação de um sistema de backup automatizado
em Linux utilizando rsync, cron e shell script, simulando um cenário
real de proteção de dados.

## Objetivo
Garantir a proteção de arquivos críticos através de backups
automatizados, com registro de execução e possibilidade de restauração.

## Cenário
Servidor Linux local com dados importantes que precisam
ser copiados regularmente para um diretório seguro.

## O que foi implementado
- Backup manual com rsync
- Script de backup automatizado
- Agendamento com cron
- Logs de execução
- Testes de restore

## Estrutura do repositório
configs/
  backup.sh
docs/
  README.md

## Tecnologias utilizadas
- Linux
- Bash
- rsync
- cron
- Git & GitHub

## Resultados
Backups realizados automaticamente conforme agendamento,
com validação dos arquivos restaurados.

## Status
Concluído

