# 📈 OMX Baltic 10 Portfelio Skaičiuoklė

Ši programėlė skirta **atkartoti OMX Baltic 10 indekso sudėtį**. Įrankis leidžia paskirstyti lėšas tarp 10 didžiausių Baltijos šalių biržos bendrovių, atsižvelgiant į jų rinkos svorius.

Programėlėje įdiegta galimybė rinktis tarp dviejų skaičiavimo metodologijų:
* **Free Float (Oficiali indekso metodika):** Apskaičiuoja svorius atsižvelgiant tik į tas akcijas, kurios yra laisvai prieinamos prekybai. Būtent šią metodiką naudoja oficialus OMX Baltic 10 indeksas, todėl ji geriausiai atspindi realią rinkos situaciją.
* **Full Market Cap (Pilna kapitalizacija):** Apskaičiuoja svorius pagal visą išleistų akcijų rinkos vertę, įskaitant ir tas, kurios nėra laisvai prekiaujamos (pvz., valstybinį kapitalą ar kontrolinius akcininkų paketus).

## ✨ Pagrindinės funkcijos

* **Dvi skaičiavimo metodologijos:** Galimybė skaičiuoti svorius pagal laisvų akcijų kiekį (*Free Float*) arba pagal pilną rinkos kapitalizaciją.
* **Automatinis 15% limitas:** Sistema automatiškai riboja vienos įmonės svorį iki 15%, kaip tai daroma realiame indekse, o „perteklių“ proporcingai padalina kitoms įmonėms.
* **Interaktyvus redagavimas:** Spustelėję bet kurią eilutę, galite pakeisti įmonės pavadinimą, bendrą akcijų kiekį ar laisvų akcijų skaičių.
* **Tiesioginis kainų atnaujinimas:** Įveskite naują kainą tiesiog lentelėje ir matykite, kaip keičiasi pirkimo planai.
* **Duomenų išsaugojimas:** Visi jūsų atlikti pakeitimai automatiškai išsaugomi jūsų naršyklėje (`localStorage`), tad grįžę rasite savo paskutinius duomenis.
* **Reset funkcija:** Vieno mygtuko paspaudimu galite atstatyti pradines oficialias reikšmes.

## 🛠️ Kaip naudotis?

1.  **Investuojama suma:** Viršutiniame laukelyje įveskite bendrą sumą, kurią planuojate investuoti (pvz., 10 000 €).
2.  **Kainų korekcija:** Jei biržoje kainos pasikeitė, įrašykite jas stulpelyje „Kaina (€)“.
3.  **Metodo pasirinkimas:** Perjunkite tarp „Free Float“ ir „Pilna Kap.“ mygtukų, kad pamatytumėte skirtingus svorių scenarijus.
4.  **Pirkimo kiekiai:** Stulpelyje „Kiekis“ matysite tikslų akcijų skaičių (vnt.), kurį turėtumėte įsigyti, kad išlaikytumėte svorius.
5.  **Likutis:** Apačioje matysite „Grynuosius“ – tai suma, kuri lieka nesuapvalinus akcijų vienetų (likutis po pirkimo).

## ⚠️ Atsakomybės apribojimas

**SVARBU:** Ši programėlė yra tik pagalbinio, informacinio pobūdžio įrankis. 

* **Autorius neprisiima jokios atsakomybės** už bet kokius finansinius nuostolius, tiesioginę ar netiesioginę žalą, patirtą naudojantis šia skaičiuokle. 
* Pateikiami duomenys (kainos, akcijų kiekiai) gali būti netikslūs, pasenę arba skirtis nuo oficialių biržos duomenų.
* Investavimo sprendimus kiekvienas vartotojas priima savarankiškai. Prieš atliekant bet kokius sandorius, privalote patikrinti informaciją oficialiuose šaltiniuose (pvz., *Nasdaq Baltic*).
* Šis įrankis nėra investavimo rekomendacija ar finansinė konsultacija.
