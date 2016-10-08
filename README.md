# JMBAG
0036493116
#Pitanje 1:
Prvi build nakon dodavanja novih referenci dodaje .dll datoteke u direktorij. Micanjem .dll datoteke iz direktorija
program više ne radi i javlja FileNotFoundException jer ne može pronaći sve svoje reference. Da bi aplikacija dobro
radila za distribuciju potrebno je uključiti .exe sa svim potrebnim dodatnim referencama (.dll datotekama).

#Pitanje 2:
Nakon izmjene i builda ispiše se novi string jer se tijekom builda bildaju i sve reference.

#Pitanje 3:
Ispisalo se "Pero: Hello World".

#Pitanje 4:
PeroClassLibrary.dll se nalazi u bin/debug jer je referenca u aplikaciji.

#Pitanje 5:
Ako obrišemo originalni .dll build/run svejedno radi. To je zato što se .dll kopira u bin/debug i reference path se
postavlja na taj file.

#Pitanje 6:
Build projekta prolazi, NuGet opet skida potrebne datoteke u direktorij tijekom build faze.