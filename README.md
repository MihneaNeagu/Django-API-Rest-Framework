# Django-API-Rest-Framework

Service auto

3.1. CRUD mașină: id, model, an achiziție, nr. km, în garanție. Km și anul achiziției să fie strict pozitivi.

3.2. CRUD card client: id, nume, prenume, CNP, data nașterii (dd.mm.yyyy), data înregistrării (dd.mm.yyyy). CNP-ul trebuie să fie unic.

3.3. CRUD tranzacție: id, id_mașină, id_card_client (poate fi nul), sumă piese, sumă manoperă, data și ora. Dacă există un card client, atunci aplicați o reducere de 10% pentru manoperă. Dacă mașina este în garanție, atunci piesele sunt gratis. Se tipărește prețul plătit și reducerile acordate.

3.4. Căutare mașini și clienți. Căutare full text.

3.5. Afișarea tuturor tranzacțiilor cu suma cuprinsă într-un interval dat.

3.6. Afișarea mașinilor ordonate descrescător după suma obținută pe manoperă.

3.7. Afișarea cardurilor client ordonate descrescător după valoarea reducerilor obținute.

3.8. Ștergerea tuturor tranzacțiilor dintr-un anumit interval de zile.

3.9. Actualizarea garanției la fiecare mașină: o mașină este în garanție dacă și numai dacă are maxim 3 ani de la achiziție și maxim 60 000 de km.
