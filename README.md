# Instruções de uso

Para uso do software, siga os seguintes passos:

- **1°:** clone o repositório para o seu computador.

- **2°:** crie uma pasta com nome `build` e execute o seguinte comando dentro da pasta criada:
    ```
        cmake ..
    ```
    O comando acima irá criar os arquivos de compilação.

- **3°:** execute a compilação do firmware usando a extensão do ***Raspberry Pi Pico*** do ***VSCode***.

- **4°:** copie o arquivo `.uf2` presente na pasta `build` para o seu ***Raspberry***.

  - Após isso, o seu código já vai está rodando na sua plaquinha ***BitDogLab***.
  
- **5°:** configure o ***Putty*** para fazer a configuração de comunicação.

![configurando Putty](/image/putty.png)

> OBS: coloque a porta **COM** onde seu ***Raspberry*** está executando.

- **6°:** clique em `open` para executar o terminal. O terminal abrirá.

![configurando Putty](/image/terminal.png)

- **7°:** Está pronto, dê os comandos para executar as funcionalidades, digitando com o teclado e apertando enter. Os comandos disponíveis são:
  - `red`: acende o LED vermelho;
  - `blue`: acende o LED azul;
  - `green`: acende o LED verde;
  - `white`: acende o LED branco (todos os leds);
  - `buzzer`: toca o buzzer por 2 segundos;
  - `offled`: desliga os LEDs.

