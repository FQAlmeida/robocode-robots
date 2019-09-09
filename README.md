# robocode-robots

## Etapas para instalar o robocode
 - Ter java JDK 8+ instalado, versão atual da Oracle: [JDK 12](https://www.oracle.com/java/technologies/jdk12-downloads.html)
    - Incluir o path do jdk no path do OS
    - Obs.: Esse repositório esta configurado para java 12, utilizando a extensão Java Dependency Viewer, comando Create Java Project, no VSCode
 - Baixar e instalar o Robocode: [Robocode Sourceforge](https://sourceforge.net/projects/robocode/files/)
    - Obs.: Esse repositório esta configurado para robocode instalado em C:/robocode, mudanças devem ser feitas no arquivo .classpath caso necessário
 - Adicionar os robos desenvolvidos nesse repositório as options do Robocode
    - Abrir o app do robocode
    - Options -> Development Options
    - Add -> Inserir o path do repositório mais a pasta bin. e.g.: C:/path/to/this/repository/bin
