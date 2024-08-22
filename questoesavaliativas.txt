       questões Avaliativas
1) Qual biblioteca é necessário incluir com diretiva #include para utilzar as funções de entrada padrão da linguagem C?
R:
a biblioteca necessaria é:
    #include<stdio.h>
essa função é essencial para realizar operações de entrada e saída, permitindo que você interaja com usuário através do console.

2) O trecho de código realiza a leitura de um número inteiro. Entretanto,ele contém dois erros. Corrija-os e justifique sua resposta.
 int n;
scanf ("%f",n);
R:
Int main(){
 int n;//corrigido:'Int' deve ser 'int'
scanf("%d", %n);//corrigido;'%f' deve ser '%d' e é necessario usar '%' antes de 'n'
 return 0;
}

3) Explique o trecho de código abaixo (linha 2)
Char c;
scanf("%c", &C),
while (getchar() != '/n');
R: 
explicação da linha: scanf("%c", %c);
lê um unico caractere de entrada padrão e armazena na variavel c.
."%c": especificador para ler um caractere.
.%c: passa o endereço da variavel para armazenar o valor lido

explicação da linha:while(getchar) != '/n');
limpa o buffer de entrada, descartando caracteres até encontrar uma nova linha ('/n').

4) Explique o trecho do código abaixo:
  float largura, comprimento;
  scanf ("%f %f", %largura, &comprimento);
R:
linha:float largura, comprimento; 
declara duas variaveis do tipo float para armazenar numeros decimais.
linha: scanf ("%f 5f", &largura, &comprimento);
Lê dois numeros do tipo float da entrada padrão e armazena nas variaveis largura e comprimento.

5) Explique o trecho de código abaixo:
   char nome [80];
   scanf ("%s", nome);
R: 
linha: char nome [80];
declara um array de caractere chamado nome, capz de armazenar até 79 caracteres (mais o caractere nulo '/0')
linha:scanf ("%s", nome);
lê uma string de entrada padrão e armazena no array nome.

6) Explique o trecho de código abaixo:
   printf("ola, mundo!");
R:
printf: utiliza para exibir texto na saída padrão (console)
o texto "ola mundo!" é uma string literal que será impressa na tela exatamente como está.

7) Explique o trecho de código abaixo.(dica:a resposta não é a mesma da questão anterior)
   printf("ola, mundo!\n");
R:printf: utiliza para exibir texto na saída padrão (console)
o texto "ola mundo!" é uma string literal que será impressa na tela exatamente como está, mas contem um caractere especial no final
(/n): faz com que o curso se mova para a proxima linha após a impressão.

8) Explique o trecho do código abaixo:
   printf("1+1\n");  
R:
printf: imprime teto na saída padrão(console)
string lateral:exibe o texto "1+1" exatamente como está.
(/n):move o cursor para a proxima linha apos a ipressão.

                             