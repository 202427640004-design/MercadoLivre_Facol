# ðŸ›’ MercadoLivre_Facol

Projeto acadÃªmico desenvolvido em **Java** com base no padrÃ£o arquitetural **MVC (Model - View - Controller)**.  
O sistema simula um pequeno marketplace, permitindo **cadastro, listagem e manipulaÃ§Ã£o de produtos** de forma organizada.

---

## ðŸ“‚ Estrutura do Projeto

O projeto segue a arquitetura **MVC**, organizada da seguinte forma:

```
src/
 â”œâ”€â”€ Main.java              # Classe principal
 â”œâ”€â”€ model/
 â”‚    â””â”€â”€ Produto.java      # RepresentaÃ§Ã£o da entidade Produto
 â”œâ”€â”€ view/
 â”‚    â””â”€â”€ ProdutoView.java  # Interface de interaÃ§Ã£o com o usuÃ¡rio
 â”œâ”€â”€ controller/
 â”‚    â””â”€â”€ ProdutoController.java # Controla a lÃ³gica entre Model e View
 â””â”€â”€ repository/
      â””â”€â”€ ProdutoRepositorio.java # ResponsÃ¡vel pela persistÃªncia em memÃ³ria
```

- **Model** â†’ Representa os dados (ex.: `Produto`).  
- **View** â†’ Interface de saÃ­da/interaÃ§Ã£o com o usuÃ¡rio (ex.: `ProdutoView`).  
- **Controller** â†’ Faz a ponte entre *Model* e *View* (ex.: `ProdutoController`).  
- **Repository** â†’ Gerencia os dados em memÃ³ria, simulando um banco de dados.  

---

## âš™ï¸ PrÃ©-requisitos

- [Java JDK 8+](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html) instalado e configurado no `PATH`.  
- Terminal ou IDE de sua preferÃªncia (Ex.: **IntelliJ IDEA**, **Eclipse**, **VS Code**).

---

## ðŸš€ Como executar

1. **Clone o repositÃ³rio** ou extraia os arquivos do `.zip`.  
   ```bash
   git clone https://github.com/seu-usuario/MercadoLivre_Facol.git
   cd MercadoLivre_Facol
   ```

2. **Compile os arquivos Java**:  
   ```bash
   javac src/model/*.java src/view/*.java src/controller/*.java src/repository/*.java src/Main.java
   ```

3. **Execute o programa**:  
   ```bash
   java -cp src Main
   ```

---

## ðŸ’» Exemplo de uso

Ao executar o programa, vocÃª poderÃ¡:

- Cadastrar novos produtos  
- Listar todos os produtos disponÃ­veis  
- Buscar um produto especÃ­fico  
- Excluir produtos  

*(A interaÃ§Ã£o depende da lÃ³gica implementada em `ProdutoView`)*

---

## ðŸ”® PossÃ­veis melhorias

- PersistÃªncia em **banco de dados** (MySQL/PostgreSQL).  
- Interface grÃ¡fica com **JavaFX** ou **Swing**.  
- ImplementaÃ§Ã£o de testes unitÃ¡rios com **JUnit**.  
- IntegraÃ§Ã£o com APIs externas.  

---

## ðŸ‘¨â€ðŸ« InformaÃ§Ãµes acadÃªmicas

- **Disciplina**: ProgramaÃ§Ã£o  
- **Professor**: *Ricardo Correia*  
- **Autor**: *Jefferson Rodrigo*  
