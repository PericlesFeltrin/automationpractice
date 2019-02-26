# automationpractice
Automação com Selenium WebDriver + Junit + Cucumber + Maven

##### Caso de teste: realizar uma compra com sucesso.
1. Acessar o site: www.automationpractice.com.
2. Escolha um produto qualquer na loja.
3. Adicione o produto escolhido ao carrinho.
4. Prossiga para o checkout.
5. Valide se o produto foi corretamente adicionado ao carrinho e prossiga caso esteja tudo certo.
6. Realize o cadastro do cliente preenchendo todos os campos obrigatórios dos formulários.
7. Valide se o endereço está correto e prossiga.
8. Aceite os termos de serviço e prossiga.
9. Valide o valor total da compra.
10. Selecione um método de pagamento e prossiga.
11. Confirme a compra e valide se foi finalizada com sucesso.

### Requisitos:
- Java 1.8
- [Eclipse](https://www.eclipse.org/downloads/)
- Navegador [Chrome](https://www.google.com/intl/pt-BR_ALL/chrome/)

#### Estrutura de arquivos
`src/main/java/`
 - `Generics/` - Contém os métodos genericos.
 - `Pages/` - Contém os componentes/telas/objetos mapeados do teste.

`src/test/java/`
 - `Fearure/` - Contém as features do cucumber.
 - `Runs/` - Contém os arquivos para execuções de teste.
 - `Step/` - Contém os steps para da feature do cucumber.

`automationpractice/`
- `drivers/` - Contém os drivers dos navegadores.
- `Log/` - Contém as evidências de execução.

#### Execução
Obs.: Atualizar os arquivos maven antes de realizar a execução.
##### Com JUnit
Para executar o teste desenvolvido com Selenium Webdriver e Junit, você deve executar o seguinte arquivo: `src/test/java/Runs/RunJUnit.java`.

##### Com Cucumber
Para executar o teste desenvolvido com Selenium Webdriver, JUnit e Cucumber, você deve executar o seguinte arquivo: `src/test/java/Runs/RunCucumber.java`.


#### Evidências
A cada execução do script é gerada uma nova pasta para armazenar os screenshots da execução. Essas pastas são armazenada em `automationpractice/Log/`.
