# Teste-automação utilizando a ferramenta selenium e seu recurso WebDriver.
Os arquivos deste repositório foram feitos para testes do sistema do senai e do sistema feito no curso de frontend no senai Limeira.
 ## Os recursos permitem fazer tete de sistema automatizado.

 ### Configuração de ambiente, passo a passo.


 * Instalar a ferramenta [Eclipse-IDE](https://www.eclipse.org/downloads/)

 * Instalar [JDK-8](https://www.oracle.com/java/technologies/downloads/)

 * Instalar o [Apache Maven](https://maven.apache.org/download.cgi)

 * Fazer o dpwnload do [WebDriver](https://chromedriver.chromium.org/downloads) na versão compátivel com o seu navegador,colocar o arquivo dentro do diretório: C:\Program Files\chrome-driver.

* Configuração das variáveis de ambiente:
  - 1° No menu do windows pesquise por variáveis de ambiente e clique em abrir.
  - 2° Clique em novo e preencha os campos sendo, Nome da variável: JAVA_HOME, & Valor da variável:  C:\Program Files\Java\jdk1.8.0_281
  - 3° Clique em novo mais uma vez, agora para informar o diretório em que está salvo o arquivo do maven como:Nome da variável: MAVEN_HOME, & Valor da variável:  C:\Program Files\apache-maven-3.6.3.
  - 4° Nas variáveis do sistema path editea colocando o diretório: C:\Program Files (x86)\Common Files\Oracle\Java\javapath
  - 5° na tela seuinte adicione as variáveis criadas(JAVA_HOME e MAVEN_HOME),para adicionar coloque: %JAVA_HOME%\bin e %MAVEN_HOME%\bin


* Para criar o projeto de testes automatizados no eclipse e o restante do passo a passo, você pode conferir a partir da página 51 do livro do [Senai.](https://bit.ly/3swXHJR)
