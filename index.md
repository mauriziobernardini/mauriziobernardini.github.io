
<html lang="it">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Maurizio Bernardini - Giornalista professionista e spin doctor</title>
    <meta name="description" content="Maurizio Bernardini, giornalista professionista e spin doctor specializzato in comunicazione istituzionale, politica e di crisi.">
    <meta name="google-site-verification" content="8d9043db9f5a90f1" />
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Newsreader:opsz,wght@6..72,500;6..72,600;6..72,700&family=Plus+Jakarta+Sans:wght@400;500;600;700&display=swap" rel="stylesheet">
    <style>
        :root {
            --bg: #eef2f6;
            --surface: #ffffff;
            --surface-soft: #f7f9fc;
            --text: #18202c;
            --muted: #526071;
            --navy: #0b243e;
            --navy-mid: #163d66;
            --accent: #0f4c81;
            --accent-warm: #b45309;
            --linkedin: #0077b5;
            --linkedin-hover: #005582;
            --border: #dde4ec;
            --radius: 12px;
        }

        *, *::before, *::after {
            box-sizing: border-box;
        }

        html {
            scroll-behavior: smooth;
            -webkit-text-size-adjust: 100%;
        }

        body {
            margin: 0;
            background:
                radial-gradient(circle at top right, rgba(15, 76, 129, 0.06), transparent 42%),
                var(--bg);
            color: var(--text);
            font-family: "Plus Jakarta Sans", system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
            line-height: 1.75;
            font-size: 16px;
            overflow-x: hidden;
        }

        .container {
            width: 100%;
            max-width: 880px;
            margin: 0 auto;
            padding: 0 20px;
        }

        .hero {
            position: relative;
            background:
                radial-gradient(circle at 88% 18%, rgba(56, 149, 211, 0.22), transparent 45%),
                linear-gradient(135deg, var(--navy) 0%, var(--navy-mid) 100%);
            color: #ffffff;
            padding: 60px 0 52px;
            border-bottom: 4px solid var(--linkedin);
            box-shadow: 0 10px 28px rgba(11, 36, 62, 0.16);
        }

        .hero-kicker {
            display: inline-block;
            font-size: 0.78rem;
            letter-spacing: 0.09em;
            text-transform: uppercase;
            color: #d6e8fa;
            background: rgba(255, 255, 255, 0.09);
            border: 1px solid rgba(255, 255, 255, 0.16);
            padding: 5px 12px;
            border-radius: 999px;
            margin-bottom: 16px;
            font-weight: 600;
        }

        .hero h1 {
            margin: 0 0 12px;
            font-family: "Newsreader", Georgia, serif;
            font-size: 2.65rem;
            line-height: 1.12;
            font-weight: 700;
            letter-spacing: -0.015em;
            color: #ffffff;
        }

        .hero-subtitle {
            margin: 0 0 24px;
            font-size: 1.12rem;
            color: #e8f1fa;
            max-width: 680px;
            font-weight: 500;
        }

        .hero-nav {
            display: flex;
            flex-wrap: wrap;
            gap: 8px;
        }

        .hero-nav a {
            display: inline-block;
            color: #f1f7fd;
            background: rgba(255, 255, 255, 0.08);
            border: 1px solid rgba(255, 255, 255, 0.18);
            text-decoration: none;
            font-size: 0.85rem;
            font-weight: 500;
            padding: 6px 13px;
            border-radius: 6px;
            transition: background-color 0.2s ease, border-color 0.2s ease, transform 0.15s ease;
        }

        .hero-nav a:hover {
            background: rgba(255, 255, 255, 0.18);
            border-color: rgba(255, 255, 255, 0.35);
            transform: translateY(-1px);
        }

        main {
            padding: 34px 0 52px;
        }

        .highlights-strip {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 14px;
            margin-bottom: 22px;
        }

        .highlight-box {
            background: var(--surface);
            border: 1px solid var(--border);
            border-radius: 10px;
            padding: 15px 16px;
            box-shadow: 0 4px 12px rgba(11, 36, 62, 0.04);
        }

        .highlight-label {
            display: block;
            font-size: 0.75rem;
            text-transform: uppercase;
            letter-spacing: 0.06em;
            color: var(--muted);
            font-weight: 700;
            margin-bottom: 4px;
        }

        .highlight-value {
            display: block;
            font-size: 0.94rem;
            font-weight: 600;
            color: var(--navy);
            line-height: 1.35;
        }

        .card {
            background: var(--surface);
            border: 1px solid var(--border);
            border-top: 4px solid var(--accent);
            border-radius: var(--radius);
            padding: 38px 40px;
            box-shadow:
                0 16px 36px -10px rgba(11, 36, 62, 0.10),
                0 4px 12px -2px rgba(11, 36, 62, 0.05);
            overflow-wrap: break-word;
            word-wrap: break-word;
        }

        .lead-highlight {
            font-family: "Newsreader", Georgia, serif;
            font-size: 1.32rem;
            line-height: 1.42;
            font-weight: 600;
            color: var(--navy);
            background: linear-gradient(90deg, rgba(15, 76, 129, 0.07) 0%, rgba(15, 76, 129, 0.01) 100%);
            border-left: 4px solid var(--accent-warm);
            padding: 14px 18px;
            border-radius: 0 8px 8px 0;
            margin: 26px 0;
        }

        .lead-highlight a {
            color: var(--navy);
            text-decoration-color: rgba(180, 83, 9, 0.55);
        }

        p {
            margin: 0 0 18px;
            text-align: left;
        }

        a {
            color: var(--accent);
            text-decoration: underline;
            text-decoration-thickness: 1.5px;
            text-underline-offset: 3px;
            overflow-wrap: break-word;
            transition: color 0.18s ease;
        }

        a:hover {
            color: var(--linkedin-hover);
        }

        h2 {
            margin: 38px 0 16px;
            padding-left: 14px;
            border-left: 4px solid var(--accent);
            font-family: "Newsreader", Georgia, serif;
            font-size: 1.55rem;
            font-weight: 700;
            line-height: 1.25;
            color: var(--navy);
        }

        .contact-panel {
            margin-top: 16px;
            padding: 22px 24px;
            background: var(--surface-soft);
            border: 1px solid var(--border);
            border-radius: 10px;
        }

        .contact-panel p {
            margin-bottom: 12px;
            color: var(--muted);
            font-weight: 500;
        }

        .btn-linkedin {
            display: inline-flex;
            align-items: center;
            justify-content: center;
            gap: 8px;
            padding: 12px 24px;
            background: linear-gradient(180deg, #0082c8 0%, var(--linkedin) 100%);
            color: #ffffff;
            text-decoration: none;
            border-radius: 8px;
            font-weight: 600;
            font-size: 0.96rem;
            box-shadow: 0 4px 12px rgba(0, 119, 181, 0.25);
            transition: background-color 0.2s ease, transform 0.15s ease, box-shadow 0.2s ease;
        }

        .btn-linkedin:hover {
            background: linear-gradient(180deg, #006da8 0%, var(--linkedin-hover) 100%);
            color: #ffffff;
            transform: translateY(-1px);
            box-shadow: 0 6px 16px rgba(0, 119, 181, 0.32);
        }

        .privacy-toggle {
            margin-top: 30px;
            padding-top: 16px;
            border-top: 1px solid var(--border);
            font-size: 0.82rem;
            color: var(--muted);
        }

        .privacy-toggle summary {
            cursor: pointer;
            display: inline-block;
            color: var(--muted);
            font-weight: 600;
            text-decoration: underline;
            text-underline-offset: 2px;
        }

        .privacy-toggle summary:hover {
            color: var(--accent);
        }

        .privacy-content {
            margin-top: 12px;
            padding: 16px 18px;
            background: var(--surface-soft);
            border-radius: 8px;
            border: 1px solid var(--border);
            font-size: 0.83rem;
            line-height: 1.6;
        }

        .privacy-content p {
            margin-bottom: 10px;
        }

        .privacy-content p:last-child {
            margin-bottom: 0;
        }

        .site-footer {
            background: var(--surface);
            border-top: 1px solid var(--border);
            padding: 24px 0;
            font-size: 0.9rem;
            color: var(--muted);
        }

        .footer-inner {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-between;
            gap: 12px;
            align-items: center;
        }

        @media (max-width: 760px) {
            .highlights-strip {
                grid-template-columns: 1fr;
                gap: 10px;
            }
        }

        @media (max-width: 600px) {
            .container {
                padding: 0 14px;
            }
            .hero {
                padding: 38px 0 34px;
            }
            .hero-kicker {
                font-size: 0.72rem;
                margin-bottom: 12px;
            }
            .hero h1 {
                font-size: 2rem;
            }
            .hero-subtitle {
                font-size: 1rem;
                margin-bottom: 18px;
            }
            .hero-nav {
                gap: 6px;
            }
            .hero-nav a {
                font-size: 0.8rem;
                padding: 5px 10px;
            }
            main {
                padding: 20px 0 36px;
            }
            .card {
                padding: 22px 16px;
                border-radius: 10px;
                box-shadow: 0 8px 22px -6px rgba(11, 36, 62, 0.09);
            }
            .lead-highlight {
                font-size: 1.14rem;
                padding: 12px 14px;
            }
            h2 {
                font-size: 1.35rem;
                margin: 30px 0 12px;
            }
            .contact-panel {
                padding: 18px 16px;
            }
            body {
                font-size: 15.5px;
                line-height: 1.68;
            }
            .btn-linkedin {
                display: flex;
                width: 100%;
            }
            .btn-linkedin:hover {
                transform: none;
            }
        }
    </style>
</head>
<body>

    <header class="hero">
        <div class="container">
            <span class="hero-kicker">Comunicazione istituzionale, politica e di crisi</span>
            <h1>Maurizio Bernardini</h1>
            <p class="hero-subtitle"><strong>Giornalista professionista e spin doctor</strong></p>
            <nav class="hero-nav" aria-label="Sezioni della pagina">
                <a href="#profilo">Profilo</a>
                <a href="#giornalismo-strategia">Giornalismo e strategia</a>
                <a href="#istituzioni-campagne">Istituzioni e campagne</a>
                <a href="#contatti">Contatti</a>
            </nav>
        </div>
    </header>

    <main>
        <div class="container">
            <section class="highlights-strip" aria-label="Sintesi del profilo">
                <div class="highlight-box">
                    <span class="highlight-label">Specializzazione</span>
                    <span class="highlight-value">Comunicazione istituzionale, politica e di crisi</span>
                </div>
                <div class="highlight-box">
                    <span class="highlight-label">Ambito geografico</span>
                    <span class="highlight-value">Toscana, Emilia-Romagna, Lazio e Liguria</span>
                </div>
                <div class="highlight-box">
                    <span class="highlight-label">Inquadramento</span>
                    <span class="highlight-value">Giornalista libero professionista e consulente</span>
                </div>
            </section>

            <article class="card">
                <h2 id="profilo">Profilo e incarichi</h2>
                <p>Classe '82, Grosseto, sono un giornalista professionista e spin doctor italiano di comprovata esperienza, specializzato nella comunicazione istituzionale, politica e di crisi. Come consulente indipendente metto la mia strategia al servizio di diversi leader e partiti. Sono attivo soprattutto in Toscana, Emilia-Romagna, Lazio e Liguria, e ho lavorato in importanti città capoluogo tra cui Firenze, Bologna, Roma, Parma, Grosseto, Piacenza, Reggio Emilia e Imperia. Opero come libero professionista e consulente per committenti pubblici e privati, mantenendo un approccio indipendente e orientato esclusivamente al metodo. In questa veste tecnica, l'ultimo incarico che ho assunto è quello di coordinamento e indirizzo operativo dello staff di comunicazione per il gruppo assembleare di Forza Italia <a href="https://wwwservizi.regione.emilia-romagna.it/amministrazionetrasparente/Incarichi/RegioneEmiliaRomagna/Dettaglio/996" target="_blank" rel="noopener noreferrer">in Regione Emilia-Romagna</a>.</p>

                <p class="lead-highlight"><a href="https://jobseekeritalia.it/2016/03/16/professionisti-comunicazione-politica-digitale/" target="_blank" rel="noopener noreferrer">Riconosciuto tra i principali spin doctor italiani.</a></p>

                <h2 id="giornalismo-strategia">Giornalismo, formazione e strategia</h2>
                <p>La mia identità professionale si sviluppa lungo due binari paralleli e complementari: da un lato la solida esperienza sul campo nella cronaca bianca (politica, economia, sociale, attualità) per realtà televisive e digitali e importanti giornali come il quotidiano di Livorno <em>Il Tirreno</em> e l'edizione toscana del <em>Corriere della Sera</em>; dall'altro la gestione strategica dell'immagine e delle relazioni pubbliche per enti e politici di alto livello. Questa duplice natura mi consente di muovermi con competenza crossmediale, sia nella supervisione di contenuti complessi, sia nel coordinamento di uffici stampa istituzionali.</p>

                <p>Nel corso della mia attività ho collaborato, a vario titolo, anche durante i periodi elettorali, a strategie, organizzazione di conferenze stampa ed eventi che hanno visto al centro personalità di assoluto rilievo come vicepresidenti del Consiglio, ministri, vicepresidenti del Parlamento europeo, deputati, senatori, eurodeputati, consiglieri regionali e sindaci.</p>

                <p>Ho un solido percorso accademico: laurea in Storia conseguita a Bologna, laurea magistrale in Comunicazione digitale e Marketing e master in Giornalismo e comunicazione. Una formazione multidisciplinare che si riflette nella mia capacità di mediazione, problem solving e coordinamento di staff.</p>

                <p>La mia visione unisce la padronanza degli strumenti mediatici tradizionali e digitali a una spiccata attitudine alla rappresentanza istituzionale e alla mediazione politica e di crisi. Il tutto supportato da un costante aggiornamento sui temi chiave dell'informazione contemporanea, come il data journalism, la gestione della par condicio, il presidio televisivo, i sistemi elettorali e le applicazioni dell'intelligenza artificiale nel mondo della comunicazione.</p>

                <h2 id="istituzioni-campagne">Istituzioni, campagne elettorali e collaborazioni</h2>
                <p>Come giornalista politico e spin doctor ho guidato numerose campagne elettorali per forze politiche e civiche in ambito locale, regionale e nazionale, occupandomi in prima persona del posizionamento dei candidati e della scelta dei relativi staff, dell'elaborazione di discorsi, del media training, della gestione dei rapporti con la stampa e delle strategie di comunicazione, compresi i social.</p>

                <p>Nella mia carriera ho creato e gestito numerosi staff di giornalisti e professionisti di settore, riuscendo ad accrescere il consenso dei miei committenti e a mantenere equilibri delicati.</p>

                <p>Forte anche il mio impegno in ambito istituzionale. Su questo fronte, tra le personalità seguite si segnalano il sindaco di Grosseto Antonfrancesco Vivarelli Colonna (<a href="https://www.comune.grosseto.it/persona_pubblica/bernardini-maurizio/" target="_blank" rel="noopener noreferrer">Capo ufficio stampa del Comune</a>) e il sindaco e presidente della Provincia di Imperia ed ex ministro Claudio Scajola, per il quale sono stato Portavoce, Capo di Gabinetto e responsabile del settore comunicazione. In passato ho inoltre ricoperto il ruolo di Capo comunicazione del Movimento 5 Stelle in <a href="https://trasparenza.consiglio.regione.toscana.it/node/26930" target="_blank" rel="noopener noreferrer">Regione Toscana</a>.</p>

                <p>Sono stato inoltre spin doctor di personalità influenti come l'ex coordinatore toscano della Lega e deputato Mario Lolini e l'ex sindaco di Parma, attuale capogruppo in Regione Emilia-Romagna per Forza Italia e segretario regionale Pietro Vignali. Ho inoltre curato la comunicazione politica della campagna elettorale del Movimento 5 Stelle di Grosseto del 2016 (candidato sindaco Giacomo Gori) con il record del 20% dei voti ottenuti, tra i migliori risultati di sempre del M5S in Italia alle Amministrative nei centri urbani di rilievo.</p>

                <p>Come dimostrato dai risultati elettorali nelle campagne seguite e dai record conseguiti, sono anche specializzato nella ricerca del consenso legato al sistema delle preferenze.</p>

                <p>In passato ho inoltre prestato la mia professionalità per l'Istituto storico grossetano della Resistenza e dell'età contemporanea, per la cooperativa fiorentina Cooplat e per esponenti del Partito Democratico.</p>

                <h2 id="contatti">Contatti e Riferimenti</h2>
                <div class="contact-panel">
                    <p>Per consulenze e contatti professionali:</p>
                    <a class="btn-linkedin" href="https://www.linkedin.com/in/mauber" target="_blank" rel="noopener noreferrer">Il mio profilo LinkedIn</a>
                </div>

                <details id="privacy" class="privacy-toggle">
                    <summary>Privacy</summary>
                    <div class="privacy-content">
                        <p><strong>Titolare del trattamento:</strong> Maurizio Bernardini, Giornalista libero professionista — P.IVA: 01792410530. Contatti tramite profilo <a href="https://www.linkedin.com/in/mauber" target="_blank" rel="noopener noreferrer">LinkedIn</a>.</p>
                        <p><strong>Dati e finalità:</strong> La navigazione non richiede registrazione. Il server/hosting può registrare solo dati tecnici di connessione (IP, browser, orario) per sicurezza e funzionamento. Link esterni (LinkedIn, enti) seguono le rispettive informative. Eventuali cookie sono solo tecnici.</p>
                        <p><strong>Diritti GDPR (artt. 15–22):</strong> Accesso, rettifica, cancellazione, limitazione, opposizione e reclamo al Garante per la protezione dei dati personali.</p>
                    </div>
                </details>
            </article>
        </div>
    </main>

    <footer class="site-footer">
        <div class="container footer-inner">
            <span>Maurizio Bernardini – Giornalista libero professionista | P.IVA: 01792410530</span>
        </div>
    </footer>

</body>
</html>
