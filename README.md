<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Founder | Verusbpo</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,700;0,900;1,700&family=Inter:wght@300;400;600&display=swap" rel="stylesheet">
    <style>
        :root {
            --brand-red: #e61919;
            --brand-dark: #000000;
            --brand-gray: #0a0a0a;
        }
        body {
            background-color: var(--brand-dark);
            color: #ffffff;
            font-family: 'Inter', sans-serif;
            overflow-x: hidden;
        }
        h1, h2, h3, .serif {
            font-family: 'Playfair Display', serif;
        }
        .text-logo {
            font-family: 'Playfair Display', serif;
            letter-spacing: -2px;
        }
        .glass-card {
            background: linear-gradient(145deg, rgba(15, 15, 15, 0.9), rgba(5, 5, 5, 0.9));
            border: 1px solid rgba(230, 25, 25, 0.1);
            backdrop-filter: blur(12px);
            transition: all 0.5s cubic-bezier(0.23, 1, 0.32, 1);
        }
        .glass-card:hover {
            border-color: var(--brand-red);
            transform: translateY(-8px);
            box-shadow: 0 15px 35px rgba(230, 25, 25, 0.15);
        }
        .btn-premium {
            background: transparent;
            border: 1px solid var(--brand-red);
            color: white;
            transition: all 0.4s ease;
            text-transform: uppercase;
            letter-spacing: 3px;
            font-size: 0.7rem;
            font-weight: 700;
        }
        .btn-premium:hover {
            background: var(--brand-red);
            box-shadow: 0 0 25px rgba(230, 25, 25, 0.4);
        }
        .feature-tag {
            background: rgba(230, 25, 25, 0.1);
            border: 1px solid rgba(230, 25, 25, 0.2);
            padding: 4px 12px;
            border-radius: 99px;
            font-size: 10px;
            font-weight: bold;
            color: var(--brand-red);
            text-transform: uppercase;
        }
        .divider {
            height: 1px;
            background: linear-gradient(90deg, transparent, #222, transparent);
        }
        .smoke {
            position: absolute;
            top: 0; left: 50%;
            transform: translateX(-50%);
            width: 100%;
            height: 100%;
            background: radial-gradient(circle at center, rgba(230, 25, 25, 0.04) 0%, transparent 70%);
            pointer-events: none;
            z-index: -1;
        }
    </style>
</head>
<body class="selection:bg-red-600 selection:text-white">

    <div class="smoke"></div>

    <div class="max-w-5xl mx-auto px-6 py-20">
        
        <!-- Header Minimalista -->
        <header class="relative mb-32 text-center">
            <h1 class="text-logo text-7xl md:text-9xl font-black mb-6 leading-none pt-12">
                Verusbpo<span class="text-red-600">.</span>
            </h1>
            <p class="uppercase tracking-[0.6em] text-gray-500 text-[10px] mb-12 font-bold">Intelligence • Growth • Automation</p>
            
            <p class="text-xl md:text-2xl text-gray-400 font-light max-w-2xl mx-auto leading-relaxed">
                Fundador e Arquiteto de Sistemas. <br>
                Construindo o futuro da <span class="text-white font-semibold">inteligência de vendas B2B</span>.
            </p>
        </header>

        <!-- Product Spotlight: Zmedia CRM -->
        <section class="mb-24">
            <div class="glass-card rounded-[40px] p-10 md:p-16 relative overflow-hidden">
                <div class="flex flex-col lg:flex-row gap-16">
                    <div class="flex-1">
                        <div class="flex items-center gap-4 mb-6">
                            <span class="feature-tag italic serif">Flagship SaaS</span>
                            <div class="flex items-center gap-2">
                                <span class="w-2 h-2 bg-green-500 rounded-full animate-pulse"></span>
                                <span class="text-[9px] font-bold text-gray-500 tracking-widest uppercase">MVP / Active</span>
                            </div>
                        </div>
                        
                        <h2 class="text-5xl md:text-7xl font-bold mb-6 italic">Zmidia CRM</h2>
                        
                        <p class="text-gray-300 text-lg mb-8 leading-relaxed font-light">
                            Plataforma B2B SaaS focada em inteligência de vendas e CRM para agências. 
                            Resolvemos o gargalo de qualificação e visibilidade comercial através de tecnologia de ponta.
                        </p>

                        <div class="grid grid-cols-2 gap-4 mb-10">
                            <div class="flex items-center gap-3 text-sm text-gray-400">
                                <i class="fas fa-check text-red-600"></i> Lead Management
                            </div>
                            <div class="flex items-center gap-3 text-sm text-gray-400">
                                <i class="fas fa-check text-red-600"></i> Sales Pipeline
                            </div>
                            <div class="flex items-center gap-3 text-sm text-gray-400">
                                <i class="fas fa-check text-red-600"></i> AI Qualification
                            </div>
                            <div class="flex items-center gap-3 text-sm text-gray-400">
                                <i class="fas fa-check text-red-600"></i> Auto Workflows
                            </div>
                        </div>

                        <div class="flex flex-wrap gap-4">
                            <a href="https://zmidia.verusbpo.com" target="_blank" class="btn-premium px-10 py-5 rounded-full">
                                Launch Platform
                            </a>
                        </div>
                    </div>

                    <!-- Tech Stack Side -->
                    <div class="lg:w-1/3 flex flex-col justify-center gap-8 border-l border-white/5 pl-0 lg:pl-12">
                        <div>
                            <h4 class="text-[10px] uppercase tracking-[0.3em] text-red-600 font-bold mb-4">Core Architecture</h4>
                            <div class="space-y-4">
                                <div class="flex justify-between items-center text-xs">
                                    <span class="text-gray-500 font-medium italic serif">Frontend</span>
                                    <span class="text-white font-bold">React.js</span>
                                </div>
                                <div class="flex justify-between items-center text-xs">
                                    <span class="text-gray-500 font-medium italic serif">Backend</span>
                                    <span class="text-white font-bold">Node.js</span>
                                </div>
                                <div class="flex justify-between items-center text-xs">
                                    <span class="text-gray-500 font-medium italic serif">AI Engine</span>
                                    <span class="text-white font-bold">Python / LLMs</span>
                                </div>
                                <div class="flex justify-between items-center text-xs">
                                    <span class="text-gray-500 font-medium italic serif">Infra</span>
                                    <span class="text-white font-bold">Cloud-Native</span>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Solutions Section -->
        <section class="grid md:grid-cols-2 gap-10 mb-32">
            <div class="glass-card p-12 rounded-[30px]">
                <div class="w-12 h-12 bg-red-600 rounded-lg flex items-center justify-center mb-8 shadow-[0_0_25px_rgba(230,25,25,0.4)]">
                    <i class="fas fa-bolt text-black text-xl"></i>
                </div>
                <h3 class="text-2xl font-bold mb-4 italic">The Problem</h3>
                <p class="text-gray-500 leading-relaxed text-sm font-light">
                    Agências perdem escala por falhas na qualificação de leads, falta de follow-up sistemático e ausência de dados precisos sobre o pipeline de vendas.
                </p>
            </div>

            <div class="glass-card p-12 rounded-[30px]">
                <div class="w-12 h-12 bg-white rounded-lg flex items-center justify-center mb-8 shadow-[0_0_25px_rgba(255,255,255,0.1)]">
                    <i class="fas fa-key text-black text-xl"></i>
                </div>
                <h3 class="text-2xl font-bold mb-4 italic">The Solution</h3>
                <p class="text-gray-500 leading-relaxed text-sm font-light text-white/70">
                    O Zmidia centraliza leads, pipelines, automações de pagamento e insights gerados por IA em um sistema único de alta performance comercial.
                </p>
            </div>
        </section>

        <!-- Divider -->
        <div class="divider mb-32"></div>

        <!-- Tech Stack -->
        <section class="mb-32 text-center">
            <h2 class="text-xs uppercase tracking-[0.4em] text-red-600 font-bold mb-16">The Ecosystem</h2>
            <div class="flex flex-wrap justify-center gap-16">
                <div class="group flex flex-col items-center gap-4">
                    <i class="fab fa-react text-5xl text-gray-700 group-hover:text-blue-400 transition-all duration-500"></i>
                    <span class="text-[8px] uppercase tracking-widest opacity-0 group-hover:opacity-100 transition-opacity">Frontend</span>
                </div>
                <div class="group flex flex-col items-center gap-4">
                    <i class="fab fa-node-js text-5xl text-gray-700 group-hover:text-green-500 transition-all duration-500"></i>
                    <span class="text-[8px] uppercase tracking-widest opacity-0 group-hover:opacity-100 transition-opacity">Backend</span>
                </div>
                <div class="group flex flex-col items-center gap-4">
                    <i class="fab fa-python text-5xl text-gray-700 group-hover:text-yellow-500 transition-all duration-500"></i>
                    <span class="text-[8px] uppercase tracking-widest opacity-0 group-hover:opacity-100 transition-opacity">AI/LLMs</span>
                </div>
                <div class="group flex flex-col items-center gap-4">
                    <i class="fas fa-cloud text-5xl text-gray-700 group-hover:text-red-600 transition-all duration-500"></i>
                    <span class="text-[8px] uppercase tracking-widest opacity-0 group-hover:opacity-100 transition-opacity">Infra</span>
                </div>
            </div>
        </section>

        <!-- Footer / Contact -->
        <footer class="text-center">
            <div class="inline-block glass-card px-12 py-8 rounded-full border-red-900/20">
                <div class="flex gap-10">
                    <a href="https://verusbpo.com" class="text-gray-400 hover:text-white transition" title="Verusbpo Home"><i class="fas fa-globe text-lg"></i></a>
                    <a href="https://zmidia.verusbpo.com" class="text-gray-400 hover:text-red-600 transition" title="Zmidia App"><i class="fas fa-rocket text-lg"></i></a>
                    <a href="#" class="text-gray-400 hover:text-white transition" title="GitHub Profile"><i class="fab fa-github text-lg"></i></a>
                </div>
            </div>
            <p class="mt-12 text-[10px] text-gray-600 uppercase tracking-[0.5em] font-bold italic">
                Verusbpo<span class="text-red-900">.</span> 
                <span class="font-light normal-case tracking-normal ml-2 text-gray-700">Engineering elitist B2B systems.</span>
            </p>
        </footer>
    </div>

</body>
</html>
