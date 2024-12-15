# Harjoitustyö

Elokuvasovellus, jossa voidaan hakea hahmon perusteella elokuvia ja lisätä niitä omaan profiiliin. Tiedot tallentuvat Firebasen Firestoreen ja käyttäjä voi profiilistaan poistaa ylimääräiset elokuvat.
Sovellus on toteutettu Reactilla ja Vite-kehyksellä TypeScriptiä käyttäen. Rest API:na toimii DisneyAPI.

*[Harjoitustyö](https://eriikakl.github.io/pwk-harjoitustyo/)*

## Sivuston testaus
Testasin sivuston toimivuutta eri kokoisilla näytöillä, erilaisilla selaimilla sekä sivun latautumisaikaa. Tulokset olivat hyvät, hieman oli huomautettavia asioita muun muassa virhe, joka tulee kun hakee hahmoja sivulle.

### Latautumisaika
Testasin etusivun latautumisaikaa, sillä siinä on eniten elementtejä.
Testin mukaan kaikki muut osoittautuivat onnistuneeksi paitsi Cumulative Layout Shift, joka on heikompi sen takia, että etusivun kuvien koko on vaihtuva. 
![Näyttökuva 2024-12-14 225315](https://github.com/user-attachments/assets/d7580ed8-0ca6-4765-baaf-bf6900f384e1)
![Näyttökuva 2024-12-14 225327](https://github.com/user-attachments/assets/3874b267-b1ea-49ad-97fd-6ae4a588db7f)
![Näyttökuva 2024-12-14 2253151](https://github.com/user-attachments/assets/049eb3b5-9665-4d72-8174-38b8005307d4)


### Responsiivisuus
Responsiivisuutta testattu sivustolla *[Am I Responsive?](https://ui.dev/amiresponsive)* 

Responsiivisuus kaikkiin kokoihin ihan näppärästi paitsi mobiiliin. Navigaatio muuttuu kuitenkin tabletti- ja mobiilikoossa. 
![Näyttökuva 2024-12-15 143337](https://github.com/user-attachments/assets/375a362b-a684-42f1-84bb-8488fcc80ad1)

Responsiivisuutta on testattu myös Chromen ikkunassa ja se toimii kuten pitääkin. Vasemmalla mobiili, oikealla tabletti.

![Näyttökuva 2024-12-15 143519](https://github.com/user-attachments/assets/d2967772-d8fb-47ed-8f36-422a6bcb3a3d)
![Näyttökuva 2024-12-15 143533](https://github.com/user-attachments/assets/4a695a84-d811-4518-a574-130f4caa577c)




### Toimivuus selaimilla
Toimivuus testattu Chromen ja Microsoft Edgen selaimilla. Todettu toimivaksi.
