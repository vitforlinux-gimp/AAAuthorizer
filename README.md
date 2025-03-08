# AAAuthorizer
A simple way to authorize APPIMAGE with AppArmor in Ubuntu... and others

Un modo semplice per autorizzare APPIMAGE con AppArmor in Ubuntu... e altri

(ENGLISH)
In Ubuntu it is difficult to run AppImages, because AppArmor blocks them, but you just need to create a file correctly in /etc/apparmor.d/ and restart it, this program also makes sure to give execution permissions to the Appimage.

USE: Open the terminal and type ./AAAuthorizer "/appimage path/name. Appimage"

Files are distinguished in /etc/apparmor.d/ because in addition to the user name and appimage they have AAA in the file name.

(ITALIANO)
In Ubuntu è difficile eseguire le AppImage, perché AppArmor le blocca, ma basta creare correttamente un file in /etc/apparmor.d/ e  riavviarlo, questo programma si assicura anche di dare i permessi di esecuzione all Appimage. 

USO: aprire il terminale e digitare ./AAAuthorizer "/percorso appimage/nome.Appimage"

I file si distinguono in /etc/apparmor.d/ perchè oltre al nome dell'utente e appimage hanno AAA nel nome del file.
