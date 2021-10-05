# FullCycleCourse - Desafio Docker Go

##Descrição:
>Esse desafio é muito empolgante principalmente se você nunca trabalhou com a linguagem Go!
Você terá que publicar uma imagem no docker hub. Quando executarmos:

>docker run <seu-user>/codeeducation<br><br>Temos que ter o seguinte resultado: Code.education Rocks!<br><br>Se você perceber, essa imagem apenas realiza um print da mensagem como resultado final, logo, vale a pena dar uma conferida no próprio site da Go Lang para aprender como fazer um "olá mundo".<br><br>Lembrando que a Go Lang possui imagens oficiais prontas, vale a pena consultar o Docker Hub.<br><br>3) A imagem de nosso projeto Go precisa ter menos de 2MB =)<br><br>Dica: No vídeo de introdução sobre o Docker quando falamos sobre o sistema de arquivos em camadas, apresento uma imagem "raiz", talvez seja uma boa utilizá-la.<br><br>Divirta-se

  
Dado o problema, a solução foi feita utilizando a imagem raiz do docker "scratch" e buildando o código docker localmente e passando para a imagem o executável
