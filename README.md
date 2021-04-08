# Vaja9-DAC-STM32VL-
Moja razvojna ploščica ima 2 DAC izhoda.
Na teh dveh izhodih lahko dobimo napetost od 0 do 3 V.
Sama sva uporabili prvi DAC izhod, ki pa je na pinu PA4.
Da nastavimo DAC izhod moramo poiskati zavihek Configuration in polje DAC, v polju parameter settings sta privzeti nastavitvi OUTPUT BUFFER - Enable in TRIGGER - None, seveda jih lahko glede na potrebe spremenimo, midva sva pustila nastavljeno na privzetih nastavitvah.
# Komentar delovanja: Ploščica STM32L1 opravi digitalno analogno pretvorbo (DAC) na izhodu PA4. V programu nastavimo kakšno napetost želimo imeti na tem izhodu, v našem primeru je napetost 2,2 V (na izbiro imamo območje od 0 do 3 V), vendar multimeter na izhodu ne pokaže napetosti 2,2 V ampak napetost 2,16 V. Sama misliva, da se to zgodi za to, ker ima multimeter majhno napako in tutdi žice imajo majhno upornost. Sicer pa program deluje odlično in sva z delovanje zadovolnja.  
