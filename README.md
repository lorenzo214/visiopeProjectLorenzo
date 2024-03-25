In questo progetto ho cercato di realizzare una conditional GAN (arxiv.org/abs/1411.1784) capace di prendere immagini di esseri umani e trasformarli in anime.
Come architettura della GAN ho utilizzato una DCGAN (https://arxiv.org/abs/1511.06434) dotata di un primo strato di fully connected net e di vari strati convolutivi.
Per allenare l'encoder e il discriminatore ho seguito questo paper:https://arxiv.org/abs/1611.06355.

Sia la GAN che l'encoder sono stati addestrati per 25 epoche (più o meno) e nel notebook sono presenti due paremetri per rete scelti tra i 25 che trovavo migliori.

Nella sezione test del notebook è possibile generare immagini come una normale GAN e trasformare immagini vere in anime e viceversa, ci sono degli esempi.
Nel encoder le immagini vanno sempre fornite in gruppo.
Per utilizzare il notebook suggerisco di usare kaggle dato che alcune funzioni potrebbero non funzionare correttamente in altri notebook come ad esempio colab.

Di seguito tre immagini di esempio 

Immagine 1 Reale

![Schermata del 2024-03-25 13-03-23](https://github.com/lorenzo214/lorenzoVisiopeProject/assets/82397140/a0ba63d5-9901-46f1-9ba2-bd328ff5a6ea)

Immagine 1 Ricostruita

![Schermata del 2024-03-25 13-03-31](https://github.com/lorenzo214/lorenzoVisiopeProject/assets/82397140/0ce81612-bd8a-40c2-a5b1-7d3b80720e00)

Immagine 1 Trasformata in Anime

![Schermata del 2024-03-25 13-03-48](https://github.com/lorenzo214/lorenzoVisiopeProject/assets/82397140/6b170fa2-d281-46c0-92e5-86d6a6e9c04f)

Immagine 2 Reale

![Schermata del 2024-03-25 13-06-56](https://github.com/lorenzo214/lorenzoVisiopeProject/assets/82397140/fe4795b2-b335-461f-a3ed-7e93481022a1)

Immagine 2 Ricostruita

![Schermata del 2024-03-25 13-06-46](https://github.com/lorenzo214/lorenzoVisiopeProject/assets/82397140/4a7d01cf-8604-489b-9eca-de2dd3b6069f)

Immagine 2 Trasformata in Anime

![Schermata del 2024-03-25 13-07-10](https://github.com/lorenzo214/lorenzoVisiopeProject/assets/82397140/764a1a30-927f-4885-b275-41db8c9f6242)

Immagine 3 Reale

![Schermata del 2024-03-25 13-08-07](https://github.com/lorenzo214/lorenzoVisiopeProject/assets/82397140/a9f111a9-80e7-4779-a5b5-ab6fa08ead56)

Immagine 3 Ricostruita

![Schermata del 2024-03-25 13-07-46](https://github.com/lorenzo214/lorenzoVisiopeProject/assets/82397140/53ecc244-5583-4dbd-a5f8-496f9f0584e1)

Immagine 3 Trasformata in Anime

![Schermata del 2024-03-25 13-07-57](https://github.com/lorenzo214/lorenzoVisiopeProject/assets/82397140/ed085aad-ac6b-4462-bd28-bc74a41f2304)
