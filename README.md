# SP-projekt

Kalkulator življenskih stroškov

OPIS: Aplikacija omogoča vnos prihodkov, odhodkov, vodenje različnih računov ter pripravo poročil. Glavni
namen aplikacije je, da se skozi poročila ugotovi katere vrste odhodke bi se dalo racionalizirati oz. kakšen
sploh je mesečni/letni odhodek določene te vrste 

CILJNA PUBLIKA IN NAPRAVE: Aplikacija je namenjena vsem, ki bi radi racionalizirali svojo potrošnjo. Aplikacija 
je namenjena za uporabo na računalnikih, tablicah in mobilnih telefonih. 

BRSKALNIKI: Sprotno testiranje na Chrome, obroba na FireFox izgleda čudno (pod meniji), črta od strani v kateri
smo trenutno skoči iz gumba, ko zaslon pomanjšamo. 

2 GRADNIKA:
- Največ sem se ukvarjal s preizkušanjem različnih layoutov in njihovim prilagajanjem
  različnim velikostim ekrana/razmerjem stranic.
- Precej časa sem porabil tudi za barvne kombinacije, vendar mi nikakor ni uspelo narediti
  tako, da bi bila stvar čemu podobna, zaradi tega sem se na koncu odločil kar za temno sivo/belo kombinacijo. 

KOMENTAR:
- V 2 delu bi rad izboljšal UI za zelo majhne zaslone mobilnih telefonov (clear:both za gumbe v meniju).
- Pošiljanja vsebine z submit nisem delal ker ne vem kaj bom rabil za backend, tega še nikoli nisem delal. 
- Ne vem še kako implementirati dodajanje kategorij brez Jscript-a, se pravi da ko dodamo kategorijo se pojavi 
  v dropdown meniju.
- Pri vpisu prihodkov/odhodkov bom dodal polje za datum, v njem bo današnji datum, lahko pa ga bo uporabnik
  tudi spremenil (npr. če ni utegnil odhodka vpisati pred 1 tednom lahko to stori za nazaj), možnost od - do
  bom dodal tudi v poročilih. 



