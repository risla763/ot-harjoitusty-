## Monopoli, alustava luokkakaavio

```mermaid
 classDiagram
    Monopolipeli "1" -- "2" Noppa
    Monopolipeli "1" -- "1" Pelilauta
    Pelilauta "1" -- "40" Ruutu
    Ruutu "1" -- "1" Ruutu : seuraava
    Ruutu "1" -- "0..8" Pelinappula
    Pelinappula "1" -- "1" Pelaaja
    Pelaaja "2..8" -- "1" Monopolipel
    Ruutu "1" -- "1" Ruutu : Aloitusruutu
    Ruutu "1" -- "1" Ruutu : Vankila
    Ruutu "1" -- "1" Ruutu : SattumaJaYhteismaa
    Ruutu "1" -- "1" Ruutu :AsematJaLaitokset
    Ruutu "1" -- "1" Ruutu :NormaaliKatu

```
