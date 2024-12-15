# Harjoitustyö
*[Harjoitustyö](https://eriikakl.github.io/pwk-harjoitustyo/)*

Elokuvasovellus, jossa voidaan hakea hahmon perusteella elokuvia ja lisätä niitä omaan profiiliin. Tiedot tallentuvat Firebasen Firestoreen ja käyttäjä voi profiilistaan poistaa ylimääräiset elokuvat.
Sovellus on toteutettu Reactilla ja Vite-kehyksellä TypeScriptiä käyttäen. Rest API:na toimii DisneyAPI.

## Latautumisaika
Testasin etusivun latautumisaikaa, sillä siinä on eniten elementtejä.
Testin mukaan kaikki muut osoittautuivat onnistuneeksi paitsi Cumulative Layout Shift, joka on heikompi sen takia, että etusivun kuvat ovat vaihtuvia. 
![Näyttökuva 2024-12-14 225315](https://github.com/user-attachments/assets/d7580ed8-0ca6-4765-baaf-bf6900f384e1)
![Näyttökuva 2024-12-14 225327](https://github.com/user-attachments/assets/3874b267-b1ea-49ad-97fd-6ae4a588db7f)
![Näyttökuva 2024-12-14 2253151](https://github.com/user-attachments/assets/049eb3b5-9665-4d72-8174-38b8005307d4)


## Responsiivisuus
Responsiivisuutta testattu sivustolla *[Am I Responsive?](https://ui.dev/amiresponsive)* sekä Chromen ikkunassa.

Responsiivisuus kaikkiin kokoihin ihan näppärästi paitsi mobiiliin. Syynä kuvien pakotettu koko. Navigaatio muuttuu kuitenkin tabletti- ja mobiilikoossa. 

## Toimivuus selaimilla
Toimivuus testattu Chromen ja Microsoft Edgen selaimilla. Todettu toimivaksi.
