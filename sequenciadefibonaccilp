# include <stdio.h>

void fibonacci(int n){
	int atual, anterior, temporario, i;
	anterior = 0;
	atual = 1;
	if(n>=1){
		printf("%d", anterior);
	} if(n>=2){
		printf("%d", atual);
	} for(i = 3; i<=n; i++) {
		temporario = atual;
		atual = anterior + atual;
		anterior = temporario;
		printf("%d", atual);
	}	
}

int main(){
	int limite;
	printf("digite o numero de termos da sequência \n");
	scanf("%d", &limite);
	fibonacci(limite);
	return 0;
}
