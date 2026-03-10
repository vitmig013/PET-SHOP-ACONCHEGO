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

### Introdução
Criada em julho de 2024, a Pet Shop Aconchego é uma empresa voltada 
aos cuidados de animais domésticos, especificamente cães e gatos.

Sua proprietária, a Sra. Maria Silva, sempre teve o sonho de se tornar 
empreendedora. Após trabalhar durante oito anos como funcionária em uma 
empresa de telemarketing, em 2024 conseguiu finalmente realizar esse objetivo, 
dando origem à Pet Shop Aconchego.

A empresa não possui sócios. A proprietária optou por administrar o negócio 
sozinha, pois, ao longo de sua experiência profissional, presenciou conflitos 
entre sócios em outras empresas, o que a motivou a seguir de forma 
independente.

Localizada na Rua Teodoro Sampaio, nº 1.212, no Bairro Pinheiros, em São 
Paulo/SP, a empresa conta com uma infraestrutura simples, porém adequada 
para oferecer conforto e segurança aos animais.

Atualmente, a Pet Shop Aconchego possui uma equipe formada por seis
funcionários: um gerente, um administrador, dois funcionários responsáveis 
pelos serviços de banho e tosa, e dois cuidadores que atuam na área da creche.

### Serviços Prestados

A Pet Shop Aconchego oferece serviços voltados ao cuidado e bem-estar 
de animais domésticos, atuando nas áreas de banho, tosa e creche.

Os serviços de banho e tosa são realizados por uma equipe composta por 
dois profissionais capacitados. A empresa possui capacidade para realizar cerca 
de 8 atendimentos por dia, totalizando aproximadamente 176 atendimentos 
mensais nos serviços de banho e tosa.

O serviço de creche funciona em período estendido, das 8h às 17h20, e 
conta com dois cuidadores responsáveis pelo acompanhamento e supervisão 
dos animais durante todo o período de permanência. A capacidade máxima de 
atendimento da creche é de 12 animais por dia.

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





