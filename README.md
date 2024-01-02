# Leading cause of disability-adjusted life year (DALY) & Death

## Përmbledhje
Ky projekt synon të identifikojë dhe kuptojë faktorët kyç që kontribuojnë në Vitin e Jetës së Përshtatur me Aftësi (DALY) dhe vdekje në 25 ekonomitë kryesore. Duke përdorur të dhënat gjithëpërfshirëse të Organizatës Botërore të Shëndetësisë (WHO), ne eksplorojmë grupe të ndryshme demografike, vende dhe vite për të parashikuar mundësitë e ardhshme të DALY dhe vdekjeve. Qëllimi ynë është të identifikojmë faktorët kritikë për të zhvilluar zgjidhje inovative për të zvogëluar ose parandaluar ndikimin e tyre, ndërsa gjithashtu rritim ndërgjegjësimin publik për çështjet e kujdesit shëndetësor.

## Të Dhënat
Të dhënat e përdorura në këtë projekt vijnë nga dataseti Top 25 Ekonomitë Shkak i Parësor i DALYs & Vdekjeve të ofruara nga Organizata Botërore e Shëndetësisë (WHO) 2021. Përfshin statistika të detajuara mbi DALY dhe shkaqet e vdekjes në grupe të ndryshme demografike, vende dhe vite.

## Kolonat që përmbanë dataset-i:

- COUNTRY_CODE: Country code
- COUNTRY: Country name
- GHE_CAUSE_CODE: Cause code
- GHE_CAUSE_TYPE: Cause type
- GHE_CAUSE_TITLE: Cause title
- YEAR: Year
- SEX_CODE: Gender code
- AGEGROUP_CODE: Age group code
- POPULATION: Population
- DEATHS: Number of deaths
- DEATHS_RATE: Death rate
- DEATHS_100K: Deaths per 100,000 population
- DALY: Disability-Adjusted Life Year
- DALY_RATE: DALY rate
- DALY_100K: DALY per 100,000 population
  
Të Drejtat e Autorit:

© Të drejtat e autorit të datasetit : Organizata Botërore e Shëndetësisë (WHO), 2021. Të gjitha të drejtat e rezervuara.

## Objektivi
Identifikimi i Faktorëve Kyç: Për të përcaktuar kontribuesit kryesorë në DALY dhe vdekje në mbarë botën.
Parashikimi i Ndodhive të Ardhshme: Për të përdorur të dhënat historike për të parashikuar tendencat e ardhshme në DALY dhe vdekje.
Zbutja e Ndikimit: Për të sugjeruar strategji të veprueshme për përmirësimet në kujdesin shëndetësor dhe politikat e shëndetit publik.
Rritja e Ndjegjësimit: Për të rritur njohuritë dhe vëmendjen publike ndaj çështjeve të rëndësishme të shëndetit.

## Përmbajtja e Repozitorit
WHOData.csv: Skedari i të dhënave që përmban informacionin mbi DALY dhe vdekjet.
main.ipynb: Shënime Jupyter me të gjithë kodin e përpunimit të të dhënave, analizës, zbulimit të anomalive, dhe vizualizimeve.

## Metodologjia
- Leximi i të Dhënave: Lexon datasetin përmes Pandas.
- Përpunimi: Përfshin kontrollin për vlera që mungojnë, riemërimin e kolonave dhe integrimin e të dhënave.
- Pastrimi i të Dhënave: Standardizon vlerat e kolonave, heq regjistrimet e dyfishta dhe menaxhon outliers.
- Binarizimi: Binarizon një kolonë bazuar në vlerën mesatare të saj.
- Zgjedhja e Nënëngrupeve: Verifikon unicitetin e asocimeve midis kolonave të caktuara.
- Paraqitja e të Dhënave: Krahasimi i dataseteve fillestare dhe të përpunuara.
- Zbulimi dhe Pastrimi i Outliers: Vizualizon dhe pastron të dhënat nga outliers.
- Zbulimi i Anomalive: Kontrollon dhe heq anomali në kolona të ndryshme.
- Parandalimi i Zbulimeve të Pasakta: Kryen analiza për të shmangur interpretimet e gabuara.
- Analiza Eksploruese e të Dhënave: Ofron statistika përshkruese dhe vizualizime.

## Përdorimi:
Vendosja e Mjedisit: Sigurohuni që të gjitha bibliotekat dhe varësitë e nevojshme janë të instaluar.
Ekzekutimi i Shënimeve: Ekzekutoni main.ipynb për të kryer hapat e përpunimit të të dhënave, analizës dhe vizualizimit.
Eksplorimi i Të Dhënave: Eksploroni WHOData.csv për njohuri shtesë dhe kuptim më të thellë.

## Kërkesat

Lista e librarive dhe varësive të nevojshme për të ekzekutuar projektin:
* NumPy (np):
NumPy është një librari themelore për llogaritje shkencore në Python. Ajo ofron mbështetje për array të mëdha,
multidimensionale dhe një koleksion të gjerë të funksioneve matematikore për të punuar me këto array.

* Scikit-learn (StandardScaler, LabelEncoder):
Scikit-learn është një librari e fuqishme dhe fleksibël në Python për mësimin e makinës.
LabelEncoder: Përdoret për të koduar etiketat e kategorive në vlera numerike, 
e cila është një parakusht i zakonshëm në procesin e mësimit të makinës për të përpunuar të dhëna kategorike.

* SciPy (stats):
SciPy është një librari që përdoret për llogaritje shkencore dhe matematike. Ajo ofron module të ndryshme për optimizim,
algjebra lineare, integrime etj.
Stats: Nënmoduli stats ofron një numër të madh të funksioneve dhe shpërndarjeve statistikore të përdorura për të kryer analiza statistikore dhe teste të ndryshme.

* Seaborn (sns):
Seaborn është një librari për vizualizimin e të dhënave statistikore në Python. Ajo ndërton mbi Matplotlib 
dhe ofron një ndërfaqe të nivelit të lartë për të krijuar grafika tërheqëse dhe informative statistikore.

* Matplotlib (plt):
Përshkrim: Matplotlib është libraria më e njohur për vizualizimin e të dhënave në Python.
Ajo ofron kontroll të plotë mbi elementet e grafikës dhe është shumë fleksibël. 

## Autorët
Rina Shabani dhe Albiona Vukaj
