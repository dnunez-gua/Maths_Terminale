# Chapitre 1 - Limites de fonctions

## Cours 

[cours Chap1](./Cours-Chap1.pdf){:target="_blank"}

### Démonstrations du chapitre 1
!!! attention "Démonstration de la limite de $e^x$ en $+\infty$"
    ===  "Propriété : "
        $$\displaystyle\lim_{x \to +\infty} {e^x}=+\infty$$
    
    ===  "Démonstration :"
        **Pré-requis : théorème de comparaison** <br>
        Soit la fonction $g$ définie sur $\mathbb{R}$ par $g(x)=e^x-x$ <br>
        $g$ est dérivable sur $\mathbb{R}$ et $g'(x)=e^x-1$ <br>
        $g'(x)>0 \Leftrightarrow x>0$. <br>
        $g$ admet donc un minimum en 0 qui vaut $g(0)=1$. Donc $g(x)>0$ pour tout $x\in \mathbb{R}$<br>
        Donc pour tout réel $x$, $e^x>x$ <br>
        Par comparaison: 
        $\displaystyle\lim_{x \to +\infty} {e^x}>\displaystyle\lim_{x \to +\infty} {x}$ <br>
        donc         $\displaystyle\lim_{x \to +\infty} {e^x}=+\infty$ **CQFD**
       
!!! attention  "Démonstration de la limite de $e^x$ en $-\infty$"  
    ===  "Propriété : "
        $$\displaystyle\lim_{x \to -\infty} {e^x}=0$$
    
    ===  "Démonstration :"
        **Pré-requis : limite en $+\infty$ et composition de limite** <br>
        $\displaystyle\lim_{x \to -\infty} {e^x}=\displaystyle\lim_{x \to +\infty} {e^{-x}}$<br>
        $=\displaystyle\lim_{x \to +\infty} \frac{1}{e^x}=0$ **CQFD**

!!! attention "Démonstration du théorème des croissances comparées"
    === "Théorème 1: "
        $\displaystyle\lim_{x \to +\infty} \frac{e^x}{x^n}=+\infty$
        
    === "Démonstration 1"
        **Pré-requis** Opérations sur les limites, composition de limites, théorème des gendarmes**<br>
        **Cas n=1**<br>
        Soit la fonction $g$ définie sur $\mathbb{R}$ par $g(x)=e^x-\frac{x^2}{2}$ <br>
        $g$ est dérivable sur $\mathbb{R}$ et $g'(x)=e^x-x$ <br>
        On a montré dans la démonstration de la limite de $e^x$ que $g'(x)>0$ donc $g$ est croissante sur $\mathbb{R}$.<br>
        donc $\forall x>0$, on a $g(x)>g(0) \Leftrightarrow g(x)>1>0$ donc $e^x>\frac{x^2}{2} \Rightarrow \frac{e^x}{x}>\frac{x}{2}$<br>
        Par comparaison, comme $\displaystyle\lim_{x \to +\infty} \frac{x}{2}=+\infty$ alors $\displaystyle\lim_{x \to +\infty} \frac{e^x}{x}=+\infty$ <br>
        
        **Cas $n> 1$** <br>
        $\frac{e^x}{x^n}=(\frac{e^{\frac{x}{n}}}{\frac{x}{n}})^n\times(\frac{1}{n})^n$<br>
        Posons $X=\frac{x}{n}$ alors $(\frac{e^{\frac{x}{n}}}{\frac{x}{n}})^n\times(\frac{1}{n})^n=(\frac{e^X}{X})^n\times(\frac{1}{n})^n$. <br>
        On a $\displaystyle\lim_{x \to +\infty}X=+\infty$ et on a vu que $\displaystyle\lim_{X \to +\infty} \frac{e^X}{X}=+\infty$ donc par produit $\displaystyle\lim_{X \to +\infty} \frac{e^X}{X}\times(\frac{1}{n})^n=+\infty$ <br>
        Et par composition on a         $\displaystyle\lim_{x \to +\infty} \frac{e^x}{x^n}=+\infty$
        **CQFD**
        
    === "Théorème 2 : "
        $\displaystyle\lim_{x \to -\infty} {x^n e^x}=0$
        
    === "Démonstration 2"
        **Pré-requis : Théorème 1**<br>
        $x^n e^x=\frac{x^n}{e^{-x}}$ <br>
        $\displaystyle\lim_{x \to -\infty} {x^n e^x}=\displaystyle\lim_{x \to -\infty}\frac{x^n}{e^{-x}}=\displaystyle\lim_{x \to +\infty}\frac{(-x)^n}{e^{x}}=\displaystyle\lim_{x \to +\infty}(-1)^n\frac{x^n}{e^{x}}$<br>
        On sait que $\displaystyle\lim_{x \to +\infty} \frac{e^x}{x}=+\infty$ donc par inverse, $\displaystyle\lim_{x \to +\infty}\frac{x^n}{e^{x}}=0$. De plus, $-1\leq (-1)^n\leq 1$ donc $-\frac{x^n}{e^{x}}<(-1)^n\frac{x^n}{e^{x}}<\frac{x^n}{e^{x}}$ par produit $\displaystyle\lim_{x \to +\infty}-\frac{x^n}{e^{x}}=\displaystyle\lim_{x \to +\infty}\frac{x^n}{e^{x}}=0$<br>
        Donc par le théorème des gendarmes         $\displaystyle\lim_{x \to -\infty} {x^n e^x}=0$ **CQFD**
      
        
## Exercices 
!!! example "Activités :" 
    A page 162 <br>
    B page 162

!!! question "Recherche de limites :"
    ===  "Exercices  :"
        N°17 p176 (5 minutes)<br>
        N°20 p176 (5 minutes)<br>
        N°21 p176 (5 minutes)<br>
        
    ===  "Corrigé :"
        A venir
        <br>
      
!!! question "Formalisme des limites :"
    === "Exercices :"
        N°38 p178 (15 minutes)
    === "Indice :"
        Pour $A$ donné, il faut résoudre l'inéquation $f(x)>A$
    === "Corrigé :"
        A venir
       <br>
!!! question "Opérations sur les limites :"
    === "Exercices :"
        N°24 p177 (7 minutes)<br>
        N°25 p177 (7 minutes)<br>
        N°26 p177 (7 minutes)<br>
    === "Indice :"
        Utiliser les formules du cours <br>
        Tracer la courbe représentative à la calculatrice pour conjecturer le résultat.
    === "Corrigé :"
        A venir       
       
    

