# Compilador de brainfuck para Z80 en MSX BASIC

Programa en MSX BASIC que lee un archivo de texto con código *brainfuck* y lo compila para generar un archivo binario. Se incluye también otro programa en BASIC como intérprete de *brainfuck* 

## Ejecución intérprete
    LOAD"BFUCK4.BAS",r

## Ejecución Compilador
    LOAD"BFCOM2.BAS",R

## Ejecución código binario

**Carga de fichero binario**   

     BLOAD"xxxx.bin",R

**Definición de rutina máquina**

    DEFUSR(0)=&HAC00
    L=USR(0)


## Enlaces

Código comentado: http://cacharreomsx.blogspot.com/2022/08/compilador-de-brainfuck-para-z80.html   
Programas en BrainFuck: http://brainfuck.org/

