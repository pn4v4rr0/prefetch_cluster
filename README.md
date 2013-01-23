prefetch_cluster
================

versio que treballe sobre el cluster, adapta a la nova versio del svn que se suposa que soluciona el problema del invalid.
Conte el controlador el memoria y la implementacio de la mem principal ambuna cola per a les loads i les stores, no diferenciades.

TO-DO:
 DOna error de invalidez en lagunes execusions
 Falten algunes stadistiques del mem principal
 
 HECHO:
 - Controlador de memoria
 - Implementacion de la mem principal : rank, bank, canal
 - COla de MC no distinguix entre loads i stores. No hi ha politica de prioritat entre peticions de prefecth i sense prefetch
 - Implementat prefetch , unica cola per a les peticions que venen de prefetch
 - Stadistiques prefetch y memoria principal
