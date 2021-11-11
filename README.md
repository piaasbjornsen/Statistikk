# Egene notater

# Varianse 
Varians er et mål på hvor mye en S.V vil variere om man gjentar forsøket uendelig mange ganger. Variansen er også knyttet til forventningsverdien.

## Notasjon
> Varians bruker notasjonen: 
>* **s<sup>2</sup>** 
>* **Var[X]**
>* **σ<sup>2</sup>**

## Definisjon
>
> Var[X] = E [( X<sup>2</sup>- μ )<sup>2</sup>]
> 
> **Diskre:**
> 
> ![Varians](../../../../../var/folders/xg/9qgl3jxn7tsc9hnr64c8msn40000gn/T/TemporaryItems/NSIRD_screencaptureui_bnOk6r/Screenshot 2021-11-11 at 20.22.23.png)
>
> **Kontinuelig:**
> 
> ![Varians](../../../../../var/folders/xg/9qgl3jxn7tsc9hnr64c8msn40000gn/T/TemporaryItems/NSIRD_screencaptureui_yNUv09/Screenshot 2021-11-11 at 20.23.01.png)
>     
> Alternativt (for både diskre og kontinuelig):
> 
> σ<sup>2</sup> = E [ X <sup>2</sup>] - μ <sup>2</sup>


Merk, varians kan aldri være negativ.

# Forventningsverdi (Mean)
Man kan tenkte på forventningsverdi til en S.V som gjennomsnittlig verdi variablen får når man gjentar forsøket uendelig mange ganger. 


## Notasjon
> Forventningsverdi bruker notasjoenne: **E(X) = μ**

### Forventningsverdi for diskre og kontinuelig 
![forventningsverdi](../../../../../var/folders/xg/9qgl3jxn7tsc9hnr64c8msn40000gn/T/TemporaryItems/NSIRD_screencaptureui_LzXJ8X/Screenshot 2021-11-11 at 19.43.59.png)

Merk at f(x) for diskre S.V er punktsannsynligheten, og med kontinuelig er f(x) sannsynlighetstettheten.

# Standardavvik (Standard deviation)
Standardavvik er den positive roten av variansen.
Standardavvik er et mål på variasjon. 
## Notasjon 
> Standatd avvik bruker notasjonen; **s**

# Frihetsgrad (Degree of freedom)
* Brukes blant annet i t-fordeling
> **n-1** er frihetsgraden 

# Utfallsrom (Sample space)
Utfallsrommet til et statistikk eksperiment er mengden *S* av alle mulige utfall. 
## Notasjon 
> Utfallsrom bruker notasjonen: *S* = {...}

#Hendelse 
En hendelse er en delmengde av utfallsrommet 
## Snitt 
Snittet av to hendelser A og B, er hendelsen som inneholder alle elementne som er felles for A og B. 
> A ∩ B
## Union 
Unionen av to hendelser A og B, er hendelsen som inneholder alle elementene i A, B eller begge.
> A ∪ B
# Permutasjoner og Kombinatorikk
## Multiplikasjonssetningen (Multiplication rule)
Hvis en operasjon kan gjøres på n<sub>1</sub> måter, og for hver av disse kan en ny operasjon bli gjort på n<sub>2</sub> måter, kan de to operasjonene bli gjort på n<sub>1</sub>* n<sub>2</sub> måter.

>![Teorem; multipikasjonssetningen](../../../../../var/folders/xg/9qgl3jxn7tsc9hnr64c8msn40000gn/T/TemporaryItems/NSIRD_screencaptureui_ZxxtbM/Screenshot 2021-11-11 at 14.52.24.png)

##Permutasjon
Permutasjon er hvor mange forksjellige måter et gitt antall elementer kan ordnes på. 

**Bruksområde:**
* Tar *ikke* hensyn til rekkefølge (ab = ba)

### Generelt
Generelt kan n objekter ordnes på n! måter. 
> n objekter, gir n! = n(n-1)(n-2)...(2)(1) permutasjoner.
### Ordnet utvalg uten tilbakelegging
>![Teorem; permutasjon](../../../../../var/folders/xg/9qgl3jxn7tsc9hnr64c8msn40000gn/T/TemporaryItems/NSIRD_screencaptureui_E6lg3z/Screenshot 2021-11-11 at 14.54.18.png)

###Objekter i en sirkel
> Antall permutasjoner av elementer satt i sirkel er **(n-1)!**

### Grupperte objekter

>![distinct permutations](../../../../../var/folders/xg/9qgl3jxn7tsc9hnr64c8msn40000gn/T/TemporaryItems/NSIRD_screencaptureui_KTpNm5/Screenshot 2021-11-11 at 16.02.57.png)

### Oppdeling av *n* objekter i *r* grupper

>![Teorem 2.5](../../../../../var/folders/xg/9qgl3jxn7tsc9hnr64c8msn40000gn/T/TemporaryItems/NSIRD_screencaptureui_JRrcY3/Screenshot 2021-11-11 at 16.05.01.png)


### Kombinasjoner av *n* objekter delt *r* om gangen

>![teorem 2.6](../../../../../var/folders/xg/9qgl3jxn7tsc9hnr64c8msn40000gn/T/TemporaryItems/NSIRD_screencaptureui_qZHMZb/Screenshot 2021-11-11 at 16.06.47.png)

## Kombinasjoner 
Når vi vil finne ut hvor mange måter vi kan velge *r* objekter fra *n* uten å ta hendyn til rekkefølgen bruker vi kombinatorikk.

**Bruksområde:**
* Tar hensyn til rekkefølge

>![choose](../../../../../var/folders/xg/9qgl3jxn7tsc9hnr64c8msn40000gn/T/TemporaryItems/NSIRD_screencaptureui_xZcouL/Screenshot 2021-11-11 at 16.42.10.png)

# Sannsynlighet for en hendelse 

##Notasjon
> Sannsynligheten for en hendelse A: **P(A)**


---------------------------------------------!!!!!!!!!!!!!!!!!2.5!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!------------------------------------------------

# Stokastisk variabel (Random variable)
En stokastisk variabel holder verdien til et bestemt utfall av en hendelse i utfallsrommet. 

##Notasjon
> Vi bruker en stor bokstav, typisk *X* for å notere en stokastisk variabel.
> 
> Vi bruker den samme bokstaven, men liten, for verdien til den stokastiske variabelen.


# Sannsynlighetsfordeling (Probability distribution)
Sannsynlighetsfordelingen til den stokastiske variabelen er sannsynlighetene for hver verdi av den stokastiske variabelen. 
Vi har tre forskjellige sannsynlighetsfordelinger:
* Punktsannsynlighet - Diskre **f(x)**
* Sannsynlighetstetthet - Kontinuelig **f(x)**
* Kumulativ fordeling - Diskre og Kontinuelig **F(x)**

## Diskre sannsynlighetsfordeling
###Punktsannsynlighet - Diskre
Punktsannsynlighet er sannsynligheten for P(X=x) for én bestemt verdi av x. 

Ekvavilent for kontinuelig S.V er *sannsynlighetstetthet*
>Punktsannsynlighet har tre egenskaper:
>1. f(x) ≥ 0
>2. Σ <sub>x</sub> f(x) = 1
>3. P(X=x) = f(x)

>![Punktsannsynlighet](../../../../../var/folders/xg/9qgl3jxn7tsc9hnr64c8msn40000gn/T/TemporaryItems/NSIRD_screencaptureui_Yo8m8J/Screenshot 2021-11-11 at 18.54.08.png)
##Kontinuelig sannsynlighetsfordeling
Når en S.V kan ta alle verdier i et intervall på tallinjen, eller alle verider på hele tallinjen. 

### Sannsynlighetstetthet - Kontinuelig 
Sannsynlighetstettheten til en kontinuelig S.V angir i en viss forstand med hvilke sannsynlighet den S.V antar de mulige verdiene. 

Sannsynligheten for at en kontinuelig S.V tar en verdi x er alltid 0, dermed må vi må alltid se på et intervall (som kan være veldig lite), og dermed må vi alltid finne P(a < X ≤ b).

Merk at sannsynlighetstetthet *f(x)* ikke er en sannsynlighet P(a < X ≤ b), men en "hjelpe-variabel" vi kan bruke for å finne P(a < X ≤ b). For å gjøre dette må vi integrere f(x) fra a til b.

* f(x) er ikke en sannsynlighet
  * f(x) må ikke være mellom 0 og 1
* Området under f(x) er alltid lik 1
>![sannsunlighetstetthet](../../../../../var/folders/xg/9qgl3jxn7tsc9hnr64c8msn40000gn/T/TemporaryItems/NSIRD_screencaptureui_1IeQYm/Screenshot 2021-11-11 at 17.50.38.png)

>Sannsynlighetstetthet har tre egenskaper:
> ![egenskaper til sannsynlihgetstetthet](../../../../../var/folders/xg/9qgl3jxn7tsc9hnr64c8msn40000gn/T/TemporaryItems/NSIRD_screencaptureui_n1k8Y2/Screenshot 2021-11-11 at 18.46.34.png)


## Kumulativ fordeling - Diskre og kontinuelig
En kumulativ fordeling bruker vi når vi ønsker å finne ut om den S.V X vil ta en verdi lik eller større enn, ≤, en verdi. 
F(x) er en sannsynlighet, og må dermed alltid være mellom 0 og 1.

### Kumulativ for diskre
> F(x) = P(X ≤ x) = Σ<sub>t ≤ x</sub> f(t)

### Kumulativ for kontinuelig
>![](../../../../../var/folders/xg/9qgl3jxn7tsc9hnr64c8msn40000gn/T/TemporaryItems/NSIRD_screencaptureui_A1SslD/Screenshot 2021-11-11 at 19.36.14.png)



