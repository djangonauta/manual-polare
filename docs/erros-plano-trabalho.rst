Planos de Trabalho
==================

O tipo do plano de trabalho não pode ser diferente da modalidade PGD
--------------------------------------------------------------------

A modalidade presencial antiga foi suspensa no sistema segundo orientação da PROGEP. Caso seja necessário
registrar uma modalidade de trabalho completamente presencial, o modelo PGD deve ser editado, excluindo os
horários presenciais e em seguida escolher "Teletrabalho Parcial (Hibrido)", selecionar todos os dias da
semana, no campo modalidade, escolher "Presencial", além de preencher os horários.

Um modelo PGD que foi atualizado precisa homologado novamente pela chefia.

.. figure:: /_static/img/modelo-pgd.jpg


Exclusão de planos de trabalho
------------------------------

O polare não permite a exclusão de planos de trabalho homologados. Caso existam dois, ou mais planos, o
usuário deverá alterar o ano dos planos de trabalho com erro para um ano que não seja o atual e salvá-los. O
plano correto deve ser atualizado para o ano atual e em seguida enviado para homologação e ser aprovado por
**chefia da mesma unidade**. Com isso será registrado no sistema apenas um plano de trabalho homologado no ano
atual.


Lista de atividades do plano de trabalho está vazia
---------------------------------------------------

É necessário que exista um plano de entregas da unidade **homologado** para a **mesma unidade e ano** do plano
de trabalho.

É possível consultar planos de entregas da unidade no menu de planos. Será necessário verificar se a unidade
(número) e o ano são os mesmos do plano de trabalho do servidor:

.. figure:: /_static/img/consulta-plano-entrega.png

Caso o plano de entregas da unidade não exista, o chefe da unidade deverá cadastrá-lo e enviá-lo para ser
homologado por **chefia de unidade superior**.

Em alguns casos o Polare atualiza o ano do plano de entregas da unidade para 0 (zero). Nesse caso a DTI deve
ajustar o ano do plano de entregas da unidade diretamente no banco de dados do Polare. A ID do plano é exibida
a URI de acesso do mesmo:

.. figure:: /_static/img/url-plano.png

.. danger::
    Toda e qualquer alteração em registros deve ser primeiramente executada em banco de dados local para testes
    antes de ser aplicada no banco de dados de produção.

SQL
***

.. code:: sql

    update polare.plano_gerencial_unidade set ano=2024 where id=<id_plano>;