<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <title>Anuska García | Digital Operations & AI Support</title>
    <style>
        :root {
            --bg-color: #0f172a;
            --card-bg: #1e293b;
            --accent-color: #38bdf8;
            --text-primary: #f8fafc;
            --text-secondary: #94a3b8;
            --border-color: #334155;
        }

        body {
            font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, sans-serif;
            background-color: var(--bg-color);
            color: var(--text-primary);
            margin: 0;
            padding: 0;
            line-height: 1.6;
        }

        .container {
            max-width: 900px;
            margin: 0 auto;
            padding: 2rem 1.5rem;
        }

        header {
            text-align: center;
            padding: 3rem 1rem 2rem;
            border-bottom: 1px solid var(--border-color);
        }

        h1 {
            font-size: 2.5rem;
            margin: 0;
            color: var(--accent-color);
            letter-spacing: -0.02em;
        }

        .subtitle {
            font-size: 1.25rem;
            color: var(--text-secondary);
            margin-top: 0.5rem;
            font-weight: 500;
        }

        .tagline {
            margin-top: 1.5rem;
            font-size: 1.1rem;
            color: var(--text-primary);
            max-width: 600px;
            margin-left: auto;
            margin-right: auto;
        }

        .metrics-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
            gap: 1.5rem;
            margin: 3rem 0;
        }

        .metric-card {
            background-color: var(--card-bg);
            border: 1px solid var(--border-color);
            padding: 1.5rem;
            border-radius: 12px;
            text-align: center;
        }

        .metric-number {
            font-size: 2rem;
            font-weight: bold;
            color: var(--accent-color);
            display: block;
        }

        .metric-label {
            font-size: 0.9rem;
            color: var(--text-secondary);
        }

        section {
            margin-bottom: 3.5rem;
        }

        h2 {
            font-size: 1.5rem;
            border-bottom: 2px solid var(--accent-color);
            padding-bottom: 0.5rem;
            display: inline-block;
            margin-bottom: 1.5rem;
        }

        .project-card {
            background-color: var(--card-bg);
            border: 1px solid var(--border-color);
            border-radius: 12px;
            padding: 1.5rem;
            margin-bottom: 1.5rem;
        }

        .project-title {
            font-size: 1.2rem;
            font-weight: bold;
            color: var(--accent-color);
            margin-bottom: 0.5rem;
        }

        .badge-list {
            display: flex;
            flex-wrap: wrap;
            gap: 0.5rem;
            margin-top: 1rem;
        }

        .badge {
            background-color: #0284c7;
            color: white;
            font-size: 0.8rem;
            padding: 0.3rem 0.8rem;
            border-radius: 20px;
            font-weight: 600;
        }

        .badge-alt {
            background-color: #334155;
            color: var(--accent-color);
            font-size: 0.8rem;
            padding: 0.3rem 0.8rem;
            border-radius: 20px;
            font-weight: 600;
        }

        ul.cert-list {
            list-style: none;
            padding: 0;
        }

        ul.cert-list li {
            background-color: var(--card-bg);
            border: 1px solid var(--border-color);
            margin-bottom: 0.8rem;
            padding: 1rem;
            border-radius: 8px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            flex-wrap: wrap;
            gap: 0.5rem;
        }

        .cta-section {
            text-align: center;
            background-color: var(--card-bg);
            border: 1px solid var(--accent-color);
            padding: 2.5rem 1.5rem;
            border-radius: 12px;
            margin-top: 3rem;
        }

        .btn {
            display: inline-block;
            background-color: var(--accent-color);
            color: #0f172a;
            font-weight: bold;
            padding: 0.8rem 1.8rem;
            border-radius: 8px;
            text-decoration: none;
            margin-top: 1rem;
            transition: opacity 0.2s;
        }

        .btn:hover {
            opacity: 0.9;
        }

        footer {
            text-align: center;
            color: var(--text-secondary);
            font-size: 0.85rem;
            margin-top: 4rem;
            padding-bottom: 2rem;
        }
    </style>
</head>
<body>

<div class="container">
    <header>
        <h1>ANUSKA GARCÍA</h1>
        <div class="subtitle">Digital Operations & Administrative Support</div>
        <p class="tagline">Gestión administrativa sólida impulsada por Inteligencia Artificial, rigor en el dato y mentalidad digital.</p>
    </header>

    <div class="metrics-grid">
        <div class="metric-card">
            <span class="metric-number">+1.500 h</span>
            <span class="metric-label">Formación Oficial Acreditada</span>
        </div>
        <div class="metric-card">
            <span class="metric-number">7</span>
            <span class="metric-label">Certificaciones Especializadas</span>
        </div>
        <div class="metric-card">
            <span class="metric-number">AI Ready</span>
            <span class="metric-label">Prompt Engineering & Workflows</span>
        </div>
    </div>

    <section>
        <h2>01. SOBRE MÍ</h2>
        <p>Aporto una trayectoria consolidada en gestión administrativa, organización de flujos de trabajo y atención al usuario. En constante evolución técnica, integro herramientas de <strong>Inteligencia Artificial y Prompt Engineering</strong> para optimizar la productividad operativa, aportando orden, agilidad y visión digital a entornos profesionales dinámicos y tecnológicos.</p>
    </section>

    <section>
        <h2>02. PORTFOLIO DE CAPACIDADES</h2>
        
        <div class="project-card">
            <div class="project-title">01 / AI Workflows & Productividad Digital</div>
            <p>Diseño e integración de flujos de trabajo apoyados en modelos de lenguaje (LLMs / Gemini API) para el análisis automatizado de documentación, optimización de textos y soporte operativo.</p>
            <div class="badge-list">
                <span class="badge">Prompt Engineering</span>
                <span class="badge">IBM Learning</span>
                <span class="badge">Automatización</span>
            </div>
        </div>

        <div class="project-card">
            <div class="project-title">02 / Data Operations & Gestión Documental</div>
            <p>Tratamiento, grabación y validación rigurosa de bases de datos. Organización de archivos digitales, soporte a despachos y gestión bajo normativas técnicas oficiales (ADGG0508 / ADGG0308).</p>
            <div class="badge-list">
                <span class="badge">Tratamiento de Datos</span>
                <span class="badge">Gestión Documental</span>
                <span class="badge">Calidad de Datos</span>
            </div>
        </div>

        <div class="project-card">
            <div class="project-title">03 / Soporte Operativo & Atención al Cliente</div>
            <p>Gestión eficiente de la relación con el usuario, resolución de incidencias, comunicación comercial y coordinación de procesos administrativos transversales.</p>
            <div class="badge-list">
                <span class="badge">Customer Support</span>
                <span class="badge">Atención Comercial</span>
                <span class="badge">PRL (329h)</span>
            </div>
        </div>
    </section>

    <section>
        <h2>03. FORMACIÓN & CERTIFICACIONES</h2>
        
        <ul class="cert-list">
            <li>
                <strong>Grabación y Tratamiento de Datos y Documentos (ADGG0508)</strong>
                <span class="badge-alt">Certificado Oficial 2026</span>
            </li>
            <li>
                <strong>Gestión Documental y Asistencia en Despachos (ADGG0308)</strong>
                <span class="badge-alt">Nivel 3 Oficial</span>
            </li>
            <li>
                <strong>Actividades Administrativas en Relación con el Cliente (ADGG0208)</strong>
                <span class="badge-alt">Acreditado SEPE / Labora</span>
            </li>
            <li>
                <strong>Gestión del Pequeño Comercio (+500 h)</strong>
                <span class="badge-alt">Certificado Oficial</span>
            </li>
            <li>
                <strong>Inglés para la Gestión Comercial (209 h)</strong>
                <span class="badge-alt">SERVEF / Labora</span>
            </li>
            <li>
                <strong>Prevención de Riesgos Laborales / PRL (329 h)</strong>
                <span class="badge-alt">Ausiàs March</span>
            </li>
            <li>
                <strong>IA & Prompt Engineering</strong>
                <span class="badge-alt">IBM (En curso)</span>
            </li>
        </ul>
    </section>

    <div class="cta-section">
        <h2>¿Conectamos para crear impacto operativo?</h2>
        <p>Disponible para posiciones de Soporte Administrativo, Operations o Customer Support en remoto o híbrido.</p>
        <a href="mailto:tu-email@ejemplo.com" class="btn">Enviar Correo Electrónico</a>
    </div>

    <footer>
        <p>© 2026 Anuska García — Digital-Minded Administration</p>
    </footer>
</div>

</body>
</html>

