Le dev soumet sa fonctionnalité qui, c'est promis, "marche sur sa machine".
Le PM teste et se rend compte que NON.
C'est frustrant certes, mais pourquoi ce problème arrive t'il de manière récurrente?
Je précise que je ne suis pas du tout là pour taper sur Cédric Copagnon, juste pour faire un peu de pédagogie sur cette question clairement importante.

Je ne suis pas là de manière générale pour savoir qui a tort, mais pour voir d'où vient le problème, étape indispensable si on veut le régler.

Le problème peut venir du Dev, surtout s'il est junior et n'a aucune idée de comment faire pour que ce problème de non-reproduction ne se pose plus.

Mais c'est pas comme si les bonnes pratiques n'existaient pas: tests automatisés, docker, TDD, CI/CD, et j'en passe et des meilleures.

Mais peut-etre que l'équipe tech n'a tout simplement pas eu le temps de mettre ces pratiques en place?

Et dans ce cas ci, à quoi c'est du?

Mon expérience c'est que c'est plutot un gros révélateur que les tickets "métiers" prennent toute la place dans JIRA et phagocytes complètement les tickets "engineering" qui, si on y consacraient suffisamment du temps, permettraient que ce genre de problèmes se reproduisent de moins en moins souvent.
Et trouver un équilibre entre les problématiques métier et engineering, dans un monde idéal, c'est justement le role du PM.

Ceci dit il y a beaucoup de PMs qui ne comprennent pas cela, et dans ce cas, c'est le role des devs d'apprendre à dire un mot magique mais de seulement trois lettres.

NON.

"NON je ne peux m'engager à faire toujours plus de tickets métiers et augmenter sans fin la dette technique, parce que si je suivais votre logique on se retrouverait exactement dans la situation déplorée dans ce ticket"