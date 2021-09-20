## <samp>Les Questions pour un entretien technique JAVA </samp>

- 1 . Qu’est ce qu’une class Java? C’est une template définissant un type de donnée. Elle est utilisée pour créer un objet.

- 2 . Qu’est-ce qu’un objet? C’est un élément d’une classe (instance)

- 3 . Qu’es-ce qu’une méthode? C’est l’action (le comportement) qu’un objet peut faire.

- 4 . La différence entre JDK, JVM et JRE:
  *  JDK : Java Devlopment Kit. C’est l’ensemble des packages et programme qu’on utilise pour écrire nos propres programmes.
  *  JVM : Java Virtuel Machine. C’est l’environnement dans lequel les codes compilés des applications Java (Byte Code) s’exécutent.
  *  JRE : Java Runtime Environment . C’est la couche logicielle fournissant les packages et les ressources nécessaires pour qu’un programme java puisse tourner.
  
- 5 . Est-ce que Java utilise les pointeurs? Non, Java importe une couche de sécurité en utilisant les références à la place des pointeurs. Donc pas de pointeurs.

- 6 . les modificateurs d’accès en java: Ce sont les mots clés utilisés pour spécifier l’accès et la porté des objets,
  *  public : les classes, attributs, les méthodes peuvent être utilisés par n’importe quel objet.
  *  protected : Seules les classes du même packages ou des sous-classes qui peuvent utiliser les objets, attributs, méthodes avec ce modificateur.
  *  private: c’est le modificateur le plus restreint, les objets, attributs, méthodes, variables ne peuvent être utilisées que dans la classes où ils sont déclarés.
  *  « nothing » : pas de modificateur ou le modificateur par défaut, la visibilité est restreinte dans le même package.

- 7 . Quelle est la différence entre inner class et subclass?
  *  inner class : ou classe interne, est une classe définie (déclarée) à l’intérieur d’une classe.
  *  subclass : sous classe, est une classe fille d’une classe mère.

- 8 . Quelles sont les étapes pour établir une connexion à une base de données?
  *  Enregistrer le driver
Créer la connexion
Créer le statement
Exécuter la requête
Récupérer les résultats ou l’état de l’exécution
Fermer la connexion

- 9 . Qu’est-ce qu’un constructeur? quels sont ses type?
Un constructeur est un bloc de code utilisé pour initialiser un objet. On distingue deux types de constructeur : constructeur par défaut, et constructeur paramètré.

- 10 . Quelle est la différence entre Overloading et Overriding?
Overloading : décrit le fait que deux méthodes (ou plus) peuvent avoir le même nom mais pas les mêmes parametres.
Overriding : décrit le fait que deux méthodes (ou plus) peuvent avoir le même nom et les mêmes parametres avec une relation mère-fille entre elles.

- 11 . Quelle est la différence entre equals() et ==?
equals() : utilisée pour comparer deux objets de point de vue logique métier
== : utilisée pour comparer les primitifs ou les objets de point de vue valeur.

- 12 . Qu’est ce qu’un thread?
Thread est une classe permettant d’exécuter un programme. En Java, chaque programme a au moins un thread en cours d’exécution (main). 

- 13 . C’est quoi le Garbage Collector?
C’est un mécanisme défini dans la JVM pour faire le ménage. Si un objet n’est plus utilisé, il sera automatiquement détruit pour libérer les ressources.

- 14 . Est-ce que les tableaux sont des primitifs en Java? Non, ce sont des objets.

- 15 . Qu’est-ce qu’une exception?
C’est un problème qui se produit lors de l’exécution d’un programme, et qui nécessite un traitement spéciale pour le bon fonctionnement de l’application. Ceci peut être réalisé, soit par:
  *  l’envoi de l’exception à un niveau supérieur (throws) 
  *  ou par la capture et le traitement au niveau local (try/catch)

- 16 . C’est quoi une classe abstraite? 
Une abstract class est une classe qui permet de définir une classe sans que cette dernière soit instanciable. Pour l’exploiter il faut absolument passer par l’héritage. C’est une technique qui renforce la programmation orientée-objet POO.

- 17 . C’est quoi une interface?
C’est une classe abstraite, qui permet de regrouper un certain nombre de définition des méthodes sans qu’elle soit instanciée. Pour l’exploiter il faut l’implémenter

- 18 . Qu’est ce qu’une servlet?
C’est une classe java qui s’exécute dans contexte au niveau du serveur. Elle permet de recevoir les requêtes client et y répondre en utilisant le protocole HTTP. pour la créer il suffit d’étendre HttpServlet ou bien d’implémenter l’interface Servlet.

- 19 . Qu’est ce qu’une JSP?
Java Server Page. C’est une technique basée sur Java permettant aux développeur de créer dynamiquement du code HTML ou XML ou autre format supporté par les navigateurs. Elle permet aussi de créer ce qu’on appelle les taglib comme étant l’extension du l’HTML et l’XML.
