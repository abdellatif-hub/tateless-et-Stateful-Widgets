## Objectifs :

- Comprendre la différence entre StatelessWidget et StatefulWidget.

- Maîtriser le cycle de vie d’un StatefulWidget (initState, build, setState, dispose…).

- Savoir choisir le bon type de widget selon le besoin.

- Manipuler l’état local avec setState.
## 1. main.dart
C’est la page principale du projet Flutter.

Elle contient la fonction main() qui lance l’application avec runApp().
<img width="2559" height="1348" alt="image" src="https://github.com/user-attachments/assets/88073288-afe8-4ca5-be94-37e63994e575" />

## 2. home_page.dart

- Cette page représente la page d’accueil de l’application.

- Elle affiche un titre dans la barre d’applications (AppBar).

- Le contenu central peut être un texte ou un bouton pour accéder à d’autres pages.

- Elle permet la navigation vers la page compteur (CounterPage).
  <img width="2557" height="1348" alt="image" src="https://github.com/user-attachments/assets/fb8bb5bc-83c6-4d24-9232-4eef5a7e9fdf" />
##  3. counter_page.dart

- C’est une page Stateful qui contient un compteur interactif.

- L’utilisateur peut incrémenter ou décrémenter une valeur à l’aide de boutons.

- Elle utilise la fonction setState() pour mettre à jour l’interface.

  <img width="2559" height="1346" alt="image" src="https://github.com/user-attachments/assets/7c1b2e18-0873-42e2-bef1-14f408ab2e02" />

##  4. home_text.dart

- Cette page contient un widget personnalisé pour afficher un texte.

- C’est un StatelessWidget, donc son contenu ne change pas.

- Elle est réutilisable dans d’autres pages pour afficher des messages statiques.
  <img width="2559" height="1339" alt="image" src="https://github.com/user-attachments/assets/90f4dbef-a9fe-4268-ab01-652576b5269e" />
 ## 5. contact_page.dart
La page contacts.dart permet de gérer une liste de contacts.
L’utilisateur peut ajouter un nom avec le champ et le bouton Add,
et supprimer un contact avec l’icône rouge .
Elle utilise un StatefulWidget et la fonction setState() pour mettre à jour la liste.
  <img width="2559" height="1360" alt="image" src="https://github.com/user-attachments/assets/c64f49d4-15ba-43a7-b151-fafe98ec385f" />





