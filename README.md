# odevev


int buyukort (int matris[5])
{
    double ort = 0;
    for (int i = 0; i < LENGTH; i++)
    {
        ort = ort + matris[i];
    }
    ort = ort / 5;

    int buyuknumara = 0;
    for (int i = 0; i < 5; i++)
    {
        if (matris[i] > avg)
        {
            buyuknumara++;
        }
    }
    return buyuknumara;
}

void kucuknumara(int matris[5])
{
    double ort = 0;
    for (int i = 0; i < 5; i++)
    {
        ort = ort + matris[i];
    }
    ort = ort / 5;

    int sayac = 0;
    for (int i = 0; i < 5; i++)
    {
        if (matris[i] > ort)
        {
            printf("%d", matris[i]);
        }
    }
}

int dahaBuyuklerinToplami(int matris[5], int sayi)
{
    int toplam = 0;
    for (int i = 0; i <5; i++)
    {
        if(sayi < matris[i])
        {
            toplam = toplam + matris[i];
        }
    }
    return toplam;
}

int dahaBuyuklerinOrtalamasi(int matris[5], int sayi)
{
    int toplam = 0;
    for (int i = 0; i < 5; i++)
    {
        if(sayi < matris[i])
        {
            toplam = toplam + matris[i];
        }
    }
    float ort = toplam / (float)5;
    return ort;
