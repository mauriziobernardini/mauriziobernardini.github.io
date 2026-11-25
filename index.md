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
            --bg: #f4f6f9;
            --surface: #ffffff;
            --text: #1c242e;
            --muted: #5a6675;
            --navy: #0f2942;
            --accent: #0f4c81;
            --linkedin: #0077b5;
            --linkedin-hover: #005582;
            --border: #e2e8f0;
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
            background-color: var(--bg);
            color: var(--text);
            font-family: "Plus Jakarta Sans", system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
            line-height: 1.75;
            font-size: 16px;
            overflow-x: hidden;
        }

        .container {
            width: 100%;
            max-width: 820px;
            margin: 0 auto;
            padding: 0 20px;
        }

        .hero {
            background: linear-gradient(135deg, #0f2942 0%, #19456b 100%);
            color: #ffffff;
            padding: 52px 0 44px;
            border-bottom: 3px solid var(--linkedin);
        }

        .hero-kicker {
            display: block;
            font-size: 0.82rem;
            letter-spacing: 0.06em;
            text-transform: uppercase;
            color: #c8dcf0;
            margin-bottom: 10px;
            font-weight: 600;
        }

        .hero h1 {
            margin: 0 0 10px;
            font-family: "Newsreader", Georgia, serif;
            font-size: 2.45rem;
            line-height: 1.15;
            font-weight: 700;
            color: #ffffff;
        }

        .hero-subtitle {
            margin: 0;
            font-size: 1.08rem;
            color: #e6eff8;
            font-weight: 500;
        }

        main {
            padding: 32px 0 48px;
        }

        .sheet {
            background: var(--surface);
            border-radius: 10px;
            padding: 36px 40px;
            box-shadow:
                0 12px 30px rgba(15, 41, 66, 0.08),
                0 2px 8px rgba(15, 41, 66, 0.04);
            overflow-wrap: break-word;
            word-wrap: break-word;
        }

        .lead-highlight {
            font-family: "Newsreader", Georgia, serif;
            font-size: 1.25rem;
            line-height: 1.45;
            font-weight: 600;
            color: var(--navy);
            border-left: 3px solid var(--accent);
            padding-left: 14px;
            margin: 24px 0;
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
        }

        a:hover {
            color: var(--linkedin-hover);
        }

        h2 {
            margin: 34px 0 14px;
            padding-bottom: 8px;
            border-bottom: 1px solid var(--border);
            font-family: "Newsreader", Georgia, serif;
            font-size: 1.45rem;
            font-weight: 700;
            line-height: 1.3;
            color: var(--navy);
        }

        .btn-linkedin {
            display: inline-block;
            padding: 12px 22px;
            background-color: var(--linkedin);
            color: #ffffff;
            text-decoration: none;
            border-radius: 6px;
            font-weight: 600;
            margin-top: 6px;
            text-align: center;
            transition: background-color 0.2s ease;
        }

        .btn-linkedin:hover {
            background-color: var(--linkedin-hover);
            color: #ffffff;
        }

        .privacy-toggle {
            margin-top: 30px;
            padding-top: 14px;
            border-top: 1px solid var(--border);
            font-size: 0.82rem;
            color: var(--muted);
        }

        .privacy-toggle summary {
            cursor: pointer;
            display: inline-block;
            color: var(--muted);
            text-decoration: underline;
            text-underline-offset: 2px;
        }

        .privacy-toggle summary:hover {
            color: var(--accent);
        }

        .privacy-content {
            margin-top: 12px;
            padding-top: 10px;
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

        @media (max-width: 600px) {
            .container {
                padding: 0 14px;
            }
            .hero {
                padding: 36px 0 32px;
            }
            .hero-kicker {
                font-size: 0.78rem;
            }
            .hero h1 {
                font-size: 1.9rem;
            }
            .hero-subtitle {
                font-size: 1rem;
            }
            main {
                padding: 20px 0 36px;
            }
            .sheet {
                padding: 22px 16px;
                border-radius: 8px;
                box-shadow: 0 6px 20px rgba(15, 41, 66, 0.07);
            }
            .lead-highlight {
                font-size: 1.12rem;
            }
            h2 {
                font-size: 1.3rem;
                margin: 28px 0 12px;
            }
            body {
                font-size: 15.5px;
                line-height: 1.68;
            }
            .btn-linkedin {
                display: block;
                width: 100%;
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
        </div>
    </header>

    <main>
        <div class="container">
            <article class="sheet">
                <h2>Profilo e incarichi</h2>
                <p>Classe '82, Grosseto, sono un giornalista professionista e spin doctor italiano di comprovata esperienza, specializzato nella comunicazione istituzionale, politica e di crisi. Come consulente indipendente metto la mia strategia al servizio di diversi leader e partiti. Sono attivo soprattutto in Toscana, Emilia-Romagna, Lazio e Liguria, e ho lavorato in importanti città capoluogo tra cui Firenze, Bologna, Roma, Parma, Grosseto, Piacenza, Reggio Emilia e Imperia. Opero come libero professionista e consulente per committenti pubblici e privati, mantenendo un approccio indipendente e orientato esclusivamente al metodo. In questa veste tecnica, l'ultimo incarico che ho assunto è quello di coordinamento e indirizzo operativo dello staff di comunicazione per il gruppo assembleare di Forza Italia <a href="https://wwwservizi.regione.emilia-romagna.it/amministrazionetrasparente/Incarichi/RegioneEmiliaRomagna/Dettaglio/996" target="_blank" rel="noopener noreferrer">in Regione Emilia-Romagna</a>.</p>

                <p class="lead-highlight"><a href="https://jobseekeritalia.it/2016/03/16/professionisti-comunicazione-politica-digitale/" target="_blank" rel="noopener noreferrer">Riconosciuto tra i principali spin doctor italiani.</a></p>

                <h2>Giornalismo, formazione e strategia</h2>
                <p>La mia identità professionale si sviluppa lungo due binari paralleli e complementari: da un lato la solida esperienza sul campo nella cronaca bianca (politica, economia, sociale, attualità) per realtà televisive e digitali e importanti giornali come il quotidiano di Livorno <em>Il Tirreno</em> e l'edizione toscana del <em>Corriere della Sera</em>; dall'altro la gestione strategica dell'immagine e delle relazioni pubbliche per enti e politici di alto livello. Questa duplice natura mi consente di muovermi con competenza crossmediale, sia nella supervisione di contenuti complessi, sia nel coordinamento di uffici stampa istituzionali.</p>

                <p>Nel corso della mia attività ho collaborato, a vario titolo, anche durante i periodi elettorali, a strategie, organizzazione di conferenze stampa ed eventi che hanno visto al centro personalità di assoluto rilievo come vicepresidenti del Consiglio, ministri, vicepresidenti del Parlamento europeo, deputati, senatori, eurodeputati, consiglieri regionali e sindaci.</p>

                <p>Ho un solido percorso accademico: laurea in Storia conseguita a Bologna, laurea magistrale in Comunicazione digitale e Marketing e master in Giornalismo e comunicazione. Una formazione multidisciplinare che si riflette nella mia capacità di mediazione, problem solving e coordinamento di staff.</p>

                <p>La mia visione unisce la padronanza degli strumenti mediatici tradizionali e digitali a una spiccata attitudine alla rappresentanza istituzionale e alla mediazione politica e di crisi. Il tutto supportato da un costante aggiornamento sui temi chiave dell'informazione contemporanea, come il data journalism, la gestione della par condicio, il presidio televisivo, i sistemi elettorali e le applicazioni dell'intelligenza artificiale nel mondo della comunicazione.</p>

                <h2>Istituzioni, campagne elettorali e collaborazioni</h2>
                <p>Come giornalista politico e spin doctor ho guidato numerose campagne elettorali per forze politiche e civiche in ambito locale, regionale e nazionale, occupandomi in prima persona del posizionamento dei candidati e della scelta dei relativi staff, dell'elaborazione di discorsi, del media training, della gestione dei rapporti con la stampa e delle strategie di comunicazione, compresi i social.</p>

                <p>Nella mia carriera ho creato e gestito numerosi staff di giornalisti e professionisti di settore, riuscendo ad accrescere il consenso dei miei committenti e a mantenere equilibri delicati.</p>

                <p>Forte anche il mio impegno in ambito istituzionale. Su questo fronte, tra le personalità seguite si segnalano il sindaco di Grosseto Antonfrancesco Vivarelli Colonna (<a href="https://www.comune.grosseto.it/persona_pubblica/bernardini-maurizio/" target="_blank" rel="noopener noreferrer">Capo ufficio stampa del Comune</a>) e il sindaco e presidente della Provincia di Imperia ed ex ministro Claudio Scajola, per il quale sono stato Portavoce, Capo di Gabinetto e responsabile del settore comunicazione. In passato ho inoltre ricoperto il ruolo di Capo comunicazione del Movimento 5 Stelle in <a href="https://trasparenza.consiglio.regione.toscana.it/node/26930" target="_blank" rel="noopener noreferrer">Regione Toscana</a>.</p>

                <p>Sono stato inoltre spin doctor di personalità influenti come l'ex coordinatore toscano della Lega e deputato Mario Lolini e l'ex sindaco di Parma, attuale capogruppo in Regione Emilia-Romagna per Forza Italia e segretario regionale Pietro Vignali. Ho inoltre curato la comunicazione politica della campagna elettorale del Movimento 5 Stelle di Grosseto del 2016 (candidato sindaco Giacomo Gori) con il record del 20% dei voti ottenuti, tra i migliori risultati di sempre del M5S in Italia alle Amministrative nei centri urbani di rilievo.</p>

                <p>Come dimostrato dai risultati elettorali nelle campagne seguite e dai record conseguiti, sono anche specializzato nella ricerca del consenso legato al sistema delle preferenze.</p>

                <p>In passato ho inoltre prestato la mia professionalità per l'Istituto storico grossetano della Resistenza e dell'età contemporanea, per la cooperativa fiorentina Cooplat e per esponenti del Partito Democratico.</p>

                <h2>Contatti e Riferimenti</h2>
                <p>Per consulenze e contatti professionali:</p>
                <a class="btn-linkedin" href="https://www.linkedin.com/in/mauber" target="_blank" rel="noopener noreferrer">Il mio profilo LinkedIn</a>

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
