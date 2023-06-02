# Utiliser les IAs génératives de texte

## Cas d'utilisation convaincants

### Texte

    - résumer un ou plusieurs documents
    - jouer le rôle d'un interlocuteur
        - coach de formation (pour répondre à des questions, pratiques ou théoriques)
        - solveur de problèmes (car on peut souvent soi-même résoudre un problème quand on se met à l'expliquer à quelqu'un)
        - colleur de prépa (pour vérifier qu'on a bien compris les concepts : oui si on sait les expliquer)
        - avocat du diable (pour aider à objectiver quand on doit prendre une décision)
        - négociateur (pour mieux se préparer à l'échange réel)

### Code

    - expliquer du code
    - faire un brouillon de code à partir d'une description
    - refactoriser du code
    - trouver des bugs dans un code
    - jouer le rôle d'un interlocuteur
        - coach de formation (pour répondre à des questions, pratiques ou théoriques)
        - solveur de problèmes / canard en plastique (car on peut souvent soi-même résoudre un problème quand on se met à l'expliquer à quelqu'un)
        - colleur de prépa (pour vérifier qu'on a bien compris les concepts : oui si on sait les expliquer)

## Prompts

### Colleur de prépa

> Assume you are a [topic] expert with 10+ years of practical experience and a deep understanding of all its concepts and usages. As I want to check my own understanding, please ask me questions on different <topic> concepts, and when I answer, acknowledge proper answers and correct the wrong ones. Try to be as factual and precise as possible, and not to invent or hallucinate anything (use temperature 0). Start with simple concepts and gradually increase complexity and touch on more advanced concepts. Only give me corrected answers if I ask you to. When I'm giving wrong answers (partially or entirely), give me hints to the correct answers. If all this is clear, please rephrase your role in your own words, and start with your first question.

### Solveur de problèmes

> Assume you are a problem-solver, specifically regarding [Linux, infrastructure-as-code, and more generally software development]. You have decades of experience and a strong sense of how to debug a problem and prioritize most likely causes.
