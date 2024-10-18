# poski
Testovací úloha FE

#Povinne zadání
- viditelnost ikon sociálních sítí v levé části vyřešena fixním pozicováním, neřešeno pro menší rozlišení
- fialový blok vpravo je neklikatelný prvek
- jednotlivé články jsou klikatelné na nadpis a štítek (label), efekt po najetí pouze na tyto dva prvky, 
  samozřejmě možné předělat na celou plochu
- použité obrázky zmenšené

#JavaScript

Po kliknutí na štítek (Travel, Tech) nebo nadpis článku se do konzole prohlížeče vypíše:
1. počet příspěvků na stránce (tag <article>)
2. průměrná výška článků v px (průměrná výška tagů <article>)
3. součet délek nadpisů článků (počet znaků v <h2>)
4. vytvoří se objekt article = { nadpis, datum, delka} a vypíše do konzole
5. vzhledem k fixed pozici socialních ikon neřešeno
