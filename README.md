# WEEK11_1
โปรแกรมรายสัปดาห์ที่ 11 อันที่ 1


    #include <stdio.h>

    float m;
    float s;
    float n[9];
    int main() {
	
	    printf("ENTER NUMBER : ");
	    scanf("%f %f %f %f %f %f %f %f %f %f", &n[0], &n[1], &n[2], &n[3], &n[4], &n[5], &n[6], &n[7], &n[8], &n[9]);
    
    	for(int i=0;i<=9;i++){
    		printf("%f ",n[i]);
    	}

    	for(int j=0; j<9; j++){
    	 m += n[j] ; 	
    	}
    	s = m/9.0 ;
    	printf("\n");
    	printf("\n");
        printf("AVERAGE : %.2f", s);
    }
