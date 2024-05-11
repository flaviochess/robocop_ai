# Robocop AI
![alt text](image.jpg)
> Robocop em referência ao filme onde o personagem é um policial humanoide e IA pois aqui ao invés de um humanoide o "policial" é uma IA.

## O projeto
Esse é um projeto em uma versão inicial para testar alguns conceitos e a partir deste ponto podendo evoluir para um projeto mais robusto.

O Robocop AI utiliza a inteligência artificial (AI) generativa do Google, a Gemini, para analisar vídeos de câmeras de segurança pública instaladas nas ruas e identificar se um carro (roubado) passou por ali. A partir deste resultado é possível utilizando serviços de localização saber quais são as possíveis próximas ruas e analisando as câmeras de cada uma traçar a rota do veículo descobrindo o paradeiro atual.

> A ideia é que este projeto seja utilizado por autorizades de segurança e não para a população em geral por conter dados pessoais como carro, placas e até mesmo a imagem dos motoristas, além de evitar que o seu uso ser deturpado, como localizar uma pessoa sem o consentimento desta.

Esta primeira versão conta com vídeos grátis de ruas de bancos de imagens (vídeos) simulando uma gravação real de uma rua.
Os vídeos usados são os seguintes:
- [vídeo 1](http://www.onsave.com.br/cdn/streets/1/video.mp4)
- [vídeo 2](http://www.onsave.com.br/cdn/streets/4/video.mp4)
- [vídeo 3](http://www.onsave.com.br/cdn/streets/9/video.mp4)

Além disso, como um projeto piloto, ainda não está integrado com um serviço de geolocalização, como o Google Maps. Ao invés disso existe um grafo simulando as ruas de uma pequena cidade:

![alt text](image.jpg)

## Uso
Esse protótipo utiliza Jupter Notebook do Python, onde você pode executar a partir da sua máquina ou através do Colab do Google em: 

