Introdução a Computação Gráfica

## Aluno
Zaqueu Moura da Silva - 11413593


## OpenGl Moderno
O objetivo deste trabalho é configurar o ambiente de desenvolvimento em OpenGL 3.3 corretamente

Para que o prorama possa ser executado precisamos instalar o freeglut3-dev, o mesmo indicou um erro que a versão 3.3 GLSL não era suportada, foi necessario dar o export MESA_GL_VERSION_OVERRIDE=3.3

#### https://stackoverflow.com/questions/52592309/0110-error-glsl-3-30-is-not-supported-ubuntu-18-04-c

#### $ sudo apt-get install freeglut3-dev
#### $ export MESA_GL_VERSION_OVERRIDE=3.3

#### $ make
#### $ ./moderngl_hello_world


Plot da imagem

<img src= https://github.com/zaqueumoura/ICG/blob/main/01_Tarefa/captura%20CG.png>
