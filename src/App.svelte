<script>
  import  alghero1  from "./lib/alghero1.png";
  import  alghero2  from "./lib/alghero2.png";
  import  alghero3  from "./lib/alghero3.png";
  import  tsunami1  from "./lib/tsunami1.png";

  const year = 2024;
  const date = "11 agosto";

  let navItems = [
      { name: 'Home', href: '#home' },
      { name: 'Storia', href: '#storia' },
      { name: 'Preparativi', href: '#preparativi' },
      { name: 'Profezie', href: '#profezie' },
      { name: 'Contatti', href: '#contatti' }
  ];
</script>

<style>
  /* Resetta margini e padding globalmente */
  * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
  }

  /* Assicura che il body non abbia margini o padding */
  body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      overflow-x: hidden; /* Evita lo scroll orizzontale */
  }

  header {
      background-color: #005f73;
      color: white;
      padding: 20px;
      text-align: center;
      width: 100%; /* Assicura che il header si estenda per tutta la larghezza */
  }

  nav {
      display: flex;
      justify-content: center;
      background-color: #0a9396;
      flex-wrap: wrap; /* Permette agli elementi di andare a capo se lo schermo è stretto */
      width: 100%; /* Assicura che la navbar si estenda per tutta la larghezza */
  }

  nav a {
      color: white;
      padding: 14px 20px;
      text-decoration: none;
      text-align: center;
      flex: 1 1 auto; /* Assicura che i link nella navbar si adattino alla larghezza */
  }

  nav a:hover {
      background-color: #94d2bd;
      color: #005f73;
  }

  section {
      padding: 20px;
      margin: 20px;
      max-width: 100%; /* Evita che le sezioni eccedano la larghezza dello schermo */
  }

  footer {
      background-color: #0a9396;
      color: white;
      text-align: center;
      padding: 20px;
      position: fixed;
      width: 100%;
      bottom: 0;
      left: 0;
      box-sizing: border-box;
      margin: 0;
  }
</style>



<header>
  <h1>Il Mistero dello Tsunami di Alghero</h1>
</header>

<nav>
  {#each navItems as item}
      <a href={item.href}>{item.name}</a>
  {/each}
</nav>

<img src="{alghero1}" alt="" style="width: 100%; margin-top:20px"> 

<section id="home">
  <h2>Benvenuti</h2>
  <p>Benvenuti sul sito dedicato allo straordinario fenomeno dello tsunami che, con una puntualità quasi sovrannaturale, colpisce le coste di Alghero ogni 20 anni, l'{date}. Mentre ci avviciniamo al prossimo evento previsto per l'{date} 2024, la città e il mondo intero si preparano a vivere nuovamente un'esperienza unica e inspiegabile. Questo sito offre una panoramica completa sulla storia, i preparativi, le profezie e i misteri legati a questo evento che ha segnato e continua a segnare la storia di Alghero.</p>
</section>

<img src="{alghero2}" alt="" style="width: 100%; margin-top:20px"> 


<section id="storia">
  <h2>Storia</h2>
  <p>Il fenomeno dello tsunami che colpisce Alghero ogni 20 anni l'{date} è uno degli eventi naturali più enigmatici e affascinanti della storia moderna. La prima testimonianza di questo evento risale al {year - 220}, quando un'improvvisa e devastante onda sommerse parte della città, cogliendo gli abitanti completamente di sorpresa. Da allora, ogni 20 anni esatti, l'{date}, le acque del mare si ritirano bruscamente per poi scatenare una potente onda che colpisce la costa con forza distruttiva.</p>
  <p>Le cronache dell'epoca descrivono l'evento del {year - 220} come un giorno di terrore e caos. Gli abitanti, che mai avevano sperimentato nulla di simile, interpretarono il fenomeno come un segno divino, un castigo per peccati sconosciuti. Nei decenni successivi, il fenomeno si ripeté con precisione matematica, ogni volta portando con sé non solo devastazione ma anche un'aura di mistero e paura. Gli storici locali iniziarono a raccogliere testimonianze, documentando ogni dettaglio di questi eventi ciclici, e presto la leggenda dello tsunami di Alghero divenne parte integrante del folklore locale.</p>
  <p>Nel {year - 200}, il fenomeno si ripeté, con modalità quasi identiche, confermando la ciclicità dell'evento. Le testimonianze di quel periodo parlano di una giornata di sole, come tante altre estati ad Alghero, che venne improvvisamente interrotta dal ritiro delle acque. I pescatori, presi dal panico, cercarono di avvertire i compaesani, ma l'onda colpì prima che molti potessero mettersi in salvo. Fu un disastro naturale senza precedenti per la cittadina sarda, eppure, anche in mezzo alla tragedia, iniziò a diffondersi una strana consapevolezza: quel giorno sarebbe tornato.</p>
  <p>Eventi simili si verificarono anche negli anni successivi, nel  {year - 180}, {year - 160}, {year - 140}, e così via, fino ai giorni nostri. Ogni evento ha portato con sé non solo distruzione, ma anche una serie di stranezze e coincidenze che hanno alimentato il mistero. Ad esempio, nel {year - 100}, lo tsunami fu preceduto da una settimana di strani fenomeni meteorologici, con temporali violenti che sembravano concentrarsi solo sulla zona costiera di Alghero. Nel {year - 60}, invece, si racconta di un'intera colonia di gabbiani che abbandonò improvvisamente la costa il giorno prima dello tsunami, un comportamento mai osservato prima.</p>
  <p>Nel {year - 20}, l'ultimo evento registrato, le autorità erano finalmente preparate. Grazie ai progressi della tecnologia e della comunicazione, fu possibile evacuare la maggior parte degli abitanti prima che l'onda colpisse, salvando così innumerevoli vite. Tuttavia, nonostante le misure preventive, il mistero dello tsunami di Alghero rimase irrisolto. Gli scienziati che studiarono l'evento non riuscirono a trovare una spiegazione soddisfacente per la regolarità e la potenza dell'onda, e così il fenomeno continuò a sfuggire alla comprensione umana.</p>
</section>

<img src="{tsunami1}" alt="" style="width: 100%; margin-top:20px"> 

<section id="preparativi">
  <h2>Preparativi per l'{date} {year}</h2>
  <p>I preparativi per il prossimo tsunami dell'{date} {year} sono già in pieno svolgimento. Ogni 20 anni, la città di Alghero si prepara in modo meticoloso per affrontare il fenomeno, e quest'anno non è diverso. Le autorità locali hanno implementato una serie di misure per garantire la sicurezza dei cittadini e ridurre al minimo i danni.</p>
  <p>Uno degli aspetti più affascinanti dei preparativi è l'antica tradizione di portare gli asini bianchi dall'Isola dell'Asinara. Questo rito risale a secoli fa e ha un significato profondo nella cultura di Alghero. Gli asini bianchi, simbolo di purezza e resistenza, vengono trasportati con grande attenzione e rispetto, e il loro arrivo è accompagnato da una serie di cerimonie e celebrazioni.</p>
  <p>Gli asini vengono portati a Alghero per servire come animali da compagnia e per aiutare nella preparazione delle aree di evacuazione e di soccorso. Questi animali, noti per la loro calma e il loro spirito resistente, giocano un ruolo simbolico nell'aiutare la comunità a mantenere la speranza e la tranquillità durante i periodi di crisi.</p>
  <p>Inoltre, la città sta attuando piani di evacuazione dettagliati, installando barriere protettive e migliorando le infrastrutture di emergenza. I residenti vengono istruiti sui protocolli di sicurezza e sui piani di evacuazione, e le esercitazioni di preparazione sono condotte regolarmente per assicurarsi che tutti sappiano come reagire in caso di emergenza.</p>
  <p>Nonostante le paure, però, c'è anche una strana forma di attesa e curiosità che pervade la città. Alghero ha imparato a convivere con questo fenomeno, e in un certo senso, lo tsunami è diventato parte integrante dell'identità cittadina. Ogni 20 anni, l'{date}, la città si ritrova a vivere un momento di unione e solidarietà, mentre tutti attendono, col fiato sospeso, che il mare riveli ancora una volta il suo mistero.</p>
</section>

<img src="{alghero3}" alt="" style="width: 100%; margin-top:20px"> 

<section id="profezie">
  <h2>Profezie e Leggende</h2>
  <p>Il mistero dello tsunami di Alghero non è solo un evento naturale, ma anche un fenomeno che ha ispirato leggende e profezie nel corso dei secoli. Una delle storie più antiche racconta di una maledizione lanciata da un antico sacerdote punico, il quale, in punto di morte e rinchiuso in un'antica torre sulle coste di Alghero, avrebbe giurato vendetta, promettendo di far risalire il mare ogni 20 anni per punire gli abitanti.</p>
  <p>Un'altra leggenda parla di un antico tempio sottomarino, costruito da una civiltà perduta e situato proprio al largo di Alghero. Questo tempio, secondo i racconti, conterrebbe un'enorme fonte di energia, capace di scatenare onde di potenza inimmaginabile quando disturbata da eventi sismici o da influenze esterne. Si narra che, ogni 20 anni, un'allineamento planetario provochi una vibrazione che attiva questa energia, causando il terribile tsunami.</p>
  <p>Oltre alle leggende, ci sono anche profezie più recenti che alimentano la paura e la curiosità attorno allo tsunami dell'{date}. Alcuni veggenti e mistici hanno affermato di aver avuto visioni di Alghero sommersa da un mare in tempesta, e hanno avvertito che il prossimo evento, quello del {year}, potrebbe essere il più devastante di tutti. Queste profezie, sebbene prive di fondamento scientifico, hanno contribuito ad alimentare l'aura di mistero che circonda l'evento.</p>
  <p>Non mancano nemmeno le teorie complottistiche, che vedono nello tsunami una prova di esperimenti segreti condotti da potenze mondiali o da organizzazioni sconosciute. Alcuni credono che il fenomeno sia in realtà il risultato di test su nuove armi o tecnologie in grado di manipolare il clima e le forze naturali. Queste teorie, pur essendo considerate fantasiose e prive di prove, continuano a circolare e a trovare adepti, soprattutto online.</p>
  <p>Indipendentemente dalla veridicità di queste storie, ciò che è certo è che lo tsunami dell'{date} è ormai parte integrante dell'identità di Alghero. Ogni 20 anni, la città si trova ad affrontare non solo la forza della natura, ma anche le sue paure più profonde, alimentate da secoli di racconti e credenze. Il prossimo {date} {year}, Alghero si prepara nuovamente ad affrontare il suo destino, con la speranza che, questa volta, il mare risparmi la città dalla sua furia.</p>
</section>

<section id="contatti" style="margin-bottom: 100px;">
  <h2>Contatti</h2>
  <p>Per ulteriori informazioni sul fenomeno dello tsunami di Alghero e sui preparativi in corso per l'evento del {year}, è possibile contattare il Comune di Alghero o la Protezione Civile locale. Siamo qui per rispondere a tutte le vostre domande e per fornirvi le indicazioni necessarie per affrontare al meglio questa situazione straordinaria.</p>
</section>

<footer>
  <p>&copy; {year} Il Mistero dello Tsunami di Alghero. Tutti i diritti riservati.</p>
</footer>
