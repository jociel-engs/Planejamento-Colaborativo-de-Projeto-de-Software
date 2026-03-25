# Relatório de Atividades - [Vinicius Antoniu]
**Função:** Desenvolvedor.

## Descrição das Tarefas Planejadas

Abaixo estão as descrições das soluções planejadas para as tarefas que me foram designadas no Trello:

### 1. Editar perfil do usuário
* **Descrição da solução planejada:** Criar uma interface onde o paciente logado possa visualizar e alterar seus dados cadastrais (nome, telefone, e-mail e senha). Será necessário planejar a validação dos dados antes de enviar a atualização para o banco de dados, garantindo a segurança da conta.

### 2. Sistema de busca de médicos
* **Descrição da solução planejada:** Desenvolver um campo de pesquisa na tela principal com filtros. O usuário poderá buscar médicos por "Nome", "Especialidade" (ex: Cardiologista, Pediatra) ou "Disponibilidade". O sistema deverá consultar o banco de dados e retornar uma lista em formato de cards.

### 3. Mensagens claras de erro ou de sucesso
* **Descrição da solução planejada:** Padronizar o feedback visual (UI/UX) do sistema. Planejar a implementação de alertas temporários (toasts ou pop-ups) nas cores verde (sucesso, ex: "Consulta agendada!") e vermelho (erro, ex: "Horário indisponível!"), melhorando a comunicação com o usuário após cada ação.

### 4. Botões grandes pros usuários
* **Descrição da solução planejada:** Focar na acessibilidade e na responsividade do sistema (mobile-first). Planejar a estilização CSS de botões de ação (Call to Action) com tamanhos adequados para toque em telas de celular, facilitando o uso por pacientes com dificuldades motoras ou visuais.

### 5. Editar dados de médicos
* **Descrição da solução planejada:** Criar um formulário restrito para médicos ou administradores da clínica. Permitirá a atualização de informações profissionais, como número do CRM, especialidades atendidas, dias de trabalho e horários de atendimento clínico.

### 6. Lembrete de consulta
* **Descrição da solução planejada:** Estruturar a lógica de um serviço (rotina em background) que verificará o banco de dados diariamente. O sistema enviará um aviso automático (por e-mail ou SMS simulado) 24 horas antes do horário da consulta para reduzir faltas.

### 7. Notificações de consulta agendada
* **Descrição da solução planejada:** Implementar um alerta imediato. Assim que o usuário finalizar a marcação de uma nova consulta, o sistema vai gerar uma notificação na tela e enviar um comprovante automático com a data, horário e nome do médico.

### 8. Histórico de consultas
* **Descrição da solução planejada:** Desenvolver uma tela no painel do paciente dividida em duas abas: "Consultas Futuras" e "Consultas Realizadas". O sistema fará uma busca no banco de dados vinculada ao ID do usuário para listar o histórico médico de forma organizada.