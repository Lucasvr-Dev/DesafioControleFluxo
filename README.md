# 🔄 Desafio Controle de Fluxo

Projeto desenvolvido como parte da **Trilha Java Básico** da [Digital Innovation One (DIO)](https://www.dio.me/), com o objetivo de praticar conceitos de controle de fluxo e exceções customizadas em Java.

---

## 📋 Sobre o Desafio

O programa recebe dois números inteiros via terminal e realiza uma contagem incremental entre eles. Caso o primeiro parâmetro seja maior que o segundo, uma exceção personalizada é lançada.

### Regras de negócio

- O usuário informa dois parâmetros numéricos inteiros via terminal.
- O sistema realiza um `for` contando do primeiro até o segundo parâmetro, imprimindo cada incremento.
- Se o **primeiro parâmetro for maior que o segundo**, o sistema lança a exceção customizada `ParametrosInvalidosException` com a mensagem:
  > *"O segundo parâmetro deve ser maior que o primeiro"*

### Exemplo de execução

```
Digite o primeiro parâmetro
12
Digite o segundo parâmetro
30
Imprimindo o número 1
Imprimindo o número 2
...
Imprimindo o número 18
```

---

## 🏗️ Estrutura do Projeto

```
DesafioControleFluxo/
├── src/
│   ├── Contador.java                  # Classe principal com a lógica do programa
│   └── ParametrosInvalidosException.java  # Exceção customizada de negócio
├── bin/                               # Arquivos compilados (.class)
└── .vscode/                           # Configurações do VS Code
```

---

## 🛠️ Tecnologias

- **Java** (JDK 11+)
- **Visual Studio Code** com extensão Java

---

## 🚀 Como executar

### Pré-requisitos

- [JDK 11+](https://www.oracle.com/java/technologies/downloads/) instalado
- [VS Code](https://code.visualstudio.com/) com o [Extension Pack for Java](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-java-pack) (opcional)

### Via terminal

```bash
# Clone o repositório
git clone https://github.com/Lucasvr-Dev/DesafioControleFluxo.git

# Acesse a pasta do projeto
cd DesafioControleFluxo

# Compile
javac src/ParametrosInvalidosException.java src/Contador.java -d bin

# Execute
java -cp bin Contador
```

### Via VS Code

Abra a pasta do projeto no VS Code e execute a classe `Contador.java` com o botão **Run**.

---

## 📚 Conceitos praticados

- Estruturas de controle (`for`, `try/catch`)
- Criação de exceções customizadas (`extends Exception`)
- Leitura de dados via `Scanner`
- Orientação a objetos em Java

---

## 🎓 Créditos

Desafio proposto pelo professor **Gleyson Sampaio** na plataforma **DIO** — Trilha Java Básico.

---

## 👤 Autor

**Lucas** — [@Lucasvr-Dev](https://github.com/Lucasvr-Dev)
