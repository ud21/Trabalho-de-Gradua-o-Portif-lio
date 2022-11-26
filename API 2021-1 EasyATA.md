### Projeto Integrador 2021-1: EasyATA
<img src="https://i.imgur.com/Zn4ICGa.png" width="200"/>

#### Parceiro Acadêmico

IACIT - Fundada em 1986, e com sede em São José dos Campos, a IACIT conta com produtos e sistemas totalmente exclusivos, internacionalmente reconhecidos. Segundo a empresa: "O propósito da IACIT é produzir tecnologia e soluções fundamentais para autonomia nacional, colocando o Brasil na vanguarda tecnológica mundial".

[Site do Parceiro Acadêmico](https://www.iacit.com.br)

#### Visão do Projeto
Foi apresentado pelo cliente a grande dificuldade no gerenciamento de suas reuniões, documentadas através das atas. junto com a equipe, foi desenvolvida uma solução para tornar o processo das reuniões algo prático e seguro.

O EasyATA foi desenvolvido com as funcionalidades de cadastro, controle de acesso, geração e monitoramento de atas, além de possuir o recurso da assinatura digital. O acesso de usuário é feito através de 3 perfis: Administrador, Colaboradores e Gerentes, que poderam cadastrar as atas informando os seguintes dados: Participantes (nomes), data, hora e assunto. O sistema conta com outras funcionalidades como alteração, exclusão e visualização de atas cadastradas. Por fim, se for desejado, o usuário pode ainda exportar o documento para PDF ou Excel. O objetivo do EasyATA é proporcionar simplicidade no gerenciamento e acesso às reuniões.

#### Requisitos Funcionais
 - Cadastro de Usuários, Cadastro de Perfil de Acesso, Cadastro de modelo de ata de Reunião;
	 - O cadastro de usuário deve conter os seguintes campos: Nome, Título/Cargo,Área/Empresa, E-mail e Telefone;
	 - Todo usuário deve ter pelo menos um perfil de acesso;
	 - O perfil de acesso define quais funcionalidades o usuário pode acessar:
		 - Administrador: Acesso total ao sistema.
		 - Usuário: Acesso ao cadastro do modelo de ata de reunião, a geração de ata de reunião, ao monitoramento de ata de reunião e à imprimir ata de reunião em PDF e Excel.
		 - Gerência: Acesso aos relatórios do sistema, à aprovação do modelo de ata de reunião e a imprimir ata de reunião em PDF e Excel.
 - Login; Logout;
 - Gerar Ata de Reunião;
 - Monitorar Ata de Reunião;
	 - Uma Ata de Reunião pode ter os seguintes estados: Nova, Revisada, Assinada e Enviada.
 
#### Requisitos Não Funcionais
 - Ser usual com dispositivos móveis;
 - Linguagem Java;
 - Linguagens HTMLS, CSS, Angular ou React;
 - Registros de testes de todas as funcionalidades;
 - Estar disponível no idioma Português do Brasil.

#### Funcionamento
##### Login Administrador - Demonstração do sistema
<img src="https://user-images.githubusercontent.com/56441534/118378633-84fadc00-b5ab-11eb-957a-e740b1efa9e8.mp4" width="500"/>
  
**Link do git**

[EasyATA](https://github.com/DaviNeves0/EasyATA)

#### Tecnologias Utilizadas
 - **Java**: Em conjunto do framework Spring para criação do sistema web;
 - **Spring**: Framework java para criação de aplicações web;
 - **MySQL**: Sistema gerenciador de Banco de Dados Relacional. Utilizado para salvar os cadastros de usuários, seus níveis de acesso e o registro de novas Atas de Reunião, registrando todo o ciclo de vida de uma Ata de Reunião;
 - **HTML**, **CSS** e **JavaScript**: Criação e desenvolvimento do design da Interface do usuário;
 - **React**: Uma biblioteca JavaScript para criar interfaces de usuário.

#### Contribuições Pessoais
Contribui bastante na parte visual do projeto, tendo como principal atuação o frontend. Tive participação parcial ou total em todas as telas do sistema, trabalhando com responsividade, posicionamento dos itens e layout dos formulários, utilizando HTML e CSS para estilização, JS para funcionalidades adicionais e React para desenvolver a interface.

#### Hard Skills
 - Desenvolver páginas para um sistema web utilizando HTML, CSS e JS: Sei fazer com autonomia;
 - Criação de um sistema web utilizando React e Spring: Sei fazer com ajuda.
 
#### Soft Skills
 - Participação efetiva nas reuniões conforme a metodologia adotada (Scrum) e na entrega de resultados, trazendo discuções sobre o que poderia ser implementado para melhorar da usabilidade da aplicação.