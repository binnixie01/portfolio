<script>
  import "../app.css";
  import { injectAnalytics } from '@vercel/analytics/sveltekit'
</script>

<svelte:head>
  <!-- PAGE TITLE -->
  <title>Thangjam Binson Singh | Frontend Developer</title>

  <!-- BASIC SEO -->
  <meta name="description" content="Portfolio of Thangjam Binson Singh — Frontend Developer specializing in Svelte, SvelteKit, JavaScript, and modern UI development.">
  <meta name="keywords" content="Thangjam Binson Singh, Binson Thangjam, frontend developer, svelte developer, sveltekit developer, javascript developer, manipur developer">
  <meta name="author" content="Thangjam Binson Singh">

  <!-- OPEN GRAPH (SOCIAL PREVIEW) -->
  <meta property="og:title" content="Thangjam Binson Singh | Frontend Developer">
  <meta property="og:description" content="Frontend Developer specializing in Svelte, SvelteKit, JavaScript, and UI engineering.">
  <meta property="og:type" content="website">

  <!-- Replace this URL AFTER deploying -->
  <meta property="og:url" content="https://https://binsonthangjam.vercel.app">

  <!-- FAVICON -->
  <link rel="icon" href="/favicon.ico" />

  <link rel="canonical" href="https://binsonthangjam.vercel.app" />

  <script type="application/ld+json">
    {
      "@context": "https://schema.org",
      "@type": "Person",
      "name": "Thangjam Binson Singh",
      "jobTitle": "Frontend Developer",
      "url": "https://binsonthangjam.vercel.app",
      "sameAs": [
        "https://github.com/binnixie01",
        "https://www.linkedin.com/in/binson-thangjam"
      ]
    }
  </script>
</svelte:head>

<slot />
