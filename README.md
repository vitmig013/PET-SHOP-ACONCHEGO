# PROJETO: PET SHOP ACONCHEGO

Integrantes do grupo

Gabriel dos Santos Loth
Karyn Aparecida da Silva
Kemily Teixeira dos Santos
Marcio Anderson da Silva Cavalcante
Vitor Miguel Costa Macedo
Wilson Gonsaga de Souza Neto


## OBJETIVO DO TRABALHO

Criar um aplicativo Desktop, para o gerenciamento dos serviços prestados.


## PET SHOP ACONCHEGO

A empresa atua no ramo de prestação de serviços classificada como Micro Empresa (MEI), oferecendo banho e tosa por meio de agendamentos. Atualmente, a operação é realizada num espaço próprio, o pet será recolhido por um serviço de Táxi especializado, terá seus devidos cuidados realizados no estabelecimento, para posteriormente ser devolvido ao tutor pelo mesmo serviço. O Pet Shop tende a ser colaborativo, com um ambiente informal porém com foco no cuidado e bem-estar dos pets. A empresa valoriza a organização e a agilidade, tendo serviços realizados sempre nos prazos estabelecidos.

### MISSÃO
Oferecer serviços de banho e tosa com excelência, segurança e carinho, promovendo bem-estar aos pets, priorizando a confiança e tranquilidade aos seus tutores.

### VISÃO
Ser reconhecida pela qualidade do serviço prestado, pelo cuidado e comprometimento com o cliente.

### VALORES
Ética e transparência com os clientes, atendimento humanizado, profissionalismo e responsabilidade.

**Problema:** “Hoje a empresa faz controles e agendamentos de forma manual e isso causa atraso nos atendimentos e dificuldade no controle geral de insumos e na disponibilidade de horário/vagas. 


**Objetivo:** “A solução deve permitir uma eficiência e agilidade no processo, reduzindo esforço físico e melhorando o armazenamento de arquivos.”

### O que o aplicativo precisa oferecer (RF)

Agendamento online
O cliente deve conseguir marcar banho e tosa diretamente pelo aplicativo data, horário, tipo de serviço (banho, tosa, hidratação, etc.) e profissional disponível.

Cadastro completo do cliente e do pet
O sistema deve permitir cadastrar: nome do tutor, telefone / WhatsApp, nome do pet, raça, porte, idade, observações (alergias, comportamento, restrições).

Organização da agenda
A agenda precisa mostrar: horários disponíveis, horários ocupados, profissional responsável, tempo de cada serviço.

Histórico do pet
Guardar informações como: serviços realizados, frequência de banho, observações do profissional

Controle financeiro básico
O aplicativo pode registrar: valor do serviço, forma de pagamento, faturamento diário.

Painel administrativo
Para o dono do pet shop visualizar: agenda do dia, quantidade de atendimentos, clientes frequentes, serviços mais solicitados.

Facilidade de uso
O aplicativo precisa ser: simples, rápido, fácil de entender para clientes e funcionários.

### O que o aplicativo NÃO pode errar (RN)

1. Não pode permitir dois agendamentos no mesmo horário. Evitar conflitos de agenda.
2. Não pode perder dados. Informações de clientes e pets devem ser armazenadas
com segurança.
3. Não pode ser lento o travar. O aplicativo precisa funcionar rápido, senão os clientes desistem de usar
4. Não pode ser complicado
Se for difícil de usar, o cliente prefere ligar ou mandar mensagem,perdendo o objetivo do sistema.

## OBSTÁCULOS E RESTRIÇÕES

Minha agenda encontra-se bastante restrita neste momento, podendo ser agendadas reuniões apenas nas terças e quartas-feiras no período da manhã.

O projeto contará com um orçamento inicial reduzido, portanto a implementação deve ser feita de maneira estratégica.

O escopo deve respeitar estes limites:
Funcionalidades:
CADASTRO, VENDAS, AGENDAMENTO PARA BANHO, AGENDAMENTO PARA TOSA, HOTEL PET, TAXI PET.


## PERFIL DE USUÁRIO
GERENTE ( deve ter total acesso ao aplicativo), ADMINISTRATIVO ( acesso ao cadastro e a agenda), TOSADOR (acesso à uma página para descrição de intercorrência).
Classes de domínio
CLIENTE, PRODUTOS, SERVIÇOS, HORÁRIOS DISPONÍVEIS, DIÁRIAS, DISPONÍVEIS, FUNCIONÁRIO RESPONSÁVEL.


1 fluxo principal por caso de uso + 1 alternativa/erro (no máximo)


Realização do cadastro do cliente;
1.1. Cliente realiza cadastro ou realiza login quando já existe cadastro.
Validar e armazenar informações;
2.1. O sistema valida as informações e as armazena ou exibe uma mensagem de erro.
O sistema oferece serviços e o cliente seleciona o desejado;
3.1. O sistema oferece calendário para seleção de datas e serviços prestados disponíveis.
3.2. O cliente seleciona data e horário desejado o tornando indisponível para uma nova seleção.
O sistema exibe mensagem de sucesso.
4.1. O sistema exibe uma mensagem de agradecimento e que o horário foi reservado com sucesso.





