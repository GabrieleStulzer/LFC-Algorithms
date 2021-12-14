# Epurare una grammatica

Epurare una grammatica regolare è un operazione fondamntale per eliminare tutti quei termini non utili della grammatica, ovvero quei termini che non portano nessun contributo al riconoscimento di una parola se non l'aggiunta di passaggi di parsing aggiunttivi.

L'algoritmo per epurare una grammatica si basa su due principi:

- se A deriva epsilon allora A può essere eliminato
- se YXW dove tutti e tre i termmini derivano epsilon allora tutta la produzione è non utile

Ricavati questi due principi fondanti possiamo iniziare nella costruzione dell'algoritmo.
