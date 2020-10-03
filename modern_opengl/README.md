# Compilando e Executando um Programa OpenGL Moderno

## Sobre
Essa atividade tem objetivo de configurar o OpenGL na máquina, compilar e executar o seguinte programa: 
![img1](https://jeferson-wwe.000webhostapp.com/img-icg/img1.png)


## Configuração 
Primeiramente tentei configurar o OpenGL e executar o programa no Windows10 em uma IDE, porém não obtive sucesso, e devido as dificuldades resolvi migrar para o sistema operacional Ubuntu, 
onde consegui configurar e rodar sem problemas.</p>
Então, instalei a biblioteca freeGlut e suas dependências no Ubuntu 20.4 utilizando os comandos: 
<blockquote> sudo apt-get update </blockquote>
<blockquote> sudo apt-get install libglu1-mesa-dev freeglut3-dev mesa-common-dev  </blockquote>

## Execução
Para compilar o programa executei o comando:  
<blockquote>gcc main.c -o exercicio1 -lglut -lGLU -lGL <blockquote>

![img2](https://jeferson-wwe.000webhostapp.com/img-icg/img2.png)

<blockquote>./exercicio1<blockquote>

Na qual, resultou na compilação e execução do programa com sucesso:

![img3](https://jeferson-wwe.000webhostapp.com/img-icg/img3.png)

## Referências
Baseado no site: http://www.codebind.com/linux-tutorials/install-opengl-ubuntu-linux/
