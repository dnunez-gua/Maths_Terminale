# Suites Numériques

## Progression
??? info "Plan de travail - 7 Séances"
    === "Séances" 
        **Séance 1 :** Pré-requis<br>
        **Séance 2 :** Démonstration par récurrence <br>
        **Séance 3 :** Opérations sur les limites<br>
        **Séance 4 :** Démonstrations <br>
        **Séance 5 :** Limites finies <br>
        **Séance 6 :** Problème
    === "A faire"
        **Seance 1 :** Etudier les rappels de 1ere dans le cours - lien vers exercices et syntèse<br>
        **Séance 3 :** Exercices 1 et 2 dans le cours <br>
        **Séance 4 :** Etudier le cours <br>
        **Séance 5 :** DM à travailler/
    
    === "Evaluation"
        DM : N°73 page 150 et N°105 page 159 <br>
        Semaine du 2 octobre
    
## Cours 
[cours Chap2](./Cours-chap2.pdf){:target="_blank"}

## Rappels

!!! info " Sens de variations d'une suite" 
    === "Méthode 1" 
        Calculer $u_{n+1}-u_n$ et étudier son signe.  
        - Si $u_{n+1}-u_n<0$ alors la suite est décroissante  
        - Si $u_{n+1}-u_n<0$ alors la suite est croissante  
        
    === "Méthode 2" 
        Calculer $\dfrac{u_{n+1}}{u_n}$ et étudier son signe.  
        - Si $\dfrac{u_{n+1}}{u_n}<1$ alors la suite est décroissante  
        - Si $\dfrac{u_{n+1}}{u_n}>1$ alors la suite est croissante  
    
    === "Méthode 3" 
        Etudier la fonction $f$ telle que $f(x)=u_n$  
        - Si $f$ est décroissante alors la suite $u_n$ est décroissante  
        - Si $f$ est croissante alors la suite $u_n$ est croissante  
        ATTENTION : ne pas confondre $u_n = f(n)$ et $u_{n+1}=f(u_n)$. Cette méthode ne sappliquerait pas dans ce cas.
        
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
        Toute suite majorée par une suite divergente, diverge
    === " Démonstration :"
        Soit deux suites $u_n$ et $v_n$ telles que à partir d'un rang $n_0$ on a $u_n\leq v_n$ <br>
        On a $\displaystyle\lim_{n\to +\infty}{u_n}=+\infty$ donc pour $A>0$ réel donné, il existe $n_1>0$ tel que $\forall n>n_1$ on a $u_n>A$<br>
        Donc pour tout $n>max(n_0,n_1)$ on a $v_n>u_n>A$ donc $\displaystyle\lim_{n\to +\infty}{v_n}=+\infty$
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
        N°49 p27 (15 minutes)<br>
        N°54 p27 (15 minutes)<br>
    === "Correction :"
        A venir

!!! question "Opérations sur les limites :"
    === "Exercices :"
        N°25 page 145 (15 minutes) <br>
        N°27 page 145 (15 minutes) <br>
        N°31 page 145 (15 minutes) <br>
    === "Correction : "
        A venir
         <!-- [25-27-31](./corr/25-27-31.pdf){:target="_blank"}-->

!!! question "Limites finies :"
    === "Exercices : "
        N°51p148 (20 minutes)<br>
        N°49p147 (20 minutes)
    === "Correction : "
        A venir
        <!-- [51-49](./corr/51-49.pdf){:target="_blank"}-->

!!! question "Problèmes : "
    === "Exercices : "
        N°94 p153 <br>
        
    === "Correction : "
        A venir
        <!-- [94](./corr/94.pdf){:target="_blank"}-->

!!! info "Algorithme "
    TP Python seuil- suite
