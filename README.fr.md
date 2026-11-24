<p align="right"><a href="./README.md">🇬🇧 English</a> · 🇫🇷 Français</p>

<h1 align="center">Salut, moi c'est Ethan Blombou 👋</h1>

<p align="center">
  <a href="https://www.linkedin.com/in/ethan-blombou"><img src="https://img.shields.io/badge/LinkedIn-ethan--blombou-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:ethancte@gmail.com"><img src="https://img.shields.io/badge/Email-ethancte%40gmail.com-EA4335?style=flat&logo=gmail&logoColor=white" alt="Email"/></a>
  <img src="https://img.shields.io/badge/📍-Paris%20·%20Brest-1f2937?style=flat" alt="Paris · Brest"/>
</p>

Élève ingénieur à **IMT Atlantique** (informatique, réseaux et télécoms) et **apprenti en cybersécurité à la Société Générale**, au sein du Group CIO Office.
Je viens des réseaux et de la cyber, et je plonge à fond dans **l'IA agentique, le ML et la data science**. Mes projets préférés sont là où les deux se rencontrent : des agents IA qui vérifient si les systèmes sont vraiment aussi sécurisés qu'on le dit.

J'aime sortir de ma zone de confort : un nouveau domaine, une nouvelle stack, 24 heures, et on livre. C'est pour ça que j'enchaîne les hackathons.

```python
class Ethan:
    ecole       = "IMT Atlantique — diplôme d'ingénieur en apprentissage (2025–2028)"
    travail     = "Société Générale — apprenti cybersécurité, Group CIO Office"
    passions    = ["IA agentique", "machine learning", "data science", "cybersécurité"]
    coup_coeur  = "finance quantitative (le cours de processus stochastiques m'a eu)"
    langues     = {"français": "natif", "anglais": "C1", "espagnol": "B1"}
    hors_boulot = ["CTF sur Root-Me / TryHackMe / Hack The Box", "foot", "échecs"]
    elo_echecs  = 1250  # le seul benchmark que je n'optimise pas (encore)

    def methode(self):
        return "Je conçois et je décide, des agents de code font le fastidieux, je relis et je livre."
```

---

## 🚀 Ce que j'ai construit

### 🔺 [TRIAD](https://github.com/BuildRunnerFr/triad) — l'audit cyber NIS2 contradictoire
*Hackathon Deloitte × Google Cloud · projet d'équipe* · [**Démo en ligne →**](https://triad-311153381291.europe-west9.run.app)

Quatre agents IA confrontent **ce que la DSI dit**, **ce qu'elle a écrit** et **ce qui est réellement configuré** dans son cloud. Chaque contradiction devient un constat sourcé, rattaché à l'article NIS2 concerné, et le dossier est scellé par une chaîne d'empreintes SHA-256 vérifiable hors ligne.
L'idée vient directement de mon alternance : dans un audit cyber, le risque se cache dans l'écart entre la politique et la réalité.

**Ma partie :** développement et déploiement sur Google Cloud
- 4 agents IA orchestrés avec **Google ADK** et **Gemini sur Vertex AI**
- des sondes en lecture seule sur la configuration GCP : IAM, pare-feu, Cloud Storage, sauvegardes, Cloud KMS, rétention des journaux
- backend **FastAPI** sur **Cloud Run**, infrastructure décrite en **Terraform**

### 🏆 [European AI Championship 2026 — équipe Epi84](https://github.com/BuildRunnerFr/epi84-european-ai-championship-2026)
*Paris, 21–22 nov. 2026 · 3 défis de sécurité de l'IA · 22 heures · un nœud de 4 GPU · projet d'équipe*

| Défi | Score public | Ma partie |
|---|:-:|:-:|
| 🔍 Localiser un tatouage invisible dans des images | **0,762** mIoU | ✅ avec [@Xelapte](https://github.com/Xelapte) |
| 🧬 Reconnaître les API qui servent le même modèle | **0,85** | coéquipiers |
| 🧹 Faire *oublier* 3 500 images à un modèle (machine unlearning) | **0,324** | ✅ |

L'astuce du tatouage : on a utilisé l'outil officiel pour fabriquer nos propres exemples annotés, donc de la vérité terrain à l'infini, puis on a entraîné un réseau de segmentation dessus.
Anecdote : c'était ma **toute première compétition de ML**.

### ✅ [Attest](https://github.com/BuildRunnerFr/attest) — l'auditeur DORA qui teste au lieu de lire
*Meta Global AI Developer Hackathon · nov. 2026 · projet solo*

Un agent IA qui audite les systèmes d'une banque selon DORA : il les teste en lecture seule, scelle et masque les preuves, fait valider les corrections, re-teste et rédige le rapport.
Banc d'essai sur 8 banques fictives : **56/56 contrôles justes à chaque exécution, 0 faux constat, injection de prompt détectée 7/7.**

`Python` `Muse Spark 1.3` `SAM 3.1` `GitHub Actions`

### 💶 [Clair](https://github.com/BuildRunnerFr/clair) — suivi financier personnel
Next.js + Supabase (sécurité au niveau des lignes), synchronisation bancaire via l'API TrueLayer, catégorisation automatique des transactions (règles d'abord, puis un LLM).

`Next.js` `TypeScript` `Supabase` `OpenAI`

<details>
<summary><b>Autres projets</b></summary>
<br/>

- **📡 Surveillance de la qualité de ligne et détection d'anomalies** (2025) — analyse de séries temporelles de métriques ADSL/VDSL2, détection statistique des interférences électromagnétiques, alertes automatiques. `Python`
- **🎬 Pipeline automatisé de production vidéo** (2026) — automatisation de bout en bout avec plusieurs API. `Claude API` `Whisper` `FFmpeg`
- **🛡️ Infrastructure réseau sécurisée** — architecture segmentée avec des scénarios d'attaque simulés automatiquement. `Active Directory` `pfSense` `Suricata` `Splunk / Elastic` `Caldera`
- **🐢 Outils pour la protection des tortues marines** (stage, Malaisie, 2026) — une Progressive Web App qui remplace les fiches papier de terrain, et un portail captif qui collecte les questionnaires des visiteurs de l'île pour l'équipe de recherche.

</details>

---

## 🧭 Mon parcours

| Quand | Où | Quoi |
|---|---|---|
| 2022–2025 | 🎓 IUT Vélizy | BUT Réseaux et Télécommunications, parcours cybersécurité |
| 2024 | 🇧🇬 Université technique de Sofia | Semestre Erasmus+ |
| 2024–2025 | 📶 Free (groupe Iliad) | Apprenti conducteur de travaux télécom : opérations terrain, équipes de sous-traitants, reporting client |
| 2025– | 🎓 IMT Atlantique | Diplôme d'ingénieur en informatique, réseaux et télécoms |
| 2025– | 🏦 Société Générale | Apprenti cybersécurité : automatisation Python qui croise les contrôles d'accès de 3 sources de données, reporting hebdomadaire vers ~100 responsables techniques dans le monde, référentiel d'audit fournisseurs partagé entre banques européennes |
| 2026 | 🇲🇾 SEATRU, Universiti Malaysia Terengganu | Stage en développement logiciel : protection des tortues marines |

---

## 🛠️ Boîte à outils

**IA & data :** IA agentique (Google ADK, orchestration de LLM) · ML (segmentation, machine unlearning) · pandas / NumPy · statistiques, probabilités, traitement du signal
**Cyber :** conformité (NIS2, DORA) · sécurité du cloud · SOC / SIEM (Splunk, Elastic) · IDS (Suricata) · pare-feu (pfSense, Stormshield) · Active Directory
**Dev & cloud :** Python · TypeScript · SQL · C · C++ · Java · FastAPI · Next.js · Google Cloud · Terraform · Docker · Linux / Bash · Git / GitLab

---

## 🔭 En ce moment

- 🤖 En alternance : un **agent IA qui répond à des questions en langage naturel en croisant des référentiels internes**, pour trouver la bonne réponse en quelques secondes au lieu de fouiller des documents.
- 🎧 Prochaine étape : le **hackathon Deezer**, Paris, 28–29 nov.
- ♟️ J'essaie de dépasser 1250 Elo. Ça progresse moins vite que mes entraînements sur GPU.

<p align="center"><i>Tu fais de l'IA agentique, du ML ou de la data science ? Parlons-en, construisons un truc, ou faisons équipe au prochain hackathon.</i></p>
