<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <meta name="theme-color" content="#fcf8f3">
  <meta name="description" content="Assistance et contact pour Menstoria.">
  <title>Assistance · Menstoria</title>

  <style>
    * { box-sizing: border-box; }

    body {
      margin: 0;
      min-height: 100svh;
      display: flex;
      flex-direction: column;
      background: #fcf8f3;
      color: #492d3b;
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
    }

    header {
      padding: 25px;
      border-bottom: 1px solid #eadcda;
      text-align: center;
      font: 28px Georgia, serif;
    }

    header span { color: #a54166; }

    main {
      flex: 1;
      width: 100%;
      max-width: 650px;
      margin: auto;
      padding: 65px 24px;
      text-align: center;
    }

    .flower {
      display: grid;
      place-items: center;
      width: 80px;
      height: 80px;
      margin: 0 auto 25px;
      border-radius: 50%;
      background: #f4e2e5;
      color: #a54166;
      font-size: 45px;
    }

    .label {
      color: #a54166;
      font-size: 11px;
      font-weight: 600;
      letter-spacing: 3px;
      text-transform: uppercase;
    }

    h1 {
      margin: 20px 0;
      font: 48px/1.1 Georgia, serif;
      letter-spacing: -1.5px;
    }

    h1 em { color: #a54166; }

    p {
      color: #75616a;
      font-size: 15px;
      line-height: 1.8;
    }

    .contact {
      margin: 30px 0;
      padding: 30px 20px;
      background: #fffdf9;
      border: 1px solid #eadcda;
      border-radius: 24px;
    }

    .email {
      color: #a54166;
      font-size: 14px;
      overflow-wrap: anywhere;
      text-underline-offset: 4px;
    }

    .button {
      display: inline-block;
      margin-top: 22px;
      padding: 15px 26px;
      border-radius: 40px;
      background: #492d3b;
      color: white;
      font-size: 14px;
      text-decoration: none;
    }

    .button:hover { background: #a54166; }

    a:focus-visible, summary:focus-visible {
      outline: 3px solid #a54166;
      outline-offset: 5px;
    }

    .faq { text-align: left; }

    details {
      padding: 20px 0;
      border-bottom: 1px solid #eadcda;
    }

    summary {
      cursor: pointer;
      font-size: 15px;
      font-weight: 500;
      line-height: 1.6;
    }

    details p { margin-bottom: 0; }

    details a { color: #a54166; }

    footer {
      padding: 24px;
      text-align: center;
      color: #75616a;
      font-size: 12px;
    }

    @media (max-width: 400px) {
      main { padding: 45px 20px; }
      h1 { font-size: 40px; }
    }
  </style>
</head>

<body>
  <header>Menstoria<span>.</span></header>

  <main>
    <div class="flower" aria-hidden="true">✿</div>
    <div class="label">À ton écoute</div>

    <h1>Un peu d’aide,<br><em>beaucoup de douceur.</em></h1>

    <p>
      Une question sur Menstoria ou un souci avec l’application ?
      Contacte-nous, nous sommes là pour t’aider.
    </p>

    <div class="contact">
      <p>Pour contacter l’assistance :</p>

      <a class="email" href="mailto:sagetpaulhenry250@gmail.com">
        sagetpaulhenry250@gmail.com
      </a>

      <br>

      <a
        class="button"
        href="mailto:sagetpaulhenry250@gmail.com?subject=Assistance%20Menstoria"
      >
        Nous écrire ↗
      </a>
    </div>

    <div class="faq">
      <details>
        <summary>Comment résilier mon abonnement ?</summary>
        <p>
          Sur iPhone, ouvre Réglages → ton nom → Abonnements →
          Menstoria. Supprimer l’application ne résilie pas
          l’abonnement.
        </p>
      </details>

      <details>
        <summary>Comment restaurer mes achats ?</summary>
        <p>
          Utilise « Restaurer les achats » sur l’écran d’abonnement,
          avec le compte Apple utilisé lors de l’achat.
          Cette action restaure l’accès, pas les données du journal.
        </p>
      </details>

      <details>
        <summary>Comment supprimer mes données ?</summary>
        <p>
          Dans Menstoria, ouvre Profil → Réinitialiser l’app,
          puis confirme pour effacer le profil et le journal actifs.
          Cela ne résilie pas ton abonnement.
        </p>
      </details>

      <details>
        <summary>Comment signaler un problème ?</summary>
        <p>
          Écris-nous en précisant le modèle de ton appareil,
          la version de l’application et le problème rencontré.
          Masque tes informations personnelles sur les captures
          et ne transmets pas de données médicales inutiles.
        </p>
      </details>
    </div>

    <p style="margin-top: 30px; font-size: 12px;">
      Pour une question médicale, consulte un professionnel de santé.
      L’assistance Menstoria répond aux questions techniques.
    </p>
  </main>

  <footer>© 2026 Menstoria · À l’écoute de toi.</footer>
</body>
</html>
