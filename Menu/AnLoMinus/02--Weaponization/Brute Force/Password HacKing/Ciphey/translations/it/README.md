<p align="center">
Traduzioni <br>
<a href=https://github.com/Ciphey/Ciphey/tree/master/translations/de/README.md>๐ฉ๐ช DE   </a>
<a href=https://github.com/Ciphey/Ciphey/tree/master/README.md>๐ฌ๐ง EN   </a>
<a href=https://github.com/Ciphey/Ciphey/tree/master/translations/fr/README.md>๐ซ๐ท FR   </a>
<a href=https://github.com/Ciphey/Ciphey/tree/master/translations/hu/README.md>๐ญ๐บ HU   </a>
<a href=https://github.com/Ciphey/Ciphey/tree/master/translations/id/README.md>๐ฎ๐ฉ ID   </a>
<a href=https://github.com/Ciphey/Ciphey/tree/master/translations/it/README.md>๐ฎ๐น IT   </a>
<a href=https://github.com/Ciphey/Ciphey/tree/master/translations/nl/README.md>๐ณ๐ฑ NL   </a>
<a href=https://github.com/Ciphey/Ciphey/tree/master/translations/pt-br/README.md>๐ง๐ท PT-BR   </a>
<a href=https://github.com/Ciphey/Ciphey/tree/master/translations/ru/README.md>๐ท๐บ RU   </a>
<a href=https://github.com/Ciphey/Ciphey/tree/master/translations/zh/README.md>๐จ๐ณ ZH   </a>
 <br><br>
โก๏ธ
<a href="https://github.com/Ciphey/Ciphey/wiki">Documentazione</a> |
<a href="https://discord.ciphey.online">Discord</a> |
 <a href="https://github.com/Ciphey/Ciphey/wiki/Installation">Guida all'installazione</a>
 โฌ๏ธ

<br>
  <img src="https://github.com/Ciphey/Ciphey/raw/master/Pictures_for_README/binoculars.png" alt="Ciphey">
</p>

<p align="center">
  <img alt="GitHub commit activity" src="https://img.shields.io/github/commit-activity/m/ciphey/ciphey">
<img src="https://pepy.tech/badge/ciphey">
 <img src="https://pepy.tech/badge/ciphey/month">
  <a href="https://discord.gg/wM3scnc"><img alt="Discord" src="https://img.shields.io/discord/728245678895136898"></a>
<a href="https://pypi.org/project/ciphey/"><img src="https://img.shields.io/pypi/v/ciphey.svg"></a>
  <img src="https://img.shields.io/badge/License-MIT-yellow.svg" alt="Ciphey">

  <img src="https://github.com/brandonskerritt/Ciphey/workflows/Python%20application/badge.svg?branch=master" alt="Ciphey">
<br>
Ciphey รจ uno strumento completamente automatizzato per la decrittazione/decodificazione/cracking che usa la processazione del linguaggio naturale e l'intelligienza  artificiale, con un po' di senso comune.
</p>
<hr>

## [Installation Guide](https://github.com/Ciphey/Ciphey/wiki/Installation)

| <p align="center"><a href="https://pypi.org/project/ciphey">๐ Python | <p align="center"><a href="https://hub.docker.com/r/remnux/ciphey">๐ Docker (Universal) | <p align="center"><a href="https://ports.macports.org/port/ciphey/summary">๐ MacPorts (macOS)| <p align="center"><a href="https://formulae.brew.sh/formula/ciphey">๐บ Homebrew (macOS/Linux) |
| --------------------------------------------------------------------- | --------------------------------------------------------------------------------- | --------------------------------------------------------------------------------- |--------------------------------------------------------------------------------- |
| <p align="center"><img src="https://github.com/Ciphey/Ciphey/raw/master/Pictures_for_README/python.png" /></p> | <p align="center"><img src="https://github.com/Ciphey/Ciphey/raw/master/Pictures_for_README/docker.png" /></p> | <p align="center"><img src="https://github.com/Ciphey/Ciphey/raw/master/Pictures_for_README/macports.png" /></p> | <p align="center"><img src="https://github.com/Ciphey/Ciphey/raw/master/Pictures_for_README/homebrew.png" /></p> |
| `python3 -m pip install ciphey --upgrade` | `docker run -it --rm remnux/ciphey` | `sudo port install ciphey` | `brew install ciphey` |

| Linux                                                                                                                   | Mac OS                                                                                                                     | Windows                                                                                                                   |
| ----------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------- |
| ![GitHub Workflow Status](https://img.shields.io/github/workflow/status/ciphey/ciphey/Python%20application?label=Linux) | ![GitHub Workflow Status](https://img.shields.io/github/workflow/status/ciphey/ciphey/Python%20application?label=Mac%20OS) | ![GitHub Workflow Status](https://img.shields.io/github/workflow/status/ciphey/ciphey/Python%20application?label=Windows) |

<hr>

# ๐ค Cos'รจ?

Inserisci del testo crittografato, ottieni il testo decrittografato indietro.

> "Che tipo di crittografia?"

Questo รจ il punto. Non lo sai, sai solo che forse รจ criptato. Ciphey lo scoprirร? per te.

Ciphey puรฒ risolvere la maggior parte delle cose in 3 secondi o meno.

<p align="center" href="https://asciinema.org/a/336257">
  <img src="https://github.com/Ciphey/Ciphey/raw/master/Pictures_for_README/index.gif" alt="Ciphey demo">
</p>

Ciphey mira ad essere uno strumento per automatizzare molte decodifiche come le codifiche multiple di base, i classici ciphers, gli hash o la crittografia piรน avanzata.

Se non ne sai molto di crittografia, o vuoi controllare rapidamente il testo cifrato prima di lavorarci da solo, Ciphey fa per te.

**La parte tecnica.** Ciphey usa un modulo di intelligenza artificiale costruito su misura (_AuSearch_) con un'interfaccia di rilevamento dei _Ciphers_ per approssimare ciรฒ con cui qualcosa รจ criptato. Successivamente usa un'elaborazione del linguaggio naturale personalizzato e personalizzabile _Language Checker Interface_, in grado di rilevare quando il testo dato diventa in chiaro.

Nessuna rete neurale o IA ripiene di funzioni inutili qua. Usiamo solo ciรฒ che e veloce e minimal.

E questa รจ solo la punta dell'iceberg. Per l'intera spiegazione tecnica cntrolla la nostra [documentazione](https://github.com/Ciphey/Ciphey/wiki).

# โจ Features

- **50+ tipi di crittografia supportati** come gli encodings (binary, base64) e tipi di crittografia normale come il cifrario di cesare, key XOR ripetuta e molto altro. **[Per la lista completa, clicca qui](https://github.com/Ciphey/Ciphey/wiki/Supported-Ciphers)**
- **Intelligenza artificiale costruita su misura con la ricerca aumentata (AuSearch) per rispondere alla domanda "quale algoritmo per la crittografia รจ stato usato?"** Il risultato รจ che le decifrazioni richiedono meno di 3 secondi.
- **Modulo di elaborazione del linguaggio naturale costruito su misura** Ciphey puรฒ determinare se qualcosa รจ in chiaro o meno. Se quel testo in chiaro รจ JSON, una flag di una CTF, o l'inglese, Ciphey puรฒ ottenerlo in un paio di millisecondi.
- **Supporto multilingue** al momento, solo tedesco e inglese (con varianti AU, UK, CAN, USA).
- **Supporta le crittografie e gli hash** che le alternative come CyberChef Magic non hanno.
- **[core in C++](https://github.com/Ciphey/CipheyCore)** Rapidissimo.

# ๐ญ Ciphey vs CyberChef

## ๐ Base64 codificato 42 volte

<table>
  <tr>
  <th>Nome</th>
    <th>โก Ciphey โก </th>
    <th>๐ข CyberChef ๐ข</th>
  </tr>
  <tr>
  <th>Gif</th>
    <td><img src="https://github.com/Ciphey/Ciphey/raw/master/Pictures_for_README/ciphey_gooder_cyberchef.gif" alt="The guy she tells you not to worry about"></td>
    <td><img src="https://github.com/Ciphey/Ciphey/raw/master/Pictures_for_README/not_dying.gif" alt="You"></td>
  </tr>
  <tr>
  <th>Tempo</th>
    <td>2 secondi</td>
    <td>6 secondi</td>
  </tr>
    <tr>
  <th>Setup</th>
    <td><ul><li>Esegui ciphey sul file</li></ul></td>
    <td><ul><li>Impostare il parametro regex su "{"</li><li>Hai bisogno di conoscere quante volte devi decodificare il file</li><li>Devi sapere che รจ sempre Base64</li><li>Devi caricare CyberChef (รจ un'applicazione JS piena di roba)</li><li>Devi conoscere abbastanza su CyberChef per creare questa pipeline</li><li>Invert the match</li></ul></td>
  </tr>
</table>

<sub><b>Nota: </b>Le gif possono caricarsi in tempi diversi, quindi una puรฒ apparire significativamente piรน veloce di un'altra.</sub><br>
<sub><b>Una nota su CyberChef Magic: </b>La funzione di CyberChef che si avvicina di piรน a Ciphey รจ Magic. Magic fallisce istantaneamente con questo input e crasha. L'unico modo per forzare CyberChef a competere รจ definirlo manualmente</sub>

Abbiamo anche testato un file da **6 gb**: Ciphey รจ riuscito a craccarlo in **5 minuti e 54 secondi**, CyberChef รจ crashato ancor prima di partire.

## ๐ Ciphey vs Katana vs CyberChef Magic

| **Nome**                                         | โก Ciphey โก | ๐ก๏ธ Katana ๐ก๏ธ | ๐ข CyberChef Magic ๐ข |
| ------------------------------------------------ | ------------ | ------------ | --------------------- |
| Controllo avanzato del linguaggio                | โ           | โ           | โ                    |
| Supporta la crittografia                         | โ           | โ           | โ                    |
| Releases named after Dystopian themes ๐         | โ           | โ           | โ                    |
| Supporta gli hashes                              | โ           | โ           | โ                    |
| Facile da impostare                              | โ           | โ           | โ                    |
| Puรฒ indovinare con cosa รจ crittografato quelcosa | โ           | โ           | โ                    |
| Creato dagli hackers per gli hackers             | โ           | โ           | โ                    |

# ๐ฌ Per iniziare

Se hai problemi a installare Ciphey, [leggi questo.](https://github.com/Ciphey/Ciphey/wiki/Common-Issues-&-Their-Solutions)

## โผ๏ธ Link importanti (Documentazione, Guida all'installazione, supporto via Discord)

| Guida all'installazione                                                          | Documentazione                                             | Discord                                     | Immagine Docker (di REMnux)                                                                          |
| -------------------------------------------------------------------------------- | ---------------------------------------------------------- | ------------------------------------------- | ---------------------------------------------------------------------------------------------------- |
| ๐ [Guida all'installazione](https://github.com/Ciphey/Ciphey/wiki/Installation) | ๐ [Documentazione](https://github.com/Ciphey/Ciphey/wiki) | ๐ฆ [Discord](https://discord.ciphey.online) | ๐ [Documentazione Docker](https://docs.remnux.org/run-tools-in-containers/remnux-containers#ciphey) |

## ๐โโ๏ธUsare Ciphey

Ci sono 3 modi per usare Ciphey:

1. File di input `ciphey -f encrypted.txt`
2. Unqualified input `ciphey -- "Encrypted input"`
3. Modo normale `ciphey -t "Encrypted input"`

![Gif che mostra i 3 modi per usare Ciphey](Pictures_for_README/3ways.gif)

Per eliminare le barre di avanzamento, la tabella delle probabilitร? e tutto il resto, usa la modalitร? quiet.

`ciphey -t "encrypted text here" -q`

Per una lista completa di argomenti, `ciphey --help`.

### โ๏ธ Importare Ciphey

Puoi importare il main di Ciphey e usarlo nei tuoi programmi e nel tuo codice. `from Ciphey.__main__ import main`

# ๐ช Contributors

Ciphey รจ stato inventato da [Brandon](https://github.com/bee-san) nel 2008, e ripreso nel 2019. Ciphey non sarebbe quello che รจ oggi senza [Cyclic3](https://github.com/Cyclic3) - presidente della societร? di Cyber Security UoL.

Ciphey รจ stato ripreso & ricreato dalla [Cyber Security Society](https://www.cybersoc.cf/) per l'uso nei CTFs. Se sarai mai a Liverpool, prendi in considerazione la possibilitร? di tenere un discorso o di sponsorizzare i nostri eventi. Inviaci un'e-mail a `cybersecurity@society.liverpoolguild.org` per saperne di piรน ๐ค?

**Un grande ringraziamento** a George H per aver capito come possiamo usare gli algoritmi corretti per velocizzare il processo di ricerca.
**Un ringraziamento speciale** a [varghalladesign](https://www.facebook.com/varghalladesign) per aver progettato il logo. Guarda gli altri loro lavori sul design!

## ๐โ๐ฆบ [Come Contribuire](https://github.com/Ciphey/Ciphey/wiki/Contributing)

Non avere paura di contribuire! Abbiamo molte, molte cose che puoi fare per aiutare. Ognuna di esse รจ etichettata e facilmente spiegabile con esempi. Se stai cercando di contribuire ma sei bloccato, tagga @bee-san o @cyclic3 in un issue di GitHub โจ

In alternativa, unisciti al gruppo della Discordia e invia un messaggio lรฌ (link nella [wiki](https://github.com/Ciphey/Ciphey/wiki/Contributing)) o in cima a questo README come distintivo.

Per favore leggi [la wiki](https://github.com/Ciphey/Ciphey/wiki/Contributing) per i dettagli esatti su come contribuire โจ

Cosรฌ facendo, il tuo nome verrร? aggiunto al README qui sotto e sarai parte di un progetto in continua crescita!
[![Stargazers nel tempo](https://starchart.cc/Ciphey/Ciphey.svg)](https://starchart.cc/Ciphey/Ciphey)

## ๐ฐ Collaboratori finanziari

I contributi saranno utilizzati per finanziare non solo il futuro di Ciphey e dei suoi autori, ma anche la Cyber Security Society dell'Universitร? di Liverpool.

GitHub non supporta "sponsorizza questo progetto e noi distribuiremo il denaro in modo equo", quindi scegli un link e ci penseremo noi ๐ฅฐ

## โจ Contributors

I ringraziamenti vanno a tutte queste fantastiche persone ([legenda emoji](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <td align="center"><a href="https://github.com/Cyclic3"><img src="https://avatars1.githubusercontent.com/u/15613874?v=4" width="100px;" alt=""/><br /><sub><b>cyclic3</b></sub></a><br /><a href="#design-cyclic3" title="Design">๐จ</a> <a href="#maintenance-cyclic3" title="Maintenance">๐ง</a> <a href="https://github.com/Ciphey/Ciphey/commits?author=cyclic3" title="Code">๐ป</a> <a href="#ideas-cyclic3" title="Ideas, Planning, & Feedback">๐ค</a></td>
    <td align="center"><a href="https://skerritt.blog"><img src="https://avatars3.githubusercontent.com/u/10378052?v=4" width="100px;" alt=""/><br /><sub><b>Brandon</b></sub></a><br /><a href="#design-brandonskerritt" title="Design">๐จ</a> <a href="#maintenance-brandonskerritt" title="Maintenance">๐ง</a> <a href="https://github.com/Ciphey/Ciphey/commits?author=brandonskerritt" title="Code">๐ป</a> <a href="#ideas-brandonskerritt" title="Ideas, Planning, & Feedback">๐ค</a></td>
    <td align="center"><a href="https://github.com/michalani"><img src="https://avatars0.githubusercontent.com/u/27767884?v=4" width="100px;" alt=""/><br /><sub><b>michalani</b></sub></a><br /><a href="https://github.com/Ciphey/Ciphey/commits?author=michalani" title="Code">๐ป</a></td>
    <td align="center"><a href="https://github.com/ashb07"><img src="https://avatars2.githubusercontent.com/u/24845568?v=4" width="100px;" alt=""/><br /><sub><b>ashb07</b></sub></a><br /><a href="https://github.com/Ciphey/Ciphey/commits?author=ashb07" title="Code">๐ป</a></td>
    <td align="center"><a href="https://github.com/TheAlcanian"><img src="https://avatars3.githubusercontent.com/u/22127191?v=4" width="100px;" alt=""/><br /><sub><b>Shardion</b></sub></a><br /><a href="https://github.com/Ciphey/Ciphey/issues?q=author%3ATheAlcanian" title="Bug reports">๐</a></td>
    <td align="center"><a href="https://github.com/Bryzizzle"><img src="https://avatars0.githubusercontent.com/u/57810197?v=4" width="100px;" alt=""/><br /><sub><b>Bryan</b></sub></a><br /><a href="#translation-Bryzizzle" title="Translation">๐</a> <a href="https://github.com/Ciphey/Ciphey/commits?author=Bryzizzle" title="Documentation">๐</a></td>
    <td align="center"><a href="https://lukasgabriel.net"><img src="https://avatars0.githubusercontent.com/u/52338810?v=4" width="100px;" alt=""/><br /><sub><b>Lukas Gabriel</b></sub></a><br /><a href="https://github.com/Ciphey/Ciphey/commits?author=lukasgabriel" title="Code">๐ป</a> <a href="https://github.com/Ciphey/Ciphey/issues?q=author%3Alukasgabriel" title="Bug reports">๐</a> <a href="#translation-lukasgabriel" title="Translation">๐</a> <a href="#ideas-lukasgabriel" title="Ideas, Planning, & Feedback">๐ค</a></td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/DarshanBhoi"><img src="https://avatars2.githubusercontent.com/u/70128281?v=4" width="100px;" alt=""/><br /><sub><b>Darshan</b></sub></a><br /><a href="https://github.com/Ciphey/Ciphey/issues?q=author%3ADarshanBhoi" title="Bug reports">๐</a></td>
    <td align="center"><a href="https://github.com/SkeletalDemise"><img src="https://avatars1.githubusercontent.com/u/29117662?v=4" width="100px;" alt=""/><br /><sub><b>SkeletalDemise</b></sub></a><br /><a href="https://github.com/Ciphey/Ciphey/commits?author=SkeletalDemise" title="Code">๐ป</a></td>
    <td align="center"><a href="https://www.patreon.com/cclauss"><img src="https://avatars3.githubusercontent.com/u/3709715?v=4" width="100px;" alt=""/><br /><sub><b>Christian Clauss</b></sub></a><br /><a href="https://github.com/Ciphey/Ciphey/commits?author=cclauss" title="Code">๐ป</a> <a href="https://github.com/Ciphey/Ciphey/issues?q=author%3Acclauss" title="Bug reports">๐</a></td>
    <td align="center"><a href="http://machinexa.xss.ht"><img src="https://avatars1.githubusercontent.com/u/60662297?v=4" width="100px;" alt=""/><br /><sub><b>Machinexa2</b></sub></a><br /><a href="#content-machinexa2" title="Content">๐</a></td>
    <td align="center"><a href="https://github.com/anantverma275"><img src="https://avatars1.githubusercontent.com/u/18184503?v=4" width="100px;" alt=""/><br /><sub><b>Anant Verma</b></sub></a><br /><a href="https://github.com/Ciphey/Ciphey/commits?author=anantverma275" title="Code">๐ป</a> <a href="https://github.com/Ciphey/Ciphey/issues?q=author%3Aanantverma275" title="Bug reports">๐</a></td>
    <td align="center"><a href="https://github.com/XVXTOR"><img src="https://avatars1.githubusercontent.com/u/40268197?v=4" width="100px;" alt=""/><br /><sub><b>XVXTOR</b></sub></a><br /><a href="https://github.com/Ciphey/Ciphey/commits?author=XVXTOR" title="Documentation">๐</a></td>
    <td align="center"><a href="https://github.com/Itamikame"><img src="https://avatars2.githubusercontent.com/u/59034423?v=4" width="100px;" alt=""/><br /><sub><b>Itamikame</b></sub></a><br /><a href="https://github.com/Ciphey/Ciphey/commits?author=Itamikame" title="Code">๐ป</a></td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/MikeMerz"><img src="https://avatars3.githubusercontent.com/u/50526795?v=4" width="100px;" alt=""/><br /><sub><b>MikeMerz</b></sub></a><br /><a href="https://github.com/Ciphey/Ciphey/commits?author=MikeMerz" title="Code">๐ป</a></td>
    <td align="center"><a href="https://github.com/jacobggman"><img src="https://avatars2.githubusercontent.com/u/30216976?v=4" width="100px;" alt=""/><br /><sub><b>Jacob Galam</b></sub></a><br /><a href="https://github.com/Ciphey/Ciphey/commits?author=jacobggman" title="Code">๐ป</a> <a href="https://github.com/Ciphey/Ciphey/issues?q=author%3Ajacobggman" title="Bug reports">๐</a></td>
    <td align="center"><a href="https://tuxthexplorer.github.io/"><img src="https://avatars1.githubusercontent.com/u/37508897?v=4" width="100px;" alt=""/><br /><sub><b>TuxTheXplorer</b></sub></a><br /><a href="#translation-TuxTheXplorer" title="Translation">๐</a></td>
    <td align="center"><a href="https://github.com/Itamai"><img src="https://avatars3.githubusercontent.com/u/53093696?v=4" width="100px;" alt=""/><br /><sub><b>Itamai</b></sub></a><br /><a href="https://github.com/Ciphey/Ciphey/commits?author=Itamai" title="Code">๐ป</a> <a href="https://github.com/Ciphey/Ciphey/issues?q=author%3AItamai" title="Bug reports">๐</a></td>
    <td align="center"><a href="https://github.com/Termack"><img src="https://avatars2.githubusercontent.com/u/26333901?v=4" width="100px;" alt=""/><br /><sub><b>Filipe</b></sub></a><br /><a href="#translation-Termack" title="Translation">๐</a></td>
    <td align="center"><a href="https://github.com/malathit"><img src="https://avatars0.githubusercontent.com/u/2684148?v=4" width="100px;" alt=""/><br /><sub><b>Malathi</b></sub></a><br /><a href="https://github.com/Ciphey/Ciphey/commits?author=malathit" title="Code">๐ป</a></td>
    <td align="center"><a href="https://hexchaos.xyz/"><img src="https://avatars1.githubusercontent.com/u/8947820?v=4" width="100px;" alt=""/><br /><sub><b>Jack</b></sub></a><br /><a href="#translation-HexChaos" title="Translation">๐</a></td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/yafkari"><img src="https://avatars3.githubusercontent.com/u/41365655?v=4" width="100px;" alt=""/><br /><sub><b>Younes</b></sub></a><br /><a href="#translation-yafkari" title="Translation">๐</a></td>
    <td align="center"><a href="https://gitlab.com/Marnick39"><img src="https://avatars2.githubusercontent.com/u/17315511?v=4" width="100px;" alt=""/><br /><sub><b>Marnick Vandecauter</b></sub></a><br /><a href="#translation-Marnick39" title="Translation">๐</a></td>
    <td align="center"><a href="https://github.com/mav8557"><img src="https://avatars0.githubusercontent.com/u/47306745?v=4" width="100px;" alt=""/><br /><sub><b>Michael V</b></sub></a><br /><a href="https://github.com/Ciphey/Ciphey/commits?author=mav8557" title="Code">๐ป</a></td>
    <td align="center"><a href="https://github.com/chuinzer"><img src="https://avatars2.githubusercontent.com/u/64257785?v=4" width="100px;" alt=""/><br /><sub><b>chuinzer</b></sub></a><br /><a href="#translation-chuinzer" title="Translation">๐</a></td>
  </tr>
</table>

<!-- markdownlint-enable -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

Questo progetto segue le specifiche [all-contributors](https://github.com/all-contributors/all-contributors) Contributi di qualunque tipo sono i benvenuti!
