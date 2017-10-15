#Pitanje 1:
Primjecujem da su se stvorila dva dodatna filea ClassLibrary1.dll i ClassLibrary1.pbd
Nakon pokretanja .exe datoteke aplikacija se srusila. Zato jer sam koristio funkciju koja se ne nalazi u istom folderu.  Treba poslati sve .dll datoteke (koje koristimo) i .exe file.

#Pitanje 2:
Koristila je staru verziju jer nije prevedena verzija sa novim stringom (.dll datoteka se obnavlja samo prilikom novog buildanja a ne samo spremanjem promjena u kodu) pa je aplikacija u sebi i dalje imala kod od prijasenjeg prevodenja (stari .dll file).

#Pitanje 3:
Build je uspio i on je vratio NodaTime u packages direktorij.
