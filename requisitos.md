# Levantamento de Requisitos — Trabalho DS

**Alunos:** Nathan Gabriel Affonso Cortello e Lucas Henrique Rodrigues Caldas  
**RMs:** 25068 e 25301  
**Professor:** Arnaldo Hidalgo  

---

# Requisitos Funcionais (RF)

## 1. Cadastro e Usuários

- **RF01:** O sistema deve permitir o cadastro dos usuários com informações além do e-mail e senha, como endereço, idade, CPF e número de telefone.
- **RF07:** O sistema deve verificar o cadastro do usuário antes de permitir a solicitação de algum produto.
- **RF16:** O usuário deve conseguir visualizar e editar seus próprios dados.

## 2. Login e Controle de Acesso

- **RF02:** O usuário deve poder realizar login utilizando suas credenciais de acesso, como e-mail ou telefone e senha.
- **RF06:** O sistema deve ter uma validação de login para impedir que usuários não autorizados acessem os mesmos campos disponíveis para os administradores.

## 3. Equipamentos, Máquinas e Categorias

- **RF03:** O administrador deve poder cadastrar, editar ou remover equipamentos e máquinas.
- **RF05:** O administrador deve ter acesso à disponibilidade dos equipamentos, podendo alterar a quantidade, o valor e o ID do produto.
- **RF11:** O administrador deve conseguir atualizar os status dos equipamentos ou máquinas e registrar suas manutenções, incluindo informações sobre a manutenção e a data em que foi realizada.
- **RF19:** O administrador deve conseguir cadastrar, editar e remover categorias de equipamentos.

## 4. Catálogo e Solicitações

- **RF08:** O sistema deve ter um catálogo de produtos para os usuários.
- **RF10:** O sistema deve ter um catálogo mostrando aos usuários os produtos disponíveis para solicitar, entre outras funcionalidades.
- **RF17:** O usuário deve conseguir solicitar equipamentos disponíveis para utilização.

## 5. Empréstimos, Devoluções e Agendamentos

- **RF13:** O sistema deve registrar os empréstimos de equipamentos, identificando o equipamento, o usuário responsável, a data do empréstimo e a data prevista para a devolução.
- **RF14:** O administrador deve conseguir consultar os agendamentos ou empréstimos feitos pelos usuários, podendo aceitar ou recusar as solicitações feitas pelos usuários.
- **RF18:** O usuário deve conseguir realizar agendamento de equipamentos, informando o período de utilização.
- **RF15:** O sistema deve ter uma parte contendo relatórios feitos pelos administradores, nos quais eles possam registrar o mau uso dos equipamentos ou máquinas que retornaram dos agendamentos dos usuários.

## 6. Relatórios e Dashboard

- **RF09:** O administrador deve conseguir gerar relatórios sobre os equipamentos, máquinas, empréstimos, devoluções, agendamentos e manutenções.
- **RF12:** O usuário deve conseguir consultar um relatório sobre suas ações realizadas no sistema, como empréstimos e agendamentos.
- **RF20:** O administrador deve conseguir visualizar um dashboard com informações sobre equipamentos, empréstimos, agendamentos e manutenção.

## 7. Comunicação

- **RF04:** O sistema deve ter mais de um meio de comunicação com os usuários caso haja qualquer tipo de problema.

---

# Requisitos Não Funcionais (RNF)

## 1. Responsividade e Compatibilidade

- **RNF01:** O sistema deve ter responsividade para todas as plataformas, como celular, tablet, desktop, entre outras.
- **RNF08:** O sistema deve funcionar corretamente nos navegadores e dispositivos definidos pelo projeto.

## 2. Segurança

- **RNF02:** As senhas dos usuários devem ser armazenadas de forma criptografada.
- **RNF03:** Usuários comuns não podem acessar áreas administrativas do sistema.
- **RNF04:** As informações dos usuários e equipamentos devem ser protegidas contra acessos não autorizados.

## 3. Desempenho

- **RNF05:** O sistema deve responder rapidamente às ações realizadas pelos usuários.
- **RNF10:** O sistema deve suportar o aumento da quantidade de usuários e equipamentos cadastrados sem comprometer seu desempenho.

## 4. Usabilidade

- **RNF06:** A interface do sistema deve ser fácil de entender e utilizar.

## 5. Integridade e Backup

- **RNF07:** Os dados de empréstimos, agendamentos, devoluções e manutenções não devem ser perdidos.
- **RNF09:** O sistema deve realizar cópias de segurança periódicas dos dados armazenados.