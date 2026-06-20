# Tenaz2010.github.io
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Electrónica ⚡ | Página de descarga</title>
    <!-- Estilos modernos y responsivos -->
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Roboto, system-ui, sans-serif;
        }

        body {
            background: linear-gradient(145deg, #0b1a2e 0%, #1b2f44 100%);
            min-height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            padding: 20px;
        }

        .card {
            background: rgba(255, 255, 255, 0.07);
            backdrop-filter: blur(12px);
            -webkit-backdrop-filter: blur(12px);
            border-radius: 48px;
            padding: 40px 30px;
            max-width: 820px;
            width: 100%;
            box-shadow: 0 30px 60px rgba(0, 0, 0, 0.6), inset 0 1px 0 rgba(255, 255, 255, 0.08);
            border: 1px solid rgba(255, 255, 255, 0.03);
            transition: transform 0.2s ease;
        }

        .card:hover {
            transform: scale(1.01);
        }

        .header {
            display: flex;
            align-items: center;
            gap: 16px;
            margin-bottom: 28px;
            flex-wrap: wrap;
        }

        .header-icon {
            background: #f0b31c;
            width: 60px;
            height: 60px;
            border-radius: 30px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 32px;
            box-shadow: 0 8px 20px rgba(240, 179, 28, 0.25);
        }

        .header h1 {
            color: #f0f4fa;
            font-weight: 600;
            font-size: 2.1rem;
            letter-spacing: -0.5px;
            text-shadow: 0 4px 12px rgba(0, 0, 0, 0.3);
        }

        .header h1 span {
            color: #f0b31c;
            font-weight: 300;
        }

        .badge {
            background: rgba(240, 179, 28, 0.15);
            padding: 8px 18px;
            border-radius: 40px;
            color: #f0b31c;
            font-weight: 500;
            font-size: 0.9rem;
            border: 1px solid rgba(240, 179, 28, 0.2);
            margin-left: auto;
            white-space: nowrap;
        }

        .hero-image {
            background: #1e3349;
            border-radius: 32px;
            padding: 30px 20px;
            margin: 20px 0 30px 0;
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 18px;
            flex-wrap: wrap;
            border: 1px solid rgba(255, 255, 255, 0.03);
            box-shadow: inset 0 4px 12px rgba(0, 0, 0, 0.3);
        }

        .chip {
            background: #0f1e2d;
            padding: 12px 20px;
            border-radius: 60px;
            color: #b6d0e8;
            font-weight: 400;
            border: 1px solid #3a5a78;
            box-shadow: 0 2px 8px rgba(0, 0, 0, 0.3);
            display: inline-flex;
            align-items: center;
            gap: 10px;
        }

        .chip i {
            font-size: 1.2rem;
        }

        .desc {
            color: #cbdcee;
            font-size: 1.1rem;
            line-height: 1.6;
            margin: 20px 0 28px 0;
            padding: 0 4px;
        }

        .desc strong {
            color: #f0b31c;
            font-weight: 500;
        }

        .download-area {
            background: rgba(0, 0, 0, 0.25);
            border-radius: 40px;
            padding: 30px 24px;
            margin: 20px 0 10px 0;
            display: flex;
            flex-direction: column;
            align-items: center;
            gap: 20px;
            border: 1px solid rgba(255, 255, 255, 0.03);
        }

        .download-btn {
            background: #f0b31c;
            border: none;
            padding: 18px 44px;
            border-radius: 100px;
            font-size: 1.4rem;
            font-weight: 600;
            color: #0b1a2e;
            display: inline-flex;
            align-items: center;
            gap: 16px;
            cursor: pointer;
            transition: all 0.2s ease;
            box-shadow: 0 12px 30px rgba(240, 179, 28, 0.25);
            border: 1px solid rgba(255, 215, 80, 0.3);
            text-decoration: none;
            width: 100%;
            justify-content: center;
        }

        .download-btn:hover {
            background: #fccf4a;
            transform: translateY(-3px) scale(1.02);
            box-shadow: 0 20px 40px rgba(240, 179, 28, 0.4);
        }

        .download-btn:active {
            transform: scale(0.97);
        }

        .download-btn i {
            font-size: 1.8rem;
        }

        .file-info {
            display: flex;
            align-items: center;
            gap: 24px;
            color: #9bb3cc;
            font-size: 0.95rem;
            flex-wrap: wrap;
            justify-content: center;
        }

        .file-info span {
            background: #1e3349;
            padding: 5px 18px;
            border-radius: 30px;
            border: 1px solid #314f69;
        }

        .features {
            display: flex;
            flex-wrap: wrap;
            gap: 14px;
            margin-top: 30px;
            justify-content: center;
        }

        .feature-item {
            background: rgba(255, 255, 255, 0.02);
            padding: 12px 20px;
            border-radius: 60px;
            border: 1px solid rgba(255, 255, 255, 0.04);
            color: #b6d0e8;
            font-size: 0.9rem;
            display: flex;
            align-items: center;
            gap: 10px;
            backdrop-filter: blur(4px);
        }

        .feature-item i {
            color: #f0b31c;
        }

        .footer-note {
            margin-top: 28px;
            text-align: center;
            color: #6d8aa8;
            font-size: 0.85rem;
            border-top: 1px solid rgba(255, 255, 255, 0.03);
            padding-top: 20px;
            letter-spacing: 0.3px;
        }

        /* iconos simulados (sin fontawesome) */
        .icon-symbol {
            display: inline-block;
            font-style: normal;
            font-weight: 400;
        }

        @media (max-width: 600px) {
            .card { padding: 28px 18px; }
            .header h1 { font-size: 1.8rem; }
            .badge { margin-left: 0; width: 100%; text-align: center; }
            .download-btn { font-size: 1.2rem; padding: 16px 20px; }
            .hero-image { flex-direction: column; align-items: stretch; }
        }
    </style>
</head>
<body>

    <div class="card" role="main">
        <!-- Encabezado -->
        <div class="header">
            <div class="header-icon">⚡</div>
            <h1>Electro<span>Hub</span></h1>
            <div class="badge">🔌 v2.0 · 2026</div>
        </div>

        <!-- Slogan / imagen simbólica -->
        <div class="hero-image">
            <span class="chip"><i>🔋</i> PCB · Arduino</span>
            <span class="chip"><i>📡</i> RF · Señales</span>
            <span class="chip"><i>🔄</i> DSP · Filtros</span>
        </div>

        <!-- Descripción -->
        <p class="desc">
            <strong>⚙️ Kit de recursos para electrónica</strong> — esquemas, códigos, simulaciones y 
            documentación técnica. Todo lo necesario para tus proyectos de <strong>hardware</strong> 
            y <strong>sistemas embebidos</strong> en un solo archivo.
        </p>

        <!-- Zona de descarga -->
        <div class="download-area">
            <!-- Botón de descarga (archivo HTML) -->
            <a href="#" id="downloadLink" class="download-btn" download="ElectroHub_recursos.html">
                <i>📥</i> Descargar archivo HTML
            </a>

            <!-- info adicional -->
            <div class="file-info">
                <span>📄 HTML · 28 KB</span>
                <span>🧩 Incluye código, estilos y scripts</span>
                <span>📅 Actualizado 2026</span>
            </div>
        </div>

        <!-- Características / badges -->
        <div class="features">
            <span class="feature-item"><i>🛠️</i> 40+ componentes</span>
            <span class="feature-item"><i>📐</i> Esquemas y PCBs</span>
            <span class="feature-item"><i>💻</i> Ejemplos en C++ / Python</span>
            <span class="feature-item"><i>📊</i> Simulación SPICE</span>
            <span class="feature-item"><i>📘</i> Guía rápida</span>
        </div>

        <div class="footer-note">
            ⚡ Haz clic en el botón para descargar la página completa · compatible con todos los navegadores
        </div>
    </div>

    <!-- ========== SCRIPT DE DESCARGA ========== -->
    <script>
        (function() {
            'use strict';

            // 1. Construir el contenido del archivo HTML que se descargará.
            //    (Incluye la misma página pero con un mensaje de "archivo descargado")
            const pageContent = `<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Electrónica · archivo descargado</title>
    <style>
        * { margin:0; padding:0; box-sizing:border-box; font-family: 'Segoe UI', Roboto, sans-serif; }
        body {
            background: #0b1a2e;
            min-height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            padding: 20px;
        }
        .card {
            background: rgba(255,255,255,0.05);
            backdrop-filter: blur(8px);
            border-radius: 48px;
            padding: 50px 35px;
            max-width: 700px;
            width: 100%;
            border: 1px solid rgba(255,255,255,0.05);
            text-align: center;
            box-shadow: 0 25px 50px rgba(0,0,0,0.6);
        }
        h1 { color: #f0b31c; font-size: 2.8rem; margin-bottom: 12px; }
        .sub { color: #b6d0e8; font-size: 1.3rem; margin-bottom: 28px; }
        .icon-big { font-size: 4rem; margin-bottom: 10px; }
        .info { color: #8aaac9; font-size: 1rem; line-height: 1.6; background: rgba(0,0,0,0.2); padding: 20px; border-radius: 32px; }
        .info strong { color: #f0b31c; }
        .btn { display: inline-block; margin-top: 30px; background: #f0b31c; padding: 14px 36px; border-radius: 60px; color: #0b1a2e; font-weight: 600; text-decoration: none; }
        .footer { margin-top: 30px; color: #4d6e8a; font-size: 0.9rem; }
    </style>
</head>
<body>
    <div class="card">
        <div class="icon-big">📦</div>
        <h1>¡Descarga completada!</h1>
        <p class="sub">Archivo <strong style="color:#f0b31c;">ElectroHub_recursos.html</strong></p>
        <div class="info">
            <strong>✅ Este archivo contiene:</strong><br>
            · Página web con recursos de electrónica (HTML, CSS, JS)<br>
            · Enlaces a documentación y esquemas simulados<br>
            · Código de ejemplo para microcontroladores<br>
            · Lista de componentes y herramientas<br>
            <span style="display:block; margin-top:12px; background:#1e3349; padding:10px; border-radius:30px;">⚡ Guarda este archivo para acceder offline</span>
        </div>
        <a href="#" onclick="alert('Ya tienes el archivo descargado 📂')" class="btn">📂 Abrir recurso</a>
        <div class="footer">ElectroHub · 2026 · versión descargable</div>
    </div>
    <script>
        // solo un pequeño mensaje
        console.log('Archivo descargado correctamente desde ElectroHub');
    </script>
</body>
</html>`;

            // 2. Obtener el elemento <a> del botón
            const downloadBtn = document.getElementById('downloadLink');

            // 3. Evento click: generar blob y forzar descarga
            downloadBtn.addEventListener('click', function(e) {
                e.preventDefault();  // Evita navegación

                // Crear Blob con el contenido (tipo HTML)
                const blob = new Blob([pageContent], { type: 'text/html; charset=utf-8' });

                // Crear URL de objeto
                const url = URL.createObjectURL(blob);

                // Crear un <a> temporal o reusar el existente
                const tempLink = document.createElement('a');
                tempLink.href = url;
                tempLink.download = 'ElectroHub_recursos.html';   // nombre del archivo

                // Disparar clic
                document.body.appendChild(tempLink);
                tempLink.click();

                // Limpiar
                setTimeout(() => {
                    document.body.removeChild(tempLink);
                    URL.revokeObjectURL(url);
                }, 200);

                // Opcional: cambiar texto del botón momentáneamente
                const originalText = downloadBtn.innerHTML;
                downloadBtn.innerHTML = '<i>✅</i> ¡Descargado!';
                setTimeout(() => {
                    downloadBtn.innerHTML = originalText;
                }, 3000);
            });

        })();
    </script>

</body>
</html>
