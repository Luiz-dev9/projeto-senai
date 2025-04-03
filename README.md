# desafio_1

SENAI AREIAS 

Programação Orientada a Objetos (POO) é uma abordagem de desenvolvimento de software que se baseia na criação e interação de objetos. Um objeto é uma entidade que combina dados e comportamentos, representando elementos do mundo real dentro do código. Esse paradigma facilita a organização e reutilização do código, tornando os programas mais estruturados e fáceis de manter. A POO possui quatro pilares fundamentais:

Abstração: Destaca as características essenciais de um objeto e oculta os detalhes internos.

Encapsulamento: Restringe o acesso direto aos dados, garantindo maior segurança e controle.

Herança: Permite que uma classe compartilhe características e comportamentos com outra, reduzindo a duplicação de código.

Polimorfismo: Possibilita que um mesmo método tenha diferentes implementações dependendo do contexto.



Exemplo de Abstração:
 Em um aplicativo de transporte, o usuário solicita um carro, informa o destino e acompanha a viagem. Ele não precisa conhecer os detalhes internos do sistema, como cálculos de rota, processamento de pagamento ou comunicação com motoristas. Isso simplifica a experiência do usuário e mantém a complexidade oculta.


Exemplo de Encapsulamento:
 Suponha uma classe ContaBancaria com um atributo saldo, que é privado. O saldo só pode ser modificado por meio de métodos específicos, como depositar(valor) e sacar(valor), garantindo que nenhuma alteração indevida seja feita diretamente no atributo.

. Exemplo de Herança:
 Uma classe Veiculo pode conter atributos como marca, modelo e ano. A classe Carro pode herdar de Veiculo e adicionar características próprias, como quantidadePortas, sem precisar reescrever atributos comuns. Isso facilita a criação de novos tipos de veículos sem repetir código.


. Exemplo de Polimorfismo: 
Considere uma classe Animal com um método emitirSom(). Subclasses como Cachorro e Gato podem sobrescrever esse método para retornar "Latido" e "Miado", respectivamente. Assim, um mesmo método se comporta de forma diferente dependendo da classe que o implementa.


As  Vantagens da POO:

Organiza melhor o código, tornando-o mais compreensível.

Protege os dados, impedindo acessos indevidos.

Facilita a manutenção e a escalabilidade do sistema.

Permite a reutilização de código, evitando redundância.

Oferece flexibilidade para modificar e expandir funcionalidades.

# desafio_2

O que é um Sistema de Controle de Versões (VCS)?

Um Sistema de Controle de Versões (VCS) é como um "histórico de mudanças" para arquivos e projetos, especialmente no desenvolvimento de software. Ele registra todas as alterações feitas ao longo do tempo, permitindo que você volte a versões anteriores caso algo dê errado. Imagine que você está escrevendo um livro com um grupo de amigos—sem um VCS, seria um caos organizar quem mudou o quê e garantir que ninguém sobrescreva o trabalho do outro. Com um VCS, cada mudança fica documentada, e várias pessoas podem trabalhar no mesmo projeto ao mesmo tempo sem conflitos. Além disso, se um erro for cometido, basta restaurar uma versão anterior sem precisar refazer tudo do zero. Esse sistema também permite criar versões paralelas do projeto para testar novas ideias sem afetar a versão principal.

5 Vantagens de usar um VCS:

 Rastreamento de alterações – Você pode ver quem mudou o quê e quando, facilitando o entendimento do projeto.


 Colaboração eficiente – Várias pessoas podem editar os arquivos ao mesmo tempo sem correr o risco de bagunçar tudo.


 Segurança contra perda de dados – Se algo der errado, você pode recuperar versões anteriores sem desespero.


 Organização do projeto – Manter um código limpo e bem documentado fica muito mais fácil.


 Testes sem medo – Criar versões separadas para testar novas funcionalidades sem afetar o código principal.


 Exemplos de VCS:

 Git – O mais popular e usado em grandes projetos, como os hospedados no GitHub e GitLab.


 Subversion (SVN) – Um sistema mais tradicional, ainda usado por algumas empresas.


 Mercurial – Uma alternativa ao Git, conhecida por ser mais simples de usar.

