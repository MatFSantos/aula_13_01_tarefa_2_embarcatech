# Instruções de uso

Para uso do software, siga os seguintes passos:

- **1°:** clone o repositório para o seu computador.

    - Ao abrir o projeto, a extensão do CMake irá criar a pasta build para você com os arquivos de compilação.

    - Caso não seja gerada a pasta, crie uma pasta com nome `build` e execute o seguinte comando dentro da pasta criada:
        ``cmake ..``

    O comando acima irá criar os arquivos de compilação.

- **2°:** execute a compilação do firmware usando a extensão do ***Raspberry Pi Pico*** do ***VSCode***.

- **3°:** copie o arquivo `.uf2` que foi gerado na pasta `build` para o seu ***Raspberry***.

  - Após isso, o seu código já vai está rodando na sua plaquinha ***BitDogLab***.
  
- **4°:** configure o ***Putty*** para fazer a configuração de comunicação.

![configurando Putty](/image/putty.png)

> OBS: coloque a porta **COM** onde seu ***Raspberry*** está executando.

- **5°:** clique em `open` para executar o terminal. O terminal abrirá.

![configurando Putty](/image/terminal.png)

- **6°:** Está pronto, dê os comandos para executar as funcionalidades, digitando com o teclado e apertando enter. 
## Comandos disponíveis

  - `red`: acende o LED vermelho;
  - `blue`: acende o LED azul;
  - `green`: acende o LED verde;
  - `white`: acende o LED branco (todos os leds);
  - `buzzer`: toca o buzzer por 2 segundos;
  - `offled`: desliga os LEDs.

## Video Ensaio

Clique em ***[video ensáio](https://drive.google.com/file/d/17ePioUmqai4G04fg9g9GIghn4U3ZCCYB/view?usp=sharing)*** para visualizar o vídeo ensaio do projeto.