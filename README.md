prefetch_cluster
================

versio que treballe sobre el cluster, adapta a la nova versio del svn que se suposa que soluciona el problema del invalid.
Conte el controlador el memoria y la implementacio de la mem principal ambuna cola per a les loads i les stores, no diferenciades.

PROBLEMAS:
 DOna error de invalidez en lagunes execusions
 
 HECHO:
 - Controlador de memoria
 - Implementacion de la mem principal : rank, bank, canal
 - COla de MC no distinguix entre loads i stores. No hi ha politica de prioritat entre peticions de prefecth i sense prefetch
