# PETITE INTRO

Ce kata est un *grand classique* (cf le README.md), le but est de refactoriser du code qui fonctionne parfaitement (ce qui 
veut dire que si un point n'est pas clair dans les explications, c'est le code qui fait foi) et de rajouter une 
fonctionnalité.

Pour cela, il faut évidemment être sûr de ne rien casser durant la refactorisation !

D'où l'importance d'avoir des **tests** avant de rebâtir !

Comme c'est une étape obligée mais pouvant être longue, on vous a écrit un canevas de tests avec Rspec, mais qui ne 
comprend pas les tests pour la nouvelle fonctionnalité (nommée "conjured"). Je vous invite à les compléter, voire à les
réécrire si vous le voulez. Vous pouvez aussi écrire les tests avec Unit.

Une fois les tests complétés, à vous la refactorisation, 
 - pour respecter les principes SOLID [back to basics SOLID in Ruby](https://thoughtbot.com/blog/back-to-basics-solid) 
  ou encore [article Medium SOLID in Ruby](https://medium.com/rubycademy/solid-ruby-in-5-short-examples-353ea22f9b05)
 - DRY (Don't Repeat Yourself)
 - éviter les [nombres magiques](https://fr.wikipedia.org/wiki/Nombre_magique_(programmation)#Constantes_num%C3%A9riques_non_nomm%C3%A9es) ou noms maqiques
 - et surtout faire de plus petits portions de code, même si le résultat intermédiaire risque d'être plus dur à lire et 
 le résultat final forcément plus long, mais beaucoup plus clair et lisible que l'original
 - et tout ce que vous trouverez pour avoir un *beau* code