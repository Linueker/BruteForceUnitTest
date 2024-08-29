Unit tests som kollar så att man inte kan skriva vilket lösenord som helst. Lösen "admin" är hårdkodat som accepterat lösen. 
Inloggningsmetoden returnerar nu false efter 10 misslyckade försök vilket avslutar programmet. Tar man bort denna retur så hamnar användaren i en timeout istället innan ytterligare försök kan påbörjas. 
