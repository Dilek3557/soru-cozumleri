# soru-cozumleri
projem

#include <stdio.h>
#include <stdlib.h>




int main() {


        int i, x, y, z, sayac = 0;
        for (i = 100; i <= 999; i++) {
            x = i / 100;
            y = (i % 100) / 10;
            z = i % 10;
            if (x != y && x != z && y != z) {
                printf("%d \n", i);

                sayac++;
            }
        }

        printf("\n\n %d sayi var", sayac);



        return 0;
}
