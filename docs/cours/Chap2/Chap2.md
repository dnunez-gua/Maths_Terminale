# Suites Numériques

## Progression
??? info "Plan de travail - ... Séances"
    === "Séances" 
        **Séance 1 :** Pré-requis<br>
        **Séance 2 :** Démonstration par récurrence <br>
        **Séance 3 :** <br>
        
    === "A faire"
        **Seance 1 :** Etudier les rappels de 1ere dans le cours - lien vers exercices et syntèse<br>
        **Séance 3 :** Exercices 1 et 2 dans le cours <br>
        **Séance 4 :** 
    
    === "Evaluation"
        Semaine du 2 octobre
    
## Cours 
[cours Chap2](./Cours-chap2.pdf){:target="_blank"}

## Démonstrations Chapitre 2
!!! attention "Démonstration "
    === "Propriété : "
        Toute suite croissante non majorée diverge

    ===  "Démonstration :"
        Soit une suite $u_n$, une suite croissante et un réel $A>0$.<br>
        $u_n$ est non majorée donc, il existe un rang $n_0$ tel que $u_{n_0}>A$<br>
        $u_n$ est croissante donc pour tout $n>n_0$ on a $u_n>u_{n_0}$<br>
        On a donc montré que pour A>0 donné, il existe $n_0$ tel que pour tout $n>n_0$ on a $u_n>A$<br>
        ce qui est la définition de <br>
        $\displaystyle\lim_{n\to +\infty}{u_n}=+\infty$
        
        <br>
        **CQFD**

!!! attention "Démonstration "
    === " Théorème de comparaison :" 
        "Toute suite majorée par une suite divergente, diverge
    === " Démonstration :"
        Soit deux suites $u_n$ et $v_n$ telles que à partir d'un rang $n_0$ on a $u_n\leq v_n$ <br>
        On a $\displaystyle\lim_{n\to +\infty}{v_n}=+\infty$ donc pour $A>0$ réel donné, il existe $n_1>0$ tel que $\forall n>n_1$ on a $v_n>A$<br>
        Donc pour tout $n>max(n_0,n_1)$ on a $u_n>v_n>A$ donc $\displaystyle\lim_{n\to +\infty}{u_n}=+\infty$
        <br>
        **CQFD**
    
!!! attention "Démonstration "
    === "Propriété : "
        Si $q>1$, alors $\displaystyle\lim_{n\to +\infty}{q^n}=+\infty$
    === "Pré-requis : "
        - Inégalité de Bernouilli : $\forall a>0, \forall n\geq 0, (1+a)^n>1+na$ <br>
        - Propriétés de comparaison

    ===  "Démonstration :"
        $q>1$ donc il existe un réel $a>0$ tel que $q=1+a$ <br>
        $q^n=(1+a)^n>1+na$ <br>
        Or $\displaystyle \lim_{n\to +\infty}{1+na}=+\infty$ donc par comparaison <br>
        $\displaystyle \lim_{n\to +\infty}{q^n}=+\infty$ 
    
        
        <br>
        **CQFD**
        


## Exercices 

!!! example "Pré-requis :" 
    N°1 page 126<br>
    N°2 page 126<br>
    N°3 page 126<br>
    N°6 page 126<br>

!!! question "Démonstration par récurrence :"
    === "Exercices :" 
        N°48 p27 (10 minutes)<br>
        N°49 p176 (15 minutes)<br>
        N°54 p176 (15 minutes)<br>
    === "Correction :"
        A venir
  
