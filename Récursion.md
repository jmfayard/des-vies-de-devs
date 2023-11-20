🤔 « Vous connaissez la super blague sur la récursion ? »  
Voir ci-dessus 🔝  
  
La récursion c'est un concept que ces paresseux de devs ont volé aux paresseux de matheux :  
❌ factorielle(5) = 5 * 4 * 3 * 2 * 1  
✅ factorielle(5) = 5 * factorielle(4)  
  
En gros, la récursion c'est comme les poupées russes...  
  
Au lieu de faire  
Tu ouvres une poupée russe, tu vois qu'il y en a une autre à l'intérieur.  
Tu ouvres une poupée russe, tu vois qu'il y en a une autre à l'intérieur.  
Tu ouvres une poupée russe, tu vois qu'il y en a une autre à l'intérieur.  
  
Tu fais :  
La plus petite poupée russe, c'est  
....la plus petite poupée russe de sa fille  
....ou elle même si elle n'a pas de fille  
  
On peut même écrire cela sous forme de code  
  
fonction Poupée.plusPetitePoupée()  
....Si fille.existe() fille.plusPetitePoupée()  
....Sinon moi  
  
La seule différence c'est que dans le cas des poupées russes, on est sûr de trouver la poupée la plus petite.  
Alors qu'une récursion mal faite t'amène sur une boucle infinie.  
  
Et l'infini c'est long, surtout à la fin.  
  
-----  
  
🤔 J'ai prévu de continuer la série toute la semaine, mais je m'interroge si je la prolonge au-delà ?  
  
👉🏻 Est-ce que toi il y a des concepts que tu entends tout le temps qui sont particulièrement incompréhensibles ?