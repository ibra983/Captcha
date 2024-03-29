# Générateur de Captcha

Ce projet est un générateur de captcha simple avec un compte à rebours intégré, conçu dans le cadre de l'apprentissage du langage JavaScript. Un captcha (Completely Automated Public Turing test to tell Computers and Humans Apart) est utilisé pour déterminer si l'utilisateur est un humain ou un programme automatisé. Dans ce générateur, l'utilisateur doit saisir le nombre affiché dans l'image captcha dans le champ de saisie pour vérification.

## Fonctionnalités

- Génération aléatoire de chiffres pour chaque captcha
- Déformation aléatoire et rotation des chiffres pour rendre le captcha plus difficile à reconnaître par les programmes automatisés
- Compte à rebours de 10 secondes pour chaque captcha, après quoi un nouveau captcha est généré
- Affichage d'un message de confirmation ou d'erreur lorsque l'utilisateur soumet une réponse

## Instructions

1. Clonez le dépôt GitHub sur votre environnement de développement local.
2. Ouvrez le fichier `MagicCaptcha.html` dans un navigateur web.
3. Saisissez le nombre affiché dans l'image captcha dans le champ de saisie.
4. Appuyez sur le bouton "Valider" pour soumettre votre réponse.
5. Attendez le message de confirmation ou d'erreur affiché en dessous du champ de saisie.

## Technologies Utilisées

- HTML5
- CSS3 (Flexbox pour la mise en page)
- JavaScript (API Canvas pour dessiner le captcha et le compte à rebours)

