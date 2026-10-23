# Inclusions du saphir

Appli web personnelle pour mémoriser les inclusions du saphir : photos rangées par thème dans **Unheated**, **Heated** et **Synthétique**, une description par photo, et des flashcards pour réviser.

- Les photos et descriptions sont enregistrées **dans le téléphone** (IndexedDB), jamais envoyées en ligne.
- L'appli marche **sans internet** une fois ouverte une première fois (service worker).
- Écran « Sauvegarde » : export et restauration en un fichier `.zip`.

Installation sur iPhone : ouvrir l'adresse dans Safari → Partager → « Sur l'écran d'accueil ».
Installation sur Android : ouvrir l'adresse dans Chrome → menu ⋮ → « Installer l'application ».

Après toute modification d'un fichier, augmenter `VERSION` dans `sw.js` pour que les téléphones récupèrent la mise à jour.
