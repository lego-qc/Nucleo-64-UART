# Nucleo-64-UART
UART kommunikáció ESP-07 modullal

UART1-en kommunikál a WIFI modulunkkal. Én Nucleoval teszteltem, mivel HAL felhasználásával implementáltam, valószínűleg nagyon egyszerű Discovery-re is átportolni. A projectet STMCube-al inicializáltam, hoztam létre, én csak a main.c-ben dolgoztam, de feltöltöttem az összes forrás és header file-t. Annyit csinál, hogy elküldi az AT parancsot, majd várja az eredményt. Ha a helyes akkor felvillantja a board LED-jét.
