# T2L4
Ejercicio 1:
ls -l | awk '{print $5 ":" $9}'
Ejercicio 2:
ls -l | awk '{print $5 ":" $9}' | sort -ri
Ejercicio 3:
grep empate derbi.txt | sed -i 's/,s/ /g' | sort -k6 > empate.txt
Ejercicio 4:
grep "Levante U.D. Levante" derbi.txt | sed -i 's/,s/ /g' | sort -k6 > empate.txt
Ejercicio 5:
grep "Valencia C.F. Valencia" derbi.txt | sed -i 's/,s/ /g' | sort -k6 > empate.txt

David Hervás Álvarez
