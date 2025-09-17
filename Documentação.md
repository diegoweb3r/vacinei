# Vacinei
## Visão do produto
<div align="justify">
<b>Vacinei</b> é uma carteira de vacinação digital, permite ao cidadão incluir, guardar, visualizar e compartilhar seus registros de vacinas de forma segura.   
<h3> Atores</h3>
<ul>
<li>Usuário final: Inclui, visualiza, e compartilha vacinas</li>
</ul>

<h3> MVP </h3>
<ol>
<li>Lading page</li> 
<li>Pagina de criar conta</li> 
<li>Pagina de login</li> 
<li>Area logada > visualização das vacinas</li> 
<li>Area logada > inclusão manual de vacinas</li> 
<li>Area logada > edição manual de vacinas</li> 
<li>Area logada > exclusção manual de vacinas</li> 
<li>Area logada > pagina de configurações</li> 
<li>Area logada > alteração de dados no perfil</li> 
<li>Area logada > exclusão de perfil</li> 
<li>Area logada > visualização de dados no perfil</li> 

<h3> Requisitos Funcionais </h3>

| ID     | Requisito Funcional (descrição clara)                                   | Prioridade (Alta/Média/Baixa) | Critério de Aceitação (como saber se está pronto)          | Observações |
| ------ | ----------------------------------------------------------------------- | ----------------------------- | --------------------------------------------------------- | ----------- |
| RF001  | Website com telas: inicial, sobre e fale conosco                        | Alta                          | Usuário acessa `vacinei.com.br` e navega entre as páginas | Website inicial da aplicação web |
| RF002  | Tela de criação de conta com e-mail, nome completo, data de nascimento e sexo | Alta | Usuário consegue criar conta com validação dos campos obrigatórios | Formulário em card para coleta de dados |
| RF003  | Usuário pode adicionar vacina manualmente                               | Alta                          | Registro salvo e exibido na carteira de vacinas           | Validar campos obrigatórios |
| RF004  | Usuário pode editar vacina manualmente                                  | Alta                          | Alteração salva e refletida na carteira de vacinas        | Validar campos obrigatórios |
| RF005  | Usuário pode excluir vacina manualmente                                 | Alta                          | Registro removido da carteira e do banco de dados         | Exclusão confirmada |
| RF006  | Usuário pode excluir conta                                              | Alta                          | Conta removida e usuário redirecionado à página inicial   | Exclusão confirmada no banco de dados |
| RF007  | Usuário pode editar conta                                               | Alta                          | Alterações salvas e refletidas no perfil do usuário       | Informações atualizadas |

<h3>Requisitos Não </h3>

| ID     | Requisito Não Funcional (descrição clara)               | Prioridade (Alta/Média/Baixa) | Critério de Aceitação (como saber se está pronto)             | Observações |
| ------ | ------------------------------------------------------- | ----------------------------- | ------------------------------------------------------------ | ----------- |
| RNF001 | O sistema deve ser responsivo                           | Alta                          | Site acessível em desktop, tablet e smartphone sem quebras    | Testar em diferentes resoluções |
| RNF002 | O site deve ter boa usabilidade                         | Alta                          | Usuário consegue concluir ações básicas em até 3 cliques      | Avaliar com teste de uso simples |
| RNF003 | O carregamento inicial deve ser rápido                  | Alta                          | Página inicial carregada em até 3 segundos                   | Testar em internet comum (4G/Wi-Fi) |
| RNF004 | O design deve seguir identidade visual simples e clara  | Média                         | Paleta de cores e fontes padronizadas em todas as telas       | Definir guia de estilo básico |
| RNF005 | O sistema deve estar disponível na maior parte do tempo | Baixa                         | Usuário consegue acessar o site em 95% do tempo de testes     | Focado em ambiente local/teste |

<h3>Arquitetura proposta</h3>
<b>Frontend:</b> HTML, CSS e Javascript   

<b>Backend:</b> Javascript   

<h3>Modelagem de dados</h3>
<b>User:</b> id, nome, email, data_nasc, sexo, created_at

<b>VaccineType:</b> id, nome_comercial, fabricante, data_aplic