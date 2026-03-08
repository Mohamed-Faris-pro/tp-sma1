# TP : Maîtrise du Prompt Engineering & Systèmes Multi-Agents

Ce dépôt contient les travaux pratiques réalisés sur l'interaction avec les Grands Modèles de Langage (LLMs) via différentes plateformes (OpenAI, Ollama, Groq) et techniques avancées de prompting.

---

## 🏗️ 1. Tokenizer avec `tiktoken`

Étude de la segmentation du texte en tokens et calcul de l'utilisation des ressources pour les modèles OpenAI.

* Utilisation de la bibliothèque `tiktoken` pour encoder/décoder les chaînes de caractères.
* Analyse de l'impact du choix du modèle sur le nombre de tokens générés.

<img width="752" height="100" alt="image" src="https://github.com/user-attachments/assets/521a054e-4fa3-4405-9fd7-2023870dbde9" />


> **📸 Capture d'écran à insérer :** Une capture de ton code montrant une phrase encodée et le nombre de tokens résultant.

---

## 🤖 2. How to Prompt OpenAI LLMs

Mise en œuvre des interactions avec les modèles GPT via l'API officielle.

* Structuration des messages : `System`, `User` et `Assistant`.
* Tests de paramètres : `Temperature`, `Top_p`, et `Max_tokens`.

> **📸 Capture d'écran à insérer :** Une capture de la cellule montrant une requête envoyée à GPT et la réponse reçue.

---

## 📡 3. Interact with OpenAI LLMs via HTTP Client (Postman)

Démonstration de l'indépendance technologique en utilisant des requêtes HTTP brutes sans SDK.

* Configuration des headers (`Authorization: Bearer`).
* Envoi de payloads JSON via Postman vers `https://api.openai.com/v1/responses`.

> **📸 Capture d'écran à insérer :** Une capture d'écran de ta fenêtre Postman montrant le statut `200 OK` et le JSON de réponse.

---

## 🏠 4. How to Prompt Local Ollama LLMs

Exploitation de modèles de langage en local pour garantir la confidentialité des données.

* Installation et configuration d'Ollama.
* Utilisation de modèles comme `Llama 3.2` directement sur la machine.

> **📸 Capture d'écran à insérer :** Une capture de ton terminal montrant l'exécution d'Ollama ou ton code Python pointant vers `localhost:11434`.

---

## 🚀 5. Interact with Ollama LLMs via HTTP Client (Postman)

Utilisation de l'API locale d'Ollama pour intégrer les LLMs dans n'importe quelle application.

* Endpoint : `POST http://localhost:11434/api/chat`.

> **📸 Capture d'écran à insérer :** Une capture Postman montrant une requête locale vers Ollama.

---

## ⚡ 6. How To Prompt Groq LLMs



> **📸 Capture d'écran à insérer :** Une capture montrant la vitesse d'exécution (tokens per second) dans tes logs.

---

## 🎨 7. Image Generation Prompting

Conception de prompts descriptifs pour obtenir des images précises.

> **📸 Capture d'écran à insérer :** Une capture du prompt utilisé et de l'image générée résultante.

---

## 👁️ 8. Image Description (Vision)

Utilisation des capacités multimodales des LLMs pour interpréter et décrire des images.

* Envoi d'images encodées en Base64 ou via URL.
* Extraction d'informations contextuelles à partir d'un visuel.

> **📸 Capture d'écran à insérer :** Une capture de l'image source et de la description textuelle générée par l'IA.

---

## 📝 9. Exemple : Aspect Based Sentiment Analysis (ABSA)

Cas d'usage avancé consistant à extraire des sentiments pour des aspects spécifiques d'un texte.


> **📸 Capture d'écran à insérer :** Une capture du résultat final montrant l'extraction JSON des sentiments par aspect.

---

## ⚙️ Installation

1. Clonez ce dépôt.
2. Installez Ollama pour la partie locale.
3. Configurez les clés dans un fichier `.env` (non inclus dans le dépôt).
4. Installez les dépendances nécessaires.
