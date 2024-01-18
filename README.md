Gustavinhogotchi v1
Minha build Pwnagotchi com o espírito Brasileiro da gambiarra -> https://pwnagotchi.ai/

## Sobre
>"Pwnagotchi é uma “IA” baseada em A2C, alimentada por Bettercap e executada em um Raspberry Pi Zero W que aprende com o ambiente WiFi para maximizar o material de chave WPA quebrável que captura (seja por meio de detecção passiva ou realizando ataques de desautenticação e associação ). Este material é coletado em disco como arquivos PCAP contendo qualquer forma de handshake suportado por hashcat, incluindo handshakes WPA completos e meio, bem como PMKIDs."

## Meu Hardware
- Raspberry Pi Zero 2 W
	![WhatsApp Image 2024-01-18 at 13 28 21 (1)](https://github.com/gomesgustavoo/Gustavinhogotchi/assets/126426037/2216d9c1-8a5e-446a-bcb6-a45f719b3c55)
- Display E-ink WeAct Studio 250x122
	![WhatsApp Image 2024-01-18 at 13 28 20 (1)](https://github.com/gomesgustavoo/Gustavinhogotchi/assets/126426037/b7336b82-dda0-4d26-bd4d-3e15d97f7f9a)
	![WhatsApp Image 2024-01-18 at 13 28 20](https://github.com/gomesgustavoo/Gustavinhogotchi/assets/126426037/a4a2cca1-0786-45b9-87cc-35320b9b4667)
- Sd Card Kodak Genérico
	![WhatsApp Image 2024-01-18 at 13 28 21](https://github.com/gomesgustavoo/Gustavinhogotchi/assets/126426037/007a2cb2-57f8-4d1a-a967-2c5f8d6ae6a6)
 
	

## Problemas:
**Cada coisa que eu consigo fazer eu descubro 3 que dão errado**

- O PI02W possui um led de atividade que indica que o boot da imagem do sistema deu certo, eu comprei o meu com o objetivo de fazer o pwnagotchi porem não está bootando nem a imagem do sistema oficial.
	- Pesquisando eu descobri que tem grandes chances de que o cartão não está sendo reconhecido pela placa mas meu leitor de cartão reconhece, no site oficial eles recomendam um cartão com velocidades acima do meu.
- Outro problema futuro vai ser a integração do display, não tenho o oficial WaveShare v2 ou v3 estou usando um genérico com os mesmos pinos de saída mas já estou sentindo toneladas de problemas com os drivers
	- A solução para isso seria usar o webui e usar o celular de display, consigo imaginar isso funcionando bem
