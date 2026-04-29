# Design do Sistema #

Este documento apresenta a decomposição do sistema, bem como a aplicação da abstração e do reconhecimento de padrões, conforme os princípios do Pensamento Computacional.

## Decomposição do Sistema:
O sistema foi dividido em módulos para facilitar o entendimento e o design da solução:

- Módulo de Usuários: cadastro e acesso ao sistema
- Módulo de Disciplinas: gerenciamento de disciplinas
- Módulo de Atividades: criação, entrega e avaliação de atividades
- Módulo de Comunicação: envio de mensagens e avisos
- Módulo de Desempenho Acadêmico: registro e visualização de notas

## Abstração:
Na abstração, foram considerados apenas os elementos essenciais do sistema:

- Usuário (aluno ou professor)
- Disciplina
- Atividade
- Nota
- Mensagem

Detalhes técnicos e implementações específicas foram deixados de fora para manter o modelo simples.

## Reconhecimento de Padrões:
Foram identificados fluxos comuns no sistema, como:

- Login do usuário
- Acesso às disciplinas
- Entrega e avaliação de atividades
- Comunicação vinculada às disciplinas
- Consulta de desempenho acadêmico

Esses padrões ajudam a entender o funcionamento geral do sistema de forma organizada.