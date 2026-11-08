# Brief : Site Web Experte Art de Vivre

> Ce fichier contient le prompt à utiliser dans Claude Code ou Claude Design pour générer le site.

---

## Le problème que cette experte résout

Beaucoup de gens souffrent en silence : stress chronique, conflits de couple, tensions familiales, manque de confiance en soi, anxiété, sentiment de perdre le contrôle de leur vie. Cette experte les accompagne pour retrouver la paix intérieure, renforcer leur personnalité et construire des relations saines.

---

## Ses services principaux

- **Coaching individuel** : renforcement de la personnalité, confiance en soi, gestion du stress et de l'anxiété
- **Thérapie de couple** : communication, résolution de conflits, retrouver la complicité
- **Accompagnement familial** : apaiser les tensions, rétablir le dialogue, créer un environnement familial sain
- **Consultations** en ligne et en présentiel

---

## Ce que le site doit accomplir

- Donner confiance dès la première seconde : le visiteur doit sentir qu'il est au bon endroit
- Permettre de réserver une séance facilement (formulaire simple : nom, téléphone, type de séance)
- Permettre de contacter l'experte par WhatsApp en un clic
- Être simple à naviguer, même pour quelqu'un qui n'est pas à l'aise avec la technologie

---

## Structure du site (one-page)

1. **Hero** : phrase d'accroche émotionnelle + bouton "Réserver une séance"
2. **Qui suis-je** : présentation courte et humaine de l'experte
3. **Services** : cartes visuelles claires
4. **Témoignages** : 3 avis clients (fictifs mais crédibles)
5. **Réservation** : formulaire minimaliste
6. **Footer** : contact (WhatsApp, email, téléphone), réseaux sociaux

---

## Direction artistique

- L'ambiance doit évoquer le calme, la sérénité et le luxe accessible
- Couleurs : tons naturels et chaleureux (beige, vert olive, blanc crème, touches dorées)
- Typographie raffinée mais lisible
- Design épuré avec beaucoup d'espace, aucune surcharge
- Animations légères au défilement
- Mobile-first, 100% responsive

---

## Intégrations API

- **WhatsApp Business API** : bouton "Contacter sur WhatsApp" qui ouvre une conversation pré-remplie avec un message d'accueil
- **Formulaire de réservation** : envoi des données du formulaire via une API (Formspree, EmailJS ou Web3Forms) pour recevoir les demandes par email sans backend
- **Google Maps** : embed de la localisation du cabinet (si en présentiel)
- **Calendly ou Cal.com** : option d'intégration d'un widget de prise de rendez-vous en ligne

---

## Contraintes techniques

- Un seul fichier HTML autonome
- CSS et JS intégrés dans le fichier
- Google Fonts uniquement comme ressource externe
- Le site doit fonctionner en ouvrant simplement le fichier dans un navigateur

---

## Langue

Français

---

## Prompt à copier-coller

```
Crée un site web professionnel one-page pour une experte marocaine spécialisée dans l'art de vivre et le bien-être personnel.

Elle aide les gens qui souffrent de stress chronique, conflits de couple, tensions familiales, manque de confiance en soi et anxiété. Elle les accompagne pour retrouver la paix intérieure, renforcer leur personnalité et construire des relations saines.

Services : coaching individuel (confiance en soi, gestion du stress), thérapie de couple (communication, résolution de conflits), accompagnement familial (apaiser les tensions, rétablir le dialogue). Consultations en ligne et en présentiel.

Structure one-page : hero avec accroche émotionnelle et bouton "Réserver une séance", section "Qui suis-je" avec la photo de l'experte, section services en cartes visuelles, 3 témoignages crédibles, formulaire de réservation minimaliste (nom, téléphone, type de séance), footer avec WhatsApp, email, téléphone et réseaux sociaux.

Photo de l'experte : je t'envoie une photo de l'experte avec ce prompt. Utilise cette photo dans le site, notamment dans la section "Qui suis-je" et/ou le hero. Tu peux la styliser (forme arrondie, ombre portée, bordure dorée, léger effet de superposition avec un fond) mais le visage et les expressions doivent rester exactement les mêmes, sans aucune modification du visage ni des traits.

Images d'inspiration : je t'envoie aussi des images d'inspiration avec la photo. Utilise-les comme référence pour le style visuel, la mise en page, les couleurs et l'ambiance générale du site. Inspire-toi de ces images pour créer un design unique et moderne.

Direction artistique : ambiance calme, sérénité, luxe accessible. Couleurs : beige, vert olive, blanc crème, touches dorées. Typographie raffinée et lisible. Design épuré, beaucoup d'espace blanc. Ajoute des effets visuels qui différencient ce site des autres : animations élégantes au scroll (fade-in, slide-up), effet parallaxe subtil sur le hero, micro-interactions sur les boutons et les cartes (hover avec ombre et légère élévation), transition douce entre les sections, effet glassmorphism léger sur certains éléments. Mobile-first, 100% responsive.

Intégrations API : bouton WhatsApp qui ouvre une conversation pré-remplie (api.whatsapp.com/send?phone=NUMERO&text=MESSAGE), formulaire de réservation connecté à un service d'envoi email sans backend (Formspree, EmailJS ou Web3Forms, mets un placeholder pour la clé API), option d'embed Calendly ou Cal.com pour la prise de rendez-vous en ligne, embed Google Maps pour la localisation du cabinet.

Technique : un seul fichier HTML autonome, CSS et JS intégrés, Google Fonts uniquement comme ressource externe. Le site doit fonctionner en ouvrant le fichier dans un navigateur. Mets des placeholders clairs (ex: VOTRE_NUMERO_WHATSAPP, VOTRE_CLE_FORMSPREE, VOTRE_LIEN_CALENDLY) pour que je puisse facilement remplacer par mes vraies valeurs. Langue : français.
```
