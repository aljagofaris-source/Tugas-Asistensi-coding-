#include <stdio.h>

int main() {
    float celcius, kelvin, fahrenheit, reamur;

    // Input dari pengguna
    printf("Masukkan suhu dalam Celcius: ");
    scanf("%f", &celcius);

    // Konversi ke satuan lain
    kelvin = celcius + 273.15;
    fahrenheit = (celcius * 9.0 / 5.0) + 32;
    reamur = celcius * 4.0 / 5.0;

    // Output hasil konversi
    printf("\nHasil Konversi Suhu:\n");
    printf("Celcius   : %.2f °C\n", celcius);
    printf("Kelvin    : %.2f K\n", kelvin);
    printf("Fahrenheit: %.2f °F\n", fahrenheit);
    printf("Reamur    : %.2f °Ré\n", reamur);

    return 0;
}
