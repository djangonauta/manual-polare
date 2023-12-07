Entregas
========

Contém uma atividade carregada da lista de atividades do plano gerencial, além de outras informações. Possuem
um prazo (início e fim, que poder ser de dez dias), um tipo (Remoto, Presencial), status atual (Prevista, Em
execução, ou Finalizada) e um campo descrição onde é possível registrar o link do google drive contendo o
plano de trabalho do servidor.

**O cadastro de uma entrega não precisa de homologação**.

**Uma entrega só pode ser alterada durante o período do prazo**. Uma justificativa (que deve ser autorizada
pela chefia da unidade) pode ser cadastrada para a entrega solicitando prorrogação de 30 dias. Nesse caso a
entrega atual é cancelada (para fins de registro) e uma nova entrega com prazo final extendido é inserida no
sistema **para o próximo mês**. Essa nova entrega prorrogada pode ser visualizada alterando o filtro de busca
para o mês seguinte.

Uma entrega pode possuir subtarefas. Subtarefas podem ser utilizadas para descrever o que foi feito no prazo
de uma entrega. O campo de texto de uma subtarefa é livre e um servidor pode registrar demandas atendidas
em outros sistema (como o GLPI), números de processos (SIPAC), ou qualquer outra atividade, como envio de
e-mails, reuniões, etc.


.. figure:: /static/img/plano_gerencial_entregas.jpg
    :align: center

    Entrega (exemplo). Título da entrega (um campo de texto livre), junto com uma atividade que foi
    selecionada da lista de atividades do respectivo plano gerencial (cadastrado anteriormente). Duas
    subtarefas foram adicionadas, contendo os números dos chamados antendidos no GLPI durante o período da
    entrega.