#### Interaktomika
<img width="700" src="https://raw.githubusercontent.com/matfija/Neuredjenost-u-interaktomu/main/slike/SARS_iRef.png">

## Neuređenost u interaktomu :m:
Seminarski rad na kursu Istraživanje podataka u bioinformatici. U radu je razmotren pojam interaktoma kao mreže proteinskih interakcija, kao i osobine i odnosi proteina u njemu. Konkretno, proučeni su interaktomi generisani na osnovu odabranog podskupa proteoma virusa [*SARS-CoV-2*](https://www.ncbi.nlm.nih.gov/Structure/SARS-CoV-2.html) (membranski i nestrukturni proteini), a kao osobina od interesa izdvojena je neuređenost proteina u njima (prema različitim kriterijumima). Zadatak je, dakle, bio uporediti stepen neuređenosti proteina sa stepenom povezanosti čvora kojim je predstavljen u grafu.

Generisani su sasvim interaktivni interaktomi prema bazama proteinskih interakcija [*IntAct*](https://www.ebi.ac.uk/intact/home) i [*iRefIndex*](https://irefindex.vib.be/), a prema njima su računati stepeni povezanosti čvora u mreži. Za određivanje stepena neuređenosti razmatranih proteina, prvo su korišćeni rezultati [*IUPred*](https://iupred.elte.hu/) prediktora, a zatim i mere na osnovu aminokiselinskog profila (poput onih sa sajta [*Composition Profiler*](http://www.cprofiler.org/cgi-bin/profiler.cgi)), mere prema [*PONDR*](http://www.pondr.com/) prediktorima (*VLXT* i *CH*), kao i izvedene mere poput broja neuređenih regiona značajne dužine. Izračunata je i neuređenost suseda (neuređenost 'na drugom kraju interakcije'), a ispitan je i uticaj dužine sekvence na njenu predviđenu neuređenost. Zaključci se mogu pronaći u priloženoj *Jupyter* svesci. Na kraju su izdvojeni najpovezaniji proteini (habovi) iz svakog od proučavanih interaktoma.
