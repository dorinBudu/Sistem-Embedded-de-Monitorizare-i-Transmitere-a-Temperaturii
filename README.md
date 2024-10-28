# Sistem-Embedded-de-Monitorizare-si-Transmitere-a-Temperaturii
Sistem Embedded de Monitorizare și Transmitere a Temperaturii prin CAN utilizând STM32 și RTOS

Proiectul presupune achiziția de date prin intermediul protocolului CAN. Acest proces se va realiza folosind o placă de dezvoltare care are încorporat un STM32F030R8T6 care va prelua datele de la un modul de temperatură (posibil BMP280) și le va gestiona în timp real folosind FreeRTOS. Apoi prin intermediul unui CAN Controller și CAN Tranciever vom trimite date pe magistrala CAN. Ulterior, dupa realizarea comunicației, se dorește implementarea unui sistem de diagnoză cu LED sau prin Mesaje CAN specifice(cazuri in care sistemul nu funcționează corect-ex. circuit intrerupt între BMP280 și STM32).
