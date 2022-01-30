# Documente fundamentale ONCR

Cum se propun modificări? 

Pentru fiecare modificare / set de modificări, se creează un "branch" nou, din "master", care este branch-ul de referință. În drop-down-ul din stânga trebuie să fie selectat master, și apoi se pune numele unui branch nou (e important să nu mai existe deja același branch), și se alege "create branch: <nume> from 'master'"
  
  D![Screenshot 2022-01-30 131439](https://user-images.githubusercontent.com/2837718/151697270-9bdf13ba-15cd-40f9-86c6-e121ac514f15.png)

Dacă creați un branch nou, el va fi selectat apoi automat. Dacă vă întoarceți pe github ulterior, trebuie să vă asigurați că branch-ul vostru este selectat în drop-down-ul din stânga, și dacă nu e, să-l selectați înainte să faceți modificări
  
  ![image](https://user-images.githubusercontent.com/2837718/151697333-df51e9d4-4b6d-4907-a086-a675e4911a3d.png)

Apoi, în branch-ul vostru, selectați fișierul în care veți să propuneți modificări (sau selectați Add file > Create new file din meniul din dreapta drop-down-ului pentru branch-uri). Odată deschis, aveți un buton de editare:
  
  ![Screenshot 2022-01-30 131919](https://user-images.githubusercontent.com/2837718/151697421-d4e5eb33-e7e5-4ec5-8265-4b9d73a07cb3.png)
  
Faceți ce modificări credeți că sunt necesare. Ideal, seturile de modificări (un set de modificări sunt schimbările înainte de a da "commit") au sens de sine stătător sau împreună cu altele, dar nu includ într-un singur set modificări care nu țin unele de altele (putem extrage și grupa mai multe seturi de modificări împreună, dar nu putem sparge o singură modificare în mai multe).
  
După ce terminați un set de modificări, în josul paginii, sub fișierul text, aveți o zonă cu "Commit changes". Ideal, folosiți prima căsuță pentru a descrie măcar sumar ce modificare se face și de ce. Pentru detalii, folosiți și a doua căsuță. Notele astea sunt super utile când, în viitor, căutăm de ce au fost modificate / adăugate articole.
  
Dacă aveți mai multe emailuri înregistrate în github, alegeți cel de @scout.ro. 
  
Alegeți întotdeauna prima opțiune - Commit directly in the `numele-branchului-meu` branch pentru ca modificările să fie grupate corect. Asigurați-vă că sunteți pe branch-ul corect. Alegeți apoi "commit".
  
  ![Screenshot 2022-01-30 132539](https://user-images.githubusercontent.com/2837718/151697614-aaf8f586-c46d-4f27-bae1-e28a7d815ff7.png)


Pentru a verifica cum s-a modificat per total branch-ul vostru față de referința din `master` după una sau mai multe modificări, puteți merge la Pull Requests / New Pull Request
  
  ![Screenshot 2022-01-30 132752](https://user-images.githubusercontent.com/2837718/151697697-2f774c86-6cee-47da-b7a9-2002090a6e1c.png)

Și aici alegeți pentru base `master` și pentru `compare` branch-ul vostru. 
  
Implicit, veți vedea toate modificările. Puteți și creați un Pull Request. După ce-l creați (și îi dați un nume, eventual), nu mai trebuie să intrați la New Pull Request, puteți să accesați comparația din lista de la pull requests.

![Screenshot 2022-01-30 133047](https://user-images.githubusercontent.com/2837718/151697808-29809300-cb21-4c87-8016-e55243c43486.png)

