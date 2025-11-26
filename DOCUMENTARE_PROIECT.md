* \# 📄 Proiect de Documentare Git \& GitHub
* 
* \## 👨‍🎓 Informații Proiect
* \* \*\*Student:\*\* Anamaria Brechler
* \* \*\*Email:\*\* brechleranamaria13@gmail.com
* \* \*\*Data Finalizării:\*\* 2025-11-26
* \* \*\*URL Repository:\*\* https://github.com/ana24T/Proiect-Documentare-Git
* 
* ---
* 
* \## 🎯 Obiectiv și Metodologie
* 
* Scopul acestui proiect a fost demonstrarea stăpânirii fluxului de lucru esențial Git/GitHub, incluzând operațiuni de bază (`commit`, `push`) și operațiuni avansate de colaborare (`branch`, `pull`). Toate operațiunile au fost executate în mediul Git Bash, după o instalare configurată la standardele moderne (branch principal `main`, utilizarea MinTTY, etc.).
* 
* ---
* 
* \## 🛠️ Documentație Comenzi Executate
* 
* \### 1. Inițializarea Proiectului Local (Git Setup)
* Etapele de configurare au inclus setarea identității utilizatorului și transformarea directorului local într-un repository Git.
* 
* | Comandă | Explicație | Obiectiv Demonstrat |
* | :--- | :--- | :--- |
* | `git config --global user.email "..."` | Setează email-ul utilizatorului, esențial pentru identificarea autorului commit-urilor. | \*\*Configurare globală\*\* |
* | `git config --global user.name "..."` | Setează numele utilizatorului. | \*\*Configurare globală\*\* |
* | `mkdir Proiect-Documentare-Git` | Crearea directorului de lucru. | \*\*Mediu local\*\* |
* | `cd Proiect-Documentare-Git` | Navigarea în director. | \*\*Navigare\*\* |
* | `git init` | Inițializează repository-ul local. Creează folderul ascuns `.git`. | \*\*Inițializare\*\* |
* | `touch DOCUMENTARE\_PROIECT.md` | Crearea fișierului de documentație. | \*\*Creare fișier\*\* |
* 
* \### 2. Primul Commit și Conectarea (Push)
* Acest pas stabilește prima versiune a proiectului și o trimite pe platforma GitHub.
* 
* | Comandă | Explicație | Obiectiv Demonstrat |
* | :--- | :--- | :--- |
* | `git add .` | Mute toate fișierele noi/modificate în zona de staging (pregătire). | \*\*Staging\*\* |
* | `git commit -m "Initial commit: Adaugare fisier de documentare"` | Creează prima versiune permanentă (commit) a proiectului. | \*\*Commit\*\* |
* | git remote add origin https://github.com/ana24T/Proiect-Documentare-Git.git | Conectează repository-ul local la cel remote de pe GitHub. | \*\*Conectare Remote\*\* |
* | `git push -u origin main` | Încarcă commit-ul local de pe branch-ul `main` la repository-ul remote `origin`. | \*\*Push\*\* |
* 
* \### 3. Dezvoltare pe Branch-uri (Branching)
* Demonstrarea fluxului de lucru de dezvoltare a unei funcționalități noi în izolare (best practice).
* 
* | Comandă | Explicație | Obiectiv Demonstrat |
* | :--- | :--- | :--- |
* | `git branch feature/profil-utilizator` | Creează o nouă ramură de lucru. | \*\*Branching\*\* |
* | `git checkout feature/profil-utilizator` | Comută contextul de lucru pe noua ramură. | \*\*Checkout\*\* |
* | `touch profil.html` | Simulează lucrul la o nouă funcționalitate (fișierul `profil.html`). | \*\*Lucru izolat\*\* |
* | `git commit -m "FEAT: Creare pagina de profil goala"` | Salvează progresul pe ramura `feature/profil-utilizator`. | \*\*Commit Feature\*\* |
* | `git push -u origin feature/profil-utilizator` | Publică noua ramură pe GitHub. | \*\*Push Branch\*\* |
* 
* \### 4. Sincronizarea Schimbărilor (Pull)
* Demonstrarea integrării muncii de la distanță (simulare de colaborare).
* 
* | Comandă | Explicație | Obiectiv Demonstrat |
* | :--- | :--- | :--- |
* | `git checkout main` | Comută înapoi la ramura principală pentru a primi actualizări. | \*\*Checkout\*\* |
* | \*(Schimbare manuală pe GitHub)\* | O modificare minoră a fost realizată direct pe GitHub pentru a simula contribuția unui coleg. | \*\*Simulare Colaborare\*\* |
* | `git pull origin main` | \*\*Descarcă și integrează (fetch \& merge)\*\* schimbările de pe branch-ul remote (`origin/main`) în branch-ul local curent (`main`). | \*\*Pull\*\* |
* 
* ---
* 
* \## ✅ Concluzie
* Toate operațiunile Git de bază și avansate (Branching, Pull) au fost realizate cu succes. Istoricul commit-urilor pe repository-ul GitHub confirmă fiecare etapă a procesului.

