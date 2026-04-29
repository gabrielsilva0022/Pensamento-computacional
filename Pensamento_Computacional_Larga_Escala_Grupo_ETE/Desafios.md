# Desafios do Projeto

Este documento apresenta os principais desafios identificados no design da ETE e as soluções propostas.

## Desafio 1: Crescimento de Usuários
- Risco: aumento simultâneo de alunos e professores acessando o sistema.
- Solução: arquitetura modular, permitindo evolução e expansão dos módulos.

## Desafio 2: Acesso simultâneo às disciplinas
- Risco: lentidão em períodos de pico.
- Solução: separação clara entre módulos de usuários, disciplinas e conteúdos.

## Desafio 3: Volume de entregas de atividades
- Risco: sobrecarga no sistema em períodos próximos aos prazos.
- Solução: módulo de atividades independente, facilitando ajustes futuros.

## Desafio 4: Comunicação interna
- Risco: crescimento do volume de mensagens.
- Solução: módulo de comunicação separado dos demais fluxos críticos.