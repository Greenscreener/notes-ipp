# Zkouška

## Úvod

- Definice: Deterministický konečný automat
- Definice: Slovo, $\epsilon$, $\lambda$, $\Sigma^*$, $\Sigma^+$, jazyk
- Definice: Operace zřetězení, mocnina, délka slova
- Definice: Rozšířená přechodová funkce
- Definice: Jazyky rozpoznatelné konečnými automaty, regulární jazyky
- Věta: Iterační (pumping) lemma pro regulární jazyky
- Věta: Neregularita $0^n1^n$
- Definice: Dosažitelné stavy
- Algoritmus: Hledání dosažitelných stavů

## Redukovaný DFA

- Definice: Kongruence
- Věta: Myhill-Nerodova věta
- Definice: Automatový homomorfismus
- Definice: Ekvivalence automatů
- Věta: O ekvivalenci automatů
- Definice: Ekvivalence stavů
- Algoritmus: Hledání rozlišitelných stavů v DFA
- Algoritmus: Testování ekvivalence regulárních jazyků
- Definice: Redukovaný DFA, redukt (viz i 2.6)
- Algoritmus: Nalezení reduktu DFA

## Nedeterministické $\epsilon$NFA

- Definice: Nedeterministický konečný automat s $\epsilon$ přechody ($\epsilon$NFA)
- Definice: $\epsilon$-uzávěr
- Definice: $\delta^*$ pro $\epsilon$NFA
- Definice: Jazyk přijímaný $\epsilon$NFA
- Definice: Konfigurace DFA, $\epsilon$NFA
- Definice: Výpočetní strom, graf $\epsilon$NFA
- Věta: Podmnožinová konstrukce (s $\epsilon$-přechody)
- Algoritmus: Podmnožinová konstrukce (s $\epsilon$-přechody)
- Věta: Převod NFA na DFA
- Věta: Uzavřenost na množinové operace
- Definice: Řetězcové operace nad jazyky
- Věta: Uzavřenost regulárních jazyků na řetězcové operace

## Regulární výrazy

- Definice: Regulární výrazy, hodnota regulárního výrazu
- Věta: Varianta Kleeneho věty
- Definice: Substituce jazyků
- Definice: Homomorfismus jazyků, inverzní homomorfismus
- Věta: Uzavřenost na homomorfismus
- Definice: Inverzní homomorfismus
- Věta: Rozhodovací problémy pro regulární jazyky

## Gramatiky

- Definice: Formální (generativní) gramatika
- Definice: Klasifikace gramatik podle tvaru přepisovacích pravidel
- Definice: Derivace $\Rightarrow^*$
- Definice: Jazyk generovaný gramatikou $G$
- Věta: $L\in RE\implies L\in\mathcal L_3$
- Věta: $\epsilon$-NFA pro gramatiku typu 3 rozpoznávající stejný jazyk
- Definice: Levé (a pravé) lineární gramatiky
- Definice: Lineární gramatika, jazyk
- Definice: Derivační strom
- Definice: Strom dává slovo (yield)
- Definice: Levá a pravá derivace
- Věta: Ekvivalence tvrzení o derivacích
- Definice: Ekvivalence gramatik

## Chomského normální forma, CFG

- Definice: Zbytečný, užitečný, generující, dosažitelný symbol
- Definice: Nulovatelný neterminál
- Algoritmus: Převod CFG do Chomského normálního tvaru
- Definice: Jednotkové pravidlo, jednotkový pár
- Věta: Gramatika v normálním tvaru, redukovaná
- Definice: Chomského normální tvar
- Věta: Chomského normální tvar bezkontextové gramatiky
- Věta: Lemma o vkládání (pumping) pro bezkontextové jazyky
- Algoritmus: CYK algoritmus, v čase $O(n^3)$
- Věta: CYK
- Definice: Jednoznačnost a víceznačnost CFG

## Zásobníkové automaty

- Definice: Zásobníkový automat (PDA)
- Definice: Přechodový diagram pro zásobníkový automat
- Definice: Konfigurace zásobníkového automatu
- Definice: $\vdash$, $\vdash^*$ posloupnosti konfigurací
- Definice: Jazyk přijímaný koncovým stavem, prázdným zásobníkem
- Věta: L(CFG), L(PDA), N(PDA)
- Algoritmus: Konstrukce PDA z CFG
- Definice: Deterministický zásobníkový automat (DPDA)
- Věta: Zařazení $L_{DPDA}$ mezi $L_{PDA}$ a regulární jazyky
- Definice: Bezprefixové jazyky
- Věta: $L\in N(P_{DPDA})$, právě když $L$ bezprefixový a $L\in L(P'_{DPDA})$

## Uzávěrové vlastnosti

- Věta: CFL uzavřené na sjednocení, konkatenaci, iteraci, reverzi, naopak neuzavřené na průnik
- Věta: CFL i DCFL jsou uzavřené na průnik s regulárním jazykem
- Věta: CFL jsou uzavřené na substituci a homomorfismus
- Věta: CFL jsou uzavřené na inverzní homomorfismus
- Věta: Odečtení regulárního jazyka
- Věta: CFL nejsou uzavřené na doplněk ani rozdíl

## Turingův stroj

- Definice: Turingův stroj
- Definice: Konfigurace Turingova stroje
- Definice: Krok Turingova stroje
- Definice: TM přijímá jazyk, rekurzivně spočetný jazyk
- Definice: Přechodový diagram pro TM
- Definice: Vícepáskový Turingův stroj
- Věta: Vícepáskový Turingův stroj
- Definice: Nedeterministický TM
- Věta: Nedeterministický TM
- Věta: TM s jednosměrnou páskou

## LBA, diagonální jazyk

- Definice: Separovaná gramatika
- Definice: Monotónní (nevypouštějící) gramatika
- Definice: Lineárně omezený automat (LBA)
- Věta: Každý kontextový jazyk lze přijímat pomocí LBA
- Věta: LBA přijímají pouze kontextové jazyky
- Věta: Rekurzivně spočetné jsou $\mathcal L_0$
- Věta: Každý jazyk typu 0 je rekurzivně spočetný
- Definice: TM zastaví
- Definice: Rekurzivní jazyky
- Definice: Diagonální jazyk
- Definice: Univerzální jazyk
- Věta: Existence univerzálního Turingova stroje
- Věta: Postova věta
- Věta: Nerozhodnutelnost univerzálního jazyka

## Nerozhodnutelné problémy

- Definice: Rozhodnutelný problém
- Definice: Redukce problému
- Věta: Redukce problému
- Věta: Problém zastavení není rozhodnutelný

## Časová složitost

- Definice: Časová složitost
- Definice: (Asymptotická) horní hranice $O(g(n))$
- Definice: Třída časové složitosti
- Definice: Notace malé $o$
- Definice: Doba běhu nedeterministického TM
- Věta: Převod mezi časovou složitostí pro deterministický a nedeterministický TM
- Definice: Třída $P$
- Věta: $CFL\subseteq P$
- Definice: Verifikátor
- Definice: Třída $NP$
- Definice: Polynomiálně vyčíslitelná funkce, převoditelný jazyk, polynomiální redukce
- Definice: SAT, 3SAT
- Definice: NP úplnost
- Věta: Cook-Levinova věta
- Věta: 3SAT je NP-úplný

## co-NP, prostorová složitost

- Definice: co-NP
- Věta: Problém tautologičnosti je co-NP
- Definice: Prostorová složitost
- Definice: Třídy prostorové složitosti
- Věta: Savitchova věta
- Definice: PSPACE
- Věta: Prostorové a časové třídy