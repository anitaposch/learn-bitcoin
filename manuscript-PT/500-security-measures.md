# Armazenando Moedas com Segurança

## Medidas de segurança
Todos os bancos de dados podem ser invadidos. Pesquise seu e-mail em https://haveibeenpwned.com/ - se você tiver sorte, você não foi pwned, mas bilhões de outras contas sim. Portanto, é importante seguir as medidas gerais de segurança que se aplicam ainda mais ao usar o Bitcoin.

### Configuração de hardware e software
Você pode usar navegadores populares como Firefox, Opera, Brave ou Chrome. Extensões de navegador que bloqueiam Javascript e Cookies são recomendadas. Ghostery, NoScript e ScriptSafe são o tipo de extensão que você pode adicionar ao seu navegador. "HTTPS em todos os lugares" impõe uma conexão SSL a todos os sites, incluindo aqueles que ainda não oferecem SSL.

Esteja ciente de que algumas lojas online não funcionam corretamente com essas extensões ativadas, portanto, você deve desativá-las manualmente.

É importante que você mantenha seus dispositivos seguros.

### Atualizações
Este conselho se aplica a todos os seus dispositivos: execute todas as atualizações de software sugeridas. Para o sistema operacional do seu computador, bem como para o seu smartphone. Sempre use a versão mais recente de sua carteira e software de firmware em sua carteira de hardware.

### Endereço de e-mail
Não use um endereço de e-mail para tudo. Obtenha endereços de e-mail descartáveis ​​que você usa apenas uma vez. Você também pode comprar um domínio que você usa apenas para endereços de e-mail falsos que você encaminha para seu endereço principal.

### Senhas seguras
Use senhas seguras para todos os serviços online. Seu aniversário, local de residência, o nome do seu gato ou 1234567 não são senhas seguras. Frases inteiras com dígitos, espaços, letras maiúsculas e minúsculas e caracteres especiais são senhas fortes.

Use uma senha diferente para cada site em que você fizer login. Caso contrário, um hacker com apenas uma senha poderá entrar em todos os serviços nos quais você está registrado. Não armazene essas senhas em um arquivo do Word ou algo parecido em seu computador. Um documento do Word é fácil para os hackers roubarem e lerem.

Você pode usar software como 1Password, Bitwarden ou KeePass (gratuito e de código aberto). São bancos de dados de senhas criptografados, onde você pode gerar e armazenar todas as suas senhas e só precisa lembrar de uma senha para abri-la.

### PIN
Configure um PIN para o software da sua carteira para que ninguém possa abrir facilmente a sua carteira no seu dispositivo.

### 2FA
Use um método de autenticação de 2 fatores para proteger suas contas. Não use SMS/texto como método de autenticação de 2 fatores devido a ataques de troca de SIM. Em vez disso, instale um aplicativo autenticador como OTP ou TOTP no seu telefone.

### Troca de SIM
A troca de SIM é quando alguém sequestra seu SIM e número de telefone. Eles podem usar seu número de telefone para fazer login em todas as contas conectadas nas quais você ativou a autenticação de 2 fatores com texto/SMS. A troca de SIM é um ataque para entrar em sua conta de e-mail principal. Se os invasores puderem acessar a conta de e-mail principal associada ao 2FA ao seu número de telefone, eles poderão encontrar todas as contas de troca de Bitcoin que você está usando com o 2FA e eliminá-las.

O ataque geralmente é iniciado ligando para o atendimento ao cliente em seu provedor de telecomunicações (Verizon, Vodafone, AT & T, Magenta,...). Eles dizem algo como "Sou o proprietário do número de telefone, perdi meu telefone, por favor, transfira meu número para o meu novo SIM". A pessoa de atendimento ao cliente solicitará uma informação pessoal para verificar sua identidade. Os atacantes, então, tentarão muitos truques. Eles atormentam a pessoa de suporte para obter pequenos pedaços de informação deles, desligam e ligam para outra pessoa e usam esse fragmento de informação para avançar para o próximo nível. Eles então obtêm mais informações e continuam construindo até que tenham informações suficientes para persuadir a última pessoa de que eles são os proprietários da conta e transferir o SIM.

Eles irão atrás de todas as exchanges de criptomoedas nas quais você possa ter configurado uma conta com seu endereço de e-mail e número de telefone.

Quando eles souberem seu e-mail, eles tentarão alterar a senha da sua conta com a funcionalidade "esqueci a senha". Bons sites não informam se a conta existe. Os invasores tentarão redefinir a senha ou tentar obter uma verificação de mensagem de texto.

**O que você pode fazer - Exemplo do Gmail**

Bloqueie sua conta de e-mail principal e remova seu número de telefone de sua conta de e-mail (como uma conta do Gmail). Veja como é feito: [https://anita.link/removegmail](https://anita.link/removegmail). Use uma senha diferente para cada conta em cada site ou serviço. Como usuário do Gmail, você pode se inscrever no Programa Proteção Avançada do Google, que protege contra ataques on-line direcionados.

## Ataques de phishing
Em 2020, o banco de dados de marketing do fabricante francês de hardware Ledger foi hackeado. Os aparelhos são seguros, mas milhares de endereços de e-mail, telefones e até endereços residenciais de clientes vazaram e podem ser encontrados por qualquer pessoa na internet. Isso é um desastre absoluto porque há uma grande chance de que as pessoas que compram uma carteira de hardware também possuam bitcoin. Na pior das hipóteses, você será "visitado" em casa. O mais provável é que sejam ameaças via e-mail e ataques de phishing. Para evitar isso, lembre-se de que talvez você nunca precise usar seu endereço físico para entrega de um produto relacionado ao Bitcoin, como uma carteira de hardware. Você pode organizar uma caixa postal para si mesmo. Nos EUA existem serviços que podem receber correio para você (CMRAs). Se possível, nem use seu nome verdadeiro ao fazer o pedido. Obtenha um segundo número de telefone e use-o caso o fornecedor solicite um. Dê a eles um endereço de e-mail descartável que você usa apenas para esse pedido específico.

Os ataques de phishing são tentativas de assustá-lo ou manipulá-lo para que você insira suas palavras iniciais no site do invasor. Por exemplo, você pode receber um e-mail dizendo: "Seu dispositivo foi corrompido ou desativado, visite este link e insira suas 12 palavras iniciais para salvar seus fundos". ou "Detectamos uma grande retirada da sua Ledger. Você tem 24 horas para responder para tornar esta transação válida. Lamentamos, mas não conseguimos entrar em contato com sua Ledger, parece estar corrompida. Vamos autorizar a retirada a menos que você comece o processo de recuperação, dê-nos suas 24 palavras-seed." ou "você recebeu um airdrop. O dinheiro está entrando em sua conta, tudo o que precisamos é de uma verificação, por favor, inicie seu processo de recuperação e nos dê suas 24 palavras iniciais."

*Representação* [^70]
{height: "70%"}
![E-mail de phishing](resources/_phishing-mail-ledger.png)
Os atacantes tentam fazer você agir rápido sem pensar. Se você receber tal e-mail. Pare. Não faça nada. Como ninguém pode confiscar seu dinheiro, ninguém pode desativar remotamente sua carteira de hardware. Esse é o objetivo de uma moeda descentralizada como o bitcoin.

Nunca confie em um email! Especialmente: nunca clique em links anexados.

Marque os sites reais dos sites oficiais do Ledger, Shift Crypto, Trezor etc. ou digite o nome de domínio você mesmo na barra de endereços do navegador e procure o certificado de autenticação SSL. Os invasores enviarão você para um site falso que se parece com o real. A única diferença é a URL. Um dos novos truques é usar domínios com caracteres Unicode que pareçam iguais ao domínio real. Por exemplo, você pode notar a mancha embaixo do l de electrum? Se você abrir esse URL, verá electrum.org, mas está visitando xn--eectrum-9hb.org.

*Representação* [^71]
![](resources/_phishing.png)

Navegadores como Opera e Chrome irão avisá-lo, mas o Firefox não faz isso por padrão. Você pode mudar isso habilitando "punycode" no Firefox, veja [anita.link/puny](https://anita.link/puny).

## Regra 3-2-1 para armazenar sua seed
A semente consiste de 12 a 24 palavras em inglês. Atualmente, mais carteiras usam 12 palavras em vez de 24 porque fornecem um nível de segurança alto o suficiente e são mais fáceis de lembrar e armazenar.

Escreva a semente em um pedaço de papel à mão quando inicializar sua carteira pela primeira vez. Certifique-se de que a ordem está correta e verifique as palavras escritas várias vezes. Observe também o fornecedor, o modelo e o software da carteira. Você pode precisar dessas informações caso queira recuperar seus fundos.

Se você configurar uma carteira de hardware, deverá enviar uma pequena quantidade de bitcoin para garantir que tudo funcione. Depois de receber a pequena quantia, exclua o software do dispositivo e restaure-o com as palavras que você anotou anteriormente. Este é um passo importante que você não deve pular.

Depois disso, é aconselhável tomar as seguintes medidas de segurança para evitar que você perca sua seed. Quando as pessoas perdem o acesso aos seus fundos, é mais frequente porque perderam a sua seed ou cometeram um erro ao escrevê-la e não porque os seus dispositivos foram invadidos.

**3**: Anote a semente três vezes

**2**: Em pelo menos dois suportes diferentes (papel laminado, gravado ou estampado em aço) e guarde-o em local seguro para proteção contra incêndio, perda e roubo.

**1**: além disso, armazene um backup em um local diferente, de preferência a pelo menos 100 quilômetros de distância.

Jameson Lopp, um dos meus convidados do podcast, está testando placas de aço que podem ser usadas para garantir a semente a longo prazo. Ele os expõe ao fogo e pressão para verificar a longevidade. Nem todos os produtos são feitos de aço ou titânio, razão pela qual derretem no fogo. Os testes podem ser encontrados aqui: [anita.link/metalseed](https://anita.link/metalseed)

Não seja criativo! Dividir as palavras em duas ou mais partes e armazená-las em locais diferentes é um erro comum. Você só precisa perder uma parte e não poderá mais acessar suas moedas.

* Nunca dê a seed para alguém em quem você não confia com seu dinheiro!
* Não insira a seed em nenhum site ou dispositivo eletrônico!
* A seed não é necessária para enviar ou receber bitcoin.
* Nenhum indivíduo ou entidade credível pediria a sua seed.
* Verifique os locais de armazenamento de suas palavras seed regularmente!
* Configure um plano de herança - os piores casos acontecem e se você não instruir seus beneficiários corretamente, seu bitcoin será perdido. Eu recomendo o livro de Pamela Morgan sobre "Cryptoasset Inheritance Planning".

### Senha
Uma senha é uma maneira adicional de garantir seus fundos em cima da semente. Se você adicionar uma senha, o software cria uma carteira adicional que você pode usar para se proteger de ataques físicos. Se alguém pegar sua seed, ainda não poderá acessar seus fundos porque não possui a senha.

Exemplo: Você pode querer deixar a minoria de seus fundos na carteira básica “sem senha” e mover a maioria de seus fundos para uma carteira protegida por senha. A ideia por trás disso é que, se você se encontrar em uma situação em que alguém está tentando extorquir um resgate de você ou o coloca sob coação, você pode desbloquear sua carteira com segurança e apenas dar ao invasor acesso à carteira normal (que contém apenas uma pequena quantidade de fundos).

Isso parece ótimo, mas também há riscos envolvidos.

1. Como a senha não é armazenada automaticamente em nenhum lugar, você precisa tomar **todas as precauções necessárias** para garantir que a senha permaneça segura e acessível, por exemplo, fazendo um backup físico.
2. Se a senha for perdida, você **não poderá mais acessar essa carteira** e quaisquer moedas armazenadas nessa carteira ficarão inacessíveis.

Com uma senha, você não precisa apenas armazenar sua seed, mas também a senha. Agora você precisa encontrar armazenamento seguro de longo prazo para a seed. E a senha, o que torna o processo mais complicado. Esteja ciente: para restaurar uma carteira desse tipo, você precisaria da sua semente e da senha que você usou para essa carteira para restaurar o acesso aos fundos.

Como os ataques físicos acontecem raramente, armazenar a seed com o método 3-2-1 deve ser suficiente.

### Backups alternativos
Algumas carteiras usam mecanismos diferentes para o backup. Por exemplo, a carteira Muun usa uma combinação de código de recuperação - que você precisa anotar como uma seed - e um kit de emergência.

## Aprendendo fazendo
Pode ser intimidante começar a usar Bitcoin porque é dinheiro real. É por isso que é uma boa prática começar com quantidades muito pequenas.

Para suas primeiras tentativas, instale uma carteira em seu telefone, procure um [Bitcoin ATM](https://anita.link/atm) https://anita.link/atm perto de você ou participe de um encontro local de Bitcoin e troque uma pequena quantia. Obtenha uma carteira para o seu computador e envie bitcoins entre suas duas carteiras para endereços diferentes.

A melhor hora para fazer isso geralmente é no fim de semana, quando o Mempool não está lotado de transações e as taxas são mais baixas.

Use um software de carteira diferente, reinstale a seed da carteira A para a carteira B, use a seed em dispositivos diferentes. Você se sentirá cada vez mais seguro mantendo as habilidades.

### Endereço de recebimento de teste
Antes de enviar uma grande quantia pela primeira vez, certifique-se de que o endereço é realmente do destinatário e faça uma pequena transação de teste. Sempre verifique o endereço Bitcoin duas ou três vezes antes de enviar a transação. Compare o primeiro e o último dígito do endereço. Bitcoins que você envia para um endereço incorreto são perdidos.

### Teste sua carteira de hardware

Antes de guardar grandes quantias em uma nova carteira de hardware, você deve verificar a funcionalidade e a seed.

Quando você configura o dispositivo inicialmente, ele cria a seed pra você e você anota à mão (além do fornecedor, modelo e versão do software). Depois, você usa o software do fornecedor (ou outro software como o Electrum) e cria o primeiro endereço Bitcoin em sua carteira de hardware clicando em "Receber". Em seguida, envie uma pequena quantia para ele da carteira do smartphone instalada anteriormente. Se a quantia na carteira de hardware chegou - status "confirmado" - o primeiro teste foi bem-sucedido.

Além disso, tente enviar da sua carteira de hardware para outra carteira. Por exemplo, você pode enviar uma pequena quantia para sua carteira de smartphone ou outro endereço de sua carteira de hardware. Não importa particularmente. O principal é que você também está testando um pagamento da carteira de hardware. Para fazer isso, você deve verificar o endereço de recebimento na carteira de hardware e confirmar o envio com um ou mais cliques diretamente na carteira de hardware. Essa confirmação manual no dispositivo torna as carteiras de hardware seguras, pois somente você pode pressionar os botões e ninguém pode pressionar os botões virtualmente pela Internet.

**Restaure sua carteira**
Em seguida, certifique-se de ter seu backup/seed! Depois, exclua todos os dados da sua carteira de hardware. Alguns fornecedores chamam isso de "redefinição de fábrica", "limpar" ou "redefinir o dispositivo". Sua carteira está vazia. Agora restaure seus fundos e carteira com a seed. Isso é chamado de "Restaurar da palavra de recuperação", "Restaurar carteira" ou "Importar seed". Em seguida, insira sua frase inicial no dispositivo de hardware. Se tudo estiver correto, a carteira é restaurada e você pode ver suas transações e saldo anteriores.

**Atualizar firmware e software**
Não basta bloquear o dispositivo. Você deve procurar atualizações para o software ou atualizações de firmware pelo menos a cada 6 meses. O espaço criptográfico está se movendo rapidamente e novos desenvolvimentos são integrados ao software de carteira regularmente.

## Smartphone perdido? Computador roubado?

### Perda, roubo ou mau funcionamento do seu dispositivo

Se seu dispositivo for roubado, lembre-se de que seu bitcoin ainda está no blockchain sob sua chave privada. Como você definiu um PIN de acesso para a carteira, o ladrão não poderá abri-la. No entanto, eles ainda tentarão encontrar uma maneira de decifrar seu PIN.

Você deve instalar imediatamente uma nova carteira e importar a semente que manteve em segurança para recuperar o acesso aos seus fundos (consulte "restaurar sua carteira"). Em seguida, mova as moedas de sua carteira roubada para um novo endereço Bitcoin em sua nova carteira assim que puder, repetindo os mesmos procedimentos de configuração de segurança para a nova carteira.

Se o seu dispositivo for corrompido, você segue os mesmos passos, mas não há necessidade de correr para mover as moedas. Basta restaurar a carteira de software e pronto.

[^70]: Anita Posch  
[^71]: [Fonte @ElectrumWallet](https://twitter.com/ElectrumWallet/status/1144678604523147265?s=20) https://twitter.com/ElectrumWallet/status/ 1144678604523147265?s=20  