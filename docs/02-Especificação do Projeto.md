# Especificações do Projeto

## Perfis de usuário

<table>
<tbody>
<tr>
<th colspan="2">Perfil 01: Administrador</th>
</tr>
<tr>
<td width="150px"><b>Descrição:</b></td>
<td width="600px">
Responsável pelo gerenciamento do sistema.
</td>
</tr>
<tr>
<td><b>Necessidades:</b></td>
<td>
1.​ Criar, editar e excluir perfis de usuários do sistema. 
</td>
</tr>
</tbody>
</table>

<table>
<tbody>
<tr>
<th colspan="2">Perfil 02: Gerente</th>
</tr>
<tr>
<td width="150px"><b>Descrição:</b></td>
<td width="600px">
Responsável pela administração dos cadastros de imóveis no sistema, leads e distribuição dos leads entre os corretores.
</td>
</tr>
<tr>
<td><b>Necessidades:</b></td>
<td>
1.​ Cadastrar e listar imóveis;<br>
2.​ Cadastrar leads;<br>
3.​ Listar e filtrar leads;<br>
4.​ Distribuir leads que ainda não têm um corretor responsável entre os corretores;<br>
5.​ Gerar relatório de performance dos corretores.
</td>
</tr>
</tbody>
</table>

<table>
<tbody>
<tr>
<th colspan="2">Perfil 03: Corretor</th>
</tr>
<tr>
<td width="150px"><b>Descrição:</b></td>
<td width="600px">
Profissional corretor de imóveis responsável por acompanhar leads e realizar vendas.
</td>
</tr>
<tr>
<td><b>Necessidades:</b></td>
<td>
1.​ Cadastrar e listar imóveis;<br>
2.​ Cadastrar leads;<br>
3.​ Listar e filtrar leads;<br>
4.​ Visualizar leads no formato kanban para acompanhar seu progresso;<br>
5.​ Ser alertado quanto ao prazo de andamento dos leads e as etapas do funil de vendas com base na data-limite.
</td>
</tr>
</tbody>
</table>

## Histórias de Usuários e Requisitos Funcionais

<table border="1" cellspacing="0" cellpadding="5">
    <thead>
        <tr>
            <th style="text-align: center;">ID</th>
            <th style="text-align: center;">Descrição do Requisito</th>
            <th style="text-align: center;" colspan="3">História</th>
            <th style="text-align: center;">Prioridade</th>
        </tr>
        <tr>
            <th></th>
            <th></th>
            <th style="text-align: center;">Eu como...</th>
            <th style="text-align: center;">Quero/Desejo/Preciso</th>
            <th style="text-align: center;">Para</th>
            <th></th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td><b>RF-01</b></td>
            <td>Permitir que o usuário realize login no sistema.</td>
            <td>Usuário</td>
            <td>fazer login no sistema</td>
            <td>ter acesso às funcionalidades que me cabem</td>
            <td>Alta</td>
        </tr>
        <tr>
            <td><b>RF-02</b></td>
            <td>Permitir que o usuário possa visualizar e editar seus dados</td>
            <td>Usuário</td>
            <td>visualizar e editar meus dados de usuário (nome, email, telefone etc)</td>
            <td>poder manter meus dados atualizados</td>
            <td>Alta</td>
        </tr>
        <tr>
            <td><b>RF-03</b></td>
            <td>Permitir que o usuário com perfil de administrador liste e visualize perfis.</td>
            <td>Administrador</td>
            <td>listar e visualizar perfis de usuários do sistema</td>
            <td>saber quais perfis estão utilizando o sistema</td>
            <td>Alta</td>
        </tr>
        <tr>
            <td><b>RF-04</b></td>
            <td>Permitir ao administrador cadastrar e editar perfis.</td>
            <td>Administrador</td>
            <td>cadastrar e editar perfis dos usuários do sistema e suas permissões</td>
            <td>garantir que usuários não tenham acesso a funcionalidades que não lhes cabem</td>
            <td>Alta</td>
        </tr>
        <tr>
            <td><b>RF-05</b></td>
            <td>Permitir que o usuário com perfil de gerente ou corretor cadastrar e editar leads.</td>
            <td>Gerente / Corretor</td>
            <td>cadastrar e editar leads</td>
            <td>registrar o interesse de compradores em potencial e convertê-los em vendas</td>
            <td>Alta</td>
        </tr>
        <tr>
            <td><b>RF-06</b></td>
            <td>Permitir que o usuário com perfil de gerente ou corretor possa filtrar os leads cadastrados aplicando diferentes critérios.</td>
            <td>Gerente / Corretor</td>
            <td>listar, visualizar e filtrar leads</td>
            <td>manter um controle dos leads cadastrados e ter uma visão ampla dos clientes em potencial</td>
            <td>Média</td>
        </tr>
        <tr>
            <td><b>RF-07</b></td>
            <td>Permitir que o usuário com perfil de gerente possa distribuir os leads entre os corretores cadastrados.</td>
            <td>Gerente</td>
            <td>distribuir leads para os corretores</td>
            <td>que os corretores possam convertê-los em vendas</td>
            <td>Média</td>
        </tr>
        <tr>
            <td><b>RF-08</b></td>
            <td>Permitir que o usuário com perfil de gerente ou corretor visualize, por meio de listas, todos os imóveis cadastrados por ele ou por corretores.</td>
            <td>Gerente / Corretor</td>
            <td>listar, visualizar e filtrar imóveis</td>
            <td>ter uma visão ampla dos imóveis à venda pela corretora</td>
            <td>Alta</td>
        </tr>
        <tr>
            <td><b>RF-09</b></td>
            <td>Permitir que o usuário com perfil de gerente ou corretor cadastre novos imóveis.</td>
            <td>Gerente / Corretor</td>
            <td>cadastrar e editar imóveis</td>
            <td>conectar potenciais compradores aos imóveis de seu interesse</td>
            <td>Alta</td>
        </tr>
        <tr>
            <td><b>RF-10</b></td>
            <td>Permitir que o usuário com perfil de corretor visualize, por meio de um quadro kanban, as etapas em que cada lead atribuído a ele se encontra.</td>
            <td>Corretor</td>
            <td>visualizar meus leads em forma de kanban</td>
            <td>organizar melhor minhas negociações e acompanhar/visualizar o progresso de cada lead</td>
            <td>Baixa</td>
        </tr>
        <tr>
            <td><b>RF-11</b></td>
            <td>Gerar relatórios de performance dos corretores</td>
            <td>Gerente</td>
            <td>gerar e visualizar relatórios de performance dos corretores</td>
            <td>acompanhar performance e  fomentar melhores estratégias de venda</td>
            <td>Baixa</td>
        </tr>
        <tr>
            <td><b>RF-12</b></td>
            <td>Acompanhar o progresso dos leads e do funil de vendas</td>
            <td>Gerente / Corretor</td>
            <td>visualizar um calendário com as próximas etapas do funil de vendas</td>
            <td>ser alertado na data de acesso, sobre os leads e as etapas do funil de vendas baseadas na data-limite</td>
            <td>Baixa</td>
        </tr>
    </tbody>
</table>


## Requisitos não Funcionais

