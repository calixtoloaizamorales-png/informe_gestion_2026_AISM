<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>index.html</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/js/all.min.js"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700;900&display=swap');
        
        body {
            font-family: 'Inter', sans-serif;
            scroll-behavior: smooth;
        }

        .gradient-green {
            background: linear-gradient(135deg, #1a4d2e 0%, #2d7a44 100%);
        }

        .photo-placeholder {
            border: 2px dashed #cbd5e1;
            display: flex;
            align-items: center;
            justify-content: center;
            background: #f8fafc;
            min-height: 350px;
            border-radius: 2rem;
            color: #64748b;
            position: relative;
            overflow: hidden;
            transition: all 0.4s cubic-bezier(0.4, 0, 0.2, 1);
        }

        .photo-placeholder:hover {
            border-color: #34a853;
            background: #f1f5f9;
            transform: scale(1.01);
        }

        .note-card {
            border-left: 4px solid #f59e0b;
            background: white;
            padding: 1.5rem;
            border-radius: 1rem;
            box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.05);
        }
    </style>
</head>
<body class="bg-slate-50 text-slate-900">

    <!-- Navegación -->
    <nav class="sticky top-0 z-50 bg-white/95 backdrop-blur-md shadow-sm border-b border-slate-100">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between h-20 items-center">
                <div class="flex items-center space-x-4">
                    <img src="Imagen1.png" alt="Logo AgroMorales" class="h-14 w-auto object-contain" onerror="this.style.display='none'; this.nextElementSibling.classList.remove('hidden');">
                    <div class="logo-fallback hidden flex items-center space-x-2 text-green-700">
                        <i class="fas fa-tractor text-3xl"></i>
                    </div>
                    <div class="hidden sm:flex flex-col">
                        <span class="font-black text-xl leading-none tracking-tighter text-slate-800 uppercase italic">AgroMorales</span>
                        <span class="text-[10px] uppercase tracking-[0.15em] text-green-700 font-bold">Servicios Morales S.A.S.</span>
                    </div>
                </div>
                <div class="hidden lg:flex space-x-8 text-xs font-bold text-slate-500 uppercase tracking-widest">
                    <a href="#inicio" class="hover:text-green-700 transition">Inicio</a>
                    <a href="#operaciones" class="hover:text-green-700 transition">Gestión</a>
                    <a href="#financiero" class="hover:text-green-700 transition">Cifras</a>
                    <a href="#notas" class="hover:text-green-700 transition">Notas</a>
                </div>
                <button class="bg-green-700 text-white px-6 py-2.5 rounded-full text-xs font-black hover:bg-green-800 transition shadow-lg uppercase tracking-tighter">
                    Exportar Datos
                </button>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <header id="inicio" class="gradient-green text-white py-32 px-4 relative overflow-hidden">
        <div class="max-w-5xl mx-auto text-center relative z-10">
            <div class="mb-12 flex justify-center">
                <div class="bg-white p-8 rounded-[3rem] shadow-2xl">
                    <img src="Imagen1.png" alt="Logo AgroMorales" class="h-32 md:h-44 w-auto object-contain">
                </div>
            </div>
            <h1 class="text-6xl md:text-9xl font-black mb-6 tracking-tighter uppercase italic leading-none">
                Informe <span class="text-yellow-400">2025</span>
            </h1>
            <p class="text-xl md:text-2xl opacity-90 mb-12 font-medium max-w-2xl mx-auto leading-relaxed">
                Rendición de cuentas y estados financieros consolidados.
            </p>
            <div class="inline-flex items-center bg-black/30 backdrop-blur-xl rounded-2xl px-10 py-4 text-sm font-bold border border-white/10 shadow-2xl">
                <i class="fas fa-calendar-check mr-3 text-yellow-400"></i> Corte a Diciembre 31 de 2025
            </div>
        </div>
    </header>

    <!-- Sección de Gerencia -->
    <section class="py-24 max-w-7xl mx-auto px-4">
        <div class="grid lg:grid-cols-2 gap-20 items-center">
            <div>
                <!-- ESPACIO PARA FOTO DEL GERENTE -->
                <!-- Para cambiar esta foto: Reemplaza el <div> de abajo por <img src="tu_foto.jpg" class="rounded-[3rem] shadow-2xl"> -->
                <div class="photo-placeholder aspect-square bg-slate-200">
                    <div class="text-center p-10">
                        <i class="fas fa-user-tie text-7xl mb-4 opacity-10"></i>
                        <p class="text-xs font-black uppercase tracking-widest text-slate-400 italic">Fotografía Gerencia General</p>
                    </div>
                </div>
            </div>
            <div class="space-y-8">
                <h2 class="text-4xl font-black text-slate-900 leading-none tracking-tighter uppercase">Mensaje de <br><span class="text-green-700">Alcides Morales</span></h2>
                <p class="text-2xl text-slate-500 leading-relaxed italic font-light">
                    "Nuestra inversión récord en infraestructura y maquinaria durante este periodo nos permite garantizar una operación ininterrumpida y eficiente para todos nuestros socios estratégicos."
                </p>
                <div class="grid grid-cols-2 gap-4">
                    <div class="p-6 bg-white rounded-3xl border border-slate-100 shadow-sm">
                        <p class="text-[10px] text-slate-400 font-bold uppercase mb-1">Crecimiento Ingresos</p>
                        <p class="text-2xl font-black text-green-700">17.1%</p>
                    </div>
                    <div class="p-6 bg-white rounded-3xl border border-slate-100 shadow-sm">
                        <p class="text-[10px] text-slate-400 font-bold uppercase mb-1">Crecimiento Utilidad</p>
                        <p class="text-2xl font-black text-green-700">13.9%</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Frentes Operativos -->
    <section id="operaciones" class="bg-slate-900 py-32 text-white">
        <div class="max-w-7xl mx-auto px-4">
            <h2 class="text-center text-5xl font-black mb-20 uppercase italic tracking-tighter italic">Gestión de <span class="text-green-400">Frentes Operativos</span></h2>
            
            <div class="grid lg:grid-cols-2 gap-16">
                <!-- Frente 1 -->
                <div class="space-y-8">
                    <!-- ESPACIO PARA FOTO DE CAMPO -->
                    <!-- Reemplazar el <div> de abajo por <img src="foto_campo.jpg" class="rounded-[2rem] w-full h-96 object-cover shadow-2xl"> -->
                    <div class="photo-placeholder !bg-slate-800 !border-slate-700 h-96">
                        <div class="text-center p-10">
                            <i class="fas fa-seedling text-5xl mb-4 text-green-500 opacity-20"></i>
                            <p class="text-xs font-bold uppercase tracking-widest text-slate-500 italic">Imagen Labores de Campo</p>
                        </div>
                    </div>
                    <div>
                        <h3 class="text-3xl font-black mb-4">Apoyo a la Agricultura</h3>
                        <p class="text-slate-400 leading-relaxed">Operación principal con facturación de <strong>$8.221.916.594</strong>. Implementación de tecnología de punta en la asistencia técnica rural.</p>
                    </div>
                </div>

                <!-- Frente 2 -->
                <div class="space-y-8">
                    <!-- ESPACIO PARA FOTO DE TRANSPORTE -->
                    <!-- Reemplazar el <div> de abajo por <img src="foto_transporte.jpg" class="rounded-[2rem] w-full h-96 object-cover shadow-2xl"> -->
                    <div class="photo-placeholder !bg-slate-800 !border-slate-700 h-96">
                        <div class="text-center p-10">
                            <i class="fas fa-truck-moving text-5xl mb-4 text-yellow-500 opacity-20"></i>
                            <p class="text-xs font-bold uppercase tracking-widest text-slate-500 italic">Imagen Flota de Transporte</p>
                        </div>
                    </div>
                    <div>
                        <h3 class="text-3xl font-black mb-4">Logística Integral</h3>
                        <p class="text-slate-400 leading-relaxed">Servicios de transporte bajo código 4921 con ingresos de <strong>$796.160.552</strong>. Seguridad y puntualidad en cada trayecto.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Indicadores -->
    <section id="financiero" class="py-24 max-w-7xl mx-auto px-4">
        <div class="bg-white p-12 rounded-[3.5rem] shadow-xl border border-slate-100">
            <h3 class="text-3xl font-black mb-12 uppercase italic text-center tracking-tighter">Resultados <span class="text-green-700">Financieros</span></h3>
            <div class="grid md:grid-cols-2 lg:grid-cols-4 gap-8">
                <div class="text-center">
                    <p class="text-xs font-black text-slate-400 uppercase mb-2">Activos Totales</p>
                    <p class="text-3xl font-black text-slate-900">$6.976M</p>
                </div>
                <div class="text-center">
                    <p class="text-xs font-black text-slate-400 uppercase mb-2">Patrimonio Neto</p>
                    <p class="text-3xl font-black text-slate-900">$3.437M</p>
                </div>
                <div class="text-center">
                    <p class="text-xs font-black text-slate-400 uppercase mb-2">Utilidad Ejercicio</p>
                    <p class="text-3xl font-black text-green-700">$656M</p>
                </div>
                <div class="text-center">
                    <p class="text-xs font-black text-slate-400 uppercase mb-2">Efectivo Final</p>
                    <p class="text-3xl font-black text-slate-900">$183M</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Firmas -->
    <section class="py-32 px-4 max-w-6xl mx-auto">
        <div class="grid md:grid-cols-3 gap-16 text-center">
            <div class="space-y-4">
                <div class="h-20 border-b-2 border-slate-100 flex items-end justify-center pb-2">
                    <span class="text-[10px] text-slate-300 uppercase font-black">Firma Representante</span>
                </div>
                <p class="font-black text-slate-900 uppercase italic">José Alcides Morales</p>
                <p class="text-[10px] text-slate-400 font-bold uppercase tracking-widest">Representante Legal</p>
            </div>
            <div class="space-y-4">
                <div class="h-20 border-b-2 border-slate-100 flex items-end justify-center pb-2 italic text-slate-400 text-xs">
                    <!-- ESPACIO PARA IMAGEN DE FIRMA CONTADORA -->
                    M. Alejandra Zamorano
                </div>
                <p class="font-black text-slate-900 uppercase italic">M. Alejandra Zamorano</p>
                <p class="text-[10px] text-slate-400 font-bold uppercase tracking-widest">Contadora | T.P. 329449-T</p>
            </div>
            <div class="space-y-4">
                <div class="h-20 border-b-2 border-slate-100 flex items-end justify-center pb-2 italic text-slate-400 text-xs">
                    Calixto Loaiza Morales
                </div>
                <p class="font-black text-slate-900 uppercase italic">Calixto Loaiza Morales</p>
                <p class="text-[10px] text-slate-400 font-bold uppercase tracking-widest">Revisor Fiscal | T.P. 233038-T</p>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-slate-950 text-white py-16 px-4">
        <div class="max-w-7xl mx-auto flex flex-col md:flex-row justify-between items-center opacity-40">
            <div class="flex items-center space-x-3 mb-4 md:mb-0">
                <img src="Imagen1.png" class="h-8 invert grayscale" alt="">
                <span class="font-black italic uppercase">AISM 2025</span>
            </div>
            <p class="text-[10px] font-bold uppercase tracking-widest">Zarzal, Valle del Cauca, Colombia</p>
        </div>
    </footer>

</body>
</html>
