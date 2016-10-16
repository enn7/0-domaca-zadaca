# 0-domaca-zadaca

#0036940455

#Pitanje 1:
Primjećujem da su stvorene dvije nove datoteke ClassLibrary1.dll i ClassLibrary1.pdb. 
Nakon što sam uklonila .dll datoteku, pokretanje .exe rezultira s Exceptionom, zato što u KonzolnaAplikacija ne može pronaći klasu MyConsole. 
Ako želim poslati aplikaciju, trebam poslati KonzolnaAplikacija.exe i ClassLibrary1.dll.

#Pitanje 2:
Bez prevođenja, ispisuje se stari string.
Tek kada prevedemo KonzolnaAplikacija, tada se prevede i ClassLibrary projekt te se ispiše novi string.

#Pitanje 3:
Ispisalo se: Pero: Hello World.

#Pitanje 4:
U mapi Bin/Debug stvorena je datoteka PeroClassLibrary.dll.

#Pitanje 5:
Kako se stvorila ta datoteka i u Bin/Debug direktoriju, aplikacija radi jer sada taj PeroClassLibrary.dll traži u Bin/Debug, a zato i build radi.

#Pitanje 6:
Build proces je uspješno izvršen jer se ponovno skinuo obrisani paket NodaTime, jer ga se nije moglo pronaći u packages folderu.
