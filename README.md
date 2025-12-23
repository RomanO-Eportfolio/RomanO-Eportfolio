<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <title>Roman Opryshko — Mechanical Engineering Intern</title>
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <meta name="description" content="Roman Opryshko — Mechanical Engineering student and manufacturing intern skilled in CAD, manufacturing processes, and engineering support." />

  <!-- JSON-LD for basic Person schema -->
  <script type="application/ld+json">
  {
    "@context": "https://schema.org",
    "@type": "Person",
    "name": "Roman Opryshko",
    "jobTitle": "Mechanical Engineering Intern",
    "email": "mailto:RomnOpryshko@gmail.com",
    "address": {
      "@type": "PostalAddress",
      "addressLocality": "Westfield",
      "addressRegion": "NJ",
      "addressCountry": "US"
    }
  }
  </script>

  <style>
    :root{
      --bg: #f5f7fa;
      --card: #ffffff;
      --muted: #6b7280;
      --text: #111827;
      --accent: #1f2933;
      --link: #2563eb;
      --border: #e5e7eb;
      --radius: 10px;
      --max-width: 900px;
      --gap: 1rem;
      --print-font-size: 12pt;
    }

    *{box-sizing:border-box}
    html,body{height:100%}
    body{
      margin:0;
      font-family: -apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,"Helvetica Neue",Arial;
      background:var(--bg);
      color:var(--text);
      line-height:1.5;
      -webkit-font-smoothing:antialiased;
      -moz-osx-font-smoothing:grayscale;
      padding:2rem 1rem;
      display:flex;
      justify-content:center;
    }

    /* Layout container */
    .container{
      width:100%;
      max-width:var(--max-width);
      background:linear-gradient(180deg, rgba(255,255,255,0.85), rgba(255,255,255,0.95));
      border-radius:var(--radius);
      box-shadow:0 6px 24px rgba(15,23,42,0.08);
      overflow:hidden;
      display:grid;
      grid-template-columns: 1fr;
    }

    /* Skip link for keyboard users */
    .skip-link{
      position:absolute;
      left:-999px;
      top:auto;
      width:1px;
      height:1px;
      overflow:hidden;
    }
    .skip-link:focus{
      left:1rem;
      top:1rem;
      width:auto;
      height:auto;
      padding:.5rem .75rem;
      background:#111827;
      color:white;
      border-radius:6px;
      z-index:1000;
    }

    header.site-header{
      background:var(--accent);
      color: #fff;
      padding:1.5rem;
      text-align:center;
    }
    header .name{
      font-size:1.6rem;
      font-weight:700;
      letter-spacing:0.2px;
    }
    header .subtitle{
      margin-top:.25rem;
      color: #d1d5db;
      font-size: .95rem;
    }
    header .contact{
      margin-top:.5rem;
      font-size:.9rem;
      color: #e6eefc;
    }
    header a.contact-link{
      color:var(--link);
      text-decoration:underline;
    }

    main{
      padding:1.5rem;
    }

    section{
      margin-bottom:1rem;
    }

    h2{
      font-size:1rem;
      margin-bottom:.6rem;
      border-bottom:2px solid var(--border);
      padding-bottom:.4rem;
      color:var(--text);
    }

    h3{
      margin: .6rem 0 .2rem;
      font-size:.98rem;
      color:var(--accent);
    }

    p, li{
      font-size:.96rem;
      color: #263238;
    }

    .skills{
      display:grid;
      grid-template-columns: repeat(auto-fit, minmax(180px,1fr));
      gap:.4rem .75rem;
      list-style:none;
      padding-left:0;
    }
    .skills li{
      background:linear-gradient(180deg,#fff,#fbfdff);
      border:1px solid var(--border);
      padding:.45rem .6rem;
      border-radius:8px;
      font-size:.9rem;
    }

    .role{
      font-weight:700;
      margin-top:.25rem;
      color:#111827;
    }

    ul.job-bullets{
      margin-top:.4rem;
      margin-left:1.1rem;
    }
    ul.job-bullets li{margin-bottom:.35rem}

    footer.site-footer{
      background:var(--border);
      padding:.8rem 1.5rem;
      text-align:center;
      font-size:.9rem;
      color:var(--muted);
    }

    /* Responsive two-column layout for wider screens */
    @media (min-width:880px){
      .container{
        grid-template-columns: 320px 1fr;
      }
      header.site-header{
        grid-column: 1 / 2;
        display:flex;
        flex-direction:column;
        align-items:flex-start;
        padding:1.25rem;
        gap:.5rem;
      }
      header .name{font-size:1.4rem}
      main{padding:1.5rem 1.5rem}
      /* Make header sticky column look like side panel */
      .side-panel{
        background:var(--accent);
        color:white;
        padding:1.5rem;
        display:flex;
        flex-direction:column;
        gap:.5rem;
        min-height:100%;
      }
      .contact-row{margin-top:.25rem}
      .container header.side-panel + main{grid-column:2 / 3}
    }

    /* Focus outlines for accessibility */
    a:focus, button:focus { outline:3px solid #cfe8ff; outline-offset:2px; }

    /* Print styles
