---
dg-publish: true
File Creation date: 2024-04-25
---
# Vorwärtskalkulation
Eigenen zu berechnen

| Listeneinkaufspreis | %   |               |
| ------------------- | --- | ------------- |
| \- Rabatt           | R   | LEP\*R        |
| = Zieleinkaufspreis |     | Lep-Rabatt    |
| \- Skonto           | S   | ZEP*S         |
| = Bareinkaufspreis  |     | ZEP-Skonto    |
| \+ [[Bezugskosten]] |     | B             |
| = Einstandspreis    |     | BEP+B         |
| \+ Handelskosten    | H   | EP*H          |
| = Selbstkosten      |     | EP+Handelsk.  |
| \+ Gewinn           | G   | SK*G          |
| = Barverkaufspreis  |     | SK+Gewinn     |
| \+ Kundenskonto     | KS  | BVP/(1-KS)*KS |
| = Zielverkaufspreis |     | BVP+KSkonto   |
| \+ Kundenrabatt     | KR  | ZVP/(1-KR)*KR |
| = Verkaufspreis     |     | ZVP+KRabatt   |
# Rückwärtskalkulation


| Listeneinkaufspreis | %   | ZEP+Rabatt  |
| ------------------- | --- | ----------- |
| \- Rabatt           | R   | ZEP/(1-R)*R |
| = Zieleinkaufspreis |     | BEP+Sonto   |
| \- Skonto           | S   | BEP/(1-S)*S |
| = Bareinkaufspreis  |     | EP-B        |
| \+ [[Bezugskosten]] |     | B           |
| = Einstandspreis    |     | SK-HK       |
| \+ Handelskosten    | H   | SK/(1+H)*H  |
| = Selbstkosten      |     | BVP-G       |
| \+ Gewinn           | G   | BVP/(1+G)*G |
| = Barverkaufspreis  |     | ZVP-KSkonto |
| \+ Kundenskonto     | KS  | ZVP*KS      |
| = Zielverkaufspreis |     | VP-KRabatt  |
| \+ Kundenrabatt     | KR  | VP*KR       |
| = Verkaufspreis     |     |             |
# Differenzkalkulation
Wenn wir es dem Kunden günstiger geben, wie viel Gewinn wir machen.

| Listeneinkaufspreis | %   |                  |
| ------------------- | --- | ---------------- |
| \- Rabatt           | R   | LEP*R            |
| = Zieleinkaufspreis |     | Lep-Rabatt       |
| \- Skonto           | S   | ZEP*S            |
| = Bareinkaufspreis  |     | ZEP-Skonto       |
| \+ [[Bezugskosten]] |     | B                |
| = Einstandspreis    |     | BEP+B            |
| \+ Handelskosten    | H   | EP*H             |
| = Selbstkosten      |     | EP+Handelsk.     |
| \+ Gewinn           | G   | BVP-Selbstkosten |
| = Barverkaufspreis  |     | ZVP-KSkonto      |
| \+ Kundenskonto     | KS  | ZVP*KS           |
| = Zielverkaufspreis |     | VP-KRabatt       |
| \+ Kundenrabatt     | KR  | VP*KR            |
| = Verkaufspreis     |     |                  |