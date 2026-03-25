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

## Cancelar agendamento

    Na aba "Minhas Consultas Agendadas". O usuário poderá ver quais consultas estão agendadas, para qual clinica, qual médico e qual horário. Abaixo dessas informações terá um texto em vermelho negrito escrito: Cancelar Consulta. Se clicar em cima desse texto, irá aparecer uma caixa no meio da tela escrito "Você tem certeza que deseja cancelar essa consulta?".
    Se essa ação for confirmada, uma mensagem em forma de pop-up aparecerá na parte inferior da tela (Consulta cancelada com sucesso!!).

## Criar dashboards simples com as próximas consultas

    Na tela inicial, terá a opção (Minhas Consultas Agendadas), que conterá o tipo da consulta, em qual clinica, com qual médico e em qual horário, também terá a opção de cancelar a consulta.

## Integração do GPS com as clínicas mais próximas

    Primeiramente o app solicitaria a localização do usuário, para assim conseguir ter acesso as clínicas mais próximas com maior precisão. Depois o backend consulta um banco de dados ou uma API de mapas para identificar as clínicas próximas e cadastradas no app, ele retornaria essas informações para o frontend que exibiria de forma visual, em um mapa ou em forma de cards.
    Permitindo assim que o usuário veja rapidamente as clínicas mais próximas e consiga agendar a sua consulta com maior facilidade.

## Avaliação dos médicos

    Um ou dois dias após a consulta, será enviada uma notificação para o celular do usuário pedindo o feedback do usuário quanto ao médico que ele foi atendido.

## Modo de voz (com a IA integrada)

    O sistema permite que o usuário interaja por voz, ditando comandos ou solicitando informações. O frontend capta a fala do idoso e envia para a IA, que processa o comando e retorna uma resposta, seja lendo agendamentos, ajudando a marcar consultas, fornecendo instruções ou até mesmo identificando sintomas breves de algum tipo de doença de forma falada, tornando a experiência mais acessível e intuitiva.

##  Página de tutorial
    O sistema oferece uma página de tutorial com instruções simples, visuais e passo a passo sobre como usar o aplicativo, como marcar ou cancelar agendamentos e acessar funcionalidades importantes. O objetivo é tornar o uso mais intuitivo e garantir que os idosos consigam utilizar todas as funções com facilidade.