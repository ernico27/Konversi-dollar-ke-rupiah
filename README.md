# Konversi-dollar-ke-rupiah

    #include<stdio.h>
    #define kurs 14323.0

    int main()
    {
    float dollar=0;
    printf("\t\t ================================== \n");
    printf("\t\t Program konversi dollar ke rupiah \n");
    printf("\t\t ================================== \n");
    printf("\t\t Jumlah Dollar = $ ");
    scanf("%f",&dollar);

    float rupiah=dollar*kurs;
    printf("\t\t Rupiah yang dipunya = Rp %.2f",rupiah);
    return 0;
    }

## Hasilnya

![img](https://github.com/ernico27/Konversi-dollar-ke-rupiah/blob/master/dollar.png?raw=true)
