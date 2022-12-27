# Api_totem

![Badge em Desenvolvimento](http://img.shields.io/static/v1?label=STATUS&message=EM%20DESENVOLVIMENTO&color=GREEN&style=for-the-badge)
Projeto de Implementação de um CRUD para consulta de linhas de ônibus usando a metodologia ágil Programing XP

Link para acessar a documentaçao no google docs: https://docs.google.com/document/d/1Oj3ejroutEpbB5wCJmfBzQdl8oQN3vks2wnDTzkJL1o/edit?usp=sharing

## DOR (Definition of Ready)
* A história segue o padrão INVEST.
* O(s) critério(s) de aceite estão claros.
* Banco de dados da aplicação.
* Design pronto.
* Os critérios de aceitação estão bem definidos.
* Os testes de aceitação devem ser escritos no padrão BDD.


## DOD (Definition of Done)
* As funcionalidades atende aos critérios de aceite.
* Orientação a teste.
* Principais funcionalidades da API.
* Código em pares.
* Criar a interface do usuário.
* Código revisado.

## História de Usuarios

<table class="tg">
<thead>
  <tr>
    <th class="tg-0pky"><span style="font-weight:bold">Cartão:</span> 02</th>
    <th class="tg-0pky"><span style="font-weight:bold">Projeto:</span> Totem de Consulta das Linhas de Ônibus de São Luís</th>
    <th class="tg-0pky"><span style="font-weight:bold">Estimativa:</span> 03</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-0pky" colspan="2"><span style="font-weight:bold">Nome da História: </span> Obter linhas de Ônibus</td>
    <td class="tg-0pky"><span style="font-weight:bold">Data:</span> 23/11/2022</td>
  </tr>
  <tr>
    <td class="tg-0pky" colspan="2"><span style="font-weight:bold">História:</span> Como usuário do Transporte Público de São Luís preciso de uma interface que me permita visualizar as linhas de ônibus baseado em uma consulta por terminal.
</td>
    <td class="tg-0pky"><span style="font-weight:bold">Critério(s) de Aceitação:</span><br><br>*Dado que o usuário logado é um Usuário do Transporte Público de São Luís/Quando informado um o nome de um terminal e o botão[BUSCAR] for clicado/Então deverá verificar se o terminal existe previamente cadastrado e exibir, caso o mesmo já exista, as linhas que passam por ele.<br><br>*Dado que o usuário logado é um Usuário do Transporte Público de São Luís/Quando o botão [BUSCAR] for clicado/Então devem ser listados todos os terminais cadastrados caso o usuário não tenha informado uma chave de pesquisa ou então buscar pela chave de pesquisa informado no campo nome do terminal e trazer os terminais que coincidem com a chave;
<br><br>Terminais não cadastrados não podem ser visualizados;<br><br></td>
  </tr>
  <tr>
    <td class="tg-0pky" colspan="2"><span style="font-weight:bold">Observações: </span> Para nossa aplicação precisamos do nome de um terminal que já se            encontre cadastrado no banco de dados.
    </td>
    <td class="tg-0pky"><span style="font-weight:bold">Risco:</span> Baixo <br><br>Este item será utilizado para identificar as linhas que passam por                 terminais.<br></td>
    <br>
  </tr>
</tbody>
</table>


## Tarefas (Padrão SMART)

Id  |Tarefa                                                             | Tempo de Execução (Dias) | Resposavel
:--:| :---------                                                        | :------:                 | :---------: 
01  | Configurar o banco de dados e inserir os dados                    | 1                        | Paulo
02  | Desenvolver a interface de usuário                                | 1                        | Italo
03  | Desenvolver o front-end da aplicação                              | 2                        | Italo
04  | Desenvolver o back-end                                            | 2                        | Italo
05  | Criar a query de consulta no banco                                | 1                        | Italo
06  | Criar função de consulta                                          | 1                        | Italo
07  | Criar testes para os valores digitados pelos Usuários             | 2                        | Paulo
08  | Criar testes para a função de busca                               | 2                        | Paulo
09  | Criar testes de verificação dos dados mantidos no Banco de Dados  | 3                        | Paulo

