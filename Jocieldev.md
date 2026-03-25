## Opção de favoritar os médicos

    Na interface de agendamento de consultas, ao lado do nome do Dr. teria uma estrela, que bastaria o usuário clicar na estrela. No momento em que o sistema reconhecesse o toque, o frontend mudaria a cor da estrela e deixaria ela amarela.

    Os médicos ficariam em uma tela própia "Meus Médicos", com uma lista organizada por nome, especialidade e disponibilidade de horário.

    O app também priorizaria esse médicos "favoritos" no momento em que o usuário fosse agendar outra consulta, assim, reduzindo o esforço para o idoso (público alvo do aplicativo).

## Criar sistema de agendamento

    No backend, o Sistema de Agendamento seria interligado por HTTP, onde o frontend envia uma requisição para o backend, e ele processa, acessa o banco de dados e devolve a resposta que se atualiza no front. O backend seria responsável por armazenar os dados e informações coletadas do usuário e também por garantir que não haja conflito de horários de agendamento.
    Já no frontend a página de agendamentos seria anexada a juntamente com a lista dos médicos que estão disponíveis. O usuário também poderia mudar o horário da consulta ou cancelar o agendamento. Tudo isso seria reforçado com uma cybersegurança para evitar o vazamento de dados do usuário.

## Selecionar data e horário da consulta

    O usuário escolhe a data através de um calendário e um seletor de horas (Com os horários que o respectivo médico atende).

## Confirmar agendamento

    Quando o usuário agendasse uma consulta (caso o horário selecionado estivesse disponível), seria enviado as informações para o backend, ele verificaria se o horário realmente está disponível, e logo após mandaria uma notificação para o celular do solicitante e pediria a confirmação do agendamento. Posteriormente, seria exibida na tela uma mensagem “Agendamento realizado com sucesso!!

