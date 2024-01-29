Planos de entrega unidade
=========================

Muitas informações registradas no Polare são obtidas dos bancos de dados do SIG (SIGRH e SIGADMIN). Dados
referentes a unidades são obtidos do SIGRH e dados referentes a perfis de responsabilidade (chefia) são
obtidos do SIGADMIN. Boa parte dos problemas de funcionamento do Polare são resolvidos corrigindo os dados dos
servidores nesses sistemas.


Não é possível cadastrar Plano de Entrega da Unidade para uma unidade onde não há servidores lotados
----------------------------------------------------------------------------------------------------

Para cadastrar um plano de entrega da unidade é necessário que exista pelo menos um servidor **localizado** na
mesma unidade do plano.

É possível gerar um extrato de quais servidores estão localizados uma unidade. Esse relatório pode ser
obtido por um usuário com perfil de chefia de unidade no SIGRH:

.. figure:: /_static/img/portal-chefia.png

.. figure:: /_static/img/relatorio-menu.png

.. figure:: /_static/img/filtro-relatorio.png

.. figure:: /_static/img/relatorio-analitico.png

Caso não haja servidores localizados, o chefe do sertor deverá entrar em contato com a PROGEP para que a mesma
localize todos os servidores na unidade correta.

Pode ser necessário alterar a unidade de exercício do servidor antes de localizá-lo. Esse procedimento também
é realizado pela PROGEP.


Exclusão de planos de entrega da unidade
----------------------------------------

O polare não permite a exclusão de planos de entrega da unidade homologados. Caso existam dois, ou mais
planos, o usuário deverá alterar o ano dos planos de entrega da unidade com erro para um ano que não seja o
atual e salvá-los. O plano correto deve ser atualizado para o ano atual e em seguida enviado para homologação
e ser aprovado por **chefia de unidade superior**. Com isso será registrado no sistema apenas um plano de
entrega da unidade homologado no ano atual.


Vinculo de chefia não está aparecendo
-------------------------------------

