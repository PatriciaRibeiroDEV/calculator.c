#include <stdio.h>


/*Student: Patricia Silva Ribeiro*/
/*From: Faculdade CDL - 2° Semestre - Analise e Desenvolvimento de Sistemas*/
/*Instagram: Patrici4ribeiro*/



void soma ()
{
        float a, b;
        
        printf("Digite dois números: ");
        scanf("\n%f%f", &a,&b);
        printf("\nResultado = %.2f", a + b);
}
void subtracao(){
        float a, b;
        
        printf("\nDigite dois números: ");
        scanf("\n%f%f", &a,&b);
        printf("\nResultado = %.2f\n", a - b);
}
  void mult(){

        float a, b;
        
        printf("\nDigite dois numeros: ");
        scanf("\n%f%f", &a,&b);
        printf("\nResultado = %.2f\n", a * b); 
}

void div ()
{
        float a, b;
        
        printf("\nDigite dois numeros: ");
        scanf("\n%f%f", &a,&b);
        printf("\nResultado = %.2f\n", a / b);
}

void potencia ()
{
int exp, base, i;
        int result = 1;
    
        printf("Digite a base : ");
        scanf("%d",&base);
        printf("\nDigite o expoente: ");
        scanf("%d",&exp);
    
        for (i = 0; i < exp; ++i)
                result *= base;
            
        printf("Resultado = %d^%d = %d\n",
                    base,exp,result);
}

void fatorial ()
{
        int a, b;
        int sum = 1;
    
        printf("Digite o número: ");
        scanf("%d", &b);
    
        for (a = 1; a <= b; ++a)
                    sum *= a;
        
        printf("%d!=%d\n",b,sum);
}

void raiz()
{
        int a, sqroot;
        
        printf("\nDigite o numero: ");
        scanf("\n%d", &a);
        sqroot = sqrt(a);
        printf("\nResultado = %d\n",sqroot);
}

int main(void) {
  int op;

  while(op!=0){ 
  printf("\nEscolha uma função: \n");
  printf("\n[1] -  SOMA");
  printf("\n[2] -  SUBTRAÇÃO");
  printf("\n[3] -  MULTIPLICAÇÃO");
  printf("\n[4] -  DIVISÃO");
  printf("\n[5] -  POTENCIA");
  printf("\n[6] -  FATORIAL");
  printf("\n[7] -  RAIZ QUADRADA");
  printf("\n[0] -  SAIR");
  printf("\n");
  scanf("%d", &op);
  system("clear");


  switch(op){
    
    case 1:
      soma();
      printf("\n");
      break;
    
    case 2:
      subtracao();
      printf("\n");
      break;
    
    case 3:
      mult();
      printf("\n");
      break;
    
    case 4:
      div();
      printf("\n");
      break;

    case 5:
      potencia();
      break;

    case 6:
      fatorial();
      break;

    case 7:
      raiz();
      break;

  
    case 0:
      printf("\nAté a próxima");
    
    default:
      break;
    
    }
  }
  return 0;
}
