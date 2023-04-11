# Resumo do Livro Padrão De Projeto do GoF

<img alt="Paulo-Spring" height="800" width="800" src="https://user-images.githubusercontent.com/88008441/229867908-ae89292b-efeb-45a9-a53b-b03e450416af.png">

#

GoF, ou "Gang of Four" se refere à um grupo de quatro grandes nomes no desenvolvimento (Erich Gamma, Richard Helm, Ralph Johnson, John Vlissides) que catalogaram 23 padrões de projeto no seu livro Design Patterns: Elements of Reusable Object-Oriented Software, em 1995. A grande maioria destes padrões continuam famosos até hoje e são peças fundamentais em diversas aplicações e frameworks modernos.

# Importancia dos Padrões 

Os padrões de projeto são soluções testadas e comprovadas para problemas comuns de desenvolvimento de software. Eles representam uma abordagem sistemática para projetar, desenvolver e manter software de alta qualidade.

A importância dos padrões de projeto no desenvolvimento de sistemas é múltipla. Eles ajudam a melhorar a qualidade, a produtividade e a manutenção do código, tornando-o mais fácil de entender, modificar e evoluir. Além disso, os padrões de projeto promovem a reutilização de código e a padronização do design, o que pode economizar tempo e esforço na criação de novos sistemas.

Outra grande vantagem dos padrões de projeto é que eles permitem a comunicação eficiente entre os membros da equipe de desenvolvimento. Os padrões fornecem uma linguagem comum que pode ser usada para discutir soluções de design e problemas de software.

Por fim, os padrões de projeto são uma parte essencial do processo de desenvolvimento de software, pois podem ajudar os desenvolvedores a criar sistemas mais eficientes, escaláveis e robustos. Com a utilização de padrões, é possível criar softwares mais confiáveis e de qualidade, que atendam às necessidades dos usuários e dos negócios.


# Padrões de Projeto Criacionais

- ## Factory: é um padrão criacional que fornece uma interface para criar objetos em uma superclasse, mas permite que as subclasses alterem o tipo de objetos que serão criados. O objetivo deste padrão é fornecer uma maneira flexível e extensível de criar objetos sem expor a lógica de criação.

- ## Abstract Factory: é um padrão criacional que fornece uma interface para criar famílias de objetos relacionados ou dependentes sem especificar suas classes concretas. O objetivo deste padrão é fornecer uma maneira de criar objetos relacionados de forma flexível e extensível, sem precisar conhecer os detalhes de implementação.

- ## Singleton:  é um padrão criacional que garante que uma classe tenha apenas uma instância e fornece um ponto global de acesso para essa instância. O objetivo deste padrão é garantir que haja apenas uma instância de uma classe em todo o sistema, permitindo que as informações sejam compartilhadas de forma consistente entre várias partes do sistema.

- ## Builder: é um padrão criacional que separa a construção de um objeto complexo de sua representação, permitindo que o mesmo processo de construção possa criar diferentes representações. O objetivo deste padrão é fornecer uma maneira flexível e extensível de criar objetos complexos sem ter que criar diferentes construtores para cada combinação possível de parâmetros.

- ## Prototype:  é um padrão criacional que permite a criação de novos objetos por meio da cópia de objetos existentes, em vez de criar novos objetos do zero. O objetivo deste padrão é fornecer uma maneira flexível e extensível de criar objetos, permitindo que as informações sejam copiadas de objetos existentes em vez de ter que criar novos objetos a partir do zero.

# Padrões Estruturais

- ## Adapter: é um padrão estrutural que converte a interface de uma classe em outra interface esperada pelo cliente. O objetivo deste padrão é permitir que classes com interfaces incompatíveis trabalhem juntas, facilitando a reutilização de código existente.

- ## Bridge:  é um padrão estrutural que separa a abstração de sua implementação, permitindo que ambas possam variar independentemente uma da outra. O objetivo deste padrão é desacoplar a abstração da sua implementação, permitindo que ambas possam ser modificadas independentemente sem afetar o outro.

- ## Composite: é um padrão estrutural que permite tratar objetos individuais e grupos de objetos da mesma maneira, formando uma estrutura hierárquica de objetos. O objetivo deste padrão é permitir que objetos individuais e grupos de objetos possam ser tratados da mesma maneira, facilitando a criação de estruturas hierárquicas de objetos.

- ## Decorator: é um padrão estrutural que permite adicionar comportamento a um objeto existente dinamicamente, sem modificar sua estrutura básica. O objetivo deste padrão é permitir que comportamentos adicionais possam ser adicionados a um objeto existente sem ter que criar uma nova classe para cada variação.

- ## Facade: é um padrão estrutural que fornece uma interface simplificada para um conjunto complexo de classes, ocultando a complexidade do sistema e fornecendo um ponto de entrada único. O objetivo deste padrão é simplificar o uso de um conjunto complexo de classes, fornecendo uma interface unificada e simplificada.

- ## Flyweight: é um padrão estrutural que permite compartilhar objetos que possuem estados semelhantes para reduzir a quantidade de memória e recursos necessários. O objetivo deste padrão é minimizar o uso de memória e recursos, permitindo que objetos com estados semelhantes possam ser compartilhados em vez de criar novos objetos para cada estado.

- ## Mediator: é um padrão comportamental que define um objeto que encapsula como um conjunto de objetos interagem, promovendo o desacoplamento entre os objetos. O objetivo deste padrão é desacoplar os objetos, permitindo que eles interajam de maneira flexível e independente.

- ## Proxy: é um padrão estrutural que fornece um substituto ou um espaço reservado para outro objeto para controlar o acesso a esse objeto. O objetivo deste padrão é controlar o acesso a um objeto, permitindo que um objeto substituto seja usado em vez do objeto real, o que pode ser útil para proteger o objeto real ou reduzir o tempo de inicialização.

# Padrões Comportamentais

- ## Chain of Responsability: é um padrão comportamental que permite que um conjunto de objetos manipule uma solicitação em cascata, cada objeto decidindo se a solicitação deve ser tratada ou passada para o próximo objeto da cadeia. O objetivo deste padrão é desacoplar o remetente de uma solicitação do seu receptor, permitindo que mais de um objeto tenha a oportunidade de tratar a solicitação.

- ## Command: é um padrão comportamental que encapsula uma solicitação em um objeto, permitindo que você faça solicitações diferentes, enfileire ou registre solicitações e implemente recursos como desfazer e refazer. O objetivo deste padrão é permitir que as solicitações sejam tratadas como objetos, facilitando sua manipulação e gerenciamento.

- ## Iterator: é um padrão comportamental que fornece um meio de acessar sequencialmente os elementos de um objeto agregado, sem expor sua representação subjacente. O objetivo deste padrão é desacoplar a coleção de objetos de sua representação interna, permitindo que os objetos possam ser percorridos de maneira uniforme e eficiente.

- ## Memento: é um padrão comportamental que permite capturar e restaurar o estado interno de um objeto sem violar o encapsulamento. O objetivo deste padrão é fornecer uma maneira de salvar e restaurar o estado interno de um objeto sem expor sua estrutura interna ou violar seu encapsulamento.

- ## Observer:  é um padrão comportamental que define uma dependência um-para-muitos entre objetos, de modo que quando um objeto muda de estado, todos os seus dependentes são notificados e atualizados automaticamente. O objetivo deste padrão é permitir que objetos dependentes possam ser notificados automaticamente quando um objeto mudar de estado, evitando a necessidade de consultas ou verificações constantes de estado.

- ## State: é um padrão comportamental que permite que um objeto altere seu comportamento quando seu estado interno muda, parecendo que o objeto mudou de classe. O objetivo deste padrão é permitir que o comportamento de um objeto mude dinamicamente de acordo com seu estado interno, sem exigir a criação de várias classes diferentes.

- ## Strategy: é um padrão comportamental que permite que um algoritmo seja selecionado dentre vários disponíveis dinamicamente, em tempo de execução. O objetivo deste padrão é permitir que diferentes algoritmos possam ser selecionados dinamicamente para executar uma tarefa específica, sem ter que modificar o código existente.

- ## Template Method: é um padrão comportamental que define o esqueleto de um algoritmo em uma classe, permitindo que subclasses especifiquem ou substituam etapas específicas sem modificar a estrutura do algoritmo. O objetivo deste padrão é permitir que diferentes implementações de uma tarefa possam ser definidas em subclasses, sem afetar a estrutura do algoritmo em si.
