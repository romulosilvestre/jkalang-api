
<h2>JKalang</h2>

<p>Um projeto de aulas particulares para atender alunos. Essa aula vai estar associada em um curso e este terá uma área de especialização. O projeto terá o valor da aula e datas para auxiliar a regra de negócio para calcular o valor das aulas e mostrar tanto para o aluno como para o  professor um controle das aulas e dos valores das aulas.</p>

Segue a modelagem conceitual do projeto:<br>

![modelo relacional do projeto](imagens/ModeloRelacional.png)

Segue conteúdo programático do treinamento:<br>

Branch	Descrição<br>
1	    Código Base no GitHub<br>
2	    README.md<br>
3	    Apresentação do Projeto<br>
4	    Requisitos Funcionais e Não Funcionais<br>
5	    Casos de Uso<br>
6	    Clone da Aplicação Base<br>
7	    Configurações iniciais no projeto<br>
8	    Buscando Professor<br>
9	    Criando o modelo do professor<br>
10	    Criando DTOs e Mappers<br>
11	    Implementando a rota de busca de professores<br>
12	    Detalhes do Professor – implementando as rotas e tratando exceções<br>
13	    Cadastro do Aluno + Manipular a Foto do Aluno<br>
14	    Cadastro do Curso, Cadastro da Área de Concentração, Cadastro da Aula<br>
15	    Validação do Email e Validação da Senha<br>
16	    Spring Security<br>
17	    Login + JWT<br>
18	    Atualizando professor e modificando para trabalhar com fotos<br>
19	    Listar os alunos<br>
20	    Excluir dados<br>
21	    Deploy do Projeto<br>

#### Branch 1 - Código Base no GitHub
_O professor irá deixar o código base para o ínicio do treinamento_

#### Branch 2 - Melhorando o seu README.d
_É importante conhecer o Git e GitHub, bem como realizar um curso básico de versionamento_ 
* Nesse link abaixo, você vai acessar um manual do markdown, para estudar como formatar o seu README.md 
* [Manual do Markdown](https://docs.pipz.com/central-de-ajuda/learning-center/guia-basico-de-markdown#open)

#### Branch 3 - Apresentando o Projeto
_Status: Em Desenvolvimento_ ⚠️
* Esses emogis estão no link [Emogis](https://emojipedia.org/warning/)

__Rotas:__  <br>
<table>
   <tr>
      <td>Rota</td>
      <td>Método</td> 
      <td>Descrição</td>     
      <td>Requer autenticação</td>     
   </tr>
   <tr>
      <td>/api/professores/{professor_id}</td>
      <td>GET</td>
      <td>Lista os professores</td>     
      <td>Não</td>       
   </tr>   
     <tr>
      <td>/api/professores/{professor_id}/alunos</td>
      <td>POST</td>
      <td>Detalhes do Professor</td>     
      <td>Não</td>       
   </tr> 
</table>

__Requisitos Funcionais:__ <br>
xxx.xxx <br>
__Requisitos Não Funcionais:__ <br>
xxx;xxx <br>
__Casos de Uso:__ <br>
xxx.xxx <br>
__Tecnologias Utilizadas:__  <br>
<table>
   <tr>
      <td>Spring Framework</td>
      <td>Java</td> 
      <td>MySQL</td>         
   </tr>
   <tr>
      <td>xx.xx</td>
      <td>xx.xx</td>
      <td>xx.xx</td>         
   </tr>   
</table>

__Como deve executar esse projeto:__ <br>
xxx.xxxx


