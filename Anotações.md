# CSharp
	dotnet new mvm -help
	doetnet new --list


#
# Trader
    F = S.(1 + i) ^ n/m
    F - Valor do contrato futuro
    S - Valor do spot(Contrato a vista)
    i - Taxa de juros(taxa:SELIC)
    n - dias uteis ate o vencimento
    m - dias da base(252du -  Dias Uteis)

    Ativo a vista
    Precificação do Ativo Futuro depende da variacao ou da precificacao do ativo a vista

    Cambio futuro
    Taxa de juros nos EUA e no BR

    Tres leis principais do mercado financeiro
    1º Lei - Oferta x Demanda
    Oferta - pressao excessiva
    Demanda - pressao comprado

    Of > Dem (Cai)
    Dem > Of(Sobe)


    Movimentacao de precos se da por um desequilibrio

    Movimento de fluxo

    -Valor dos contratos
    Qtd Contratos x Var. pontos x preço do ponto(Ex.: $0,20)
    Simulação:
    10 x 150 x 0,20 = 60
#
# Linux

    Espaço ocupado pelo cache
    du -sh /var/cache/apt/archives

    Para limpar
    sudo apt-get clean

    Remover versoes do kernel nao usados
    sudo apt-get autoremove --purge

    Remover apps antigas e pacotes
    Lista os programas instalados
    history | grep "apt-get install"

    Remove os programas/pacotes
    sudo apt remove APP/PACOTE

#### LPI 1
    ls mostra os arquivos, nao mostra os ocultos
    ls -a mostra todos os arquivos incluindo os ocultos.
    ls -A mostra todos os arquigoa, incluindo ocultoa, mas nak mostra o '.' e '..'
    ls -i mostra o numerk do inode
    ls -l detalha os arquivos
    drwxr-xr-x 11 root root 4096 Fev 15 10:03 usr
    permissoes do usuario; nº de subdiretorios; proprietario; grupo; tamanho; data; pasta
    Tipo de arquivo
    diretorio( 'd' )
    subdiretorio ou link( 'l' )
    ls -m em sequencia
    ls -n mostra o id e gid do diretorio (Zero é o usuario e grupo root)
    ls -O mostra o proprietario, mas nao o grupo
    ls -p mostra a pasta com uma barra na frente, dizendo que é um diretorio
    ls -r ordem inversa
    ls -h so lista os diretorios. Sempre combinar com outros
    ls . nesna coisa do ls
    ls ~ mostra o conteudo do diretorio atual
    ls </diretorio>
    ls -lh </diretorio> | less vai dividir o conteudo em paginas, para sair é o 'q'
    man ls manual
    Combinar letras (Exemplo)
    ls -la
    ls -lh mostra o tamanho dos arquivos de forma legivel para os humanos ler
    Permissoes
    drwxr - xr - x
    d = diretorio
    - = arquivo comum
    c = arquivo de caractere
    b = arquivo de bloco
    l = link
    Proprietario Grupo Outros
    rwx
    r-x
    r-x
    Sempre na ordem
    r - Read(Leitura)
    w - Write(Escrita)
    x - Execution(Execucao)
    - Sem permissao

#
## Inglês
###  M0 | V. A. 1
    Introductions | Greetings and Farewells
    Introdução | Saudações e Despedidas
    Hi! Oi
    Hello! Olá
    Hey there! Ei você
    Good morning! Bom dia
    Good afternoon! Boa noite(Chegando)
    Good evening! Boa noite(Saindo)

    My name is, I'm or It's

    What 's your name?
    -My name is Danilo

    What's your full name?
    -It 's Danilo Diego de Menz. Alc., or;
    -My full name is Danilo Diego de Menz. Alc.

    What's your first name?
    -My first name is Danilo
    -It's Danilo

    What's your last name?
    -My last name is Alcantara
    It's Alcantara

    Nice to meet you!
    Nice to meet you, too! (Too - Tambem)

    I'm fine, I'm ok, thanks or Not bad

    How are you? 
    I'm fine

    How are you doing?
    I'm ok, thanks

    And you? 
    Not bad


    Bye-bye! 
    Bye!
    See you!
    See you next class!
    Good night!

### V.A. 2
    Introductions  | Greetings and Farewells revisions, Countries, This/That

    Laís(L) Hey there!
    André(A) Hi!
    L What 's your name?
    My name is André and yours?
    L My name's Laís. Nice to meet you!
    Nice to meet you, too!
    L How are you doing, André?
    A I'm fine. And you?
    I'm Ok, thanks!
    A Where are you from, Laís?
    L I'm from Canada. And you?
    A Oh, how nice! I'm from England.
    L Cool
    [Gustavo come in]
    L André, this is my friend Gustavo. He's from Canada.
    A Oh, nice to meet you, Gustavo. I'm André.
    G Nice to meet you, André.
    L Sorry  André, we have to go now.
    A Ok, see you!
    G Bye!


### V.A. 3
    Occupations | Verb to be - Affirmative form, Personal information questions, His/Her

    Hi, everyone! I'm Laís. Sorry, I don't have a nickname. I'm from Brazil. Nice to meet you! How are you doing today?

    What's your nickname?
    -Sorry, I don't have a nickname.
    Where are you from?
    -I'm from brazil
    How are you doing today?
    I'm fine, thanks.

    Let's talk about what we do...
    What's your occupation?
    -A student
    What do you do?
    -An engineer

    A(Consoante)
    AN(Vogal)

    a student
    a secretary
    a housekeeper(EUA) or Maid - Governanta, Diarista
    a driver - O motorista
    a waiter / Waitress - Garçom / Garçonete
    a chef / cook(England) - Chefe de cozinha
    a salesperson - Vendedor
    a clerk - Atendente
    an engineer
    a photographer
    a videomaker
    a housewife - Dona de casa

    What's Gustavo's occupation?(his - dele)
    What 's his occupation? (Quando tiver falando dele)

    He's videomaker

    What's Camilla's occupation?(her - )
    What's her occupation?
    She's photographer

    -> Hi, everyone - Oi, pessoal [Avulso]

### V.A. 4
    Subject pronouns | Verb to be - Interrogative form, Verb to be - Short answers

    A Hi, are you Laís?
    L Yeah, I am. Sorry, what's your name again?
    A I'm André, from England. Remember me?
    L Oh, yeah! Sure! How are you doing?
    A I'm fine, thanks. You?
    L Not bad, too.
    A Laís, what do you do?
    L I'm the chief. Work in a restaurant called Le Petit
    A Wow! That 's cool.
    L And you, André? What's your occupation?
    A I'm a salesperson. I have an online business.
    L Cool!
    A Is your restaurant near here?
    L Yes, it is. It's downtown.
    A Is Gustavo a cook too?
    L No, he's not. He's a videomaker.
    A Wow! That's interesting!

    Chef(American English(AmE))
    Cook(British English(BrE))

    - Q -
    Are you a teacher?
    No, I'm not. I am an engineer.
    Is your house near your work?
    Yes, it is!
    Are your parents retired?
    Yes, they are.

    retired - aposentados

### V.A. 5
    Hi there. I'm André. I am married and I have two daughters

    Are you married or single?
    -I'm single.

    Do you have any children?
    -No, I don't. No, I don't have any kids

    Do you have any brothers or sisters?
    -Yes, I do. I have one sister.

    - Plural -
    Couple - Casal
    Siblings - irmãos
    Parents - Pais
    Children - Crianças

    Who - Quem?
    Who's He? He is my friend
    Who's She? She's my girlfriend
    Who are they? They are my family'

### V.A. 6
    Nuclear family | This / That, These / Those, WH-questions + verb to be

    What - Qual?
    What's your son's name?
    What's his name?(Quando estiver falando dele)
    -His name is Roberto

    What's your friend's name?
    What 's her name?
    -Her name is Leona

    A Hey, how are you Laís?
    L I'm fine, thanks. And you?
    A I'm okay, thanks. What are these things?
    L These are some photos of my family
    A Wow, beautiful kid! Who's he?
    L He's my son
    A What 's his name?
    L His name is Augusto. He's 2 years old. Do you have any children, André?
    A Yes, I do. I have two daughters. Look, I have some photos too.
    L Hey nice! Let me see!
    A Yeah, sure, look, this is my wife Alexandra and these are my daughters
    L And what are their names?
    A This one here's Julia, she is ten years old. And that is Alice, she's 5.
    L So sweet! They are so cute!

    This - este(a), esse(a)

    -- Próximo, este lugar, junto comigo
    These - estes(as), essas(as)

    That - aquele(a)

    -- Longe, Ali, Não estar junto comigo
    Those - aqueles(as)

    -- Speaking --
    Who 's he?
    -He:s my son
    Who 's she?
    -She's my wife
    Who are they?
    - They're my daughters
    Who are they?
    - They're my husband and my son

    Who 's Augusto?
    - He's my son
    Who 's Alexandra?
    - She's my wife / She's André wife
    Who are Julia and Alice?
    - They're my daughters / They're André daughters
    Who are Cézar and Augusto?
    - They're my husband and my son
    Who 's your family? 
    - My family is my husband Cézar and my son Augusto
    - My family is my wife Alexandra and my daughters Alice and Julia

### V.A. 7
    Hi there?
    How are you doing, people?
    Where do you live?
    Eu vivo em São Paulo. I work in Campinas, but I don't live in Campinas.

    Do you work? 
    Yes, I do. / No, I don't.

    Where do you work?
    I work in Canoas. I don't work in Porto Alegre

    Cidades, paises, estado usar o in

    Do you work in an office? No, I don't.
    Do you work in a bank? No, I don't
    Do you work in a factory? In the past, yes. Now, I don't work anymore.
    Do you work in a cofé? No, I don't.
    Do you work in a hospital? No, I don't
    Do you work at home? Not yet.

    at - no

    Well, I work at a school. I work at Mais Lingua

    When do you work? I don't work yet
    Do you work part-time or full-time?

    I work full-time
    I don't work in the morning, but I work in the afternoon and in the evening

    Usar in em:
    In the morning
    In the afternoon
    In the evening

    Do you study? 
    Where do you study? 
    Do you study at university or at a school? 

    don't - Presente

    Wrap-up
    I work in a school
    I don't work in a hospital
    Do you work in a hospital?

    --> Practice
    To Work
    I work
    I work part-time
    I work in a school
    I don't work
    I don't work full-time 
    I don't work in a bank
    Do you work?
    You work part-time?
    You work in an office?

    To study
    I study English
    I study English in the morning
    I study English at home
    I don't  study in the afternoon
    I don't study in the evening
    Do you study English?
    You study English at in Mais Lingua?

### V.A. 8
    University courses
    What do you study at university?
    I study business
    I study Art and Literature
    I study English
    I study French
    I study Engineering
    I study Architecture
    I study Law
    I study Medicine
    I study Psychology
    I study Nursing

    A Laís, do you also study at university?
    L Oh. Yes, André. I work as a chef and I study business at university
    A What an interesting thing! Where do you study business?
    L I study business at University of London. What about you, André?
    A I study at university well. I study french.
    L Wow! French is cool!
    A Yeah. My family and I want to move to france next year
    L Wow! What about your job?
    A I don't work in a office, Laís.
    L Really? Where do you work?
    A I work at home. I work online sales and I work full-time with that.
    L I see. Good luck with your studies!
    A Thanks! You too! See you around
    L See you! Bye!

    "Se você quer fazer algum comentário no meio de uma conversa, é bacana dizer algo sobre o que a outra pessoa disse antes de falar sobre você."

    ->Some phrases
    What an interesting things![Que coisa interessante]
    Oh, I see.[Hmm, entendi]
    Wow![Uau]
    That 's interesting
    How nice!
    That 's cool!
    What a nice thing![Que coisa legal]

    -> Speaking pratices
    I study Engineering
    I study Law
    What an interesting thing! I don't study Law
    I don't studt Medicine, I study nursing
    Wow! How nice! Nursing 's interesting
    Do you study business?
    Do you study in the morning?

### V.A. 9

    Do you like to listen to music? 
    I like to listen to rock and roll.
    I don't like to listen to heavy metal.

    What kind of music do you like to listen to? I like to listen to blues, rock and roll and jazz.

    Do you like watch comedies? 
    I prefer to watch thrillers and dramas.
    I don't enjoy horror films.

    What kind of film do you prefer to watch? I like to films to comedies, actions, drama, science fiction, documentaries.

    kind - tipo

    I like to listen to music
    I like to watch tv series
    I like to listen to classical music

    I prefer to listen to reggaes
    I prefer to watch science fiction
    I prefere to listen to music in the car

    I don't like to heavy metal
    I don't like to watch romance
    I don't like to folk music

    Do you like to listen music?
    Do you like to watch comedies?
    Do you like to watch documentations?

### V.A. 10
    What's your favourite band?
    What's your favourite film[BtE]?

    -movie[AmE]

    My favourite music is AC/DC and my favourite film is Transformers 1

    Who's your favourite singer?
    Who's your favourite actor/actress?

    My favourite singer is Indiara
    My favourite actor is Leonardo Di'Caprio and my favourite actress is Hayley Atwell

    Intro: Teacher Laís wants to find a film to watch at[BtE](on[AmE]) the weekend with her family.

    L Hi, André. I want to find a good film to watch tomorrow with my family.
    A Hey, Laís. What kind of film do you prefer to watch?
    L Well, I don't no. I do prefer to watch drama
    A Drama? Really? What's your favourite film?
    L It's difficult to say. A film that really love is Dallas Buyers Club.
    A Oh, nice! I like this filme, too! But, my favourite film is The Matrix.
    L Oh, that's a very interesting film! But I need a film to watch with my family.
    A Hum. Maybe an animation or a comedy.
    L That would be great!
    A Do you know Inside out? It's great film!
    L No, I don't. It sound good! Thanks!
    A No problem! Have fun!

    Speaking pratice
    What's your favourite film?
    My favourite film is Ghost in the shell

    Who's your favourite actor/actress?
    My favourite actor/actress is Leonardo Di'Caprio
                                   or

    What kind of filme do you prefer?
    I prefer action and documentaries

    What kind of music do you like?
    I like to listen to R&B

    music - tipo musical
    song - musica

    What's your favourite band?
    My favorite band is Ac/Dc

    Who's you favourite singer?
    My favourite singes is Ozzy Osbourne

#
# JavaScript

    node <dir>/index.js

    body

    //Final
    <script src="index.js"></script>

    alert("rexto")

    let para criar variaveis
    let name = "Example"

    console.log(name, " nasceu em 1984")

    //Case sensitive
    let name = "Ok"
    let namE = "Blz"

    // Utilize let

    // Valor da const nao pode ser alterado
    // Não utilize var, utilize const
    // Sempre inicializar a const
    // Js é tipagem dinamica






#
# Git / Github

    Branche - ramificação do projeto
    branch master

                    Base                                            Branch FuncB
    -----------/-----------------------------------/---------------->
                    Branch FunA                              Base

    rebase - refazer a base

    non-bare
    bare

    ----
    Pesquisar:
    FETCH_HEAD
    ----

#
# Kotlin


    -> Any
    Descendentes de Any - Int, Boolean, String etc
    fun values(value: Any){} //Exemplo

    -> Unit
    Função não tem retorno
    fun values(value: Any): Unit{} // Exemplo

    -> Nothing
    Não tem retorno
    Usar quando quer usar uma exceção.
    fun values(value: Any): Nothing {
    TODO ("Nothing")
    }

#
# Java
### JavaFX
    View
    @Override
    public void start(Stage stage) {
        try {
            Parent parent = FXMLLoader.load(getClass().getResource("/gui/View.fxml"));
            Scene scene = new Scene(parent);
            stage.setScene(scene);
            stage.show();
        } catch (IOException e) {
            e.printStackTrace();
        }
    }
-----

    -Eclipse
    sudo apt-get install openjdk-11-jdk
    sudo tar -zxvf <arquivo .tar.gz>
    Para instalar: sudo ./eclipse-inst
    --------------------------------
    Léxica -  Ortografia. Palavras isoladas.
    main
    maim

    Sintática - Gramática. Sentença como um todo.
    x= y + 2;
    x = y2 +;

    Compilador -  transforma codigo fonte em codigo objeto
    Maquina virtual ou Gerador de codigo - permite a execucao do codigo objeto

    .o - objeto

    Expressões aritméticas
    Precedência:
    1º
    *
    /
    %(mod)

    2º
    +
    -

    <tipo> <nome> = <valor inicialOpcional>;

    bits - Quantidade de bits representa o número de valores possiveis diferentes que uma variavel desse tipo pode armazenar

    Um bit pode armazenar 2 valores possíveis(0 ou 1)
    8 bits -> 8 ² = 2 x 2 x 2 x 2 x 2 x 2 x 2 x 2 = 256 Possibilidades

    Valor padrão = 0
    -128 a 127 = 255


    marcadores de variaveis  ...printf("%.2f", exemplo);
    %s - Texto(String)
    %d - Inteiro(int)
    %f - Ponto flutuante(double / float)
    %n - Quebra de linha

    comando de atribuição: Sintaxe -> <variável> = <expressão>
    Regra:
    1 - A expressão é calculada
    2 - O resultado da expressão é armazenado na variável

    tipo float -> 6f

    int a, b;
    double calc = (double) a / b;  //Casting

    println - pega localidade independente

    char letra = read.next().charAt(0);

    Limpar o buffer de leitura
    read.nextLine();

    sqrt(x) - raiz quadrada
    pow(x, y) - x elevado a y
    abs(x) - absoluto sem o negativo


    trim(); //elimina os espaços
    replace("a", "b"); // troca uma letra por outra, por exemplo
    substring(2, 5); //conta a estring a partir da posicao da posicao desejada e o final dela
    substring(3); //conta a estring a partir da posicao desejada(vetor)
    split(" "); //Corta um texto

    Classes e metodos final
    -Evita que a classe seja herdada
    public final class SavingAccount{
    ...

    Em metodo
    public final void Withdraw(){
    ...

    Pra quê?
    Segurança:
    -Regras de negocio
    -Sobreposiçoes multiplas podem ser uma porta de entrada para inconsistencias.

    Perfomance:
    -São analisados de forma mais rapida em tempo de execução

    Poli - muitas
    morfismos - formas

    -- Generics
    tipo comparable


    -- Estr. Dados e algoritmos em java
    "Vetor cheio"
    java.lang.ArrayIndexOutOfBoundsException

    HvC
    Relação é um

    Gen. / Espec
    Figura(Shape) / <<Interface>>TaxService - tipo generico
    Rectangle / Circle | BrazilTaxService / USATaxService- especialização(ou especificos)

    Diferença
    Herança - reuso
    Interface - Contrato

    --Javafx
    1
    http://www.eclipse.org/downloads/packages/

    2 SDK
    https://gluonhq.com/products/javafx
    Descompactar em /opt

    3
    Em: Help -> Install new Software, colar link
    http://download.eclipse.org/efxclipse/updates-released/3.4.1/site/

    4 Por diretorio do Scenebuilder, no ubuntu é na pasta bin do Scenebuilder
    Window -> Preferences -> JavaFX

    5 Criar uma User library do javafx
    Window -> Preferences -> Java -> Build Path -> User Libraries -> New

    --module-path "/opt/fxSdk/lib" --add-modules=javafx.fxml,javafx.controls



    @FXML //Exemplo
    private Button buttonTest;

    eventHandler // Métodos

    Associar botão com codigo:
    Controller - canto inferior esquerdo

    chamar o atributo para associar na aba code : identity > fx: id

    d inteiro
    * qualquer quantidade

    url - caminho da tela
    rb - recursos

    ObservableList<E> - Tipo especial de lista que fica associado ao componente visual. Coleção!

    project > clean

    AnchorPane
    GridPane - Caixas organizadas
    Splitpane
    VBox | HBox - v vertical; h horizontal
    BorderPane
    Scrollpane

    Comparable - Como que um objeto é comparado com outro

    Com algum tipo T

    Desde que T seja qualquer subtipo de Comparable T

    Wildcard types - Tipos coringa
    Generics são invariantes

    Lista de Integer não é lista de object

    Tipo coringa List<?>
    é o super tipo de qualquier tipo de lista

    Tipos coringa pode receber generico de qualquer tipo
        public static void printList(List<?> pList) {
        ...
        }
        ...
        List<Integer> integer = Arrays.asList(5, 2, 10);
        printList(integer);

    Não é possível adicionar dados a uma coleção de tipo curinga

        public static void main(String [] args){
        List<?> listas = new ArrayList<>();
        listas.add(3); //Erro de compilação

    Curinga delimitado -
    public static double totalArea(List<? extends Shape>list){}

    *Não será possivel adicionar elementos na lista do método

    -Covariância
    get é permitida
    put não é permitida
        List<? extends Number> listNumber = integer;
        listNumber.add(43); //erroi de compilação

    -Contravriância
    Qualquer tipo super  number
    Pode ser Number ou qualquer super tipo de number
        List<? super Number> supNumber = obj;
        supNumber.add(287);

        Number number = supNumber.get(0);

    get não é permitida
    put é permitida

    -Comparator
    Interface funcional tem apenas um método

    Classe anonima
    Comparator<Product> comp = new Comparator<Product>() {
        @Override
        public int compare(Product prod1, Product prod2) {
            return prod1.getName().toUpperCase().compareTo(prod2.getName().toUpperCase());
        }

    -- Implementação de uma função, apos a ->
        Comparator<Product> comp = (prod1, prod2) -> {

    Arrow function ( -> )

    <-- JAVA PT 2 -->
    hashcode e equals

    tratamento especial para literais
    String t1 = "Teste1";
    String t2 = "Teste2";
    >true

    String t1 = new String ("Teste1");
    String t2 = new String (Teste2");
    >false

    Generics, Set, Map
    Set - É uma interface
    https://docs.oracle.com/javase/8/docs/api/java/util/Set.html
    /* Anotações
    O(1)  - Ordem de 1
    log(n)
    Arvore rubo-negra

    ** Exemplo
    */

    //**
    //HASHSET
    //Não ordenado e mais rapido
    Set<String> sString = new HashSet<>();
        sString.add("Geladeira");
        sString.add("Notebook");
        sString.add("Tv");
        System.out.println(sString.contains("Notebook"));

    //**
    //TREESET
    //Mais lento e Ordenado pelo compareTo do Obj ou Comparator
    Set<String> tString = new TreeSet<>();
        tString.add("Fogao");
        tString.add("Copo");
        tString.add("Caneca");

    //**
    //LINKEDHASHSET
    //Vel. Intermediária e elementos na ordem em que são adicionados
    Set<String> lString = new LinkedHashSet<>();
        lString.add("Guarda-roupa");
        lString.add("Mesa");
        lString.add("Armário");

    TreeSet
    https://docs.oracle.com/javase/7/docs/api/java/util/TreeSet.html

    Map
    https://docs.oracle.com/javase/8/docs/api/java/util/Map.html

    Funções são objetos de primeira ordem (ou primeira classe)

    Utilizamos aqui "method references"
    Operador ::
    Sintaxe
    Classe :: método

    Tipagem dinâmica / inferência de tipos

    Expressividade / código conciso

    O que são "expressões lambda"?

    Predicate
    https://docs.oracle.com/javase/8/docs/api/java/util/function/Predicate.html

    Function
    https://docs.oracle.com/javase/8/docs/api/java/util/function/Function.html

    Consumer
    https://docs.oracle.com/javase/8/docs/api/java/util/function/Consumer.html
    Nota: ao contrário das outras interfaces funcionais, no caso do Consumer, é
    esperado ele possa gerar efeitos colaterais

    Stream
    https://docs.oracle.com/javase/8/docs/api/java/util/stream/Stream.html

    Pipeline
    https://www.javadoc.io/doc/redis.clients/jedis/3.1.0-rc/redis/clients/jedis/Pipeline.html

    -- Jogo Xadrez
    # sublinhado - protected e estático

    Hook methods - Faz um gancho com subclasse
    Template method

#
# Spring boot

    -STS
    Descompactar:
    sudo tar -zxvf <arquivo .tar.gz>

    Para abrir o STS4
    sudo ./SpringToolSuite4

    Criar um icone
    sudo gedit /usr/share/applications/STS.desktop

    [Desktop Entry]
    Name=Spring Tool Suite
    Comment=Spring Tool Suite 4.7.1
    Exec=/opt/sts/SpringToolSuite4
    Icon=/opt/sts/icon.xpm
    StartupNotify=true
    Terminal=false
    Type=Application
    Categories=Development;IDE;Java;


    monorepo - repositorio para vários projetos

    Balanceador de carga. Pode levantar mais de uma instância do mesmo projeto.
    "Aí, quando um projeto fizer uma requisição para outro projeto, que tem mais de uma instância levantada,

    vai haver ali um balanceamento de carga."

    -- Ribbon
    -Dserver.port=8002


    -Djava.security.egd=file:/dev/./urandom


#
#### Dica do prof. Nelio

    -> Ordem sugerida

    • Atributos privados
    • Propriedades autoimplementadas
    • Construtores
    • Propriedades customizadas
    • Outros métodos da classe

#
#### Dicas de cyber

    -Danilo Diego De Menz opa, eu comecei com os
    cursos grátis da cisco,
    se você souber inglês ou usar um navegador que possui sistema de tradução, dá uma
    olhada no
    try hack me,
    hack the box, e
    portswigger.
    Também dá uma olhada no canal
    hacking na web.
    Também dá uma olhada no Instagram dele, hacking na web, da Carol que é
    hacknlearn e do cadu que é o
    crodwdsec,
    Segue a menina de cybersec também e pede o discord, pq no discord tem muuuuuuito
    material.

#
#### Dicas

    Observando algumas postagens, percebo que algumas pessoas tem dificuldade de relatar
    seus problemas, principalmente quando se está no início dos estudos (e isso é normal).
    Por isso, gostaria de propor um método que pode auxiliar aqueles que não tem ideia de
    como descrever um problema.
    Pessoalmente, utilizo essa técnica para troubleshooting até hoje. Inclusive às vezes, o
    próprio ato de descrever o problema com detalhes, acabo tendo insights para a solução,
    antes mesmo de pedir ajuda:
    DESCRIÇÃO DO PROBLEMA
    Breve descrição do problema para contextualizar o tema.
    COMO REPRODUZIR O ERRO
    Lista de passos executados que levam ao erro em questão, como comandos executados,
    ações aplicadas, passos seguidos.
    SOLUÇÕES APLICADAS
    Descrição das ações que já foram tomadas, mas que não surtiram efeito, fóruns já
    acessados, vídeos assistidos, etc.
    RESULTADOS ATUAIS
    Descrição dos resultados obtidos com a execução do passo anterior, códigos de erro,
    screenshots, logs, etc.
    RESULTADOS ESPERADOS
    Descrição do que se espera obter em um cenário ideal.
    OBSERVAÇÕES ADICIONAIS
    Informações gerais que possam contribuir para a identificação da origem do problema e
    possíveis caminhos para solucioná-lo. Sistema operacional e versão, se é uma VM ou não,
    qual software de virtualização (se for o caso), versão do aplicativo com erro, modelo de
    hardware, firmware, etc.
    Enfim. Espero que esta dica seja útil para alguém como é para mim.

#
#### Desenhar

    -> Probições:
        Preguiça para terminar
        Pressa para terminar o trabalho
        Nao desenhar pelinhos
        Desenhar um tamanho razoavel na folha
        Simplificar formas

#
#### Docker

    Docker
    //Remove a imagem do docker
        docker rm <nome da imagem> //Ex. hr-worker-pg12
    //Inicia a imagem no docker
        docker start **CONTAINER ID**

        -- Terminal ubuntu - sudoers --
        su -
        nano /etc/sudoers

        -- Dimensionar ubuntu no virtualbox
        sudo ./VBoxLinuxAdditions.run

#
## Eletricista

    Newton metro
    1J = 1N . 1m
    Quilograma
    (1J = 1kg . m² / s²)

    ------
    Area = Comprimento x Largura

    NBR 5410 - 9.5.2.1.1

    Metragem quadrada
    Para os primeiros 6m² = 100va

    VA - Volt Ampere
    TUG  - TOMADA DE USO GERAL
    prumada - tento para baixo
    Quarto 1


    Quarto 2


    Sala

    monofasico
    1 fase
    1 neutro
    bifasico
    2 fase
    1 neutro
    trifasico
    3 fases
    1 neutro

    Quanto maior a potencia, maior a tensao
    Unifilar -composto por.uma.linha so

    Neutro e a parte que da o retorno da instalacao que fecha com a fase
    Neutro - 0v
    Fase -
    Terra -


    Media tensao ê composto pela fases, nao tem neutro nela. Neutro é gerado pelo transformador

    Neutro + fase = faz a coisa funcionar
    Terra ofereca protecao quando tem fuga de corrente

    Diagramas unifilar
    Quem faz  e Engenheiros

    (Vermelho) Aterramento. Olhar print 0001
    (Verde) Barramento. Olhar print 0002
    (Amarelo) Fases. Olhar print 0003
    QD
    Disjuntor geral
    -- Bipolar(Dois riscos) -  dois polos, protehet duas fases. Indicado para circuito bifasico 220v


    Disjunto branco(No 63A)

    Dutar - passar os conduites
    Tomadas da cozinha vao estar em outro circuito, dai nao da para fazer um furo na parede e extender o cabo de la.

    bitola

    Continuidade eletrica
    Deve garantir que a corrente eletrica passe de um condutor para o outro, a partir do momento que eu faca a conexao entre eles.

    Protecao

    Limite mecanico
    Emenda que nao solte sozinha

    Conectores
    emendas
    terminais

### Livros
    A. C.
    Atividades assistenciais
    Participação como ministrante em congressos
    Visitas tecnicas
    Livros
    William Stallings
    Arquitetura e Organização de Computadores
    681.3.062
    L769d
    Dagliam, J lógica e algebra de boole
    Lógica, o calculo setencial, calculo de predicado e calculo com igualdade
    Alencar filho e iniciação a lógica matematica
    510.6
    D125l
    4ed
    V.0
    Shell script profissional — Aurelio Marinho
    Delphi 7 — Pierre-Jean Bellavoine
    Effective AWK Programming — Arnold Robbins
    Internet Programming with — Mark Baker
    Xsl: The personal Trainer for xslt, xpath and xsl-fo — William Stanek
    XSLT Programmer's reference — Michael Howard key
    Xpath 1.0 — Surhone lambert M.; Timpledon, mirian t.
    Introducing maven — balaji varanasi, sudha belida
    Introduçao ao hibernate — madhusudhan konda
    Programando em Javaserver faces — Budi kurniawan
    XML programming using the microsoft XML parser — Soo mee Foo
    Oracle database 11G pl/sql programaçao — michael mclaughlin
    Microsoft visual basic 2008 — michael halvorson
    Sistemas Operacionais Modernos — Andrew Tanenbaum - 4a. edição. editora Pearson
    --------
    hacker sec
    EC-Council – CEH – Certified Ethical Hacker
    (ISC)2 – CISSP – Certified Information Systems Security Professional
    ISACA – CISM – Certified Information Security Manager
    CompTIA Security+
    (ISC)2: CCSP – Certified Cloud Security ProfessionalCISSP – Certified Information Systems Security Professional
    EC-Council – CHFI – Computer Hacking Forensic Investigator
    -------
    -SGBD
    Heuser
    DATE
    Modelagem: Paulo Cougos
    Data warehousing: kimball; Innmon
    Linguagens sql: sempre os manuais do site da linguagem
    1º Sistemas de banco de dados (4a. ed.) - Ramez Elmasri e Shamkant B. Navathe
    2º Business intelligence - DM DW
    cara eu te aconselho a entender toda estrutura de banco primeiro ja que vc nao tem
    conhecimento, esse vai ser seu caminho ideia, procura por esse livro antes de iniciar
    qualquer atividade dentro de uma ferramenta de banco de dados.
    Esse navathe e o cara mais foda em banco de dados o livro dele é simples e pratico, vc vai
    entender toda a logica e fundamento, ai depois vc parte para a pratica quando ja estiver
    com a ideia de banco formulada na cabeça.

# MySql and Postgresql on Ubuntu
### MYSQL

    sudo apt install mysql-server
    sudo mysql_secure_installation

    Erro para ...secure_installation
    https://stackoverflow.com/questions/72103302/mysql-installation-on-ubuntu-20-04-error-when-using-mysql-secure-installation

    Se aparecer esse erro abaixo:
    "Failed! Error: SET PASSWORD has no significance for user 'root'@'localhost' as the authentication method used doesn't store authentication data in the MySQL server. Please consider using ALTER USER instead if you want to change authentication parameters.`"

    Use:
    ALTER USER 'root'@'localhost' IDENTIFIED WITH mysql_native_password by 'mynewpassword';

    e quando for acessar usando 'sudo mysql' e der erro use:
    sudo mysql -u root -p

    # ERROR 1819 (HY000): Your password does not satisfy the current policy requirements
    show global variables like 'validate_password%';

    ALTER USER 'root'@'localhost' IDENTIFIED WITH mysql_native_password by 'mynewpassword';

    no terminal
    sudo mysql -u root -p
    ALTER USER 'root'@'localhost' IDENTIFIED WITH mysql_native_password by 'mynewpassword';

    ou

    SET GLOBAL validate_password_policy=LOW;

    Workbench(20 megabyte)
    https://www.mysql.com/downloads/
    --------------------------------------------------------

    --------------------------------------------------------
    Desinstalar
    sudo apt-get remove --purge mysql*
    sudo apt-get purge mysql*
    sudo apt-get autoremove
    sudo apt-get autoclean
    sudo apt-get remove dbconfig-mysql
    sudo apt-get dist-upgrade
    --------------------------------------------------------
    -u usuario
    -p senha
    --------------------------------------------------------
    sudo systemctl status mysql
    sudo systemctl stop mysql
    sudo systemctl start mysql
    --------------------------------------------------------

    CREATE USER 'novo_usuário'@'localhost' IDENTIFIED BY 'senha';
    GRANT ALL PRIVILEGES ON * . * TO 'novo_usuario'@'localhost';
    FLUSH PRIVILEGES; -- Para que as mudanças tenham efeito, execute imediatamente um flush dos privilégios ao executar o seguinte comando <

    --------------------------------------------------------



    user=developer
    password=1234567
    dburl=jdbc:mysql://localhost:3306/coursejdbc
    useSSL=false

    the type java.sql.Connection is not acessible
    Excluir module info

    Statement
    Montar um comando sql para ser executado

    ResultSet
    Objeto contendo o resultado da consulta na forma de tabela


    first - O resultSet não tera a posição 1
    beforefirst - Começo do RS antes de ter os dados
    next - Proximo.
    absolute(int) - Numero inteiro

    Falha de integridade referencial
    Quando deletar uma linha que contenha uma chave estrangeira

    Transação é uma operação que tem que manter a consistência do banco de dados
    Atomica
    Consistente
    Isolada
    Duravel

    ### Postgresql
    # Create the file repository configuration:
    sudo sh -c 'echo "deb http://apt.postgresql.org/pub/repos/apt $(lsb_release -cs)-pgdg main" > /etc/apt/sources.list.d/pgdg.list'

    # Import the repository signing key:
    wget --quiet -O - https://www.postgresql.org/media/keys/ACCC4CF8.asc | sudo apt-key add -

    # Update the package lists:
    sudo apt-get update

    # Install the latest version of PostgreSQL.
    # If you want a specific version, use 'postgresql-12' or similar instead of 'postgresql':
    sudo apt-get -y install postgresql

    Ubuntu includes PostgreSQL by default. To install PostgreSQL on Ubuntu, use the apt-get (or other apt-driving) command:
    apt-get install postgresql-12

--- PGAdmin ---
    #
    # Setup the repository
    #

    # Install the public key for the repository (if not done previously):
    curl -fsS https://www.pgadmin.org/static/packages_pgadmin_org.pub | sudo gpg --dearmor -o /usr/share/keyrings/packages-pgadmin-org.gpg

    # Create the repository configuration file:
    sudo sh -c 'echo "deb [signed-by=/usr/share/keyrings/packages-pgadmin-org.gpg] https://ftp.postgresql.org/pub/pgadmin/pgadmin4/apt/$(lsb_release -cs) pgadmin4 main" > /etc/apt/sources.list.d/pgadmin4.list && apt update'

    #
    # Install pgAdmin
    #

    # Install for both desktop and web modes:
    sudo apt install pgadmin4

    # Install for desktop mode only:
    sudo apt install pgadmin4-desktop

    # Install for web mode only:
    sudo apt install pgadmin4-web

    # Configure the webserver, if you installed pgadmin4-web:
    sudo /usr/pgadmin4/bin/setup-web.sh

    service postgresql status
    service postgresql stop
    service postgresql start


# Redes
    // Html


    // UI / UX
    tipografia
    Interface web é composta por 95% de tipografia


    // Arq. de redes
    Késhe(Cache)

    arq estatico temp - que nao sao modificados com frequencia

    F5 Recarrega o conteudo da pagina, utilizando o cache local

    Ctrl+F5 Recarrega o conteudo da pagina totalmente do servidor


    // Pentest[ Kali ] - Comandos
    ls -l
    cat <arquivo> - vai ler o conteudo desse arquivo
    head -3 passwd // Exemplo. Tres primeiras linhas
    tail - 2 passwd // Exemplo. Duas ultimas linhas

    | - pipe sainda de um comando para a entrada de outro.
    more - pausando ate que insira
    less - subir e descer com mais calma.
    grep - filtra

    echo Uma nova linha >> passwd
    > - Apaga tudo que tiver dentro do arquivo
    >> Inclui no final do arquivo a frase


    ← Arq. redes →
    Késhe(Cache)

    arq estatico temp - que nao sao modificados com frequencia

    F5 Recarrega o conteudo da pagina, utilizando o cache local

    Ctrl+F5 Recarrega o conteudo da pagina totalmente do servidor

    Proxy(Plural: Proxies)
    Intermediario entre uma origem e um destino
    Proxy direto atuara do lado do cliente
    1- Servidor de cache compartilhado(A. Cache pt 1)
    Esta em desuso porque nao é criptografado

    2- Mascaramento do cliente
    Servidor de destino pensara que é o proxy e nao o nosso cliente.
    Desvantagens:
    Uma maquina possivelmente nao confiavel como intermediaria.
    Em geral so suporta trafego web e nao é um sistema web.

    Esta aplicacao atualmente é feita servidor vpn.

    3 - Controle de acesso(Ex.: Firewall) no sentido da rede local para a internet

    Um firewall no sentido da internet para um servidor sera um proxy reverso (e nao  um proxy direto)
    Proxy reverso aruara no lado do servidor

    vpn(Virtual Private Network)
    vpn "original" site-to-site vpn*
    Camada 3 do modelo OSI(Camada de rede)
    Pilha tcp/ip- Protoco IPsec

    * "site" neste contexto significa infraestrutura de uma empresa e nao um "website"

##### Links

    https://education.oracle.com/learning-explorer
    https://www.universetoday.com/150754/in-a-comprehensive-new-test-the-emdrive-fails-to-generate-any-thrust/
    https://diolinux.com.br/noticias/kernel-linux-suporte-cpu-antigos.html
    https://www.brainlatam.com/blog/computacao-quantica-e-o-futuro-da-tecnologia-807
    https://www.infomoney.com.br/mercados/as-5-maiores-quedas-e-as-5-maiores-altas-do-ibovespa-em-janeiro-2021/amp/
    https://noticiasconcursos.com.br/fgts-libera-saques-de-r-50-a-r-2-900-em-fevereiro-saiba-quanto-receber/
    https://www.inovacaotecnologica.com.br/noticias/noticia.php?artigo=sensor-gera-sua-propria-energia-usando-tunelamento-quantico&id=010165201130#.YBX1gVNv_xM
    https://www.infomoney.com.br/onde-investir/quer-investir-no-mercado-acionario-chines-confira-as-principais-alternativas-sem-sair-do-brasil/amp/
    https://www.tecmundo.com.br/ciencia/210069-microsoft-anuncia-avanco-computacao-quantica.html
    htpps://www.inovacaotecnologica.com.br/noticias/noticia.php?artigo=tunelamento-quantico-100-probabilidade&id=010165210125#.YBNfUFNv_xO
    https://www.ibm.com/blogs/ibm-training/free-getting-started-with-ibm-cloud-new-learning-path-for-all/
    https://www.vmware.com/learning/connect-learning.html
    https://www.aws.training/
    http://crysa.fzu.cz/ondra/documents/airlines_as_OS.html?fbclid=IwAR3FpiXem4jlnp_UYJOrLrQv3D6wc4g5YTWMvTbq0E4r-D1SpKV3YxlBF9M
    https://produto.mercadolivre.com.br/MLB-1668526114-nave-uss-enterprise-ncc-1701-d-star-trek-qmx-quantum-_JM?matt_tool=51082743&matt_word=&gclid=Cj0KCQjwk8b7BRCaARIsAARRTL5bITI1pBQq1-PYMEOFv7sqSp0C8hasd2uFqmx9xeWyHqEscmetA1YaAvxmEALw_wcB
    https://sempreupdate.com.br/conheca-o-emulador-de-terminal-linux-edex-ui-inspirado-na-ficcao-cientifica/
    https://www.guiafoca.org/#download
    https://interestingengineering.com/science/new-magnet-is-powerful-enough-to-lift-an-aircraft-
    carrier?utm_source=Facebook&utm_medium=content&utm_campaign=organic&utm_content=F
    eb10&h=AT2oOv08hZvsDoaIRC4nZOJpLhgYz-
    tNujecAiG5VUVWvgtRW7wETaC4sEGyW7KrxO44ERuc6yFDeEppfG3enqCaXzilZcZevoxM4T
    Af-94fSBPIN4pOfIwQRgBAibxFfzQY2mTUrmKQkOVJQ7Rl
    https://www.mql5.com/en/docs
    https://liteboxer.com/
    https://www.shellscript.sh/
    https://www.4devs.com.br/gerador_de_pessoas#
    https://www.service-architecture.com/articles/web-services/representational-state-transfer-
    rest.html
    https://en.m.wikipedia.org/wiki/Radio-frequency_identification
    https://asdf-vm.com/
    https://militarywatchmagazine.com/
    https://en.m.wikipedia.org/wiki/AIM-9_Sidewinder
    https://www.comptia.org/pt/certificacoes/security
    https://docs.oracle.com/javase/10/docs/api/java/util/List.html
    https://docs.oracle.com/javase/tutorial/java/javaOO/enum.html
    https://commons.apache.org/proper/commons-cli/
    https://en.m.wikipedia.org/wiki/JavaBeans
    https://docs.gradle.org/current/userguide/getting_started.html
    https://pt.m.wikipedia.org/wiki/Programa%C3%A7%C3%A3o_orientada_a_aspecto
    https://ieeexplore.ieee.org/Xplore/home.js
    https://spring.io/projects/spring-cloud https://wiki.osdev.org/?fbclid=IwAR3fimz9dotDZ35-
    hhKZJZOOqehT4ZbciLqyt40LCIW3dRW HHsDbtgTuApo
    https://docs.mongodb.com/ http://json.org/json-pt.html
    https://angular.io/docs https://docs.github.com/en/github/writing-on-github/getting-started-with-
    writing-and-formattin g-on-github/basic-writing-and-formatting-syntax
    https://docs.pipz.com/central-de-ajuda/learning-center/guia-basico-de-markdown#open
    https://devicon.dev/
    https://github.com/florinpop17/app-ideas?fbclid=IwAR13-41FDaFDXRGKlxz_evGxQSgBKx6
    xBrJPacJ9x3VI9TqU6OIson6I1UQ
    https://m.lightinthebox.com/pt/p/homens-colete-de-terno-colete-festa-festival-casual-vintage-
    formais-solido-comum-1-botao-delgado-misto-de-algodao-masculino-terno-preto-decote-v_p
    8707641.html?prm=1-2.3.5.11#header_anchor
    https://app.diagrams.net/
    https://www.inovacaotecnologica.com.br/
    https://br.financas.yahoo.com/noticias/por-que-os-telescopios-nos-mostram-sempre-o-pa
    ssado-121742304.html
    https://bashrcgenerator.com/
    http://www.snb.org.br/portal/ —docs—
    https://gradle.org/install/#helpful-information
    https://doc.rust-lang.org/book/ch01-00-getting-started.html
    https://dev.to/envoy_/150-badges-for-github-pnkhttps://emojipedia.org/search/?q=bag
    https://picrew.me/image_maker/338224
    https://jjeanjacques10.medium.com/tornando-seu-c%C3%B3digo-mais-solid-fabc10ce7ca 3
    https://www.devmedia.com.br/dao-pattern-persistencia-de-dados-utilizando-o-padrao-da
    o/30999
    https://www.lingohut.com/en/v773488/german-lessons-meeting-someone
    https://uspdigital.usp.br/jupiterweb/listarGradeCurricular?codcg=17&codcur=17050&cod
    hab=0&tipo=N
    https://uspdigital.usp.br/jupiterweb/listarGradeCurricular?codcg=18&codcur=18070&cod
    hab=0&tipo=N
    https://www.collinsdictionary.com/pt/ https://alternativeto.net/ —githubs—
    https://docs.pipz.com/central-de-ajuda/learning-center/guia-basico-de-markdown#open
    https://github.com/anuraghazra/github-readme-stats
    https://github.com/rafaballerini/rafaballerini
    https://github.com/rafaballerini/PerfilGithub —ms— https://docs.microsoft.com/pt-br/ef/
    https://dotnet.microsoft.com/en-us/apps/aspnet/mvc
    https://docs.microsoft.com/pt-br/azure/quantum/overview-what-is-qsharp-and-qdk —eh—
    https://www.internic.net/ https://registro.br/tecnologia/ferramentas/whois/ https://archive.org/
    https://web.archive.org/web/20000601000000*/
    https://www.comclick.com.br/kit-04-parafusos-da-base/pino-de-engate-fab30016124-tv-lg-
    32lp560h-43lx541h-55lf6500-
    70uf7300?parceiro=4159&gclid=CjwKCAjw_MqgBhAGEiwAnYOAejYoxnbNKWwF6NjiLi4ngHE
    WLPaZNQlMe9wBuvNwHlyUGtfsxL7_JxoCD10QAvD_BwE
    https://www.helpnetsecurity.com/2023/03/16/pen-200-penetration-testing-with-kali-linux-2023/
    https://brasilescola.uol.com.br/amp/quimica/modelo-atomico-de-schrodinger.htm
    https://developer.mozilla.org/en-US/docs/Glossary/REST
    https://lib-rtdqugfdlnslmtlewk6qavff.b-ok.africa/
    https://blog.daryus.com.br/certificacoes-de-ciberseguranca-por-onde-comecar-2/
    https://studio.polotno.com/
    https://www.4devs.com.br/gerador_de_cpf
    https://tekeye.uk/programming/how-to-create-an-ide
    https://rogerdudler.github.io/git-
    guide/index.pt_BR.html?fbclid=IwAR20Ru9KYWT3c_NpmimILdrit5KohlWKXXzHRjLgmw31xQO
    PrlL7j0vu_9M
    https://brasil.uxdesign.cc/10-heur%C3%ADsticas-de-nielsen-para-o-design-de-interface-
    58d782821840
    https://medium.com/programadores-ajudando-programadores/a-hist%C3%B3ria-do-unix-o-pai-
    dos-sistemas-operacionais-modernos-2795d0fd564b
    https://qntm.org/clean
    https://www.autodesk.com/certification/learn/course/autocad-drawing-design-drafting-
    professional/6kkL8weszFye7RM4aqSwL9
    https://codigo35.com/2016/01/02/microsservicos/
    https://www.frameworkdemoiselle.gov.br/wiki7e79.html?p_p_id=54_INSTANCE_22yPPz0LwGH
    G&p_p_lifecycle=0&p_p_state=normal&p_p_mode=view&p_p_col_id=column-
    1&p_p_col_pos=1&p_p_col_count=2&_54_INSTANCE_22yPPz0LwGHG_struts_action=%2Fwiki_display%2Fview&_54_INSTANCE_22yPPz0LwGHG_nodeName=Main&_54_INSTANCE_22
    yPPz0LwGHG_title=Conven%C3%A7%C3%A3o%20desenvolvedor%2FConven%C3%A7%C3
    %A3o%20c%C3%B3digo%2FComent%C3%A1rios#:~:text=Coment%C3%A1rios%20de%20do
    cumenta%C3%A7%C3%A3o%20(conhecidos%20como,detalhes%20um%20c%C3%B3digo%2
    0em%20particular.
    https://martinfowler.com/articles/microservices.html
    https://www.computerenhance.com/p/clean-code-horrible-performance
    https://docs.pipz.com/central-de-ajuda/learning-center/guia-basico-de-markdown#open
    https://www.cin.ufpe.br/~if114/Monografias/Definicao%20de%20LPs/doc3.htm?fbclid=IwAR19j6
    T8sobna5FBOy7J7Fa7Oc33OTOgW0_BYNOSUd-vA6Osvd7nT_uN3Tk
    https://cursojavanow.com.br/o-pacote-javax-parte-1/
    https://quantum-computing.ibm.com/composer/docs/iqx/first-circuit
    https://quantum-
    computing.ibm.com/composer/files/3123102f464f4abaec600d2f7d7afc2f35d711262f7f4ec3d106
    db4256269bc5
    https://silq.ethz.ch/
    https://spring.io/
    https://phys.org/news/2023-03-scientists-door-quantum.amp
    https://scitechdaily.com/quantum-breakthrough-a-new-understanding-of-quantum-turbulence/
    https://debian-handbook.info/browse/pt-BR/stable/
    https://revistaamazonia.com.br/estudo-feito-por-brasileiros-e-chineses-compatibiliza-dois-
    principios-fundamentais-da-teoria-quantica/?amp=1
    https://legendei.top/page/12/?s=blue+bloods
    https://www.hackster.io/news/researchers-spot-silicon-level-hardware-trojans-in-chips-release-
    their-algorithm-for-all-to-try-ba00bbd56248.amp
    https://in-kotlin.com/design-patterns/
    https://www.debian.org/releases/sarge/ia64/pr01.html.pt_BR
    https://www.mestresdomandarim.com.br/fundamentos-do-
    mandarim/?fbclid=IwAR2Kr_KegJFJLfB7JrYMDTM2lq891ivPV3bGSkaz7aaeryDxhlvyQYKBXY
    U_aem_Ac8eRqBn1xBO3Tmv4Ww53XP5vPF0bHVZ56ddeY81v_yvcN6OkRVouC7EOj2IA8HL
    GYeL0Ob3CMd0XQHyaEeuDWFWqpfwjCzL8gbxAcVscv_QpxssJQNj11ukH0vx31qvzRuBvDn
    K2fEAgBUDPG3Q109A
    https://dev.to/github/leia-me-ou-te-devoro-como-escrever-um-bom-readme-5hl4
    https://phys.org/news/2023-03-scalable-programmable-quantum-phononic-processor.amp
    https://www.itau.com.br/contas/conta-corrente
    https://learn.microsoft.com/pt-br/dotnet/csharp/tour-of-csharp/
    https://www.jamesedition.com/real_estate/fowey-united-kingdom/the-old-sawmills-11430498
    https://docs.oracle.com/javase/8/docs/api/java/util/concurrent/atomic/AtomicLong.html
    https://chat.openai.com/chat
    https://www.guiadojava.com.br/2021/04/java-records.html
    https://learn.microsoft.com/pt-br/training/modules/qsharp-create-first-quantum-development-kit/
    https://www.dcce.ibilce.unesp.br/~aleardo/cursos/fsc/cap12.php
    https://learning.postman.com/docs/getting-started/introduction/
    https://netbeans.apache.org/kb/docs/java-ee_pt_BR.html#:~:text=Weblogs-
    https://www.ibm.com/topics/quantum-computinghttps://linuxhint.com/installing_gradle_ubuntu/
    https://builtwith.com/
    https://portal.if.usp.br/fnc/pt-br/p%C3%A1gina-de-livro/fus%C3%A3o
    https://dev.to/jon_snow789/9-hidden-websites-for-programmers-278f
    https://javaee.github.io/
    https://www.anhangueraferramentas.com.br/produto/carrinho-de-mao-extraforte-com-cacamba-
    metalica-65-litros-77714-435-tramontina-
    96447?utm_source=google&utm_medium=cpc&utm_campaign=https://www.anhangueraferram
    entas.com.br/produto/carrinho-de-mao-extraforte-com-cacamba-metalica-65-litros-77714-435-
    tramontina-
    96447?utm_source=google&utm_medium=cpc&utm_campaign=merchant&gclid=Cj0KCQjwz6S
    hBhCMARIsAH9A0qU1kdIFIvmYrVqL1Fbbe1fQCoBzQzwa-
    BaqV_90zxvJ6C_ws7s0s48aAgQMEALw_wcB
    https://www.madeiramadeira.com.br/cama-solteiro-monaco-tcil-moveis-728751.html?origem=pla-728751&utm_source=google&utm_medium=cpc&utm_content=camas-5081&utm_term=&utm_id=19794695260&gclid=Cj0KCQjwla-hBhD7ARIsAM9tQKt49RRGwB0JeENcpXYxFLkAjKsgw08ucb3PP2j87jQ6gmEmp3MRnZ8aAj7iEALw_wcB

    ----- 17/7/23 -----
    https://pro.clear.com.br/#home
    https://trade.metatrader5.com/terminal
    https://www.office.com/?flight=unauthrefresh&auth=1
    https://www.udemy.com/
    https://bash-prompt-generator.org/
    https://github.com/
    https://www.youtube.com/watch?v=N3K8PjFOhy4&list=PLGxZ4Rq3BOBrgumpzz-l8kFMw2DLERdxi
    https://www.youtube.com/watch?v=rejqIp7ExXA&list=PLbIBj8vQhvm0Yfx1JMCEOM-BB-WOCOUE1
    https://pt.slideshare.net/loianeg/exercicios-vetores-arrays-estruturas-de-dados-e-algoritmos-com-java
    https://medium.com/collabcode/criando-um-web-service-base-no-spring-boot-com-kotlin-962a51317d63
    https://www.vintepila.com.br/
    https://www.99freelas.com.br/
    https://github.com/chinnonsantos/clp-siemens-s7-1200
    https://learn-xpro.mit.edu/systems-engineering?utm_medium=paidsocial&utm_source=facebook&utm_campaign=SysEngx&utm_content=fb-b&hsa_acc=1299971533379342&hsa_cam=23853892983590504&hsa_grp=23853892983580504&hsa_ad=23853892983600504&hsa_src=fb&hsa_net=facebook&hsa_ver=3&fbclid=IwAR1bhixwuRxKMUSUmjjWfz5ZsjNW5yt0VsJwTi_2lyjT8bY7pmerP_kt0RI_aem_AdXVnAiGMTnEzXZgMdbWH7FdEUegWCy7SIWOcM1GPmBq-p8hpqyQX_Ie5uZFtbjH1_pdPRYU-ULmh5X1HIQQSvAA
    https://pt.m.wikipedia.org/wiki/Propuls%C3%A3o_Alcubierre#:~:text=A%20Propuls%C3%A3o%20de%20Alcubierre%20(ou,Estrelas%20ou%20Caminho%20das%20Estrelas.
    https://www.casadaergonomia.com.br/dicas-ergonomia-no-escritorio/
    https://devdocs.io/
    https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Guide/Regular_expressions
    Certificados
    https://help.eclipse.org/2023-06/index.jsp
    https://uspdigital.usp.br/jupiterweb/listarGradeCurricular?codcg=27&codcur=27421&codhab=101&tipo=N&print=true
    https://uspdigital.usp.br/jupiterweb/listarGradeCurricular?codcg=97&codcur=97001&codhab=0&tipo=N
    https://bugzilla.readthedocs.io/en/5.0.4/using/index.html?fbclid=IwAR2gEoVVwdKTtzbCC6-zuZT8oYJQjth9fahG94iiqlHXIdXTvjIEv_3Cs3M
    https://www.se.com/br/pt/download/document/Machine_Expert_Basic_V1_2_SP1/
    https://quantumai.google/

    ----- 7/8/23 -----
    https://trade.metatrader5.com/terminal
    https://www.office.com/?flight=unauthrefresh&auth=1
    https://www.udemy.com/
    https://redis.io/docs/
    https://www.json.org/json-en.html
    https://github.com/
    https://github.com/acenelio/ms-course
    https://devdocs.io/
    https://quantumai.google/cirq/start/start
    https://developer.mozilla.org/pt-BR/
    https://help.codesys.com/webapp/documentation;product=LibDevSummary
    https://www.altus.com.br/base-conhecimento/categoria/19/detalhe/275/nexto-xpress---primeiros-passos-
    https://www.altus.com.br/produto/11/clp-duo
    https://epson.com.br/Suporte/Rob%C3%B4s/Software/Epson-RC%2B-7-0/s/SPT_R12N793031
    https://www.cambridgeenglish.org/exams-and-tests/cefr/
    https://www.intel.com/content/www/us/en/homepage.html
    Trader
    https://www.tabnews.com.br/VictorManhani/os-principais-fundamentos-da-programacao
    https://dev.to/ocodista/a-magia-do-event-loop-in1
    https://www.interviewbit.com/blog/html-projects/?amp=1
    https://www.interviewbit.com/blog/c-sharp-projects/?amp=1

    -- Trader
    https://www.google.com/amp/s/www.infomoney.com.br/guias/lci-lca/amp/
    https://www.google.com/amp/s/www.infomoney.com.br/guias/cdb/amp/
    https://www.bcb.gov.br/controleinflacao/taxaselic

    https://lapumia.org/
    https://comandofilmes3.com/
    https://lib-ubuwfgpjfno267vfpot4wqce.booksc.eu/
    https://www.mideastore.com.br/panela-de-pressao-eletrica-6-l-digital-preta-midea/p
    https://askubuntu.com/questions/282951/how-to-completely-uninstall-eclipse
    https://gauchazh.clicrbs.com.br/donna/fitness/amp/2023/08/10-exercicios-para-emagrecer-que-voce-pode-fazer-em-casa-clksjhrwp009501790svkqq5e.html
    https://diariomomento.com.br/web-stories/equipamentos-essenciais-para-treinar-em-casa/
    https://pobreflix.biz/episodios/assistir-the-expanse-1x2-online/

    ------

    UI / UX
    Mais alguns links:
    https://www.maisaprendizagem.com.br/como-ler-livros-didaticos-o-metodo-sq3r-vale-a-pena/
    3
    https://pt.wikipedia.org/wiki/T%C3%B3pico_frasal
    Estudar um pouco sobre linguística (acho que o texto se refere a esta área) também ajuda
    no processo de aprendizagem, porque se entende o que de fato é um texto.
    2
    Realizar só a leitura de determinado material não é a melhor maneira de se estudar
    corretamente. Recomendo ver este vídeo: https://www.youtube.com/watch?v=i_hdffLUdPA
    1
    Sites para buscar inspiração!
    Collect UI: http://collectui.com/
    Best Website: https://bestwebsite.gallery/
    Awwwards: https://www.awwwards.com/
    Themeforest: https://themeforest.net/
    OnePage Love: https://onepagelove.com/
    Call To Idea: http://www.calltoidea.com/

21/09/23

web
https://developer.mozilla.org/pt-BR/
https://jwt.io/
https://blog.saninternet.com/hsts#:~:text=O%20que%20%C3%A9%20HSTS%20(HTTP%20Strict%20Transport%20Security)%3F&text=O%20termo%20significa%20Seguran%C3%A7a%20Restrita,uma%20p%C3%A1gina%20executada%20em%20HTTPS.

Microsoft
https://learn.microsoft.com/pt-br/dotnet/csharp/language-reference/builtin-types/numeric-conversions
https://learn.microsoft.com/pt-br/dotnet/core/tools/?tabs=netcore2x

https://www.office.com/?flight=unauthrefresh&auth=1
https://www.udemy.com/
https://redis.io/docs/
https://github.com/
https://learn.microsoft.com/en-us/dotnet/csharp/fundamentals/coding-style/coding-conventions
https://uk.investing.com/
https://www.tabnews.com.br/VictorManhani/os-principais-fundamentos-da-programacao
https://web.autocad.com/acad/me
https://www.interviewbit.com/blog/html-projects/?amp=1
https://www.interviewbit.com/blog/c-sharp-projects/?amp=1
https://freelancer.com.br/
https://www.manualdocarro.com.br/
https://www.yamaha-motor.com.br/manuaisecatalogos
https://www.blender.org/
https://wiki.freecad.org/Getting_started
https://developer.mozilla.org/pt-BR/docs/WebAssembly

https://redis.io/docs/
https://www.yamaha-motor.com.br/manuaisecatalogos
https://www.manualdocarro.com.br/
https://www.interviewbit.com/blog/c-sharp-projects/?amp=1
https://www.interviewbit.com/blog/html-projects/?amp=1
https://web.autocad.com/acad/me
https://learn.microsoft.com/en-us/dotnet/csharp/fundamentals/coding-style/coding-conventions
https://olhardigital.com.br/2023/08/28/ciencia-e-espaco/yin-yang-quantico-visto-em-experimento-revolucionario/amp/
https://itforum.com.br/colunas/a-magia-da-computacao-quantica-e-sua-aplicacao-pratica-na-educacao/
https://universoracionalista.org/um-estado-entre-o-liquido-e-o-solido-pode-ter-sido-encontrado/
https://futurorelativo.com.br/manipulando-particulas-fisicos-criam/
https://olhardigital.com.br/2023/08/30/ciencia-e-espaco/novo-robo-minusculo-muda-de-forma-e-cabe-em-espacos-apertados/amp/
https://olhardigital.com.br/2023/08/30/ciencia-e-espaco/robo-brasileiro-pode-mudar-agricultura-em-grande-escala/amp/
https://blog.bianch.com.br/dicas-para-estudar-navegacao-aerea/
https://digitalks.com.br/noticias/os-segredos-do-league-of-legends-para-atrair-clientes-de-maneira-organica/
https://olhardigital.com.br/2023/09/03/dicas-e-tutoriais/o-que-e-um-software-de-limpeza-de-registro-e-qual-o-melhor-para-voce/amp/
https://visme.co/blog/pt-br/programa-de-animacao/
https://ficatranquilo.com.br/
https://www.revistabula.com/32593-2-manual-pessimista-para-viver-a-vida-segundo-akira-kurosawa/
https://pt.m.wikipedia.org/wiki/M%C3%A1quina_de_Antic%C3%ADtera
https://www.tudocelular.com/curiosidade/noticias/n211310/site-do-google-fonts-ganha-novo-design-dando-bom-exemplo-do-material-3-na-web.html
https://support.google.com/admanager/answer/12270545?hl=pt
https://universoracionalista.org/cientistas-desenvolveram-uma-maneira-de-saber-se-o-chatgpt-se-torna-consciente-de-si-mesmo/
https://sempreupdate.com.br/?noamp=mobile&amp=1
https://semtorrent.com/serie/ted-lasso-2-temporada/
https://www.anitube.cx/video/276730
https://animesonline.nz/animes/4-cut-hero/
https://animefire.vip/animes/street-fighter-ii-v-dublado/15
https://lib-ubuwfgpjfno267vfpot4wqce.booksc.eu/
https://www.google.com/search?q=deusa+solar&oq=deusa+solar&gs_lcrp=EgZjaHJvbWUyBggAEEUYOTIKCAEQABixAxiABDIMCAIQABhDGLEDGIoFMg0IAxAuGIMBGLEDGIAEMgoIBBAAGLEDGIAEMgcIBRAuGIAEMg0IBhAuGIMBGLEDGIAEMgcIBxAuGIAEMgoICBAuGLEDGIAEMgcICRAuGIAEMgoIChAAGLEDGIAEMgoICxAuGLEDGIAEMgcIDBAAGIAEMg0IDRAuGIMBGLEDGIAEMg0IDhAuGIMBGLEDGIAE0gEIMTYzM2owajmoAgCwAgA&client=ms-android-motorola-rvo3&sourceid=chrome-mobile&ie=UTF-8
https://www.wappalyzer.com/
https://betterprogramming.pub/5-vs-code-extensions-for-bash-scripting-da94a6915598
