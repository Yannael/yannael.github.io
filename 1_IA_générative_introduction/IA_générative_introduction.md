(part1)=
# IA générative: Introduction

## L'intelligence artificielle générative

Les outils d'intelligence artificielle (IA) générative sont des outils informatiques capables de générer de façon partiellement automatisée des contenus numériques tels que du texte, des images, des vidéos, de la musique ou encore du code informatique.

La capacité de ces outils à générer de nouveaux contenus provient du fait qu'ils ont été préalablement entrainés avec de large quantités de données (Wikipédia, livres numérisés, banques d'images, forum Internet, etc...), en utilisant des algorithmes d'un domaine de l'informatique appelé **apprentissage automatique (ou "machine learning" en anglais)**. Le résultat de cet entraînement est appelé un **modèle de prédiction**, qui est une représentation approximative et imparfaite des connaissances fournies lors de l'entraînement.

![generative_ai](attachments/generative_ai.jpg)


Ces outils fonctionnent en prenant en compte des instructions fournies par l'utilisateur, souvent désignées par le terme "**prompt**" (parfois appelé "invite" en français).
## Exemples

Voyons quelques exemples avec l'outil Microsoft Copilot, qui est l'outil d'IA générative de référence proposé par Microsoft.

**Note**: **Microsoft Copilot est l'outil à privilégier à l'ULB** car c'est le seul qui garantit la confidentialité et la propriété des données transmises ou produites grâce au contrat qui lie Microsoft à l’ULB. De nombreux autres outils d'IA génératives existent, en particulier open-source, voir la section "Boîte à outils de référence".

Microsoft Copilot est accessible à l'adresse [https://copilot.cloud.microsoft/](https://copilot.cloud.microsoft/), où tu pourras t'y connecter avec ton adresse email ULB. Le pictogramme d’un bouclier vert doit être présent en haut à droite pour confirmer que tes conversations sont protégées.

### Génération de texte

Voici ci-dessous un échange avec Copilot, demandant de générer des paroles d'une chanson sur le thème du libre examen dans un style hip-hop.

![copilot_example_gpt4](attachments/copilot_example_gpt5.png)
Pas si mal !

Que s'est-il passé dans cet échange ?

- Avec Copilot en mode génération de texte, le modèle de prédiction s'appelle [GPT-4](https://en.wikipedia.org/wiki/GPT-4). Notre prompt a été envoyé à ce modèle de prédiction, qui a renvoyé la réponse sous forme de texte. 
- GPT-4 est développé par OpenAI, la société américaine qui commercialise aussi ChatGPT. 
- **Il est important de distinguer le modèle de l'interface utilisateur**. Ici, l'interface utilisateur est celle de Microsoft, qui offre des fonctionnalités pratiques comme le fait de fournir des suggestions pour continuer les échanges, ou d'aller chercher du contenu sur Internet. Le coeur de la génération de texte est cependant le modèle GPT-4 (qui est aussi celui derrière l'outil ChatGPT d'OpenAI) qui n'a pas accès à Internet, et ne fait que prédire les mots suivants comme un outil d'auto-complétion. 

Pour plus d'explications sur ce que font réellement les modèles de langage comme GPT-4, rends-toi sur la capsule "Comment ça marche?" !

### Génération d'images

L'interface utilisateur Copilot permet aussi de générer des images. Lorsque l'on entre un prompt demandant la création d'une image, c'est alors un autre modèle qui est appelé. Ce modèle s'appelle [DALL-E 3](https://openai.com/index/dall-e-3/), qui est aussi développé par OpenAI.

Le modèle renvoie à Copilot l'image (ou les images) générées.

Ici, nous avons demandé de générer des illustrations, dans un style art-nouveau, de Pierre-Théodore Verhaegen en train de rapper sur la place Flagey.

![copilot_example_dalle3](attachments/copilot_example_dalle4.png)

On note dans ces propositions la présence d'un style art-nouveau. En revanche, Flagey n'y est pas spécialement reconnaissable, à l'instar du [fondateur de l'ULB](https://fr.wikipedia.org/wiki/Pierre-Th%C3%A9odore_Verhaegen "https://fr.wikipedia.org/wiki/Pierre-Th%C3%A9odore_Verhaegen"). 

Cet exemple illustre un point essentiel des IA génératives : si elles peuvent se révéler assez efficaces d'un point de vue créatif, elles ne sont cependant pas conçues pour générer des contenus factuellement corrects.
### Génération d'audio/vidéo

Enfin, générons une musique à partir des paroles de chanson obtenues précédemment.

<video controls="true" title="C'est le libre examen">
        <source src="https://github.com/ULB-AcademIA/guide_usages_IA/raw/refs/heads/main/1_IA_g%C3%A9n%C3%A9rative_introduction/attachments/libre_examen_suno.mp4">libre_examen_suno.mp4
</video>

C'est ici l'outil [Suno](https://suno.com/create) que nous avons utilisé, en demandant un morceau dans un style "hip-hop avec des riffs de piano". L'application Suno a aussi au passage généré une illustration pour la chanson, représentant un intérieur d'ancienne bibliothèque.
## A retenir

Nous avons ainsi, en quelques minutes, créé le texte d'une chanson, produit des illustrations et mis le tout en musique. 

Retenons ici que si les outils d'IA générative utilisés se sont montrés assez utiles d'un point de vue créatif, ils l'ont beaucoup moins été d'un point de vue factuel.
## Vocabulaire de base pour l'IA générative

**Prompt (aussi appelé requête, ou invite de commande)**: Description textuelle de la tâche qu’une IA générative doit effectuer ([Wikipedia](https://fr.wikipedia.org/wiki/Ing%C3%A9nierie_de_prompt "Wikipedia")).

**Modèle de prédiction:** Fonction produite après avoir été entraînée à reconnaître des relation statistiques dans des données. Dans le cas de la génération de texte, on parle de **grand modèle de langage** (ou **large language model (LLM)** en anglais) ([Wikipedia](https://fr.wikipedia.org/wiki/Grand_mod%C3%A8le_de_langage "Wikipedia")). 

**Apprentissage automatique (ou "machine learning" en anglais)** : Champ d'étude de l'[intelligence artificielle](https://fr.wikipedia.org/wiki/Intelligence_artificielle "intelligence artificielle") qui se fonde sur des approches mathématiques et statistiques pour donner aux ordinateurs la capacité d'« apprendre » à partir de données ([Wikipedia](https://fr.wikipedia.org/wiki/Apprentissage_automatique "Wikipedia")).

**Algorithme:** Suite finie et non ambiguë d'instructions et d’opérations permettant de résoudre une classe de problèmes ([Wikipedia](https://fr.wikipedia.org/wiki/Algorithme "Wikipedia")).








