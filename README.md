# Abrir-porta-modem-Nokia-G-240W-C

<h1> Identificando o ip do seu modem </h1>

<p> Com o atalho WIN + R irá aparecer a janalinha do executar onde você digitará <strong>cmd</strong> e teclar enter </p>

<p> Já no CMD você digita "ipconfig" aqui você poderá ver o **IPv4** que corresponde ao endereço da sua máquina e logo abaixo o <strong>Gateway Padrão</strong>, é com ele que você acessará o Modem. </p>

<p> Com o Gateway Padrão em mãos, você vai no seu navegador e ponha ele na barra de pesquisa "Se por acaso aparece algum aviso de segurança, ignore ele e continue" </p>

<h2> Abrindo as Portas do Modem </h2>

<p> E aqui chegamos na página de login do modem **GPON Home Gateway** aqui você informa o nome de usuário(Normalmente é userAdmin)  e a senha que lhe foi dada no momento da instalação </p>

<p> Dentro do modem, navegue em </p>

1. Application
   - Port Forwarding

<p> É aqui que tudo acontece, vamos precisar do <strong>IPv4</strong> que vimos lá atrás. </p>

<p align="center">
  <img width="763" height="336" src="https://i.imgur.com/868yQw1.png">
</p>

<p> Em application Name você escolhe Custom Settings, em sequida nas quatro caixas você coloca a porta que deseja abrir, em Internal Client é onde você seleciona a sua máquina na caixa da esquerda, se caso estiver tendo dificuldades em encontrar sua máquina, selecione **Custom Settings e na caixa do lado colocar o seu IPv4**, selecione o protocolo no qual deseja e por fim **add**  </p>

<p> No exemplo eu estou abrindo a porta do Minecraft </p>

<p> Para ver se foi ativada com sucesso basta descer um pouco e terá uma lista com as portas abertas, do lado direto abaxio de "<strong>Status</strong>" mostrará "<strong>ACTIVE</strong>", indicado que a porta está aberta. </p>
