ZajednickaSvojstvaTipova
========================

SystemObjekt
------------
Ilustrira kako se pona�aju implementacije metoda naslje�enih 
izravno iz baznog System.Object tipa.


ToString
--------
Primjer ga�enja (override) metode ToString


MetodaEquals
------------
Ilustrira razliku izme�u stati�ke i nestati�ke metode Equals.


MetodaEqualsZaReferentniTip
---------------------------
Primjer ga�enja (override) metode Equals za referentni tip koji je
izveden izravno iz System.Object.
Klasa Osoba sadr�i jedno polje referentnog tipa (string m_ime) i jedno
polje vrijednosnog tipa (int m_mati�niBroj). �elimo definirati da su
dva objekta tipa Osoba jednaka ako imaju isto ime i isti mati�ni broj.
(Prekrili smo i metodu ToString da bismo dobili ljep�i ispis).


MetodaEqualsZaIzvedeniReferentiTip
----------------------------------
Klasa Student je izvedena iz klase Osoba - njena metoda Equals mora
pozvati Equals bazne klase + napraviti usporedbu polja koja su specifi�na
za izvedenu klasu.


MetodaEqualsZaVrijednosniTip
----------------------------
Primjer implementacije metode Equals za vrijednosni tip.


JednakostReferentnogTipa
------------------------
Primjer implementacije operatora == i != za referentni tip.


JednakostVrijednogTipa
----------------------
Primjer implementacije operatora == i != za vrijednosni tip.


GetHashCodeString
-----------------
Primjer �to vra�a GetHashCode za sli�ne znakovne nizove.


GetHashCode
-----------
Primjer za�to je neophodno pregaziti metodu GetHashCode ako
se pregazi metoda Equals (i obrnuto).


Clone
-----
Primjer implementacije ICloneable su�elja.