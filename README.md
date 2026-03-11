<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Informe de Gestión 2025 - AgroMorales</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/js/all.min.js"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700;900&display=swap');
        body { font-family: 'Inter', sans-serif; scroll-behavior: smooth; }
        .gradient-green { background: linear-gradient(135deg, #1a4d2e 0%, #2d7a44 100%); }
        .note-card { border-left: 4px solid #f59e0b; background: white; padding: 1.5rem; border-radius: 1rem; box-shadow: 0 4px 6px rgba(0,0,0,0.05); }
        .photo-placeholder { border: 2px dashed #cbd5e1; display: flex; align-items: center; justify-content: center; background: #f8fafc; min-height: 350px; border-radius: 2rem; color: #64748b; }
    </style>
</head>
<body class="bg-slate-50 text-slate-900">

    <!-- Navegación -->
    <nav class="sticky top-0 z-50 bg-white/95 backdrop-blur-md shadow-sm border-b border-slate-100">
        <div class="max-w-7xl mx-auto px-4 flex justify-between h-20 items-center">
            <div class="flex items-center space-x-4">
                <!-- Usando Imagen1.png con I mayúscula como está en tu GitHub -->
                <img src="Imagen1.png" alt="Logo AgroMorales" class="h-14 w-auto object-contain" onerror="this.style.display='none'; this.nextElementSibling.classList.remove('hidden');">
                <div class="hidden sm:flex flex-col">
                    <span class="font-black text-xl leading-none text-slate-800 uppercase italic">AgroMorales</span>
                    <span class="text-[10px] uppercase text-green-700 font-bold">Servicios Morales S.A.S.</span>
                </div>
            </div>
            <div class="hidden lg:flex space-x-8 text-xs font-bold text-slate-500 uppercase tracking-widest">
                <a href="#inicio" class="hover:text-green-700">Inicio</a>
                <a href="#operaciones" class="hover:text-green-700">Gestión</a>
                <a href="#financiero" class="hover:text-green-700">Cifras</a>
                <a href="#legal" class="hover:text-green-700">Legal</a>
            </div>
            <button class="bg-green-700 text-white px-6 py-2 rounded-full text-xs font-black uppercase shadow-lg">Descargar</button>
        </div>
    </nav>

    <!-- Hero -->
    <header id="inicio" class="gradient-green text-white py-24 px-4 text-center">
        <div class="max-w-5xl mx-auto">
            <div class="mb-10 flex justify-center">
                <div class="bg-white p-6 rounded-[2.5rem] shadow-2xl">
                    <!-- Logo Central con I mayúscula -->
                    <img src="Imagen1.png" alt="Logo AgroMorales" class="h-32 md:h-40 w-auto">
                </div>
            </div>
            <h1 class="text-6xl md:text-8xl font-black mb-4 tracking-tighter uppercase italic">Informe <span class="text-yellow-400">2025</span></h1>
            <p class="text-xl opacity-90 mb-8 font-medium">Agroindustrial de Servicios Morales S.A.S. | NIT: 901.271.865-4</p>
            <div class="inline-flex bg-black/20 rounded-xl px-6 py-3 text-sm font-bold border border-white/10">
                Km 2 vía corregimiento limones - Zarzal, Valle
            </div>
        </div>
    </header>

    <!-- Gerencia -->
    <section class="py-20 max-w-7xl mx-auto px-4">
        <div class="grid lg:grid-cols-2 gap-16 items-center">
            <div class="photo-placeholder bg-slate-200">
                <i class="fas fa-user-tie text-7xl opacity-10"></i>
                <p class="absolute bottom-6 text-[10px] font-black uppercase text-slate-400">José Alcides Morales Rincón</p>
            </div>
            <div class="space-y-6">
                <h2 class="text-4xl font-black text-slate-900 uppercase italic">Mensaje de Gerencia</h2>
                <p class="text-xl text-slate-500 italic leading-relaxed">
                    "El 2025 ha sido un año de inversión estratégica. Con la adquisición de maquinaria y el fortalecimiento de nuestros dos frentes operativos, garantizamos la eficiencia que nuestros clientes en el Valle exigen."
                </p>
                <div class="grid grid-cols-2 gap-4">
                    <div class="p-5 bg-white rounded-2xl border border-slate-100 shadow-sm">
                        <p class="text-[10px] text-slate-400 font-bold uppercase mb-1 italic">Ingresos</p>
                        <p class="text-2xl font-black text-green-700">$9.094M</p>
                    </div>
                    <div class="p-5 bg-white rounded-2xl border border-slate-100 shadow-sm">
                        <p class="text-[10px] text-slate-400 font-bold uppercase mb-1 italic">Patrimonio</p>
                        <p class="text-2xl font-black text-green-700">$3.437M</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Operaciones -->
    <section id="operaciones" class="bg-slate-900 py-24 text-white">
        <div class="max-w-7xl mx-auto px-4">
            <h2 class="text-center text-4xl font-black mb-16 uppercase italic">Unidades de <span class="text-green-400">Negocio</span></h2>
            <div class="grid md:grid-cols-2 gap-12">
                <div class="space-y-6">
                    <div class="photo-placeholder !bg-slate-800 !border-slate-700 h-80">
                        <i class="fas fa-tractor text-5xl opacity-10 text-green-500"></i>
                    </div>
                    <h3 class="text-2xl font-black uppercase">Actividades de Campo</h3>
                    <p class="text-slate-400">Asistencia técnica agrícola con ingresos de $8.221.916.594. Somos especialistas en el apoyo integral a la agricultura.</p>
                </div>
                <div class="space-y-6">
                    <div class="photo-placeholder !bg-slate-800 !border-slate-700 h-80">
                        <i class="fas fa-truck-moving text-5xl opacity-10 text-yellow-500"></i>
                    </div>
                    <h3 class="text-2xl font-black uppercase">Transporte Logístico</h3>
                    <p class="text-slate-400">Movilización de pasajeros y carga con ingresos de $796.160.552, cumpliendo con los más altos estándares de seguridad vial.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Cifras -->
    <section id="financiero" class="py-24 max-w-7xl mx-auto px-4">
        <h2 class="text-3xl font-black mb-12 uppercase italic text-center">Resultados Financieros <span class="text-green-700">Consolidados</span></h2>
        <div class="grid lg:grid-cols-3 gap-8">
            <div class="note-card">
                <h4 class="text-xs font-black uppercase text-slate-400 mb-4 tracking-widest">Activos Totales</h4>
                <p class="text-3xl font-black text-slate-900">$6.976.219.107</p>
                <div class="mt-4 w-full bg-slate-100 h-2 rounded-full overflow-hidden">
                    <div class="bg-green-600 h-full w-full"></div>
                </div>
            </div>
            <div class="note-card">
                <h4 class="text-xs font-black uppercase text-slate-400 mb-4 tracking-widest">Utilidad del Ejercicio</h4>
                <p class="text-3xl font-black text-green-700">$656.233.278</p>
                <div class="mt-4 w-full bg-slate-100 h-2 rounded-full overflow-hidden">
                    <div class="bg-green-600 h-full w-3/4"></div>
                </div>
            </div>
            <div class="note-card">
                <h4 class="text-xs font-black uppercase text-slate-400 mb-4 tracking-widest">Flujo de Efectivo</h4>
                <p class="text-3xl font-black text-slate-900">$183.617.251</p>
                <div class="mt-4 w-full bg-slate-100 h-2 rounded-full overflow-hidden">
                    <div class="bg-yellow-500 h-full w-1/4"></div>
                </div>
            </div>
        </div>
    </section>

    <!-- Firmas -->
    <section id="legal" class="py-24 bg-white border-t">
        <div class="max-w-6xl mx-auto px-4">
            <div class="grid md:grid-cols-3 gap-16 text-center">
                <div class="space-y-4">
                    <div class="h-20 border-b-2 border-slate-100 flex items-end justify-center pb-2 uppercase text-[10px] font-black text-slate-300 italic tracking-widest">Firma Representante</div>
                    <p class="font-black text-slate-900 uppercase text-lg italic">José Alcides Morales</p>
                    <p class="text-[10px] text-slate-400 font-bold uppercase tracking-widest">Gerente General</p>
                </div>
                <div class="space-y-4">
                    <div class="h-20 border-b-2 border-slate-100 flex items-end justify-center pb-2 uppercase text-[10px] font-black text-slate-300 italic tracking-widest">Firma Contadora</div>
                    <p class="font-black text-slate-900 uppercase text-lg italic">M. Alejandra Zamorano</p>
                    <p class="text-[10px] text-slate-400 font-bold uppercase tracking-widest">T.P. 329449-T</p>
                </div>
                <div class="space-y-4">
                    <div class="h-20 border-b-2 border-slate-100 flex items-end justify-center pb-2 uppercase text-[10px] font-black text-slate-300 italic tracking-widest">Firma Revisor</div>
                    <p class="font-black text-slate-900 uppercase text-lg italic">Calixto Loaiza Morales</p>
                    <p class="text-[10px] text-slate-400 font-bold uppercase tracking-widest">T.P. 233038-T</p>
                </div>
            </div>
        </div>
    </section>

    <footer class="bg-slate-950 text-white/40 py-12 text-center text-[10px] uppercase font-bold tracking-widest italic">
        © 2025 Agroindustrial de Servicios Morales S.A.S. - Todos los derechos reservados
    </footer>

</body>
