<html lang="it">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Maurizio Bernardini | Giornalista professionista e spin doctor</title>

    <meta name="description" content="Maurizio Bernardini, giornalista professionista e spin doctor. Comunicazione politica e istituzionale.">
    <meta name="author" content="Maurizio Bernardini">
    <meta name="robots" content="index, follow">
    <meta name="theme-color" content="#142b40">

    <meta property="og:type" content="website">
    <meta property="og:title" content="Maurizio Bernardini | Giornalista professionista e spin doctor">
    <meta property="og:description" content="Giornalista professionista e spin doctor. Comunicazione politica e istituzionale.">
    <meta property="og:locale" content="it_IT">

    <link rel="canonical" href="https://mauriziobernardini.github.io/">

    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>

    <link href="https://fonts.googleapis.com/css2?family=IBM+Plex+Mono:wght@400;500;600;700&family=Roboto+Slab:wght@400;500;600;700;800&family=Source+Sans+3:wght@400;500;600;700;800&display=swap" rel="stylesheet">

    <style>
        :root {
            --navy: #142b40;
            --navy-light: #203e56;
            --ink: #202b35;
            --muted: #68737d;
            --paper: #f7f6f2;
            --white: #ffffff;
            --line: #deded8;
            --accent: #b18a54;
            --accent-light: #d6bc94;

            --serif: "Roboto Slab", Georgia, serif;
            --sans: "Source Sans 3", Arial, sans-serif;
            --mono: "IBM Plex Mono", monospace;

            --max: 1120px;
        }

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        html {
            scroll-behavior: smooth;
            scroll-padding-top: 90px;
        }

        body {
            background: var(--paper);
            color: var(--ink);
            font-family: var(--sans);
            font-size: 17px;
            font-weight: 500;
            line-height: 1.8;
            letter-spacing: -.15px;
            -webkit-font-smoothing: antialiased;
        }

        a {
            color: inherit;
            text-decoration: none;
        }

        .container {
            width: min(var(--max), calc(100% - 64px));
            margin: auto;
        }

        /* NAVIGAZIONE */

        .navigation {
            position: sticky;
            top: 0;
            z-index: 100;
            background: rgba(247,246,242,.96);
            backdrop-filter: blur(12px);
            border-bottom: 1px solid var(--line);
        }

        .nav-inner {
            min-height: 76px;
            display: flex;
            align-items: center;
            justify-content: space-between;
            gap: 30px;
        }

        .brand {
            font-family: var(--serif);
            font-size: 20px;
            font-weight: 700;
            color: var(--navy);
            letter-spacing: -.4px;
        }

        .nav-links {
            display: flex;
            align-items: center;
            gap: 30px;
        }

        .nav-links a {
            font-size: 12px;
            font-weight: 700;
            letter-spacing: .055em;
            text-transform: uppercase;
            color: #58636d;
            transition: color .2s;
        }

        .nav-links a:hover {
            color: var(--accent);
        }

        /* HERO */

        .hero {
            background: var(--navy);
            color: white;
            position: relative;
            overflow: hidden;
        }

        .hero::after {
            content: "";
            position: absolute;
            width: 440px;
            height: 440px;
            border: 1px solid rgba(214,188,148,.18);
            border-radius: 50%;
            right: -100px;
            top: -200px;
            box-shadow:
                0 0 0 45px rgba(214,188,148,.025),
                0 0 0 90px rgba(214,188,148,.025);
            pointer-events: none;
        }

        .hero-inner {
            min-height: 530px;
            display: flex;
            flex-direction: column;
            justify-content: center;
            padding: 90px 0 100px;
            position: relative;
            z-index: 1;
        }

        .eyebrow {
            display: flex;
            align-items: center;
            gap: 14px;
            color: var(--accent-light);
            font-family: var(--mono);
            font-size: 11px;
            font-weight: 600;
            letter-spacing: .08em;
            text-transform: uppercase;
            margin-bottom: 32px;
        }

        .eyebrow::before {
            content: "";
            width: 36px;
            height: 1px;
            background: var(--accent);
        }

        .hero h1 {
    font-family: var(--serif);
    font-size: clamp(52px, 7vw, 88px);
    font-weight: 800;
    line-height: 1.12;
    letter-spacing: 0.5px;
    max-width: 850px;
    margin-bottom: 25px;
}
        .hero h1 span {
            color: var(--accent-light);
        }

        .hero-description {
            font-size: 20px;
            line-height: 1.65;
            color: #e0e7ed;
            font-weight: 700;
        }

        .hero-bottom {
            display: flex;
            align-items: center;
            gap: 24px;
            margin-top: 45px;
        }

        .hero-link {
            display: inline-flex;
            align-items: center;
            gap: 12px;
            color: white;
            font-size: 12px;
            font-weight: 700;
            letter-spacing: .08em;
            text-transform: uppercase;
            border-bottom: 1px solid var(--accent);
            padding-bottom: 8px;
            transition: color .2s;
        }

        .hero-link:hover {
            color: var(--accent-light);
        }

        /* ELEMENTI COMUNI */

        .section-label {
            color: var(--accent);
            font-family: var(--mono);
            font-size: 11px;
            font-weight: 600;
            text-transform: uppercase;
            letter-spacing: .08em;
            margin-bottom: 20px;
        }

        .section-heading {
            font-family: var(--serif);
            color: var(--navy);
            font-size: clamp(36px, 4vw, 51px);
            font-weight: 700;
            line-height: 1.2;
            letter-spacing: -1px;
        }

        /* PROFILO */

        .intro {
            padding: 110px 0;
            border-bottom: 1px solid var(--line);
        }

        .intro-grid {
            display: grid;
            grid-template-columns: .75fr 1.25fr;
            gap: 90px;
        }

        .intro-content p {
            font-size: 17px;
            font-weight: 500;
            color: #505c66;
            margin-bottom: 22px;
        }

        .intro-content .highlight {
            font-family: var(--serif);
            font-size: 25px;
            line-height: 1.55;
            font-weight: 600;
            color: var(--navy);
            border-left: 2px solid var(--accent);
            padding-left: 25px;
            margin: 32px 0;
        }

        .intro-content a,
        .experience-content a {
            color: #315c7a;
            text-decoration: underline;
            text-decoration-color: #b8c7d2;
            text-underline-offset: 4px;
        }

        .intro-content a:hover,
        .experience-content a:hover {
            color: var(--accent);
        }

        /* COMPETENZE */

        .expertise {
            background: #eeede7;
            padding: 100px 0;
        }

        .section-top {
            max-width: 650px;
            margin-bottom: 55px;
        }

        .section-top p {
            color: var(--muted);
            margin-top: 18px;
        }

        .expertise-grid {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 1px;
            background: #d9d8d0;
            border: 1px solid #d9d8d0;
        }

        .expertise-card {
            background: #eeede7;
            padding: 35px 30px;
            min-height: 215px;
            transition: background .2s;
        }

        .expertise-card:hover {
            background: #fff;
        }

        .card-number {
            font-family: var(--mono);
            font-weight: 600;
            color: var(--accent);
            font-size: 25px;
            margin-bottom: 25px;
        }

        .expertise-card h3 {
            font-family: var(--serif);
            font-size: 22px;
            font-weight: 700;
            color: var(--navy);
            margin-bottom: 10px;
        }

        .expertise-card p {
            font-size: 15px;
            font-weight: 500;
            color: var(--muted);
            line-height: 1.7;
        }

        /* ESPERIENZA PROFESSIONALE */

        .experience {
            padding: 110px 0;
        }

        .experience-content {
            max-width: 900px;
            margin: auto;
        }

        .experience-content p {
            color: #505c66;
            font-size: 17px;
            font-weight: 500;
            margin-bottom: 22px;
        }

        .experience-content h3 {
            font-family: var(--serif);
            font-size: 27px;
            font-weight: 700;
            color: var(--navy);
            margin: 42px 0 15px;
        }

        .experience-content h3:first-child {
            margin-top: 0;
        }

        /* FORMAZIONE */

        .education {
            background: var(--navy);
            color: white;
            padding: 90px 0;
        }

        .education .section-heading {
            color: white;
        }

        .education-grid {
            display: grid;
            grid-template-columns: .75fr 1.25fr;
            gap: 90px;
        }

        .education-content p {
            color: #d0d9df;
            font-size: 17px;
            font-weight: 500;
            margin-bottom: 20px;
        }

        .education-note {
            border-left: 2px solid var(--accent);
            padding-left: 22px;
            font-family: var(--serif);
            font-size: 22px;
            line-height: 1.5;
            font-weight: 600;
            color: var(--accent-light);
            margin-top: 30px;
        }

        /* COMPETENZE TRASVERSALI */

        .references {
            padding: 100px 0;
            border-bottom: 1px solid var(--line);
        }

        .references-inner {
    display: grid;
    grid-template-columns: .75fr 1.25fr;
    gap: 45px;
    align-items: start;
        }

        .reference-list {
            list-style: none;
            margin-top: 30px;
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 0 30px;
        }

        .reference-list li {
            border-top: 1px solid var(--line);
            padding: 17px 0;
            color: var(--navy);
            font-size: 15px;
            font-weight: 600;
        }

        .reference-list li:last-child {
            border-bottom: 1px solid var(--line);
        }

        /* CONTATTI */

        .contact {
            background: #eeede7;
            padding: 100px 0;
        }

        .contact-inner {
            display: grid;
            grid-template-columns: 1fr 1fr;
            align-items: center;
            gap: 60px;
        }

        .contact h2 {
            font-family: var(--serif);
            font-size: clamp(38px, 5vw, 58px);
            color: var(--navy);
            font-weight: 700;
            line-height: 1.15;
        }

        .contact-content p {
            color: var(--muted);
            margin-bottom: 25px;
        }

        .contact-button {
            display: inline-flex;
            align-items: center;
            justify-content: center;
            padding: 15px 25px;
            background: var(--navy);
            color: white;
            font-size: 12px;
            font-weight: 700;
            letter-spacing: .08em;
            text-transform: uppercase;
            transition: background .2s;
        }

        .contact-button:hover {
            background: var(--accent);
        }

        /* FOOTER */

        footer {
            background: #102436;
            color: #d0d9df;
            padding: 40px 0;
        }

        .footer-inner {
            display: flex;
            justify-content: space-between;
            align-items: center;
            gap: 30px;
        }

        .footer-name {
            font-family: var(--serif);
            font-size: 21px;
            font-weight: 700;
            color: white;
        }

        .footer-meta {
            font-size: 12px;
            color: #aebbc5;
            line-height: 1.8;
        }

        .footer-links {
            display: flex;
            gap: 20px;
            font-size: 12px;
        }

        .footer-links a:hover {
            color: var(--accent-light);
        }

        /* PRIVACY */

        .privacy {
            background: #102436;
            border-top: 1px solid #334656;
            padding: 25px 0;
            color: #aebbc5;
        }

        .privacy summary {
            cursor: pointer;
            font-family: var(--mono);
            font-size: 12px;
            font-weight: 500;
            letter-spacing: .08em;
            text-transform: uppercase;
        }

        .privacy-content {
            padding-top: 20px;
            max-width: 800px;
            font-size: 12px;
            line-height: 1.8;
        }

        .privacy-content p {
            margin-bottom: 12px;
        }

        .privacy-content a {
            text-decoration: underline;
        }

        /* RESPONSIVE */

        @media (max-width: 850px) {

            .container {
                width: min(100% - 44px, var(--max));
            }

            .nav-links {
                gap: 16px;
            }

            .nav-links a {
                font-size: 10px;
            }

            .intro-grid,
            .education-grid,
            .references-inner {
                grid-template-columns: 1fr;
                gap: 35px;
            }

            .expertise-grid {
                grid-template-columns: repeat(2, 1fr);
            }

            .contact-inner {
                grid-template-columns: 1fr;
                gap: 25px;
            }
        }

        @media (max-width: 580px) {

            body {
                font-size: 16px;
            }

            .container {
                width: calc(100% - 36px);
            }

            .nav-inner {
                min-height: 65px;
                flex-direction: column;
                justify-content: center;
                gap: 7px;
                padding: 10px 0;
            }

            .brand {
                font-size: 19px;
            }

            .nav-links {
                width: 100%;
                justify-content: center;
                gap: 16px;
                flex-wrap: wrap;
            }

            .nav-links a {
                font-size: 9px;
            }

          .hero-inner {
    min-height: 440px;
    padding: 75px 0;
}

.hero h1 {
    font-size: 52px;
    letter-spacing: 0.2px;
    line-height: 1.12;
}
        
           .hero h1 {
    font-size: 52px;
    letter-spacing: 0.2px;
    line-height: 1.12;
}

            .hero-description {
                font-size: 17px;
            }

            .intro,
            .experience,
            .references,
            .contact {
                padding: 70px 0;
            }

            .expertise,
            .education {
                padding: 70px 0;
            }

            .expertise-grid {
                grid-template-columns: 1fr;
            }

            .expertise-card {
                min-height: auto;
                padding: 27px;
            }

            .section-heading {
                font-size: 38px;
            }

            .intro-content p,
            .experience-content p,
            .education-content p {
                font-size: 16px;
            }

            .intro-content .highlight {
                font-size: 22px;
            }

            .reference-list {
                grid-template-columns: 1fr;
            }

            .footer-inner {
                flex-direction: column;
                align-items: flex-start;
            }

            .footer-links {
                flex-wrap: wrap;
            }
        }

        /* ACCESSIBILITÀ */

        @media (prefers-reduced-motion: reduce) {

            html {
                scroll-behavior: auto;
            }

            *,
            *::before,
            *::after {
                transition-duration: .01ms !important;
            }
        }

    </style>
</head>

<body>

    <!-- NAVIGAZIONE -->

    <nav class="navigation">
        <div class="container nav-inner">

            <div class="nav-links">
                <a href="#profilo">Profilo</a>
                <a href="#competenze">Competenze</a>
                <a href="#esperienza">Esperienza</a>
                <a href="#formazione">Formazione</a>
                <a href="#contatti">Contatti</a>
            </div>

        </div>
    </nav>


    <!-- HERO -->

    <header class="hero" id="inizio">
        <div class="container hero-inner">

            <div class="eyebrow">
                Comunicazione istituzionale, politica e strategica
            </div>

            <h1>
                Maurizio<br>
                <span>Bernardini</span>
            </h1>

            <p class="hero-description">
                Giornalista professionista e consulente indipendente
            </p>

            <div class="hero-bottom">
                <a href="#profilo" class="hero-link">
                    Scopri il profilo <span>→</span>
                </a>
            </div>

        </div>
    </header>


    <main>

        <!-- PROFILO -->

        <section class="intro" id="profilo">
            <div class="container intro-grid">

                <div>
                    <div class="section-label">01 / Profilo</div>

                    <h2 class="section-heading">
                        Esperienza giornalistica.
                        Visione strategica.
                    </h2>
                </div>

                <div class="intro-content">

                    <p>
                        Classe 1982, sono un giornalista professionista
                        e consulente nel campo della comunicazione
                        istituzionale, politica e strategica.
                    </p>

                    <p>
                        La mia attività si sviluppa soprattutto in Toscana,
                        Emilia-Romagna, Lazio e Liguria. Nel corso della
                        carriera ho lavorato in importanti città capoluogo,
                        tra cui Firenze, Bologna, Roma, Parma, Grosseto,
                        Piacenza, Reggio Emilia e Imperia.
                    </p>

                    <p>
                        Opero come libero professionista e consulente
                        per committenti pubblici e privati, mantenendo
                        un approccio indipendente e orientato
                        esclusivamente al metodo. In questa veste
                        tecnica l'ultimo incarico che ho assunto è quello
                        in Regione Emilia-Romagna, presso i gruppi
                        consiliari, per il coordinamento e l'indirizzo
                        operativo dello staff di comunicazione.
                        <a href="https://wwwservizi.regione.emilia-romagna.it/amministrazionetrasparente/Incarichi/RegioneEmiliaRomagna/Dettaglio/996"
                           target="_blank" rel="noopener noreferrer">
                            Consulta il riferimento istituzionale.
                        </a>
                    </p>

                    <div class="highlight">
                        Giornalismo, comunicazione politica e istituzioni:
                        tre dimensioni di un percorso professionale
                        orientato alla strategia e alla gestione della
                        complessità.
                    </div>

                    <p>
                        Sono stato inoltre riconosciuto tra i principali
                        professionisti italiani della comunicazione
                        politica.
                        <a href="https://jobseekeritalia.it/2016/03/16/professionisti-comunicazione-politica-digitale/"
                           target="_blank" rel="noopener noreferrer">
                            Leggi il riferimento.
                        </a>
                    </p>

                </div>
            </div>
        </section>


<!-- COMPETENZE -->

<section class="expertise" id="competenze">
    <div class="container">

        <div class="section-top">
            <div class="section-label">02 / Ambiti professionali</div>

            <h2 class="section-heading">
                Le aree di competenza
            </h2>

            <p>
                Un'esperienza trasversale che integra
                informazione, strategia, relazioni istituzionali
                e comunicazione politica.
            </p>
        </div>

        <div class="expertise-grid">

            <article class="expertise-card">
                <div class="card-number">01</div>
                <h3>Campagne elettorali e comunicazione politica</h3>
                <p>
                    Posizionamento, strategie di consenso,
                    comunicazione dei candidati e supporto
                    ai gruppi politici, coordinamento delle
                    strutture operative e mediazione politica.
                </p>
            </article>

            <article class="expertise-card">
                <div class="card-number">02</div>
                <h3>Comunicazione istituzionale</h3>
                <p>
                    Uffici stampa, coordinamento degli staff
                    e comunicazione per amministrazioni
                    e organismi istituzionali.
                </p>
            </article>

            <article class="expertise-card">
                <div class="card-number">03</div>
                <h3>Comunicazione di crisi</h3>
                <p>
                    Gestione della comunicazione in contesti
                    complessi, mediazione e rapporti
                    con gli interlocutori istituzionali.
                </p>
            </article>

            <article class="expertise-card">
                <div class="card-number">04</div>
                <h3>Media relations</h3>
                <p>
                    Rapporti con giornalisti, organizzazione
                    di conferenze stampa, presidio mediatico
                    e gestione dei contenuti.
                </p>
            </article>

            <article class="expertise-card">
                <div class="card-number">05</div>
                <h3>Strategia digitale</h3>
                <p>
                    Comunicazione crossmediale, social media,
                    data journalism e applicazioni
                    dell'intelligenza artificiale.
                </p>
            </article>

            <article class="expertise-card">
                <div class="card-number">06</div>
                <h3>Presentazione eventi</h3>
                <p>
                    Conduzione e presentazione di eventi istituzionali,
                    politici e pubblici, moderazione di incontri,
                    dibattiti e conferenze, gestione degli interventi.
                </p>
            </article>

        </div>
    </div>
</section>

<!-- ESPERIENZA PROFESSIONALE -->

<section class="experience" id="esperienza">
    <div class="container">

        <div class="experience-content">


                    <h3>Comunicazione istituzionale</h3>

                    <p>
                        Ho ricoperto incarichi di responsabilità
                        nella comunicazione di amministrazioni
                        pubbliche e organismi politici.
                    </p>

                    <p>
                        Capo ufficio stampa del Comune
                        di Grosseto durante l'amministrazione
                        del sindaco Antonfrancesco Vivarelli Colonna.
                        <a href="https://www.comune.grosseto.it/persona_pubblica/bernardini-maurizio/"
                           target="_blank" rel="noopener noreferrer">
                            Riferimento istituzionale.
                        </a>
                    </p>

                    <p>
                        Capo di Gabinetto, portavoce e responsabile
                        del settore comunicazione a Imperia su incarico del sindaco e già ministro Claudio Scajola.
                    </p>

                    <p>
                        Capo comunicazione del Movimento 5 Stelle
                        in Regione Toscana.
                        <a href="https://trasparenza.consiglio.regione.toscana.it/node/26930"
                           target="_blank" rel="noopener noreferrer">
                            Riferimento istituzionale.
                        </a>
                    </p>


                    <h3>Consulenza politica e collaborazioni</h3>

                    <p>
                        Nel corso della mia attività professionale
                        ho seguito, a vario titolo, esponenti politici
                        di diversi orientamenti, occupandomi
                        di posizionamento, strategia, rapporti
                        con i media e coordinamento della comunicazione.
                    </p>

                    <p>
                        Tra le personalità seguite figurano
                        Mario Lolini, già coordinatore toscano
                        della Lega e deputato, e Pietro Vignali,
                        già sindaco di Parma, attuale capogruppo
                        di Forza Italia in Regione Emilia-Romagna
                        e segretario regionale. Ho curato anche
                        l'immagine di esponenti di rilievo
                        del Partito democratico.
                        Nel 2016 ho curato la comunicazione politica
                        della campagna elettorale del Movimento 5 Stelle
                        di Grosseto, con candidato sindaco Giacomo Gori.
                        La lista ottenne il 20% dei voti, uno dei risultati
                        più significativi del Movimento nei centri urbani.
                    </p>

                    <p>
                        Ho collaborato, anche durante eventi
                        o iniziative elettorali, con personalità
                        istituzionali e politiche di rilievo nazionale
                        ed europeo, tra cui vicepresidenti del Consiglio,
                        ministri, vicepresidenti del Parlamento europeo,
                        deputati, senatori, eurodeputati, consiglieri
                        regionali e sindaci.
                    </p>

                    <p>
                        Ho prestato la mia professionalità anche
                        per l'Istituto storico Grossetano della
                        Resistenza e dell'età contemporanea
                        e per realtà del mondo cooperativo nazionale.
                    </p>


                    <h3>Campagne elettorali</h3>

                    <p>
                        Ho guidato e contribuito a numerose campagne
                        elettorali in ambito locale, regionale e nazionale,
                        curando il posizionamento dei candidati,
                        l'organizzazione degli staff, l'elaborazione
                        dei discorsi, il media training, le conferenze
                        stampa, la comunicazione digitale e le relazioni
                        con il sistema dell'informazione.
                    </p>

                    <p>
                        Una parte della mia attività è dedicata
                        alla ricerca del consenso attraverso il sistema
                        delle preferenze.
                    </p>

                </div>
            </div>
        </section>


        <!-- FORMAZIONE E GIORNALISMO -->

        <section class="education" id="formazione">
            <div class="container education-grid">

                <div>
                    <div class="section-label">03 / Giornalismo e formazione</div>

                    <h2 class="section-heading">
                        Il valore dell'informazione.
                    </h2>
                </div>

                <div class="education-content">

                    <p>
                        La mia identità professionale si fonda
                        sull'integrazione tra esperienza giornalistica
                        e consulenza strategica.
                    </p>

                    <p>
                        Ho lavorato per anni nella cronaca bianca,
                        occupandomi di politica, economia, società
                        e attualità, per realtà televisive e digitali
                        e per importanti testate giornalistiche,
                        tra cui <em>Il Tirreno</em> e l'edizione
                        toscana del <em>Corriere della Sera</em>.
                    </p>

                    <p>
                        Questa esperienza mi ha consentito di sviluppare
                        una conoscenza diretta dei meccanismi
                        dell'informazione, delle dinamiche editoriali
                        e delle relazioni tra istituzioni e media.
                    </p>

                    <p>
                        Ho conseguito una laurea in Storia a Bologna,
                        una laurea magistrale in Comunicazione digitale
                        e marketing e un master in Giornalismo
                        e comunicazione.
                    </p>

                    <p>
                        Nel mio aggiornamento professionale trovano
                        anche spazio temi come data journalism,
                        par condicio, presidio televisivo, sistemi
                        elettorali e applicazioni dell'intelligenza
                        artificiale nella comunicazione.
                    </p>

                    <div class="education-note">
                        «Non esiste vento favorevole per il marinaio
                        che non sa dove andare».
                        <br>
                        <span style="font-family:var(--sans);font-size:12px;letter-spacing:.08em;text-transform:uppercase;">
                            Seneca
                        </span>
                    </div>

                </div>
            </div>
        </section>


        <!-- COMPETENZE TRASVERSALI -->

        <section class="references">
            <div class="container references-inner">

                <div>
                    <div class="section-label">04 / Competenze</div>

                    <h2 class="section-heading">
                        Skills
                    </h2>
                </div>

                <div>

                    <ul class="reference-list">
                        <li>Comunicazione istituzionale, politica e di crisi</li>
                        <li>Rappresentanza istituzionale</li>
                        <li>Mediazione</li>
                        <li>Selezione e gestione staff</li>
                        <li>Formazione crossmediale</li>
                        <li>Presentazione eventi</li>
                        <li>Problem solving</li>
                    </ul>

                </div>
            </div>
        </section>


        <!-- CONTATTI -->

        <section class="contact" id="contatti">
            <div class="container contact-inner">

                <div>
                    <div class="section-label">05 / Contatti professionali</div>

                    <h2>
                        Parliamo di comunicazione e strategia.
                    </h2>
                </div>

                <div class="contact-content">

                    <p>
                        Per consulenze, collaborazioni
                        e contatti professionali è possibile
                        utilizzare il mio profilo LinkedIn.
                    </p>

                    <a class="contact-button"
                       href="https://www.linkedin.com/in/mauber"
                       target="_blank"
                       rel="noopener noreferrer">
                        Profilo LinkedIn &nbsp; →
                    </a>

                </div>
            </div>
        </section>

    </main>


    <!-- FOOTER -->

    <footer>
        <div class="container footer-inner">

            <div>
                <div class="footer-name">Maurizio Bernardini</div>

                <div class="footer-meta">
                    Giornalista libero professionista<br>
                    P.IVA: 01792410530
                </div>
            </div>

            <div class="footer-links">
                <a href="#inizio">Torna all'inizio ↑</a>

                <a href="https://www.linkedin.com/in/mauber"
                   target="_blank"
                   rel="noopener noreferrer">
                    LinkedIn
                </a>
            </div>

        </div>
    </footer>


    <!-- PRIVACY -->

    <div class="privacy">
        <div class="container">

            <details>
                <summary>Informativa privacy</summary>

                <div class="privacy-content">

                    <p>
                        <strong>Titolare del trattamento:</strong>
                        Maurizio Bernardini, giornalista libero
                        professionista. P.IVA: 01792410530.
                        Contatti tramite il profilo
                        <a href="https://www.linkedin.com/in/mauber"
                           target="_blank"
                           rel="noopener noreferrer">
                            LinkedIn
                        </a>.
                    </p>

                    <p>
                        <strong>Dati e finalità:</strong>
                        la navigazione non richiede registrazione.
                        Il server o il servizio di hosting può
                        registrare dati tecnici di connessione,
                        quali indirizzo IP, browser e orario,
                        per esigenze di sicurezza e funzionamento.
                    </p>

                    <p>
                        I collegamenti verso servizi esterni,
                        tra cui LinkedIn e siti istituzionali,
                        sono soggetti alle rispettive informative.
                    </p>

                    <p>
                        Eventuali cookie tecnici sono utilizzati
                        per il funzionamento del sito.
                    </p>

                    <p>
                        <strong>Diritti dell'interessato:</strong>
                        ai sensi degli articoli 15-22 del GDPR,
                        è possibile esercitare i diritti di accesso,
                        rettifica, cancellazione, limitazione
                        e opposizione, nonché proporre reclamo
                        al Garante per la protezione dei dati personali.
                    </p>

                </div>
            </details>

        </div>
    </div>

</body>
</html>
