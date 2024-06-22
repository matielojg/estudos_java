# Arquitetura Java: Descomplicando Clean Architecture

## Introdução

Este curso aborda os princípios da Clean Architecture aplicada em projetos Java. Clean Architecture é um conjunto de diretrizes para estruturar sistemas de forma que sejam flexíveis, testáveis e de fácil manutenção.

## Conteúdo do Curso

### 1. Princípios da Clean Architecture
- **Independência de frameworks**: Evitar dependências diretas de frameworks.
- **Testabilidade**: Facilitar a escrita de testes automatizados.
- **Independência de UI**: Separar a lógica de negócio da interface de usuário.
- **Independência de banco de dados**: A lógica de negócio não deve depender de detalhes específicos de banco de dados.
- **Independência de agentes externos**: Separar a lógica de negócio de elementos externos, como APIs e serviços externos.

### 2. Estrutura de Camadas
- **Entities**: Representam as regras de negócio e objetos de negócio.
- **Use Cases**: Contêm a lógica de aplicação específica.
- **Interface Adapters**: Adaptadores que convertem dados entre a aplicação e a interface de usuário, banco de dados, ou outros sistemas.
- **Frameworks and Drivers**: Detalhes específicos de frameworks e drivers, como bancos de dados, interfaces de usuário, etc.

### 3. Implementação Prática
- **Criação de Entidades**: Definindo entidades de negócio.
- **Casos de Uso**: Implementando a lógica de aplicação.
- **Adaptadores e Interfaces**: Criando adaptadores e definindo interfaces.
- **Configuração de Frameworks**: Configurando frameworks e drivers.

### 4. Benefícios
- **Manutenibilidade**: Facilita a manutenção e evolução do sistema.
- **Flexibilidade**: Aumenta a capacidade de adaptação a mudanças.
- **Testabilidade**: Melhora a capacidade de testar o sistema de forma isolada.

## Conclusão

A Clean Architecture promove a construção de sistemas robustos e escaláveis, reduzindo a dependência de frameworks e facilitando a testabilidade e a manutenção.

Para mais detalhes, visite o curso na [Alura](https://cursos.alura.com.br/course/arquitetura-java-descomplicando-clean-architecture/task/153216).
