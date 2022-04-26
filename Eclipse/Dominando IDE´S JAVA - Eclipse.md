# Dominando IDE´S JAVA - Eclipse

### Java => Programação Orientada a Objetos(POO) / 90's 

- Grande vantagem: Não roda apenas em um único Sistema Operacional (S.O) ou hardware, pois seus programas rodam através de uma Máquina Virtual (VM) que pode ser emulado.

- Java EE (web), SE, ME(móveis e embarcados).

  

  ## Fases de execução: 

  1. Escrever o código-fonte (.java);
  2. Kit Java Desenvolvedor (JDK) -  (compilar) (.class); 
  3. Java Virtual Machine (JVM) - execução); 
     - versões Java: OpenJDK (open source - gratuito) / JDK Oracle (pago)



####  		OpenJDK (instalar):

- IDE =>Ambiente de desenvolvimento integrado; são ferramentas; (GUI)
  	- instalando no Windows:
  	- WINDOWS + R => (executar) CMD => java -- version (verificar se tem java instalada na máquina)
  	- Download no site zulu (https://www.azul.com/downloads/?package=jdk#download-openjdk)
  	- Descompactar em C://Arquivo de Programas/Java/ (criar uma nova pasta java e copiar o arquivo zulu....)
  	- Clicar no Iniciar => (digitar na barra de pesquisa) => VAR => Abrir variáveis do sistema => Clicar em avançado => clicar em Variáveis de ambiente => em variáveis do sistema clicar em path => Clicar em editar => Clicar em Novo => Colar => Mover pra cima até ficar m primeiro.
- Instalando o ECLIPSE IDE:
  - Download no site : [Eclipse Downloads | The Eclipse Foundation](https://www.eclipse.org/downloads/)
  - Executar e instalar o Eclipse IDE for Enterprise and Web Developers.



## Criando o primeiro projeto com o Eclipse

- Abrir o Eclipse
  - se quiser mudar a perspectiva apertar (Ctrl + 3) e digitar o que você quer. No nosso caso é o JAVA.
  - Clicar em Create a Java project ou Crtl + N (project -> Java project) ou File -> New -> Java project.
    - src -> Ctrl + N -> (digitar) class -> package -> "com.dio" (nome do pacote) -> public "Primeiro Programa" (nome do programa) -> marcar a opção public static void main (String args[]) ou digitar sysout e pressionar ctrl + barra de espaço (a IDE auto-completa com systemOut.println()) -> Após digitar tudo clicar em Run As (automaticamente ele salva e roda).
- ATALHOS: 
  - mudar cor: WINDOWS -> Preference -> General -> Appearance -> Theme: Dark (existem outra opções - prefiro essa) -> Apply
  - mudar fonte: WINDOWS -> Preference -> General -> Appearance -> Color and Fonts -> Java -> Java Editor Text Font -> Edit
  - mudar class (alterar package): em cima do pacote aperta F2 -> Renomear e continuar ou Refector (ALT + SHIFT + N) ou class Ctrl +N
  - Expandir arquivo -> Ctrl + M
  - Inserir construtores: 
    - Ctrl + 3 (digitar constructor) => clicar em: Generate Constructor using Field 
    - Ctrl + 3 (digitar getter) => clicar em: Generate Getters and Setters 
    - Ctrl + 3 (digitar equals) => clicar em: Generate hashcode() and equals
    - Ctrl + 3 (digitar toString) => clicar em: Generate to String
  - Mudar de lugar (caso esteja fora de ordem): alt + seta pra cima ou pra baixo
  - Refatorar (identação): Ctrl + SHIFT + F
  - Importar: Ctrl + SHIFT + O