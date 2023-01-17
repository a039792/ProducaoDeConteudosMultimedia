# PRODUÇÃO DE CONTEÚDOS MULTIMÉDIA - TIWM - 2ºANO
No decorrer do período da aula será utilizado a plataforma photoshop (https://www.adobe.com/pt/products/photoshop.html) para a exploração de diferentes tipos de medias. O principal objetivo do caderno em desenvolvimento é anotar os apontamentos mais importantes assim como os trabalhos feitos durante o período de avaliação.
_____________________________________________________________________________________________________________________________________________________________
# O que é a multimédia?
A multimédia compreende basicamente o uso de media estáticos (texto, gráficos e imagens) e o uso de media dinâmico (vídeo, audio ou animações). Para unir e manipular esses dois tipos de media é necessário um dispositivo móvel ou um computador que conta com algum programa de edição, por exemplo o Photoshop. Como exemplo da multimédia temos: televisão, revistas, gravador de vídeo, internet, entre outras. 
Qualquer tipo de média é codificado de uma forma única, ou seja todos os tipos de caracteres, letras números são traduzidos numa sequência de 0 e 1, assim entramos na- Representação digital da informação. 

## Representação digital da informação
Os computadores lidam com as informações codificadas sob a forma de uma sucessão de dígitos binários ou bits, que assumen apenas um dos dois valores 0 e 1.
Existem outros sistemas de numeração além do sistema binário (escolhido para a codificação da informação utilizado internamente pelo computador por ser simples) como sistema octal e o hexadecimal. Tem como maior vantagem a universidade da representação e como maior desvantagem a distorção na informação.

Para se obter uma representação digital da informação associada aos media, é necessário proceder à sua digitalização que é definido como um processo de transformação de um sinal análogico (valor físico que varia continuamente com o tempo e o espaço) num sinal digital (sequência de valores codificados em formato binário dependente do tempo e do espaço, resultante de uma transformação de um sinal analógico.  

## Interatividade
-> É a forma de coomunicação entre o ser humano e o computador. Para um sistema ser interativo deve suportar a comunicação em ambas as direções, é subentendida como ação e reação. É caracterizado pelo tipo de suporte que a sua interface fornece à actividade do utilizador.

# Tipos de media estático
## O texto
O texto possui uma natureza dupla:
  - Representação visual da linguagem;
  - Elemento gráfico

A representação do texto pode ter 3 formas possíveis:
  - Texto não formatado (plain text);
  - Texto formatado (rich text);
  - Hipertexto;


Para que se possa representar o texto no formato digital é necessário definir um mapeamento entre os caracteres abstratos de um lado alfabeto e os valores que podem ser armazenados no computador. 

O primeiro conjunto de caracter a ser normalizado foi o ASCII que continuou sendo a norma dominante, este utiliza 7 bits para representar cada código, sendo assim representa 128 caracteres diferentes: 

<img width="340" alt="7bits" src="https://user-images.githubusercontent.com/114168701/202014985-81ec7e08-9b9a-42cb-a96f-fb92bcab8c5f.PNG">

Tendo em conta os outros idiomas o ASCII foi ampliado o reportório de caracteres suportadas por um conjunto de caracteres com 8 bits resultando num total de 256 caracteres, como mostra a figura:

<img width="316" alt="8bits" src="https://user-images.githubusercontent.com/114168701/202018205-7f9a067e-3266-40a4-997d-438cf096566a.PNG">

## A imagem
As imagens bitmaps não são conteúdos corrigíveis porque o modo como se representam (matrizes de pixeis) não contém informação estrutural, a representação bitmap não descreve a imagem em termos de cor e brilho dos vários pixeis que constituem a imagem. A imagem pode ser resultado de um processo de captura do mundo real ou podem ser geradas por computador.

### Representação
Cada pixel da imagem possui um valor numérico, chamado de amplitude, que representa a sua cor;

### Resolução
Sabendo as dimensões em pixeis de uma imagem, sabe-se imediatamente "quanto" detalhe está contido na imagem.

### Compressão e formatos 
Podem ser de duas naturezas:
  - Compressão sem perdas -> a compressão seguida pela descompressão preserva os dados da imagem, exemplos:
    - .BMP;
    - .TIFF;
    - .DNG;
    - .PNG;
    - .ZIP;
  - Compressão com perdas -> a compressão seguida de descompressão conduz à perda de alguma informação da imagem (pode ou não ser aparente ao sistema visual humano) 
    - .GIF;
    - .JPEG;
_____________________________________________________________________________________________________________________________________________________________

## Introdução ao estudo do vídeo
### O que é vídeo?
-> Vídeo é um sistema de combinações de imagens, no qual este pode ser acompanhado de som. 
Existem dois grandes tipos de compreensão: 
  - Intraframe ou espacial;
  - Interframe ou temporal.
   
#### Intraframe ou espacial 
Cada fotograma é comprimido independentemente.
Assim como na imagem há compreensão com e sem perda. Ele possui o seguinte conjunto de formato: 

    - DVD Pro; 
    - Apple Prores; 
    - AVC-Intra; 
    - Digital Betacam. 
    
Nesse tipo de compreensão é ajustado de forma que cada fotograma ocupa 125k.

#### Interframe (Temporal) 
É o tipo em que o algoritmo escolhe um grupo de imagem e a primeira é compremida inteira, e os outros é observados nos difernças de pixeis e só a parte em diferenças é que muda. Este tipo de compreensão é muito recomendado porque só são gravado as diferenças.
Codecs Interframe:

     - MPeg video;
     - MPeg2 video (verefica a mudança de posições dos pixeis);
     - Div X ou MPeg4;
     - Windows Media video;
     - Theora;
     - H.264 (Normas de videoconferência em tempo real)

#### O que é bitrate de vídeo?
Bitrate refere a quantidade de dados que é tranferido. Ele é medido por Bits por segundos (bts/s)
O bitrate pode ser: 
  - Constante; 
  - Variável.

# Prática

Assim como em todos os casos de estudos, a prática faz uma grande diferença na aprendizagem dos alunos, então essa segunda parte vai focar em alguns pontos práticos no desenvolvimento de exercícios/trabalho prático que foi solicitado pelo Docente. 

O primeiro projeto baseou no desenvolvimento de um cartaz com o objetivo de promover um evento sobre qualquer tema escolhido pelo aluno. Importante realçar que para o desenvolvimento desse trabalho há um conjunto de regras a serem compridos como por exemplo em relação a dimensão e ao formato. Para o segundo projeto o objetivo é criar um vídeo de aproximadamente 3 minuto, considerando a regra de 30 graus e a regra de 180. 



