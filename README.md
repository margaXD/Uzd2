# v0.1
Studentu duomenu programa su vektoriais v0.1 versija.
1. Visi kintamieji saugomi strukturoje.
2. Vektorius saugo visus namu darbu rezultatus.
3. Programa pritaikyta nekorektiskiems kintamiesiems ir parodo, ka reikia taisyti, kad veiktu.
4. Isvedami medianos ir vidurkiai su pasirinkimu.
#  v0.2
1. Pridetas pasirinkimas skaityti is failo.
2. Visur naudojami vektoriai.
3. Mokiniai rusiuojami pagal pavarde.
# v0.3
1. Exception handling'as pridetas prie kodo.
2. Sukurti papildomi .h ir .cpp failai, kuriuose laikomos funkcijos ir strukturos.
# v0.4
Laiko testavimas.
1. Sudaro sarasa, nuskaito duomenis, juos surusiuoja.
2. Parodo laika, per kuri atliko veiksmus.
# v0.5 
Konteineriu testavimas:
Versija v0.5 skirta std::vector, std::list ir std::deque konteineriu palyginimui.
Testavimo sistemos parametrai:
1. CPU: Intel i5-8300H 2.3Ghz 8CPUs
2. RAM: 12GB
3. SSD

Rezultatai vector konteineriui:
  1. 1000 irasu rezultatai:
  - nuskaitymas 0.009s
  - rusiavimas 0.019s
  2. 10000 irasu rezultatai:
  - nuskaitymas 0.013s
  - rusiavimas 0.116s
  3. 100000 irasu rezultatai:
  - nuskaitymas 0.049s
  - rusiavimas 1.074s
  4. 1000000 irasu rezultatai:
  - nuskaitymas 0.404s
  - rusiavimas 10.704s
  5. 1000000 irasu rezultatai:
  - nuskatymas 4.104s
  - rusiavimas 109.287s
  
Rezultatai list konteineriui:
  1. 1000 irasu rezultatai:
  - nuskaitymas 0.011s
  - rusiavimas 0.026s
  2. 10000 irasu rezultatai:
  - nuskaitymas 0.094s
  - rusiavimas  0.124s
  3. 100000 irasu rezultatai:
  - nuskaitymas 0.93s
  - rusiavimas 1.143s
  4. 1000000 irasu rezultatai:
  - nuskaitymas 9.389s
  - rusiavimas 11.337s
  5. 10000000 irasu rezultatai:
  EXEPTION - BAD ALLOC - Daryta su CodeBlocks, del to nepagalvojau apie atminties alokavima.
 
 Rezultatai deque konteineriui:
   1. 1000 irasu rezultatai:
   - nuskaityams 0.009s
   - rusiavimas 0.021s
   2. 10000 irasu rezultatai:
   - nuskaitymas 0.092s
   - rusiavimas 0.122s
   3. 100000 irasu rezultatai:
   - nuskaitymas 0.924s
   - rusiavimas 1.152s
   4. 1000000 irasu rezultatai:
   - nuskaitymas 9.329s
   - irasymas 11.439s
   5. 10000000 irasu rezultatai:
   EXEPTION - BAD ALLOC - Daryta su CodeBlocks, del to nepagalvojau apie atminties alokavima.
