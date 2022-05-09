# Computação Gráfica
Repositório que contém atividades das Aulas de Computação Gráfica <br>
Universidade Anhembi Morumbi <br>
Pedro Silva <br>

### Instruções para setup (linux)
- Exemplo utilizando o projeto Hello Triangles
- A instalação de bibliotecas no Debian, e seus derivados, foi feita baseada na seguinte entrada de [forum](https://askubuntu.com/questions/1186517/which-package-to-install-to-get-header-file-glad-h)
- Garanta que as bibliotecas foram corretamente instaladas, baseado no passo anterior ;)
- navegue para a pasta 'Hello Triangle'
    - `cd  Hello Triangle`
- Na primeira vez que tentamos rodar o projeto, é preciso compilar a biblioteca glad
    - basta executar o comando `g++ -c glad.c` no terminal
    - PS: fiz o uso do compilar g++, do projeto GNU. Talvez a instalação seja necessária
- Faça a compilação do programa:
    - `g++ main.cpp -o helloTriangle glad.o -lglfw -ldl`
- Execute o programa
    - `./helloTriangle`
- [Captura de tela](https://drive.google.com/file/d/1ALOuaXJpGXqMfhy_ls4_8Pk0tkjApoX3/view?usp=sharing) do programa em execução
