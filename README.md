<!DOCTYPE html>
        <html>
          <head>
            <title data-id="th-modified">Web Page</title>
            
          <meta property="og:title" content="Web Page" data-id="th-modified"><meta name="description" content="code" data-id="th-modified"><meta property="og:description" content="code" data-id="th-modified"><meta property="og:image" content="https://presentacionb2b.tiiny.site/og-image.jpeg" data-id="th-modified"><meta property="og:url" content="https://presentacionb2b.tiiny.site/" data-id="th-modified"><meta property="og:type" content="website" data-id="th-modified"><script defer data-domain="presentacionb2b.tiiny.site" src="https://analytics.tiiny.site/js/plausible.js"></script></head>
          <body>
            <!doctype html>
<html lang="es">
<head>
  <meta charset="UTF-8" >
  <meta name="viewport" content="width=device-width, initial-scale=1.0" >
  <title>Representación para Compradores | Isaac Uribe</title>

  <!-- Tailwind CDN -->
  <script src="https://cdn.tailwindcss.com"></script>

  <style>
    /* micro-animaciones suaves sin framer */
    .fade-up { opacity: 0; transform: translateY(14px); animation: fadeUp .7s ease forwards; }
    .fade-up.delay-1 { animation-delay: .08s; }
    .fade-up.delay-2 { animation-delay: .16s; }
    @keyframes fadeUp { to { opacity: 1; transform: translateY(0); } }
  </style>
</head>

<body class="min-h-screen bg-neutral-950 text-neutral-100">
  <script>
    // =========================
    // Variables editables
    // =========================
    const officeName = "CENTURY 21";
    const advisorName = "Isaac Uribe";
    const city = "Guadalajara y Zona Metropolitana";
    const whatsappPhone = "+523316045758"; // E.164 recomendado
    const zoomSchedulerUrl = "https://scheduler.zoom.us/isaac-uribe";

    const brand = {
      gold: "#BEAF87",
      darkGold: "#A19276",
    };

    // helper: wa.me
    function buildWaUrl(text){
      const clean = whatsappPhone.replace(/[^\d+]/g, "");
      const digits = clean.startsWith("+") ? clean.slice(1) : clean;
      return `https://wa.me/${digits}?text=${encodeURIComponent(text)}`;
    }
  </script>

  <!-- Background blobs -->
  <div class="pointer-events-none fixed inset-0 overflow-hidden">
    <div class="absolute -top-40 left-1/2 h-[520px] w-[820px] -translate-x-1/2 rounded-full blur-3xl"
      style="background: radial-gradient(circle at 50% 50%, rgba(190,175,135,0.25), rgba(37,37,38,0));">
    </div>
    <div class="absolute bottom-[-220px] right-[-140px] h-[520px] w-[520px] rounded-full blur-3xl"
      style="background: radial-gradient(circle at 30% 30%, rgba(161,146,118,0.22), rgba(37,37,38,0));">
    </div>
  </div>

  <!-- Header -->
  <header class="relative z-10">
    <div class="mx-auto flex max-w-6xl items-center justify-between px-5 py-5 sm:px-8">
      <div class="flex items-center gap-3">
        <div class="flex h-10 w-10 items-center justify-center rounded-2xl border"
          style="border-color: rgba(190,175,135,0.35); background-color: rgba(190,175,135,0.10);">
          <span class="text-sm font-semibold" style="color: #BEAF87;">21</span>
        </div>
        <div class="leading-tight">
          <p class="text-sm font-semibold text-neutral-100" id="h-name"></p>
          <p class="text-xs text-neutral-400" id="h-sub"></p>
        </div>
      </div>

      <div class="hidden items-center gap-3 sm:flex">
        <a id="btn-zoom-top"
          class="inline-flex w-full items-center justify-center rounded-2xl border border-neutral-700/70 bg-neutral-950/40 px-5 py-3 text-sm font-semibold text-neutral-100 backdrop-blur transition hover:border-neutral-500 active:translate-y-[1px]"
          target="_blank" rel="noopener noreferrer">
          Agendar Zoom
        </a>
        <a id="btn-wa-top"
          class="inline-flex w-full items-center justify-center rounded-2xl px-5 py-3 text-sm font-semibold text-neutral-900 shadow-[0_12px_30px_rgba(0,0,0,0.35)] transition hover:brightness-105 active:translate-y-[1px]"
          style="background: linear-gradient(135deg, #BEAF87, #A19276);"
          target="_blank" rel="noopener noreferrer">
          WhatsApp
        </a>
      </div>
    </div>
  </header>

  <!-- Hero -->
  <section class="relative z-10">
    <div class="mx-auto grid max-w-6xl grid-cols-1 gap-10 px-5 pb-12 pt-6 sm:px-8 lg:grid-cols-12 lg:items-center lg:gap-10 lg:pb-16">
      <div class="lg:col-span-7 fade-up">
        <p class="inline-flex items-center gap-2 rounded-full border border-neutral-800/70 bg-neutral-950/40 px-4 py-2 text-xs font-semibold text-neutral-300">
          <span class="h-2 w-2 rounded-full" style="background-color: #BEAF87;"></span>
          Llamada estratégica (15 min): sales con plan y próximos pasos.
        </p>

        <h1 class="mt-5 text-3xl font-semibold leading-tight text-neutral-100 sm:text-4xl">
          ¿Quieres pagar menos y evitar errores caros al comprar? Yo me encargo.
        </h1>

        <p class="mt-4 max-w-xl text-sm leading-relaxed text-neutral-300">
          Si tienes miedo de pagar de más, equivocarte en lo legal o tomar una decisión por emoción, aquí es donde lo resolvemos.
          Negocio con datos, reviso riesgos antes de que sean problema y llevo el proceso hasta firma.
        </p>

        <div class="mt-6 grid grid-cols-1 gap-3 sm:grid-cols-2">
          <a id="btn-zoom-hero"
            class="inline-flex w-full items-center justify-center rounded-2xl px-5 py-3 text-sm font-semibold text-neutral-900 shadow-[0_12px_30px_rgba(0,0,0,0.35)] transition hover:brightness-105 active:translate-y-[1px]"
            style="background: linear-gradient(135deg, #BEAF87, #A19276);"
            target="_blank" rel="noopener noreferrer">
            Agendar Zoom ahora
          </a>
          <a id="btn-wa-hero"
            class="inline-flex w-full items-center justify-center rounded-2xl border border-neutral-700/70 bg-neutral-950/40 px-5 py-3 text-sm font-semibold text-neutral-100 backdrop-blur transition hover:border-neutral-500 active:translate-y-[1px]"
            target="_blank" rel="noopener noreferrer">
            Escribir por WhatsApp
          </a>
        </div>

        <div class="mt-7 flex flex-wrap gap-2">
          <span class="inline-flex items-center gap-2 rounded-full border border-neutral-800/70 bg-neutral-950/40 px-4 py-2 text-xs text-neutral-300">
            <span class="h-2 w-2 rounded-full" style="background-color:#BEAF87;"></span>
            Negociación con método
          </span>
          <span class="inline-flex items-center gap-2 rounded-full border border-neutral-800/70 bg-neutral-950/40 px-4 py-2 text-xs text-neutral-300">
            <span class="h-2 w-2 rounded-full" style="background-color:#BEAF87;"></span>
            Riesgo reducido
          </span>
          <span class="inline-flex items-center gap-2 rounded-full border border-neutral-800/70 bg-neutral-950/40 px-4 py-2 text-xs text-neutral-300">
            <span class="h-2 w-2 rounded-full" style="background-color:#BEAF87;"></span>
            Proceso legal cuidado
          </span>
        </div>

        <div class="mt-8 grid grid-cols-1 gap-3 sm:grid-cols-3">
          <div class="rounded-2xl border border-neutral-800/70 bg-neutral-950/40 p-5">
            <p class="text-xs font-semibold tracking-wide text-neutral-400">RESULTADO REAL</p>
            <p class="mt-1 text-2xl font-semibold text-neutral-100">Hasta 10% menos</p>
            <p class="mt-2 text-xs text-neutral-400">Históricamente, 9 de cada 10 compradores han logrado mejoras en precio cuando el mercado lo permite.</p>
          </div>
          <div class="rounded-2xl border border-neutral-800/70 bg-neutral-950/40 p-5">
            <p class="text-xs font-semibold tracking-wide text-neutral-400">TODO INCLUIDO</p>
            <p class="mt-1 text-2xl font-semibold text-neutral-100">Negociación + Legal + Crédito</p>
            <p class="mt-2 text-xs text-neutral-400">Estrategia, revisión de riesgos, coordinación notarial y apoyo en financiamiento.</p>
          </div>
          <div class="rounded-2xl border border-neutral-800/70 bg-neutral-950/40 p-5">
            <p class="text-xs font-semibold tracking-wide text-neutral-400">PARA TI</p>
            <p class="mt-1 text-2xl font-semibold text-neutral-100">Cero costo directo</p>
            <p class="mt-2 text-xs text-neutral-400">Representación completa sin que tengas que pagar honorarios directos.</p>
          </div>
        </div>
      </div>

      <!-- Form -->
      <div class="lg:col-span-5 fade-up delay-1">
        <div class="rounded-[28px] border border-neutral-800/70 bg-neutral-950/40 p-6 backdrop-blur">
          <div class="flex items-start justify-between gap-4">
            <div>
              <p class="text-sm font-semibold text-neutral-100">Diagnóstico rápido</p>
              <p class="mt-1 text-xs text-neutral-400">Te mando una estrategia inicial por WhatsApp.</p>
            </div>
            <span class="shrink-0 rounded-full px-3 py-1 text-[11px] font-semibold"
              style="background-color: rgba(190,175,135,0.14); color: #BEAF87; border: 1px solid rgba(190,175,135,0.25);">
              15 min
            </span>
          </div>

          <p class="mt-2 text-xs leading-relaxed text-neutral-400">
            Completa esto y te devuelvo una estrategia inicial. Al enviar, se abrirá WhatsApp con el resumen.
          </p>

          <form id="lead-form" class="mt-5 space-y-4">
            <div class="space-y-1">
              <label class="text-sm font-medium text-neutral-200">Nombre</label>
              <input id="f-nombre" class="w-full rounded-2xl border border-neutral-700/70 bg-neutral-900/60 px-4 py-3 text-neutral-100 placeholder:text-neutral-500 outline-none transition focus:border-neutral-500" placeholder="Tu nombre" autocomplete="name" >
              <p id="e-nombre" class="text-xs text-red-300 hidden">Escribe tu nombre.</p>
            </div>

            <div class="space-y-1">
              <label class="text-sm font-medium text-neutral-200">WhatsApp</label>
              <input id="f-whatsapp" class="w-full rounded-2xl border border-neutral-700/70 bg-neutral-900/60 px-4 py-3 text-neutral-100 placeholder:text-neutral-500 outline-none transition focus:border-neutral-500" placeholder="Ej. 33 1234 5678" autocomplete="tel" >
              <p class="text-xs text-neutral-400">Si prefieres, escribe tu número tal cual lo usas.</p>
              <p id="e-whatsapp" class="text-xs text-red-300 hidden">Escribe tu WhatsApp.</p>
            </div>

            <div class="grid grid-cols-1 gap-4 sm:grid-cols-2">
              <div class="space-y-1">
                <label class="text-sm font-medium text-neutral-200">Presupuesto aprox.</label>
                <input id="f-presupuesto" class="w-full rounded-2xl border border-neutral-700/70 bg-neutral-900/60 px-4 py-3 text-neutral-100 placeholder:text-neutral-500 outline-none transition focus:border-neutral-500" placeholder="Ej. $3.5M MXN" >
                <p id="e-presupuesto" class="text-xs text-red-300 hidden">Indica tu presupuesto aproximado.</p>
              </div>
              <div class="space-y-1">
                <label class="text-sm font-medium text-neutral-200">Zona(s) de interés</label>
                <input id="f-zona" class="w-full rounded-2xl border border-neutral-700/70 bg-neutral-900/60 px-4 py-3 text-neutral-100 placeholder:text-neutral-500 outline-none transition focus:border-neutral-500" placeholder="Ej. Providencia, Andares…" >
                <p id="e-zona" class="text-xs text-red-300 hidden">Indica zona(s) de interés.</p>
              </div>
            </div>

            <div class="grid grid-cols-1 gap-4 sm:grid-cols-2">
              <div class="space-y-1">
                <label class="text-sm font-medium text-neutral-200">Plazo</label>
                <input id="f-plazo" class="w-full rounded-2xl border border-neutral-700/70 bg-neutral-900/60 px-4 py-3 text-neutral-100 placeholder:text-neutral-500 outline-none transition focus:border-neutral-500" placeholder="Ej. 30–60 días" >
                <p id="e-plazo" class="text-xs text-red-300 hidden">Indica tu plazo estimado.</p>
              </div>

              <div class="space-y-1">
                <label class="text-sm font-medium text-neutral-200">Financiamiento</label>
                <select id="f-fin" class="w-full rounded-2xl border border-neutral-700/70 bg-neutral-900/60 px-4 py-3 text-neutral-100 outline-none transition focus:border-neutral-500">
                  <option value="">Selecciona</option>
                  <option value="Crédito bancario">Crédito bancario</option>
                  <option value="INFONAVIT / cofinavit">INFONAVIT / Cofinavit</option>
                  <option value="Contado">Contado</option>
                  <option value="Aún lo estoy definiendo">Aún lo estoy definiendo</option>
                </select>
              </div>
            </div>

            <div class="space-y-1">
              <label class="text-sm font-medium text-neutral-200">¿Ya tienes una propiedad en vista?</label>
              <select id="f-actual" class="w-full rounded-2xl border border-neutral-700/70 bg-neutral-900/60 px-4 py-3 text-neutral-100 outline-none transition focus:border-neutral-500">
                <option value="">Selecciona</option>
                <option value="Sí, ya tengo 1–2 opciones">Sí, ya tengo 1–2 opciones</option>
                <option value="Estoy explorando">Estoy explorando</option>
                <option value="Apenas voy a iniciar">Apenas voy a iniciar</option>
              </select>
            </div>

            <div class="space-y-1">
              <label class="text-sm font-medium text-neutral-200">Comentarios (opcional)</label>
              <textarea id="f-coment" class="w-full min-h-[120px] resize-y rounded-2xl border border-neutral-700/70 bg-neutral-900/60 px-4 py-3 text-neutral-100 placeholder:text-neutral-500 outline-none focus:border-neutral-500"
                placeholder="Tipo de propiedad, must-haves, si ya hay un precio en mente, etc."></textarea>
              <p class="text-xs text-neutral-400">Mientras más contexto, más precisa la estrategia inicial.</p>
            </div>

            <button type="submit"
              class="w-full rounded-2xl px-5 py-3 text-sm font-semibold text-neutral-900 transition hover:brightness-105 active:translate-y-[1px]"
              style="background: linear-gradient(135deg, #BEAF87, #A19276);">
              Enviar y abrir WhatsApp
            </button>

            <p class="text-[11px] leading-relaxed text-neutral-400">
              Al enviar, se abrirá WhatsApp. Tu información se usa solo para coordinar tu asesoría.
            </p>
          </form>
        </div>
      </div>
    </div>
  </section>

  <!-- PILARES -->
  <section class="relative z-10">
    <div class="mx-auto max-w-6xl px-5 py-12 sm:px-8">
      <div class="mx-auto max-w-3xl text-center">
        <p class="text-xs font-semibold tracking-[0.22em] text-neutral-400">PILAR 1</p>
        <h2 class="mt-3 text-2xl font-semibold text-neutral-100 sm:text-3xl">Todo esto lo tienes conmigo. Y no te cuesta.</h2>
        <p class="mt-3 text-sm leading-relaxed text-neutral-300">
          Negociación profesional, estrategia de oferta, análisis real de mercado y estructura de concesiones. No es acompañamiento. Es representación completa.
        </p>
      </div>

      <div class="mt-8 grid grid-cols-1 gap-4 md:grid-cols-3">
        <div class="group rounded-3xl border border-neutral-800/70 bg-neutral-950/40 p-6 backdrop-blur transition hover:border-neutral-600/70">
          <div class="flex h-11 w-11 items-center justify-center rounded-2xl"
            style="background-color: rgba(190,175,135,0.14); border: 1px solid rgba(190,175,135,0.25);">
            <span class="text-sm font-semibold" style="color:#BEAF87;">01</span>
          </div>
          <h3 class="mt-4 text-base font-semibold text-neutral-100">Valor real en 1 hoja</h3>
          <p class="mt-2 text-sm leading-relaxed text-neutral-300">Comparables, tiempo en mercado, estado y urgencia del vendedor. Con eso se define tu rango.</p>
        </div>

        <div class="group rounded-3xl border border-neutral-800/70 bg-neutral-950/40 p-6 backdrop-blur transition hover:border-neutral-600/70">
          <div class="flex h-11 w-11 items-center justify-center rounded-2xl"
            style="background-color: rgba(190,175,135,0.14); border: 1px solid rgba(190,175,135,0.25);">
            <span class="text-sm font-semibold" style="color:#BEAF87;">02</span>
          </div>
          <h3 class="mt-4 text-base font-semibold text-neutral-100">Oferta + concesiones</h3>
          <p class="mt-2 text-sm leading-relaxed text-neutral-300">Si el precio no baja, gano condiciones: reparaciones, muebles, tiempos, penalizaciones y entrega.</p>
        </div>

        <div class="group rounded-3xl border border-neutral-800/70 bg-neutral-950/40 p-6 backdrop-blur transition hover:border-neutral-600/70">
          <div class="flex h-11 w-11 items-center justify-center rounded-2xl"
            style="background-color: rgba(190,175,135,0.14); border: 1px solid rgba(190,175,135,0.25);">
            <span class="text-sm font-semibold" style="color:#BEAF87;">03</span>
          </div>
          <h3 class="mt-4 text-base font-semibold text-neutral-100">Número defendible</h3>
          <p class="mt-2 text-sm leading-relaxed text-neutral-300">Que avalúo y notaría tengan sentido. Ganar no es “humillar”: es cerrar bien.</p>
        </div>
      </div>

      <div class="mt-8 rounded-3xl border border-neutral-800/70 bg-neutral-950/40 p-6">
        <div class="grid grid-cols-1 gap-4 sm:grid-cols-3 sm:items-center">
          <div class="sm:col-span-2">
            <p class="text-sm font-semibold text-neutral-100">Siguiente paso: agenda una llamada y sal con estrategia</p>
            <p class="mt-1 text-sm text-neutral-300">Te digo qué conviene, qué no conviene, y cómo atacarlo: oferta, tiempos, checklist y riesgos.</p>
          </div>
          <div class="grid grid-cols-1 gap-3">
            <a id="btn-zoom-p1" class="inline-flex w-full items-center justify-center rounded-2xl px-5 py-3 text-sm font-semibold text-neutral-900 shadow-[0_12px_30px_rgba(0,0,0,0.35)] transition hover:brightness-105 active:translate-y-[1px]"
              style="background: linear-gradient(135deg, #BEAF87, #A19276);" target="_blank" rel="noopener noreferrer">Agendar Zoom</a>
            <a id="btn-wa-p1" class="inline-flex w-full items-center justify-center rounded-2xl border border-neutral-700/70 bg-neutral-950/40 px-5 py-3 text-sm font-semibold text-neutral-100 backdrop-blur transition hover:border-neutral-500 active:translate-y-[1px]"
              target="_blank" rel="noopener noreferrer">WhatsApp</a>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- PILAR 2 -->
  <section class="relative z-10">
    <div class="mx-auto max-w-6xl px-5 py-12 sm:px-8">
      <div class="mx-auto max-w-3xl text-center">
        <p class="text-xs font-semibold tracking-[0.22em] text-neutral-400">PILAR 2</p>
        <h2 class="mt-3 text-2xl font-semibold text-neutral-100 sm:text-3xl">Te protejo de errores que cuestan años</h2>
        <p class="mt-3 text-sm leading-relaxed text-neutral-300">
          Riesgo financiero, legal y emocional bajo control. Si algo no te conviene, se detiene.
        </p>
      </div>

      <div class="mt-8 grid grid-cols-1 gap-4 md:grid-cols-3">
        <div class="group rounded-3xl border border-neutral-800/70 bg-neutral-950/40 p-6 backdrop-blur transition hover:border-neutral-600/70">
          <div class="flex h-11 w-11 items-center justify-center rounded-2xl" style="background-color: rgba(190,175,135,0.14); border: 1px solid rgba(190,175,135,0.25);">
            <span class="text-sm font-semibold" style="color:#BEAF87;">01</span>
          </div>
          <h3 class="mt-4 text-base font-semibold text-neutral-100">Red flags en visita</h3>
          <p class="mt-2 text-sm leading-relaxed text-neutral-300">Ruido, accesos, microzona, mantenimiento, administración, humedad y vicios comunes.</p>
        </div>
        <div class="group rounded-3xl border border-neutral-800/70 bg-neutral-950/40 p-6 backdrop-blur transition hover:border-neutral-600/70">
          <div class="flex h-11 w-11 items-center justify-center rounded-2xl" style="background-color: rgba(190,175,135,0.14); border: 1px solid rgba(190,175,135,0.25);">
            <span class="text-sm font-semibold" style="color:#BEAF87;">02</span>
          </div>
          <h3 class="mt-4 text-base font-semibold text-neutral-100">Precio en mercado</h3>
          <p class="mt-2 text-sm leading-relaxed text-neutral-300">Detecto si está inflado. Si está fuera de realidad, lo sustentamos con datos.</p>
        </div>
        <div class="group rounded-3xl border border-neutral-800/70 bg-neutral-950/40 p-6 backdrop-blur transition hover:border-neutral-600/70">
          <div class="flex h-11 w-11 items-center justify-center rounded-2xl" style="background-color: rgba(190,175,135,0.14); border: 1px solid rgba(190,175,135,0.25);">
            <span class="text-sm font-semibold" style="color:#BEAF87;">03</span>
          </div>
          <h3 class="mt-4 text-base font-semibold text-neutral-100">Tablero de control</h3>
          <p class="mt-2 text-sm leading-relaxed text-neutral-300">Qué sigue, qué falta y qué decisión sí mueve la aguja. Sin comprar desde la emoción.</p>
        </div>
      </div>

      <div class="mt-8 rounded-3xl border border-neutral-800/70 bg-neutral-950/40 p-6">
        <div class="grid grid-cols-1 gap-4 sm:grid-cols-3 sm:items-center">
          <div class="sm:col-span-2">
            <p class="text-sm font-semibold text-neutral-100">Siguiente paso: agenda una llamada y sal con estrategia</p>
            <p class="mt-1 text-sm text-neutral-300">Te digo qué conviene, qué no conviene, y cómo atacarlo: oferta, tiempos, checklist y riesgos.</p>
          </div>
          <div class="grid grid-cols-1 gap-3">
            <a id="btn-zoom-p2" class="inline-flex w-full items-center justify-center rounded-2xl px-5 py-3 text-sm font-semibold text-neutral-900 shadow-[0_12px_30px_rgba(0,0,0,0.35)] transition hover:brightness-105 active:translate-y-[1px]"
              style="background: linear-gradient(135deg, #BEAF87, #A19276);" target="_blank" rel="noopener noreferrer">Agendar Zoom</a>
            <a id="btn-wa-p2" class="inline-flex w-full items-center justify-center rounded-2xl border border-neutral-700/70 bg-neutral-950/40 px-5 py-3 text-sm font-semibold text-neutral-100 backdrop-blur transition hover:border-neutral-500 active:translate-y-[1px]"
              target="_blank" rel="noopener noreferrer">WhatsApp</a>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- PILAR 3 -->
  <section class="relative z-10">
    <div class="mx-auto max-w-6xl px-5 py-12 sm:px-8">
      <div class="mx-auto max-w-3xl text-center">
        <p class="text-xs font-semibold tracking-[0.22em] text-neutral-400">PILAR 3</p>
        <h2 class="mt-3 text-2xl font-semibold text-neutral-100 sm:text-3xl">Yo opero todo. Tú decides con claridad.</h2>
        <p class="mt-3 text-sm leading-relaxed text-neutral-300">
          Agenda, filtros, logística, coordinación y seguimiento. Sin perder fines de semana ni energía.
        </p>
      </div>

      <div class="mt-8 grid grid-cols-1 gap-4 md:grid-cols-3">
        <div class="group rounded-3xl border border-neutral-800/70 bg-neutral-950/40 p-6 backdrop-blur transition hover:border-neutral-600/70">
          <div class="flex h-11 w-11 items-center justify-center rounded-2xl" style="background-color: rgba(190,175,135,0.14); border: 1px solid rgba(190,175,135,0.25);">
            <span class="text-sm font-semibold" style="color:#BEAF87;">01</span>
          </div>
          <h3 class="mt-4 text-base font-semibold text-neutral-100">Curaduría</h3>
          <p class="mt-2 text-sm leading-relaxed text-neutral-300">Te enseño pocas opciones, correctas. Las que sí aplican a tu objetivo.</p>
        </div>
        <div class="group rounded-3xl border border-neutral-800/70 bg-neutral-950/40 p-6 backdrop-blur transition hover:border-neutral-600/70">
          <div class="flex h-11 w-11 items-center justify-center rounded-2xl" style="background-color: rgba(190,175,135,0.14); border: 1px solid rgba(190,175,135,0.25);">
            <span class="text-sm font-semibold" style="color:#BEAF87;">02</span>
          </div>
          <h3 class="mt-4 text-base font-semibold text-neutral-100">Visita con conclusión</h3>
          <p class="mt-2 text-sm leading-relaxed text-neutral-300">Cada recorrido termina en “avanza” o “descarta”. No repetimos el mismo ciclo.</p>
        </div>
        <div class="group rounded-3xl border border-neutral-800/70 bg-neutral-950/40 p-6 backdrop-blur transition hover:border-neutral-600/70">
          <div class="flex h-11 w-11 items-center justify-center rounded-2xl" style="background-color: rgba(190,175,135,0.14); border: 1px solid rgba(190,175,135,0.25);">
            <span class="text-sm font-semibold" style="color:#BEAF87;">03</span>
          </div>
          <h3 class="mt-4 text-base font-semibold text-neutral-100">Ahorro de tiempo</h3>
          <p class="mt-2 text-sm leading-relaxed text-neutral-300">Agenda, llaves, confirmaciones y coordinación. Tu sábado vale oro.</p>
        </div>
      </div>

      <div class="mt-8 rounded-3xl border border-neutral-800/70 bg-neutral-950/40 p-6">
        <div class="grid grid-cols-1 gap-4 sm:grid-cols-3 sm:items-center">
          <div class="sm:col-span-2">
            <p class="text-sm font-semibold text-neutral-100">Siguiente paso: agenda una llamada y sal con estrategia</p>
            <p class="mt-1 text-sm text-neutral-300">Te digo qué conviene, qué no conviene, y cómo atacarlo: oferta, tiempos, checklist y riesgos.</p>
          </div>
          <div class="grid grid-cols-1 gap-3">
            <a id="btn-zoom-p3" class="inline-flex w-full items-center justify-center rounded-2xl px-5 py-3 text-sm font-semibold text-neutral-900 shadow-[0_12px_30px_rgba(0,0,0,0.35)] transition hover:brightness-105 active:translate-y-[1px]"
              style="background: linear-gradient(135deg, #BEAF87, #A19276);" target="_blank" rel="noopener noreferrer">Agendar Zoom</a>
            <a id="btn-wa-p3" class="inline-flex w-full items-center justify-center rounded-2xl border border-neutral-700/70 bg-neutral-950/40 px-5 py-3 text-sm font-semibold text-neutral-100 backdrop-blur transition hover:border-neutral-500 active:translate-y-[1px]"
              target="_blank" rel="noopener noreferrer">WhatsApp</a>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- PILAR 4 -->
  <section class="relative z-10">
    <div class="mx-auto max-w-6xl px-5 py-12 sm:px-8">
      <div class="mx-auto max-w-3xl text-center">
        <p class="text-xs font-semibold tracking-[0.22em] text-neutral-400">PILAR 4</p>
        <h2 class="mt-3 text-2xl font-semibold text-neutral-100 sm:text-3xl">Blindaje legal desde antes de enamorarte</h2>
        <p class="mt-3 text-sm leading-relaxed text-neutral-300">
          Checklist completo, revisión documental y coordinación notarial antes de que firmes cualquier cosa.
        </p>
      </div>

      <div class="mt-8 grid grid-cols-1 gap-4 md:grid-cols-3">
        <div class="group rounded-3xl border border-neutral-800/70 bg-neutral-950/40 p-6 backdrop-blur transition hover:border-neutral-600/70">
          <div class="flex h-11 w-11 items-center justify-center rounded-2xl" style="background-color: rgba(190,175,135,0.14); border: 1px solid rgba(190,175,135,0.25);">
            <span class="text-sm font-semibold" style="color:#BEAF87;">01</span>
          </div>
          <h3 class="mt-4 text-base font-semibold text-neutral-100">Checklist de documentación</h3>
          <p class="mt-2 text-sm leading-relaxed text-neutral-300">Régimen, gravámenes, adeudos, nombres/escrituras y estatus antes de firmar nada.</p>
        </div>
        <div class="group rounded-3xl border border-neutral-800/70 bg-neutral-950/40 p-6 backdrop-blur transition hover:border-neutral-600/70">
          <div class="flex h-11 w-11 items-center justify-center rounded-2xl" style="background-color: rgba(190,175,135,0.14); border: 1px solid rgba(190,175,135,0.25);">
            <span class="text-sm font-semibold" style="color:#BEAF87;">02</span>
          </div>
          <h3 class="mt-4 text-base font-semibold text-neutral-100">Notaría y cierre eficiente</h3>
          <p class="mt-2 text-sm leading-relaxed text-neutral-300">Coordinación con notaría y aliados para cerrar limpio, sin dramas ni costos sorpresa.</p>
        </div>
        <div class="group rounded-3xl border border-neutral-800/70 bg-neutral-950/40 p-6 backdrop-blur transition hover:border-neutral-600/70">
          <div class="flex h-11 w-11 items-center justify-center rounded-2xl" style="background-color: rgba(190,175,135,0.14); border: 1px solid rgba(190,175,135,0.25);">
            <span class="text-sm font-semibold" style="color:#BEAF87;">03</span>
          </div>
          <h3 class="mt-4 text-base font-semibold text-neutral-100">Tú entiendes lo que firmas</h3>
          <p class="mt-2 text-sm leading-relaxed text-neutral-300">Te explico lo importante en simple. Firmas con claridad, no con prisa.</p>
        </div>
      </div>

      <div class="mt-8 rounded-3xl border border-neutral-800/70 bg-neutral-950/40 p-6">
        <div class="grid grid-cols-1 gap-4 sm:grid-cols-3 sm:items-center">
          <div class="sm:col-span-2">
            <p class="text-sm font-semibold text-neutral-100">Siguiente paso: agenda una llamada y sal con estrategia</p>
            <p class="mt-1 text-sm text-neutral-300">Te digo qué conviene, qué no conviene, y cómo atacarlo: oferta, tiempos, checklist y riesgos.</p>
          </div>
          <div class="grid grid-cols-1 gap-3">
            <a id="btn-zoom-p4" class="inline-flex w-full items-center justify-center rounded-2xl px-5 py-3 text-sm font-semibold text-neutral-900 shadow-[0_12px_30px_rgba(0,0,0,0.35)] transition hover:brightness-105 active:translate-y-[1px]"
              style="background: linear-gradient(135deg, #BEAF87, #A19276);" target="_blank" rel="noopener noreferrer">Agendar Zoom</a>
            <a id="btn-wa-p4" class="inline-flex w-full items-center justify-center rounded-2xl border border-neutral-700/70 bg-neutral-950/40 px-5 py-3 text-sm font-semibold text-neutral-100 backdrop-blur transition hover:border-neutral-500 active:translate-y-[1px]"
              target="_blank" rel="noopener noreferrer">WhatsApp</a>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- PROCESO -->
  <section class="relative z-10">
    <div class="mx-auto max-w-6xl px-5 py-12 sm:px-8">
      <div class="mx-auto max-w-3xl text-center">
        <p class="text-xs font-semibold tracking-[0.22em] text-neutral-400">CÓMO TRABAJAMOS</p>
        <h2 class="mt-3 text-2xl font-semibold text-neutral-100 sm:text-3xl">Así te llevo de “quiero” a “ya es mío”</h2>
        <p class="mt-3 text-sm leading-relaxed text-neutral-300">Yo manejo la operación para que tú tomes decisiones con calma. Rápido, claro y sin sorpresas.</p>
      </div>

      <div class="mt-8 grid grid-cols-1 gap-4 md:grid-cols-4">
        <div class="rounded-3xl border border-neutral-800/70 bg-neutral-950/40 p-6">
          <p class="text-xs font-semibold" style="color:#BEAF87;">01</p>
          <p class="mt-2 text-base font-semibold text-neutral-100">Diagnóstico</p>
          <p class="mt-2 text-sm leading-relaxed text-neutral-300">Aterrizo tu presupuesto, tu zona y tu timing. Dejamos claro qué sí y qué no.</p>
        </div>
        <div class="rounded-3xl border border-neutral-800/70 bg-neutral-950/40 p-6">
          <p class="text-xs font-semibold" style="color:#BEAF87;">02</p>
          <p class="mt-2 text-base font-semibold text-neutral-100">Curaduría + visitas</p>
          <p class="mt-2 text-sm leading-relaxed text-neutral-300">Te enseño pocas, correctas. Visitas con intención y decisión al final.</p>
        </div>
        <div class="rounded-3xl border border-neutral-800/70 bg-neutral-950/40 p-6">
          <p class="text-xs font-semibold" style="color:#BEAF87;">03</p>
          <p class="mt-2 text-base font-semibold text-neutral-100">Oferta inteligente</p>
          <p class="mt-2 text-sm leading-relaxed text-neutral-300">Rango, timing y concesiones. Todo sustentado.</p>
        </div>
        <div class="rounded-3xl border border-neutral-800/70 bg-neutral-950/40 p-6">
          <p class="text-xs font-semibold" style="color:#BEAF87;">04</p>
          <p class="mt-2 text-base font-semibold text-neutral-100">Cierre limpio</p>
          <p class="mt-2 text-sm leading-relaxed text-neutral-300">Checklist, notaría y entrega. Firmas con claridad.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- FAQ -->
  <section class="relative z-10">
    <div class="mx-auto max-w-6xl px-5 py-12 sm:px-8">
      <div class="mx-auto max-w-3xl text-center">
        <p class="text-xs font-semibold tracking-[0.22em] text-neutral-400">FAQ</p>
        <h2 class="mt-3 text-2xl font-semibold text-neutral-100 sm:text-3xl">Preguntas frecuentes</h2>
        <p class="mt-3 text-sm leading-relaxed text-neutral-300">Respuestas cortas para avanzar rápido.</p>
      </div>

      <div class="mt-8 grid grid-cols-1 gap-4 md:grid-cols-2">
        <div class="rounded-3xl border border-neutral-800/70 bg-neutral-950/40 p-6">
          <p class="text-sm font-semibold text-neutral-100">¿De verdad puedo pagar menos si compro contigo?</p>
          <p class="mt-2 text-sm leading-relaxed text-neutral-300">
            No te vendo magia. Te vendo método. Históricamente, 9 de cada 10 clientes han logrado pagar hasta 10% menos vs. lista, cuando el mercado y el inmueble lo permiten.
            Si no se puede bajar precio, te consigo condiciones que equivalen a dinero.
          </p>
        </div>

        <div class="rounded-3xl border border-neutral-800/70 bg-neutral-950/40 p-6">
          <p class="text-sm font-semibold text-neutral-100">¿Tu servicio tiene costo para mí como comprador?</p>
          <p class="mt-2 text-sm leading-relaxed text-neutral-300">
            Cero costo directo para ti. Mi compensación normalmente está contemplada dentro del esquema de comercialización de la operación.
            En tu llamada inicial te lo explico claro, antes de avanzar.
          </p>
        </div>

        <div class="rounded-3xl border border-neutral-800/70 bg-neutral-950/40 p-6">
          <p class="text-sm font-semibold text-neutral-100">¿Trabajas con crédito?</p>
          <p class="mt-2 text-sm leading-relaxed text-neutral-300">
            Sí, 100%. Y si lo necesitas, te consigo pre-calificación: con banco tradicional o con fintechs, según tu perfil y velocidad deseada.
            Así tu oferta sale fuerte y defendible.
          </p>
        </div>

        <div class="rounded-3xl border border-neutral-800/70 bg-neutral-950/40 p-6">
          <p class="text-sm font-semibold text-neutral-100">¿En qué zona trabajas?</p>
          <p class="mt-2 text-sm leading-relaxed text-neutral-300" id="faq-zona"></p>
        </div>
      </div>

      <div class="mt-8 rounded-3xl border border-neutral-800/70 bg-neutral-950/40 p-6">
        <div class="grid grid-cols-1 gap-4 sm:grid-cols-3 sm:items-center">
          <div class="sm:col-span-2">
            <p class="text-sm font-semibold text-neutral-100">Listo para comprar con control</p>
            <p class="mt-1 text-sm text-neutral-300">Agenda Zoom o escríbeme. Saldrás con un plan: rango de oferta, concesiones, checklist y tiempos.</p>
          </div>
          <div class="grid grid-cols-1 gap-3">
            <a id="btn-zoom-faq" class="inline-flex w-full items-center justify-center rounded-2xl px-5 py-3 text-sm font-semibold text-neutral-900 shadow-[0_12px_30px_rgba(0,0,0,0.35)] transition hover:brightness-105 active:translate-y-[1px]"
              style="background: linear-gradient(135deg, #BEAF87, #A19276);" target="_blank" rel="noopener noreferrer">Agendar Zoom</a>
            <a id="btn-wa-faq" class="inline-flex w-full items-center justify-center rounded-2xl border border-neutral-700/70 bg-neutral-950/40 px-5 py-3 text-sm font-semibold text-neutral-100 backdrop-blur transition hover:border-neutral-500 active:translate-y-[1px]"
              target="_blank" rel="noopener noreferrer">WhatsApp</a>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Legal -->
  <section class="relative z-10">
    <div class="mx-auto max-w-6xl px-5 pb-14 sm:px-8">
      <div class="rounded-3xl border border-neutral-800/70 bg-neutral-950/40 p-6">
        <h3 class="text-base font-semibold text-neutral-100">Cumplimiento y transparencia</h3>
        <div class="mt-3 space-y-2 text-sm leading-relaxed text-neutral-300">
          <p>
            Este sitio describe servicios de asesoría/representación para compradores. Cualquier beneficio (precio o condiciones) depende del mercado,
            del inmueble, del vendedor y de la negociación.
          </p>
          <p>
            La información compartida no constituye asesoría legal o financiera. Para decisiones finales se recomienda validar con notaría y,
            en su caso, institución financiera.
          </p>
          <p class="text-xs text-neutral-400">Pie reglamentario: Cada Oficina es de Propiedad y Operación Independiente.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer class="relative z-10 border-t border-neutral-900">
    <div class="mx-auto max-w-6xl px-5 py-10 sm:px-8">
      <div class="grid grid-cols-1 gap-6 sm:grid-cols-2 sm:items-center">
        <div>
          <p class="text-sm font-semibold text-neutral-100" id="f-name"></p>
          <p class="mt-1 text-xs text-neutral-400" id="f-sub"></p>
          <p class="mt-2 text-xs text-neutral-500">Cada Oficina es de Propiedad y Operación Independiente.</p>
        </div>
        <div class="grid grid-cols-1 gap-3 sm:grid-cols-2">
          <a id="btn-zoom-footer"
            class="inline-flex w-full items-center justify-center rounded-2xl px-5 py-3 text-sm font-semibold text-neutral-900 shadow-[0_12px_30px_rgba(0,0,0,0.35)] transition hover:brightness-105 active:translate-y-[1px]"
            style="background: linear-gradient(135deg, #BEAF87, #A19276);" target="_blank" rel="noopener noreferrer">
            Agendar Zoom
          </a>
          <a id="btn-wa-footer"
            class="inline-flex w-full items-center justify-center rounded-2xl border border-neutral-700/70 bg-neutral-950/40 px-5 py-3 text-sm font-semibold text-neutral-100 backdrop-blur transition hover:border-neutral-500 active:translate-y-[1px]"
            target="_blank" rel="noopener noreferrer">
            WhatsApp
          </a>
        </div>
      </div>
    </div>
  </footer>

  <!-- Mobile sticky CTA -->
  <div class="fixed bottom-0 left-0 right-0 z-20 border-t border-neutral-900 bg-neutral-950/90 p-3 backdrop-blur sm:hidden">
    <div class="mx-auto grid max-w-6xl grid-cols-2 gap-3 px-2">
      <a id="btn-zoom-sticky"
        class="inline-flex w-full items-center justify-center rounded-2xl border border-neutral-700/70 bg-neutral-950/40 px-5 py-3 text-sm font-semibold text-neutral-100 backdrop-blur transition hover:border-neutral-500 active:translate-y-[1px]"
        target="_blank" rel="noopener noreferrer">Zoom</a>

      <a id="btn-wa-sticky"
        class="inline-flex w-full items-center justify-center rounded-2xl px-5 py-3 text-sm font-semibold text-neutral-900 shadow-[0_12px_30px_rgba(0,0,0,0.35)] transition hover:brightness-105 active:translate-y-[1px]"
        style="background: linear-gradient(135deg, #BEAF87, #A19276);"
        target="_blank" rel="noopener noreferrer">WhatsApp</a>
    </div>
  </div>

  <script>
    // =========================
    // Pintar variables en UI
    // =========================
    document.getElementById("h-name").textContent = advisorName;
    document.getElementById("h-sub").textContent = `Representación para compradores · ${city}`;
    document.getElementById("f-name").textContent = advisorName;
    document.getElementById("f-sub").textContent = `${city} · ${officeName}`;

    document.getElementById("faq-zona").textContent =
      `Principalmente ${city}. Pero puedo representarte en cualquier parte de México o Sudamérica: directamente o con aliados verificados (yo sigo llevando estrategia, negociación y control del proceso).`;

    const waQuickText = `Hola ${advisorName}. Quiero agendar mi diagnóstico de compra (Zoom) y recibir una estrategia para negociar mi compra.`;
    const waQuickUrl = buildWaUrl(waQuickText);

    // botones
    const zoomButtons = [
      "btn-zoom-top","btn-zoom-hero","btn-zoom-p1","btn-zoom-p2","btn-zoom-p3","btn-zoom-p4","btn-zoom-faq","btn-zoom-footer","btn-zoom-sticky"
    ];
    zoomButtons.forEach(id => {
      const el = document.getElementById(id);
      if (el) el.href = zoomSchedulerUrl;
    });

    const waButtons = [
      "btn-wa-top","btn-wa-hero","btn-wa-p1","btn-wa-p2","btn-wa-p3","btn-wa-p4","btn-wa-faq","btn-wa-footer","btn-wa-sticky"
    ];
    waButtons.forEach(id => {
      const el = document.getElementById(id);
      if (el) el.href = waQuickUrl;
    });

    // =========================
    // Form -> WhatsApp resumen
    // =========================
    function showError(id, show){
      const el = document.getElementById(id);
      if (!el) return;
      el.classList.toggle("hidden", !show);
    }

    document.getElementById("lead-form").addEventListener("submit", function(ev){
      ev.preventDefault();

      const nombre = (document.getElementById("f-nombre").value || "").trim();
      const whatsapp = (document.getElementById("f-whatsapp").value || "").trim();
      const presupuesto = (document.getElementById("f-presupuesto").value || "").trim();
      const zona = (document.getElementById("f-zona").value || "").trim();
      const plazo = (document.getElementById("f-plazo").value || "").trim();
      const financiamiento = document.getElementById("f-fin").value || "-";
      const compraActual = document.getElementById("f-actual").value || "-";
      const comentarios = (document.getElementById("f-coment").value || "").trim();

      const okNombre = !!nombre;
      const okWhatsapp = !!whatsapp;
      const okPresupuesto = !!presupuesto;
      const okZona = !!zona;
      const okPlazo = !!plazo;

      showError("e-nombre", !okNombre);
      showError("e-whatsapp", !okWhatsapp);
      showError("e-presupuesto", !okPresupuesto);
      showError("e-zona", !okZona);
      showError("e-plazo", !okPlazo);

      if (!(okNombre && okWhatsapp && okPresupuesto && okZona && okPlazo)) return;

      const lines = [
        `Hola ${advisorName}. Quiero agendar mi diagnóstico de compra y trabajar contigo como mi representante.`,
        ``,
        `Nombre: ${nombre}`,
        `WhatsApp: ${whatsapp}`,
        `Presupuesto aprox.: ${presupuesto}`,
        `Zona(s): ${zona}`,
        `Plazo: ${plazo}`,
        `¿Ya tengo propiedad en vista?: ${compraActual}`,
        `Financiamiento: ${financiamiento}`,
        comentarios ? `Comentarios: ${comentarios}` : "",
        ``,
        `¿Qué disponibilidad tienes para una llamada/Zoom?`
      ].filter(Boolean).join("\n");

      window.open(buildWaUrl(lines), "_blank", "noopener,noreferrer");
    });
  </script>
</body>
</html>
          </body>
        </html>
