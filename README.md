# bakalarka
Bakalarska praca Michal Macej.


Na spustenie programu je potrebne mat nainstalovany python 2.7 a program volatility https://github.com/volatilityfoundation/volatility dalej treba mat aj plugin Hollowfind https://github.com/monnappa22/HollowFind
Tieto programy su v subore program_bakalarka.rar 
Dalej je potrebne uistit sa ze cesty v konfiguracnych suboroch  agenta (MultiagentovySystem\Agent\config) su nastavene spravne na vstupne a vystupne subory v ontologii MultiagentovySystem\Agent\memory_init).

Prve treba zapnut gui v subore Agent (vyskoci pop-up treba kliknut na NO!) a nasledne potom spusti gui v subore Sensor. (Tymto sa zapne multi-agentova cast)

Dalej na zapnutie programu na zber dat z operacnej pamate je potrebne zapnut subor main.py (\Volatility_program\main.py) kde su jeho vstupmi cesta k obrazu pamate a profil daneho obrazy napr: (WinXPSP2x86 C:\...\...\stuxnet.vmem)
