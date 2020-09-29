# Primeiros Passos

Nesta seção, você encontrará um guia geral para se ambientar na plataforma, seja no painel ou no aplicativo.
De forma geral, a gestão se dá a partir de uma boa organização do painel e um entendimento de como configura-lo.
O painel de gestão se comunica diretamente com o aplicativo, ou seja, o roteiro do colaborador, as pesquisas cadastradas,
o endereço do Ponto de Venda, tem que ser cadastrados de forma correta. Por isso devemos entender o funcionamento geral
da ferramenta.

### 1. Cadastro do Colaborador  
![Screenshot](assets/primeiros-passos/cadastro-colaborador.gif)

Para cadastro de um novo colaborador entre em **Gerenciamento > Colaborador** . Clique em Novo Colaborador
e preencha os campos de cadastro.

* `Nome` - O nome do colaborador. <span style="color:red">*</span>
* `CPF` - O CPF do colaborador. 
* `E-mail` - Email do colaborador. <span style="color:red">*</span>
* `Telefone` - Telefone do colaborador, DD + Número.
* `Username` - Username é o nome de usuário que dá acesso ao App do colaborador. <span style="color:red">*</span>
* `Password` - É a senha de acesso ao App do colaborador. <span style="color:red">*</span>

***Obs.:** os campos com* <span style="color:red">*</span> *são campos de preenchimento obrigatório.*

<br>

#### 1.1 Controle de Expediente
O controle de expediente pode ser utilizado para bloquear o aplicativo quando o colaborador estiver fora dos horários estabelecidos.  

#### 1.2 Tipo de Monitoramento do Celular
Para configurar o tipo de rastreamento do posicionamento por GPS do promotor. 

* `Padrão` - Os dados de posicionamento serão gravados apenas no momento do check-in e check-out.
* `Fulltime` - O colaborador será rastreado dentro e fora do ponto. A posição é atualizada a cada 5 minutos.

### 2. Cadastro de PDV

![Screenshot](assets/primeiros-passos/cadastro-pdv.gif)

O cadastro de PDV é feito através de **Gerenciamento > PDV > Adicionar Novo PDV**. Quanto mais completo o cadastro mais preciso será o ponto no mapa. Em casos de pontos sem número, recomenda-se utilizar a Latitude e a Logitude. Todos os campos do cadastro de PDVs são campos de facil entendimento por isso nesta parte falaremos sobre os campos que podem gerar mais dúvidas e que podem auxiliar na gestão do painel, mas caso deseje uma explicação mais detalhada de todos os campos você poderá encontrar em [PDVs](gerenciamento/pdv.md#3-cadastro-de-um-novo-PDV).

* `Nome Fantasia` - Nome do PDV que será exibido para o promotor no app e que terá destaque no Tempo Real.
* `E-mail` - E-mail do PDV, caso deseje que as informações coletadas seja enviado para o PDV onde elas foram coletadas, pode-se configurar no painel que as informações serão enviadas para o e-mail neste campo.
* `Raio limite de check-in` - É a distância máxima para o colaborador realizar check-in no PDV, caso o colaborador esteja a uma distância maior que a do raio, o app irá bloquear o check-in.
* `Código do PDV` - Caso possua um sistema próprio para realizar o relacionamento dos dados, o código do pdv é um campo especial feito para que possa realizar esta tarefa, pois nele poderá colocar o código do PDV no seu sistema e então cruzar as informações utilizando este código.
* `Observações` - Observações sobre o PDV.

### 3. Criação de um Roteiro ou Carteira

O roteiro ou carteira é como os PDV's são relacionados ao colaborador. A diferença entre um roteiro e a carteira é que o roteiro tem como objetivo seguir um calendário de visitas, que podem ser configuradas em vários períodos de repetição. Já na carteira, os PDV's ficam atribuídos ao colaborador, que pode acessar e realizar suas visitas através da função "Buscar" no App.

#### 3.1 Configuração de Roteiro

![Screenshot](assets/primeiros-passos/roteiro-1.png)

Em **Gerenciamento > Roteiro** ficam dispostos os colaboradores cadastrados. Clicando no colaborador que 
terá um roteiro cadastrado leva à pagina com o calendário do mês:

![Screenshot](assets/primeiros-passos/roteiro-2.png)
<br>
<br>
Em **adicionar visita ao roteiro**, a visita pode ser cadastrada:
 

![Screenshot](assets/primeiros-passos/roteiro-3.png)

Selecione um PDV e configure o período.

##### 3.1.1 Períodos de repetição da visita

* `Visita Única` - Será uma visita ao PDV que só será feita em um dia.
* `Diária` - Esta visita se repetirá todos os dias da semana durante um período selecionado. Podem ser adicionados sábados e domingos.
* `Semanal` - É um roteiro que se repete baseado nos dias da semana dentro de um período.
* `A cada 10 dias` - Repete-se a loja a cada 10 dias.
* `A cada 2 semanas` - A cada duas semanas, esse roteiro se repete. Por exemplo: Ao selecionar uma segunda-feira num mês, em 15 dias (Próxima segunda-feira em duas semanas) a visita será disponibilizada ao colaborador.
* `A cada 3 semanas` - A cada três semanas, esse roteiro se repete. Por exemplo: Ao selecionar uma segunda-feira num mês, em 22 dias (Próxima segunda-feira em três semanas) a visita será disponibilizada ao colaborador.  
* `Mensal` - Todo mês, a visita vai se repetir no dia especificado.
* `Bimestral` - A cada dois meses, a visita vai se repetir no dia especificado.
* `Trimestral` - A cada três meses, a visita vai se repetir no dia especificado.
* `Semestral` - A cada seis meses, a visita vai se repetir no dia especificado.      
* `Anual` - A visita será realizada por ano.

##### 3.1.2 Exemplo de um Roteiro

O colaborador fará uma visitação semanal todas as segundas, quartas, sextas e sábados em um PDV.
Para isso, vamos utilizar o tipo de visita semanal. Marcar os dias da semana e selecionar um período.


![Screenshot](assets/primeiros-passos/roteiro-semanal.gif)

#### 3.2 Registro de Carteira

A configuração de uma carteira é mais simples que a de roteiro. Em **Gerenciamento > Carteira**, são adicionados os PDV's cadastrados no painel à carteira do promotor.

![Screenshot](assets/primeiros-passos/cadastro-carteira.gif)

### 4. Pesquisa

A criação de uma pesquisa e perguntas é a parte final de uma configuração básica do painel.

![Screenshot](assets/primeiros-passos/pesquisa-1.png)

Em **Gerenciamento > Pesquisa**, todas as configurações de pesquisa estão disponíveis. Clique em **Criar Nova Pesquisa**  para adicionar uma nova pesquisa.

Insira um nome e clique em cadastrar. O código de pesquisa não é obrigatório.

![Screenshot](assets/primeiros-passos/pesquisa-2.png)

Para configuração de Grupos, siga para a página de [Grupos](gerenciamento/grupos.md)

![Screenshot](assets/primeiros-passos/pesquisa-3.png)

Com a pesquisa cadastrada, é necessário cadastrar as perguntas, para cadastrar as perguntas de uma pesquisa, basta clicar no **nome da pesquisa**, ou clicar no **ícone de perguntas**, após isso você será redirecionado, para esta página.

![Screenshot](assets/primeiros-passos/pesquisa-4.png)

Aqui, estão dispostas todas as perguntas para essa pesquisa. 

##### 4.1 Tipos de pergunta

* `Multipla Escolha` - Será apresentado ao colaborador várias opções de resposta, podendo selecionar uma delas para responder à pergunta. As opções são dadas no campo **Opções** separado por **" ;; "** (Dois ponto e vírgula).
* `Discursiva` - O colaborador insere os dados por meio do teclado. Estes dados podem ser filtrados pelo tipo de resposta.
* `Upload de Imagem` - Será aberta a camera do dispostivo, possibilitando a captura de uma imagem. Só imagens tiradas naquele instante seram aceitas, ou seja, não é possível enviar fotos da galeria.
* `Lista Dinâmica` - Uma versão da multipla escolha que suporta muito mais itens.
* `Assinatura` - Um campo onde poderá ser coletado a assinatura de uma pessoa.
* `Geolocalização` - Uma pergunta que coleta a localização atual do colaborador quando a pergunta foi respondida.
* `Múltipla Resposta` - Uma versão da múltipla escolha, onde poderá ser selecionado mais de um item de uma vez.
* `Qr code / Código de barras` - Uma pergunta com um leitor de código de barras e de Qr code.


##### Tipos de Respostas

* `Texto` - O teclado do dispositivo será aberto possibilitando a entrada de dados do tipo texto.

* `Inteiro Positivo` - Um teclado numérico será aberto para inserir números inteiros. Quantidade de estoque por exemplo, é verificada com esse tipo de resposta.

* `Decimal Positivo` - Entrada de números decimais, utilizada por exemplo para preço de um determinado produto.

##### Ordem

A ordem é o que dita quais perguntas aparecem primeiro no aplicativo.
É importante pois dá o sentido do questionário.


### 5. Utilizando o Aplicativo

Após a configuração básica do painel, o aplicativo já pode ser utilizado. Para isso,
acesse a Google Play Store clicando [aqui](https://play.google.com/store/apps/details?id=br.com.movindigital.apps.pdv_info&hl=pt_BR) ou pesquisando no aplicativo da loja
por "PDV Info".

![Screenshot](assets/primeiros-passos/pdv-info-playstore.png#center)

Ao abrir o aplicativo, será aberta a tela de login. Esse login é o criado dentro do painel, em "Colaboradores".


![Screenshot](assets/primeiros-passos/login-app.png#center)


Após entrar na conta, será apresentada a tela inicial, com o nome da ação no topo.

![Screenshot](assets/primeiros-passos/tela-inicial.png#center)

Agora, com tudo configurado e o roteiro/carteira prontos, só falta testar sua pesquisa:

![Screenshot](assets/primeiros-passos/resp-pesquisa.gif#center)

### 6. Considerações Finais

Parabéns! Você chegou ao final do guia de primeiros passos no PDV Info. Agora que está mais ambientado, pode 
partir para as funcionalidades mais detalhadas, que te oferecem um controle completo da sua equipe.

Siga para a página de dúvidas frequentes caso tenha encontrado algum problema. Lá temos as soluções 
para os problemas mais comuns e como corrigi-los.

