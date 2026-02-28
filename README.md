# Pizzakalkulator
Pizzakalkulator er en enkel nettside som regner ut omtrent hvor mye pizza man skal bestille til en fest, jobbsamling eller sulten gjeng.

# Beregning
Pizzakalkulatoren har en enkel metode for å regne ut hvor mye pizza man trenger. Kalkulatoren tar først inn `Antall personer` og et visst `Sultnivå`, ganger disse sammen, for så å gange med en faktor for antall pizzaer per person. Den siste faktoren er åpen for tolkning, men `Sultnivå`-leddet forsøker å ta høyde for dette. `Sultnivå`-et er definert slik:

- `Småsulten` = 0.8
- `Sulten` = 1.0
- `Kjempesulten` = 1.2

# Videre utvikling
Pizzakalkulatoren er inspirert og delvis direkte kopiert fra Fremskrittspartiet Ungdom (FpU) sin [kalkulator](https://fpu.no/common/pizza/). Tanken er å iterere videre på dette konseptet og å legge til:

- Mulighet til å velge type pizza (Chicago, Italian, digg, ...)
- Mulighet til å overstyre `Sultnivå`-faktorene