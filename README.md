# Description
Une app console toute simple qui scrute r�guli�rement doctolib en recherchant les cr�neaux dispos autour de votre ville.
Quand un cr�neau dispo est trouv�, l'app �met un signal sonore et ouvre le navigateur sur la page du centre de vaccination en question.
En th�orie cela fonctionne sous Windows, Mac et Linux.

# Bien d�marrer
1. Si ce n'est pas d�j� fait, installer le SDK dotnet core correspondant � votre syst�me depuis ici : https://dotnet.microsoft.com/download
2. Editez le fichier Program.cs avec l'URL correspondant � votre ville (variable `doctolibSearchUrl`). Si vous souhaitez ignorer les cr�neaux de certains centres de vaccination, vous pouvez les mentionner dans la variable `centersToIgnore`. Il y a �galement une variable `centerDepartmentsToIgnore` pour s�pcifier des d�partements entiers (voire des codes postaux) dont on souhaite ignorer les disponibilit�s des centres de vaccination.
3. Depuis un terminal ou une invite de commande dans le r�pertoire clon�, lancez la commande `dotnet run` et laissez la magie op�rer ;) 

# Quelques conseils
Ce n'est certainement pas le bout de code dont je suis le plus fier mais il a rempli son r�le.
A l'heure o� j'�cris ces lignes, les cr�neaux partent en quelques secondes, aussi je vous conseille d'avoir cr�� au pr�alable votre compte utilisateur doctolib :)
Bonne chance � vous.

