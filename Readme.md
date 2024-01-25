# Simulando uma ligação para o Call Center da Quantum Finance, um projeto de FinTech da FIAP

## Assista a simualação abaixo

[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/3scUDgL8Rjw/0.jpg)](https://youtu.be/3scUDgL8Rjw)


> Utilizado python 3.11.3 no desenvolvimento.

Para a simulação da automatização do telemarketing da Quantum Finance, foi desenvolvido um script que gera os audios que a automação deve usar em todas as situações mapeadas. Para isso usamos a biblioteca gTTS.

Com os audios geradas, convertemos-os para WAV, para que em seguida fossem usados em uma simulação de ligação. 

Construímos então um algoritmo que executa esses audios, e com base na resposta que recebe no cliente, toma uma decisão de resposta, executando o audio esperado.