# practica2git
Passos per crear un conflicte
1. Crear o clonar repositori local
2. Crear un arxiu pex. index.html (branca master)
3. git add index.html - Afegir-lo al repositori (branca master)
4. git commit -m 'Primer commit'
5. git branch hotfix1 - Cream nova branca
6. git branch hotfix2 - Cream nova branca
7. git checkout hotfix1 - Canviam de branca (branca hotfix1)
8. Afegim una linea a l'arxiu index.html
9. git add index.html - Afegiam arxiu a branca (branca hotfix1)
10. git commit -m 'index modificat' (branca hotfix1)
11. git checkout master - Canviam a branca (branca master)
12. git merge hotfix1 - Ajuntam la branca hotfix1 a la banca master (branca master)
13. git checkout hotfix2 - Canviam a branca (branca hotfix2)
14. Afegim una linea a arxiu index.html
15. git add index.html - Afegim a index.html a la branca (branca hotfix2)
16. git commit -m 'index modificat' (branca hotfix2)
17. git checkout master - Canviam de branca (branca master)
18. git merge hotfix2 - Aquí es crea el CONFLICTE si es fa amb un entorn gràfic es podrà ajuntar els 2 arxius <----------
