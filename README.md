# tablica1
to ta tablica co muszę 3 liczby największe wypisać



#include <stdio.h>
#include <stdlib.h>

int main()
{
	int tab [] = {1,2,3,4,-2,44,89,76,12,-123,0}; 
	
	int max=tab[0];
		int size = sizeof(tab) /sizeof(tab[0]);
	for (int i=0;i<size;i++) {
		max = max<tab[i]?tab[i]:max;
		
		
		
	}
	
	printf("3 najwieksze liczby z tablicy= %i,",max);
	
	


	return 0;
	
}






Nowa wersja !!!!!!!!!!!!!!!!!!!!









#include <stdio.h>
#include <stdlib.h>

int main()
{
	int tab [] = {1,2,3,4,-2,44,89,76,12,-123,0}; 


	int max=tab[0];
	int size = sizeof(tab) /sizeof(tab[0]);
	for (int i=0;i<size;i++) {
		max = max<tab[i]?tab[i]:max;
		
	
}
		int max1=tab[1];
		int max2=tab[2];{
			int size = sizeof(tab) /sizeof(tab[0]);
			for (int i=0;i<size;i++)
		max1 = max1<max&&max1>max2,max1<tab[i]?tab[i]:max1;
		
}

			{
			int size = sizeof(tab) /sizeof(tab[0]);
			for (int i=0;i<size;i++)
		max2 = max2<max1&&max2<max,max2<tab[i]?tab[i]:max2;
		
		
		
	}
	
	printf("3 najwieksze liczby z tablicy= %i,",max);
	printf("%i,",max1);
	printf("%i", max2);
	
	


	return 0;
	
}
