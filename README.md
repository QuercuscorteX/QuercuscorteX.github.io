<!doctype html>
<html lang="es">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Quercus corteX Arborismo | Arboricultura técnica</title>
  <meta name="description" content="Arboricultura técnica, poda y tala de riesgo, acceso por cuerdas y emergencias de arbolado urbano 24/7.">
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
  <style>
    :root{
      --verde-neon:#b7f000;
      --negro:#000;
      --rojo:#e53935;
      --verde-oscuro:#1f2d16;
    }
    body{scroll-behavior:smooth;}
    .navbar{background:#000;}
    .navbar-brand{color:var(--verde-neon)!important;font-weight:800;}
    .nav-link{color:#fff!important;font-weight:600;}
    .btn-alert{background:var(--rojo);color:#fff;font-weight:700;}
    .btn-main{background:var(--verde-neon);color:#000;font-weight:700;}
    .hero{
      background:linear-gradient(rgba(0,0,0,.65),rgba(0,0,0,.65)),
      url('[https://images.unsplash.com/photo-1508780709619-79562169bc64?q=80&w=1600&auto=format&fit=crop](https://unsplash.com/es/fotos/hombre-bajo-el-arbol-durante-el-dia-boE2xft0cAo)');
      background-size:cover;background-position:center;
      color:#fff;
      padding:140px 20px;
    }
    .icon-circle{
      width:70px;height:70px;border-radius:50%;
      background:var(--verde-neon);
      display:flex;align-items:center;justify-content:center;
      font-size:26px;font-weight:800;
    }
    .emergency{
      background:#000;color:#fff;
      padding:80px 20px;
    }
    .floating-call{
      position:fixed;bottom:18px;right:18px;z-index:999;
      background:var(--rojo);color:#fff;padding:14px 18px;
      border-radius:999px;font-weight:800;text-decoration:none;
      box-shadow:0 6px 20px rgba(0,0,0,.35);
    }
  </style>
</head>
<body>

<!-- NAVBAR -->
<nav class="navbar navbar-expand-lg fixed-top">
  <div class="container">
    <a class="navbar-brand" href="#">Quercus corteX</a>
    <button class="navbar-toggler bg-light" type="button" data-bs-toggle="collapse" data-bs-target="#navMenu">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navMenu">
      <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
        <li class="nav-item"><a class="nav-link" href="#servicios">Servicios</a></li>
        <li class="nav-item"><a class="nav-link" href="#equipo">Quiénes Somos</a></li>
        <li class="nav-item"><a class="nav-link" href="#emergencias">Emergencias</a></li>
        <li class="nav-item ms-lg-3">
          <a class="btn btn-alert" href="tel:+56973839028">📞 +56 9 7383 9028</a>
        </li>
      </ul>
    </div>
  </div>
</nav>

<!-- HERO -->
<section class="hero text-center" id="home">
  <div class="container">
    <h1 class="display-4 fw-bold mb-3">Arboricultura técnica en escenarios complejos</h1>
    <p class="lead mb-4">Podas de riesgo, talas controladas y emergencias de arbolado urbano con protocolos reales de seguridad.</p>
    <a href="#servicios" class="btn btn-main btn-lg me-2">Ver servicios</a>
    <a href="tel:+56973839028" class="btn btn-alert btn-lg">🚨 Llamar ahora</a>
  </div>
</section>

<!-- SERVICIOS -->
<section class="py-5" id="servicios">
  <div class="container text-center">
    <h2 class="fw-bold mb-4">Servicios profesionales</h2>
    <div class="row g-4">
      <div class="col-md-3">
        <div class="p-4 border rounded h-100">
          <div class="icon-circle mx-auto mb-3">🌳</div>
          <h5>Poda técnica</h5>
          <p>Intervenciones estructurales y sanitarias para estabilidad y seguridad.</p>
        </div>
      </div>
      <div class="col-md-3">
        <div class="p-4 border rounded h-100">
          <div class="icon-circle mx-auto mb-3">🪚</div>
          <h5>Tala controlada</h5>
          <p>Desmontaje por secciones en espacios reducidos.</p>
        </div>
      </div>
      <div class="col-md-3">
        <div class="p-4 border rounded h-100">
          <div class="icon-circle mx-auto mb-3">🧗</div>
          <h5>Acceso por cuerdas</h5>
          <p>Trabajos en altura hasta 50 m donde no entra maquinaria.</p>
        </div>
      </div>
      <div class="col-md-3">
        <div class="p-4 border rounded h-100">
          <div class="icon-circle mx-auto mb-3">🚨</div>
          <h5>Emergencias 24/7</h5>
          <p>Respuesta inmediata ante riesgo por árboles o ramas.</p>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- QUIÉNES SOMOS -->
<section class="py-5 bg-light" id="equipo">
  <div class="container">
    <div class="row align-items-center">
      <div class="col-md-6 mb-3">
        <h2 class="fw-bold">Profesionales del trabajo en altura</h2>
        <p>Equipo técnico especializado en arboricultura urbana, acceso por cuerdas y control de riesgos en entornos complejos.</p>
        <p>Planificamos cada intervención con criterios de seguridad, técnica y respeto por el entorno.</p>
      </div>
      <div class="col-md-6">
        <img src="https://images.unsplash.com/photo-1593115057322-e94b77572f20?q=80&w=1200&auto=format&fit=crop" class="img-fluid rounded" alt="Trabajo en altura arborismo">
      </div>
    </div>
  </div>
</section>

<!-- EMERGENCIAS -->
<section class="emergency text-center" id="emergencias">
  <div class="container">
    <h2 class="fw-bold mb-3">Emergencias de arbolado urbano 24/7</h2>
    <p class="mb-4">Árboles caídos, ramas en riesgo o peligro inmediato para personas y viviendas.</p>
    <a href="tel:+56973839028" class="btn btn-alert btn-lg">📞 Llamar ahora</a>
  </div>
</section>

<!-- FOOTER -->
<footer class="bg-black text-white text-center py-4">
  <div class="container">
    <p class="mb-1">📞 +56 9 7383 9028 | Instagram: <a href="https://instagram.com/quercuscortex" class="text-success" target="_blank">@quercuscortex</a></p>
    <p class="mb-0">© 2026 Quercus corteX Arborismo</p>
  </div>
</footer>

<a class="floating-call" href="tel:+56973839028">🚨 Llamar</a>

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
