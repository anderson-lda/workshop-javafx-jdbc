# workshop-javafx-jdbc
Programa que permite a manipulação de um banco de dados MySQL através de uma interface gráfica, feito usando o SDK JavaFX. Foram utilizados também o JDK 11, MySQL e a IDE NetBeans.

Configurações (NetBeans):
Criar biblioteca javafx e importá-la no projeto;
Botão direito sobre o projeto -> properties -> libraries:
  adicionar a biblioteca javafx em run e em module path;
  adicionar em run, em VM options:
    --add-modules javafx.controls,javafx.fxml
