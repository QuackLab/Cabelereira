## Briefing Case #1 

Olá, amiga Manu!
<br>
Fechei um projeto com uma cliente de uma Landing Page simples. O nome dela é Lúcia Valentim, ela tem um salão de beleza chamado Lu Valentim Studio. Ela nos encomendou um site estático, não responsivo e insistiu para que as cores do site fossem harmônicas. Se não estiver inspirada, pode dar uma olhada no https://coolors.co/palettes/trending .
<br>
- Ela quer que tenha um campo para enviar uma mensagem, tipo um formulário. 
<br>
- Quer também um botão que quando clicado leve ao WhatApp. 
- Ela nos enviou uma pasta de fotos que está aqui anexada no projeto. Disse que não é necessário usar todas, é só pra nos ajudar.
- Falou que nessa pasta há uma logo antiga que gostaria de mudar mas que, por enquanto,  pretende utilizar (ela não espera que a gente também faça papel de design, né?!).

As informações que ela me passou foi que o salão foi aberto por sua mãe, Clara, em 1999 e foi passado de mãe para filha. Ela, a Lúcia, está à frente do salão desde 2008. O salão é especializado em beleza e saúde dos cabelos femininos, design de sobrancelhas e design de unhas. Ela também faz maquiagem e cabelo para festas.

- Os valores são passados pelo WhatsApp ou pedindo orçamento pelo formulário. 
- Até o final do ano, está tendo uma promoção de dois combos:
 -  - Combo 1 - Mechas Loiro (Mechas, Corte, Ozonoterapia e Finalização) por R$ 450,00.
 -  - Combo 2 - Mechas Morena Iluminada (Mechas, Corte, Ozonoterapia e Finalização) por R$ 380,00.

Aqui está o endereço do salão:
- Av. Min. Guilhermino de Oliveira, 340 - Santa Amelia, Belo Horizonte - MG, CEP 31560-100
- Telefone: (31) 2515-7549
- WhatsApp: (31) 98708-3400

No local há estacionamento próprio com acessibilidade, tem banheiro e wi-fi gratúito.
Os pagamento podem ser feitos em cartões de débito e crédito, Pix e dinheiro.

------------
## Uteis:
- Caso queira: https://looka.com/
  
- Para adicionar o 'botão' do whatsApp:
  ```html
  <a href="https://wa.me/numeroDoTelefone" target="_blank">
    <button>WhatsApp</button>
  </a>

  <!-- Exemplo: https://wa.me/5581991234567-->
  ```

<br>

  ----------

  # ATENÇÃO!!

  ## Para clonar o projeto:
  <br>
  Aqui em cima do repositório, clica em 'Code'. Depois clica em HTTPS e copia o código:
  <br>
  <img src="https://i.ibb.co/cCsGBsW/Captura-de-tela-de-2023-11-14-08-36-16.png">
  <br>
  Abra o VSCode em uma pasta de sua escolha, abra o terminal (CTRL + J) e clone o projeto:
  
  ```shell
  git clone <código copiado do repositório>
  ```

  No terminal, entre dentro da pasta que você clonou:
  ```shell
  cd Cabelereira
  ```

 A partir daqui, faça tudo como você fez nos outros repositórios:
 - Cria um repositório novo no seu perfil.
 - Copia o código do repositório.
  <br>

Entenda que agora o 'origin' está apontando para o repositório que você clonou. Por isso, você terá de dar outro nome ao seu remote. Digite:

  ```
    git remote add github <código que você copiou do seu repositório criado>

    // Depois digite:

    git remote

    // Veja que haverá dois remotes, o origin e o github.
  ```

  <br>

  Se você der o push no 'origin', irá para o repositório clonado. Se der o push no 'github', irá para o repositório que você criou no seu perfil.

  Então, quando você der um push, digite:
  ```
    git push -u github master
  ```

### Sei que pode parecer que estamos complicando algo que era mais simples mas você terá que aprender esse fluxo, e alguns outros, para quando for trabalhar com repositórios compartilhados.
