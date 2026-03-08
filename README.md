# TP : Maîtrise du Prompt Engineering & Systèmes Multi-Agents

Ce dépôt contient les travaux pratiques réalisés sur l'interaction avec les Grands Modèles de Langage (LLMs) via différentes plateformes (OpenAI, Ollama, Groq) et techniques avancées de prompting.

---

## 🏗️ 1. Tokenizer avec `tiktoken`

Étude de la segmentation du texte en tokens et calcul de l'utilisation des ressources pour les modèles OpenAI.

* Utilisation de la bibliothèque `tiktoken` pour encoder/décoder les chaînes de caractères.
* Analyse de l'impact du choix du modèle sur le nombre de tokens générés.

<img width="752" height="100" alt="image" src="https://github.com/user-attachments/assets/521a054e-4fa3-4405-9fd7-2023870dbde9" />
<img width="758" height="95" alt="image" src="https://github.com/user-attachments/assets/30bfece2-a313-4eaf-ab6f-11dcb0ba91b7" />
<img width="758" height="172" alt="image" src="https://github.com/user-attachments/assets/3dce8b8c-b635-4a23-8144-c2e47b651727" />
<img width="758" height="157" alt="image" src="https://github.com/user-attachments/assets/a9d28cfd-e291-4d98-805e-274d450bb1db" />
<img width="759" height="188" alt="image" src="https://github.com/user-attachments/assets/4368a71d-6591-44c7-b886-815504c4638e" />


## 🤖 2. How to Prompt OpenAI LLMs

Mise en œuvre des interactions avec les modèles GPT via l'API officielle.

* Structuration des messages : `System`, `User` et `Assistant`.
* Tests de paramètres : `Temperature`, `Top_p`, et `Max_tokens`.

<img width="757" height="302" alt="image" src="https://github.com/user-attachments/assets/c796348e-c957-42d2-8979-a07276b27297" />
<img width="754" height="220" alt="image" src="https://github.com/user-attachments/assets/146dca5f-85a7-4691-96ca-5fd87230d72d" />


## 📡 3. Interact with OpenAI LLMs via HTTP Client (Postman)

Démonstration de l'indépendance technologique en utilisant des requêtes HTTP brutes sans SDK.

* Configuration des headers (`Authorization: Bearer`).
* Envoi de payloads JSON via Postman vers `https://api.openai.com/v1/responses`.

<img width="1158" height="793" alt="Capture d&#39;écran 2026-03-08 135542" src="https://github.com/user-attachments/assets/6a675a2f-2869-4bbb-b9e3-b7806f170d9a" />


## 🏠 4. How to Prompt Local Ollama LLMs

Exploitation de modèles de langage en local pour garantir la confidentialité des données.

* Installation et configuration d'Ollama.
* Utilisation de modèles comme `Llama 3.2` directement sur la machine.

<img width="757" height="337" alt="image" src="https://github.com/user-attachments/assets/0c322669-eb99-41ca-8c2a-701c6e9a2027" />


## 🚀 5. Interact with Ollama LLMs via HTTP Client (Postman)

Utilisation de l'API locale d'Ollama pour intégrer les LLMs dans n'importe quelle application.

* Endpoint : `POST http://localhost:11434/api/chat`.

<img width="1169" height="900" alt="Capture d&#39;écran 2026-03-08 143625" src="https://github.com/user-attachments/assets/5ddcd83e-2eb5-4aab-a8f6-7fd3037c1990" />



## ⚡ 6. How To Prompt Groq LLMs

<img width="755" height="322" alt="image" src="https://github.com/user-attachments/assets/156526bd-4e3c-4766-9004-30ca5d000421" />
<img width="751" height="220" alt="image" src="https://github.com/user-attachments/assets/282491b0-e23c-4484-96b5-e8ec657a225f" />


## 🎨 7. Image Generation Prompting

Conception de prompts descriptifs pour obtenir des images précises.

<img width="755" height="329" alt="image" src="https://github.com/user-attachments/assets/77a9e08e-477e-4d37-8fd8-69f93a22ae58" />
<img width="1024" height="1536" alt="image" src="https://github.com/user-attachments/assets/180418f7-bb38-4895-8bfa-2899111cee31" />


> **📸 Capture d'écran à insérer :** Une capture du prompt utilisé et de l'image générée résultante.

---

## 👁️ 8. Image Description (Vision)

Utilisation des capacités multimodales des LLMs pour interpréter et décrire des images.

* Envoi d'images encodées en Base64 ou via URL.
* Extraction d'informations contextuelles à partir d'un visuel.

<img width="758" height="293" alt="image" src="https://github.com/user-attachments/assets/2cd3c0b8-ba9a-450b-bdfa-5db24654d9bd" />
<img width="756" height="316" alt="image" src="https://github.com/user-attachments/assets/08ad6999-92a4-4a15-b2d1-6282404b4dd6" />


## 📝 9. Exemple : Aspect Based Sentiment Analysis (ABSA)

Cas d'usage avancé consistant à extraire des sentiments pour des aspects spécifiques d'un texte.

<img width="758" height="327" alt="image" src="https://github.com/user-attachments/assets/f665470d-e1f1-4a23-ad11-cca8b5e95562" />
<img width="758" height="236" alt="image" src="https://github.com/user-attachments/assets/40cfe6ef-b106-494f-b69f-b272fa7a1a07" />
<img width="760" height="214" alt="image" src="https://github.com/user-attachments/assets/b20c4e10-4d2d-4299-b713-d1b668d20c04" />
<img width="755" height="209" alt="image" src="https://github.com/user-attachments/assets/6b465f9c-b501-4d12-aec1-d7f945cc6677" />
<img width="758" height="281" alt="image" src="https://github.com/user-attachments/assets/e80e7e70-b559-4ce3-9037-f3dea7454a39" />


## ⚙️ Installation

1. Clonez ce dépôt.
2. Installez Ollama pour la partie locale.
3. Configurez les clés dans un fichier `.env` (non inclus dans le dépôt).
4. Installez les dépendances nécessaires.
