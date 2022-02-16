Atividade desenvolvida por Lucas Vicente Reis.

Desenvolvida em algoritimo que é uma linguagem que você usa para adaptar em qualquer linguagem.



Questão 1

funcao escada(n)

{

//Definir variáveis de controle

variável inteiro a = n – 1

variável inteiro = n - a

 

//Iteração para desenho da escada de asteriscos

Para i=0; i<=n; i++

{

​            //Iteração para inclusão de espaços

Para j=0; j<=a; j++

​            {

​                  Imprimir(<b>)

​            }

​            //Iteração para inclusão de asteriscos

Para k=0; k<=b; k++

​            {

Imprimir(“*“)

​            }

​            a = a – 1

​            b = b + 1     

}

}

​      

Questão 2

funcao (senha)

{

​      //Variável com tamanho da senha conforme definido nas regras do sistema

variável inteiro tamanho_minimo = 6

 

//Variável para armazenar comprimento da senha digitada

variável inteiro comprimento_total = 0

 

//Varíavel para armazenamento de caracteres da senha digitada

variável matriz de caracteres = {Comprimento(senha)}

 

//Iteração para eliminar possíveis espaços em branco na senha digitada

Para i=0; i<= Comprimento(senha); i++

{

​      Se caracteres[i] <> espaço em branco

​      {

​            comprimento_total = comprimento_total + 1

​      }

}

 

//Iteração para a cálculo do número de caracteres faltantes  

Se comprimento_total – tamanho_minimo < 0

{

​      Imprimir(tamanho_minimo – comprimento_total)

}

} 

 

Questão 3

função anagrama(palavra)

{

//Variável para contar total de anagramas

variável inteiro contador = 0

 

//Variáveis para guardar a palavra e compará-las entre si

variável matriz de palavra_A = {palavra}

variável matriz de palavra_B = variável matriz de palavra_A

 

//Variáveis para guardar a quantidade de letras de cada palavra

variável matriz de quantidade_caracter_A = { }

variável matriz de quantidade_caracter_B = { }

 

//Iteração para percorrer letras da palavra

Para i=0; i<=ContaCaracter(palavra_A); i++

{

​            armazenar quantidade_caracter_A[palavra_A[i]]

}

 

//Iteração para percorrer letras da cópia da palavra

Para i=0; i<=ContaCaracter(palavra_B); i++

{

​            armazenar quantidade_caracter_B[palavra_B[i]]

}

​      

​      //Iteração para buscar anagramas

​      Para i=0; i<=ContaCaracter(palavra_B); i++

{

​      Se quantidade_caracter_A[i] = quantidade_caracter_B[i]

​      {

​            contador = contador + 1

​      }

}

 

Imprimir(contador)