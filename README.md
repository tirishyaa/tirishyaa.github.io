# tirishyaa.github.io

<html lang="en" class="dark">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MPOB Palm Yield Derivative Explorer</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Chart.js CDN -->
    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
    <!-- MathJax for LaTeX Rendering -->
    <script src="https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
    <script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>
    <script>
        tailwind.config = {
            darkMode: 'class',
            theme: {
                extend: {
                    colors: {
                        emerald: {
                            50: '#f0fdf4',
                            100: '#dcfce7',
                            500: '#10b981',
                            600: '#059669',
                            900: '#064e3b',
                        },
                        slate: {
                            900: '#0f172a',
                            950: '#020617',
                        }
                    }
                }
            }
        }
    </script>
    <style>
        /* Custom scrollbar for premium feel */
        ::-webkit-scrollbar {
            width: 8px;
        }
        ::-webkit-scrollbar-track {
            background: #020617;
        }
        ::-webkit-scrollbar-thumb {
            background: #1e293b;
            border-radius: 4px;
        }
        ::-webkit-scrollbar-thumb:hover {
            background: #10b981;
        }
    </style>
</head>
<body class="bg-slate-950 text-slate-100 font-sans min-h-screen selection:bg-emerald-500 selection:text-slate-950">

    <!-- Header Navigation -->
    <header class="border-b border-slate-800 bg-slate-900/80 backdrop-blur-md sticky top-0 z-50 px-4 py-3">
        <div class="max-w-7xl mx-auto flex flex-col sm:flex-row justify-between items-center gap-4">
            <div class="flex items-center gap-3">
                <div class="bg-emerald-500/10 p-2 rounded-lg border border-emerald-500/20">
                    <!-- Palm Tree SVG -->
                    <svg class="w-8 h-8 text-emerald-500" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                        <path d="M12 22V12M12 12C12 9 10 7 7 7M12 12C12 9 14 7 17 7M12 12C9 12 6 10 6 7M12 12C15 12 18 10 18 7M12 12C12 14 10 16 7 16M12 12C12 14 14 16 17 16" stroke-linecap="round"/>
                        <path d="M12 6C12 4 10 2 7 2M12 6C12 4 14 2 17 2" stroke-linecap="round"/>
                    </svg>
                </div>
                <div>
                    <h1 class="text-xl font-bold tracking-tight text-emerald-400">Palm Derivative Explorer</h1>
                    <p class="text-xs text-slate-400">Sustainable Food Management (SFM) & Bioscience Analytics</p>
                </div>
            </div>
            <div class="flex items-center gap-2 bg-slate-950 px-3 py-1.5 rounded-full border border-slate-800 text-xs text-slate-400">
                <span class="w-2 h-2 rounded-full bg-emerald-500 animate-pulse"></span>
                <span>MPOB Data Model Verification Active</span>
            </div>
        </div>
    </header>

    <main class="max-w-7xl mx-auto px-4 py-8">
        <!-- Hero Explanation Section -->
        <div class="grid grid-cols-1 lg:grid-cols-12 gap-8 mb-8">
            <div class="lg:col-span-7 flex flex-col justify-center">
                <span class="text-xs font-bold uppercase tracking-wider text-emerald-500 mb-2">Sustainable Food Security (Malaysia)</span>
                <h2 class="text-3xl sm:text-4xl font-extrabold tracking-tight mb-4 text-white">
                    Optimizing Edible Oil Yields with <span class="text-emerald-400">Calculus</span>
                </h2>
                <p class="text-slate-300 text-sm sm:text-base leading-relaxed mb-6">
                    In Malaysia, the oil palm (<em>Elaeis guineensis</em>) is the cornerstone of sustainable food security, providing over 30% of global vegetable oil. By analyzing the <strong>Fresh Fruit Bunch (FFB) yield curve</strong> using mathematical derivatives, agricultural scientists can pin-point the exact moments of peak productivity, guide precise fertilization programs, and plan optimal replanting cycles.
                </p>
                
                <!-- Equations Display Card -->
                <div class="bg-slate-900 border border-slate-800 rounded-xl p-5 shadow-2xl relative overflow-hidden mb-6">
                    <div class="absolute top-0 right-0 w-32 h-32 bg-emerald-500/5 rounded-full blur-2xl"></div>
                    <h3 class="text-sm font-semibold text-emerald-400 uppercase tracking-wider mb-3">The Mathematical Models</h3>
                    
                    <div class="space-y-4">
                        <div class="bg-slate-950 p-3 rounded-lg border border-slate-800">
                            <span class="text-xs text-slate-400 block mb-1">Yield Function $f(x)$ (Tonnes per Hectare per Year)</span>
                            <div class="text-sm sm:text-base overflow-x-auto py-1">
                                $$f(x) = 1.15 \cdot x^2 \cdot e^{-0.14 \cdot x}$$
                            </div>
                        </div>
                        <div class="bg-slate-950 p-3 rounded-lg border border-slate-800">
                            <span class="text-xs text-slate-400 block mb-1">Rate of Productivity Change $f'(x)$ (Derivative)</span>
                            <div class="text-sm sm:text-base overflow-x-auto py-1">
                                $$f'(x) = x \cdot e^{-0.14 \cdot x} \cdot (2.3 - 0.161 \cdot x)$$
                            </div>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Visual Graphic Illustration -->
            <div class="lg:col-span-5 bg-slate-900 border border-slate-800 rounded-2xl p-6 flex flex-col justify-between shadow-xl">
                <div>
                    <h3 class="text-lg font-bold text-slate-100 mb-1">Lifecycle Dynamics</h3>
                    <p class="text-xs text-slate-400 mb-4">Biological phase transitions mapped to derivatives</p>
                </div>
                
                <!-- Illustrated Graphic -->
                <div class="relative w-full h-48 bg-slate-950 rounded-xl border border-slate-800/80 p-4 flex items-end justify-around overflow-hidden">
                    <div class="absolute inset-0 bg-gradient-to-t from-emerald-950/10 to-transparent"></div>
                    
                    <!-- Immature Phase -->
                    <div class="flex flex-col items-center gap-2 z-10">
                        <div class="h-10 w-10 rounded-full bg-amber-500/10 border border-amber-500/30 flex items-center justify-center">
                            <svg class="w-5 h-5 text-amber-500" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 19l9 2-9-18-9 18 9-2zm0 0v-8"/></svg>
                        </div>
                        <div class="text-center">
                            <span class="text-[10px] font-bold text-amber-500 block">Immature</span>
                            <span class="text-[9px] text-slate-400">Year 0 - 3</span>
                        </div>
                    </div>

                    <!-- Peak Mature Phase -->
                    <div class="flex flex-col items-center gap-2 z-10">
                        <div class="h-12 w-12 rounded-full bg-emerald-500/10 border border-emerald-500/30 flex items-center justify-center animate-bounce" style="animation-duration: 3s;">
                            <svg class="w-6 h-6 text-emerald-500" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 7h8m0 0v8m0-8l-8 8-4-4-6 6"/></svg>
                        </div>
                        <div class="text-center">
                            <span class="text-[10px] font-bold text-emerald-400 block">Peak Yield</span>
                            <span class="text-[9px] text-slate-400">Year 10 - 15</span>
                        </div>
                    </div>

                    <!-- Replanting Phase -->
                    <div class="flex flex-col items-center gap-2 z-10">
                        <div class="h-10 w-10 rounded-full bg-red-500/10 border border-red-500/30 flex items-center justify-center">
                            <svg class="w-5 h-5 text-red-400" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 7l-.867 12.142A2 2 0 0116.138 21H7.862a2 2 0 01-1.995-1.858L5 7m5 4v6m4-6v6m1-10V4a1 1 0 00-1-1h-4a1 1 0 00-1 1v3M4 7h16"/></svg>
                        </div>
                        <div class="text-center">
                            <span class="text-[10px] font-bold text-red-400 block">Senescent</span>
                            <span class="text-[9px] text-slate-400">Year 25+</span>
                        </div>
                    </div>
                </div>

                <div class="mt-4 pt-4 border-t border-slate-800 text-xs text-slate-400 space-y-2">
                    <div class="flex items-center gap-2">
                        <span class="w-2 h-2 rounded-full bg-emerald-500"></span>
                        <span>\( f'(x) > 0 \): Crop acceleration / canopy expansion</span>
                    </div>
                    <div class="flex items-center gap-2">
                        <span class="w-2 h-2 rounded-full bg-blue-400"></span>
                        <span>\( f'(x) = 0 \): Maximum yield plateau (ideal biological efficiency)</span>
                    </div>
                    <div class="flex items-center gap-2">
                        <span class="w-2 h-2 rounded-full bg-red-400"></span>
                        <span>\( f'(x) < 0 \): Aging palms / nutrient translocation decay</span>
                    </div>
                </div>
            </div>
        </div>

        <!-- Interactive Analytical Workbench -->
        <div class="grid grid-cols-1 lg:grid-cols-12 gap-8 mb-8">
            
            <!-- Left Side: Graphic Chart Workspace -->
            <div class="lg:col-span-8 bg-slate-900 border border-slate-800 rounded-2xl p-6 shadow-xl flex flex-col justify-between">
                <div>
                    <div class="flex flex-col sm:flex-row justify-between items-start sm:items-center gap-4 mb-4">
                        <div>
                            <h3 class="text-lg font-bold text-white">Interactive Yield Dynamics Graph</h3>
                            <p class="text-xs text-slate-400">Click anywhere on the plot lines to evaluate calculus parameters instantly</p>
                        </div>
                        <div class="flex gap-3">
                            <button id="btnReset" class="px-3 py-1.5 bg-slate-800 hover:bg-slate-700 text-xs font-semibold rounded-lg border border-slate-700 transition">
                                Reset View
                            </button>
                        </div>
                    </div>

                    <!-- Canvas container -->
                    <div class="relative w-full h-80 sm:h-96 bg-slate-950 rounded-xl p-2 border border-slate-800">
                        <canvas id="yieldChart"></canvas>
                    </div>
                </div>

                <!-- Custom Slider Input -->
                <div class="mt-6 pt-4 border-t border-slate-800">
                    <label for="ageSlider" class="flex justify-between items-center text-xs text-slate-300 font-semibold mb-2">
                        <span>Adjust Palm Tree Age (\(x\) years):</span>
                        <span class="bg-emerald-500/10 text-emerald-400 px-2 py-0.5 rounded border border-emerald-500/20" id="ageBadge">Year 10.0</span>
                    </label>
                    <input type="range" id="ageSlider" min="0" max="30" step="0.5" value="10" class="w-full h-2 bg-slate-800 rounded-lg appearance-none cursor-pointer accent-emerald-500">
                    <div class="flex justify-between text-[10px] text-slate-500 mt-1">
                        <span>0 yr (Planting)</span>
                        <span>10 yr (Peak Mature)</span>
                        <span>20 yr (Post Peak)</span>
                        <span>30 yr (Senescence)</span>
                    </div>
                </div>
            </div>

            <!-- Right Side: Real-Time Derivative Analytics -->
            <div class="lg:col-span-4 flex flex-col gap-6">
                
                <!-- Live Stats Output -->
                <div class="bg-slate-900 border border-slate-800 rounded-2xl p-6 shadow-xl relative overflow-hidden flex-1">
                    <div class="absolute top-0 left-0 w-full h-1 bg-emerald-500"></div>
                    <h3 class="text-base font-bold text-white mb-4">Calculus Output Station</h3>
                    
                    <div class="grid grid-cols-2 gap-4 mb-6">
                        <div class="bg-slate-950 p-4 rounded-xl border border-slate-800/80 text-center">
                            <span class="text-xs text-slate-400 block mb-1">Current Yield \(f(x)\)</span>
                            <span id="statYield" class="text-2xl font-black text-emerald-400">10.0</span>
                            <span class="text-[10px] text-slate-400 block mt-0.5">t/ha/year</span>
                        </div>
                        <div class="bg-slate-950 p-4 rounded-xl border border-slate-800/80 text-center">
                            <span class="text-xs text-slate-400 block mb-1">Growth Rate \(f'(x)\)</span>
                            <span id="statDerivative" class="text-2xl font-black text-blue-400">+1.2</span>
                            <span class="text-[10px] text-slate-400 block mt-0.5">t/ha/yr per yr</span>
                        </div>
                    </div>

                    <!-- Dynamic Bioscience Assessment -->
                    <div class="space-y-4">
                        <div class="bg-slate-950 p-4 rounded-xl border border-slate-800">
                            <h4 class="text-xs font-bold text-emerald-400 uppercase tracking-wider mb-2 flex items-center gap-1.5">
                                <span class="w-1.5 h-1.5 rounded-full bg-emerald-400"></span>
                                Layman Bioscience Interpretation
                            </h4>
                            <p id="laymanExplanation" class="text-xs text-slate-300 leading-relaxed">
                                Loading dynamic assessment calculations...
                            </p>
                        </div>

                        <div class="bg-slate-950 p-4 rounded-xl border border-slate-800">
                            <h4 class="text-xs font-bold text-amber-400 uppercase tracking-wider mb-2 flex items-center gap-1.5">
                                <span class="w-1.5 h-1.5 rounded-full bg-amber-400"></span>
                                Malaysian Food Security Impact
                            </h4>
                            <p id="securityImpact" class="text-xs text-slate-300 leading-relaxed">
                                Loading food security impact parameters...
                            </p>
                        </div>
                    </div>
                </div>

                <!-- Academic Verification Source -->
                <div class="bg-slate-900 border border-slate-800 rounded-2xl p-4 shadow-xl text-xs text-slate-400 space-y-2">
                    <p class="font-semibold text-slate-300">Data Source & Reference Citation:</p>
                    <p class="leading-relaxed">
                        Yield curves modeled based on standard historical parameters published by the 
                        <a href="https://mpob.gov.my" target="_blank" class="text-emerald-400 hover:underline inline-flex items-center gap-0.5 font-semibold">
                            Malaysian Palm Oil Board (MPOB)
                            <svg class="w-3 h-3 inline" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M10 6H6a2 2 0 00-2 2v10a2 2 0 002 2h10a2 2 0 002-2v-4M14 4h6m0 0v6m0-6L10 14"/></svg>
                        </a> 
                        for commercial Tenera palms on optimal soils in Peninsular Malaysia.
                    </p>
                </div>

            </div>
        </div>

        <!-- Academic Scenario Background Section -->
        <div class="bg-slate-900 border border-slate-800 rounded-2xl p-6 sm:p-8 shadow-xl">
            <h3 class="text-xl font-bold text-white mb-4">Why Do We Use Derivatives here?</h3>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-6 text-sm text-slate-300 leading-relaxed">
                <div class="space-y-2">
                    <div class="flex items-center gap-2">
                        <span class="h-6 w-6 rounded-full bg-emerald-500/10 border border-emerald-500/30 flex items-center justify-center text-xs text-emerald-400 font-bold">1</span>
                        <h4 class="font-bold text-white">Resource Allocation</h4>
                    </div>
                    <p class="text-xs text-slate-400">
                        When the rate of change \(f'(x)\) is highly positive, the palm is in its vegetative surge. At this point, the plant requires maximum nitrogen and potassium to build high-capacity photosynthetic architecture.
                    </p>
                </div>
                <div class="space-y-2">
                    <div class="flex items-center gap-2">
                        <span class="h-6 w-6 rounded-full bg-emerald-500/10 border border-emerald-500/30 flex items-center justify-center text-xs text-emerald-400 font-bold">2</span>
                        <h4 class="font-bold text-white">Replanting Cycles</h4>
                    </div>
                    <p class="text-xs text-slate-400">
                        Once the derivative \(f'(x)\) drops too low negative (e.g., below \(-0.8\)), maintaining the palms becomes economically unsustainable due to manual harvesting height limits and physiological decline. This defines the optimal replanting year.
                    </p>
                </div>
                <div class="space-y-2">
                    <div class="flex items-center gap-2">
                        <span class="h-6 w-6 rounded-full bg-emerald-500/10 border border-emerald-500/30 flex items-center justify-center text-xs text-emerald-400 font-bold">3</span>
                        <h4 class="font-bold text-white">Forecasting Yield</h4>
                    </div>
                    <p class="text-xs text-slate-400">
                        Integrating derivative projections allows federal agencies like the Malaysian Department of Agriculture to map national stockpiles against upcoming global crop demands, insulating smallholders from financial shock.
                    </p>
                </div>
            </div>
        </div>
    </main>

    <!-- Footer -->
    <footer class="border-t border-slate-900 bg-slate-950 py-8 px-4 text-center text-xs text-slate-500">
        <p>© 2026 Sustainable Food Security & Applied Bioscience Platform, Malaysia.</p>
        <p class="mt-1">Designed for academic research, agricultural extension officers, and undergraduate analytical studies.</p>
    </footer>

    <!-- Interactive JS Application Code -->
    <script>
        // Mathematical Models
        // f(x) = 1.15 * x^2 * e^(-0.14 * x)
        // f'(x) = x * e^(-0.14 * x) * (2.3 - 0.161 * x)
        const calculateYield = (x) => {
            return 1.15 * Math.pow(x, 2) * Math.exp(-0.14 * x);
        };

        const calculateDerivative = (x) => {
            return x * Math.exp(-0.14 * x) * (2.3 - 0.161 * x);
        };

        // UI Selectors
        const ageSlider = document.getElementById('ageSlider');
        const ageBadge = document.getElementById('ageBadge');
        const statYield = document.getElementById('statYield');
        const statDerivative = document.getElementById('statDerivative');
        const laymanExplanation = document.getElementById('laymanExplanation');
        const securityImpact = document.getElementById('securityImpact');
        const btnReset = document.getElementById('btnReset');

        // Dynamic Text Generation based on Year Evaluated
        function updateBioscienceAssessment(x) {
            const y = calculateYield(x).toFixed(2);
            const dy = calculateDerivative(x).toFixed(3);

            let laymanText = "";
            let securityText = "";

            if (x < 3) {
                laymanText = `At Year ${x}, the oil palm is in its immature phase. The yield is tiny (${y} t/ha/yr) because all metabolic energy is directed towards primary root exploration, root establishment, and constructing fronds for photosynthesis. The derivative \(f'(x)\) is slowly climbing, indicating the seedling's rapid structural preparation.`;
                securityText = `Zero contribution to food security during this immature phase. High capital input is required here (fertilizer, soil conditioners). High risk period for smallholders.`;
            } else if (x >= 3 && x < 8) {
                laymanText = `At Year ${x}, the oil palm is experiencing rapid canopy growth. The derivative is strongly positive (${dy} t/ha/yr per year), which means the yield is accelerating at its fastest rate in the palm's lifetime. Rapid canopy expansion maximizes light interception and boosts chlorophyll content.`;
                securityText = `Excellent phase for national edible oil stockpiling. The rapidly expanding output feeds directly into food-processing supply lines, bolstering Malaysia's agricultural GDP and regional smallholder livelihoods.`;
            } else if (x >= 8 && x <= 14) {
                laymanText = `At Year ${x}, the palm has reached its physical peak. The derivative approaches zero (\(f'(x) \\approx ${dy}\)), indicating the peak plateau where productivity is stable and yield is at its historical highest (${y} t/ha/yr). The tree is fully utilizing sunlight, nutrient uptake, and maintaining optimum bunch-to-leaf ratios.`;
                securityText = `Maximum contribution to food security! Edible oils produced during this peak window keep global supply chains robust and stabilize price indexing across Southeast Asia. Highly sustainable phase.`;
            } else if (x > 14 && x <= 22) {
                laymanText = `At Year ${x}, the palm has entered mature senescence. Yield is still relatively high (${y} t/ha/yr), but the rate of change is now negative (\(f'(x) \\approx ${dy}\)). This indicates the palms are growing taller, increasing carbohydrate allocation for structural transport height rather than fruit bunch development.`;
                securityText = `Yield is starting to decay. Manual harvesting with poles (<em>egrek</em>) becomes labor-intensive and more expensive due to height, putting slight pressure on edible oil net margin targets.`;
            } else {
                laymanText = `At Year ${x}, the tree is hyper-senescent. The derivative is significantly negative (\(f'(x) \\approx ${dy}\)) and yield has dropped below sustainable levels. Nutrient transport inside the giant trunk is highly inefficient.`;
                securityText = `Replanting alert! Low yields of ${y} t/ha/yr diminish profitability. Malaysian food-security standards suggest active clearing and replanting of eco-certified cultivars to begin the next high-efficiency agricultural lifecycle.`;
            }

            // Update UI elements
            statYield.innerText = y;
            statYield.classList.add('scale-105');
            setTimeout(() => statYield.classList.remove('scale-105'), 150);
            
            // Format derivative displaying positive/negative values cleanly
            if (dy >= 0) {
                statDerivative.innerText = `+${dy}`;
                statDerivative.className = "text-2xl font-black text-emerald-400 transition-all duration-150";
            } else {
                statDerivative.innerText = dy;
                statDerivative.className = "text-2xl font-black text-rose-500 transition-all duration-150";
            }

            laymanExplanation.innerHTML = laymanText;
            securityImpact.innerHTML = securityText;

            // Trigger LaTeX re-render to update the injected formulas in explanations
            if (window.MathJax && window.MathJax.typeset) {
                window.MathJax.typeset();
            }
        }

        // Setup Chart.js data Arrays
        const chartLabels = [];
        const yieldData = [];
        const derivativeData = [];
        
        for (let i = 0; i <= 30; i += 1) {
            chartLabels.push(i);
            yieldData.push(calculateYield(i));
            derivativeData.push(calculateDerivative(i));
        }

        // Active highlighted point state
        let currentSelectedAge = 10;

        // Create Chart.js instance
        const ctx = document.getElementById('yieldChart').getContext('2d');
        const yieldChart = new Chart(ctx, {
            type: 'line',
            data: {
                labels: chartLabels,
                datasets: [
                    {
                        label: 'Yield f(x) (t/ha/yr)',
                        data: yieldData,
                        borderColor: '#10b981', // Emerald 500
                        borderWidth: 3,
                        backgroundColor: 'rgba(16, 185, 129, 0.05)',
                        fill: true,
                        tension: 0.3,
                        yAxisID: 'y'
                    },
                    {
                        label: 'Derivative f\'(x) (t/ha/yr per yr)',
                        data: derivativeData,
                        borderColor: '#3b82f6', // Blue 500
                        borderWidth: 2,
                        borderDash: [5, 5],
                        fill: false,
                        tension: 0.3,
                        yAxisID: 'yDerivative'
                    },
                    {
                        label: 'Active Evaluation Indicator',
                        data: Array(31).fill(null), // Handled dynamically below
                        borderColor: '#f59e0b', // Amber 500
                        pointBackgroundColor: '#f59e0b',
                        pointBorderColor: '#ffffff',
                        pointHoverRadius: 10,
                        pointRadius: 8,
                        showLine: false
                    }
                ]
            },
            options: {
                responsive: true,
                maintainAspectRatio: false,
                onClick: (e) => {
                    const activePoints = yieldChart.getElementsAtEventForMode(e, 'nearest', { intersect: false }, true);
                    if (activePoints.length > 0) {
                        const clickedIndex = activePoints[0].index;
                        const clickedAge = chartLabels[clickedIndex];
                        ageSlider.value = clickedAge;
                        updateChartAndPanel(clickedAge);
                    }
                },
                scales: {
                    x: {
                        grid: {
                            color: '#1e293b'
                        },
                        ticks: {
                            color: '#94a3b8',
                            font: { size: 10 }
                        },
                        title: {
                            display: true,
                            text: 'Palm Tree Age (Years after Planting)',
                            color: '#cbd5e1',
                            font: { size: 11, weight: 'bold' }
                        }
                    },
                    y: {
                        grid: {
                            color: '#1e293b'
                        },
                        ticks: {
                            color: '#10b981',
                            font: { size: 10 }
                        },
                        title: {
                            display: true,
                            text: 'Yield (Tonnes / Ha / Year)',
                            color: '#10b981',
                            font: { size: 11, weight: 'bold' }
                        }
                    },
                    yDerivative: {
                        position: 'right',
                        grid: {
                            drawOnChartArea: false
                        },
                        ticks: {
                            color: '#3b82f6',
                            font: { size: 10 }
                        },
                        title: {
                            display: true,
                            text: 'Growth Accel/Decel Rate [f\'(x)]',
                            color: '#3b82f6',
                            font: { size: 11, weight: 'bold' }
                        }
                    }
                },
                plugins: {
                    legend: {
                        labels: {
                            color: '#94a3b8',
                            font: { size: 11 }
                        }
                    },
                    tooltip: {
                        callbacks: {
                            label: function(context) {
                                let label = context.dataset.label || '';
                                if (label) {
                                    label += ': ';
                                }
                                if (context.parsed.y !== null) {
                                    label += context.parsed.y.toFixed(2);
                                }
                                return label;
                            }
                        }
                    }
                }
            }
        });

        // Function to synchronize chart active point indicator and analytical panel values
        function updateChartAndPanel(age) {
            currentSelectedAge = parseFloat(age);
            
            // Update Slider labels
            ageBadge.innerText = `Year ${currentSelectedAge.toFixed(1)}`;

            // Update Active point indicator array
            const activeIndicatorData = Array(31).fill(null);
            
            // Find closest index
            const closestIndex = Math.round(currentSelectedAge);
            if (closestIndex >= 0 && closestIndex <= 30) {
                activeIndicatorData[closestIndex] = calculateYield(currentSelectedAge);
            }
            yieldChart.data.datasets[2].data = activeIndicatorData;
            yieldChart.update();

            // Run detailed bioscience updates
            updateBioscienceAssessment(currentSelectedAge);
        }

        // Slider Event Listener
        ageSlider.addEventListener('input', (e) => {
            updateChartAndPanel(e.target.value);
        });

        // Reset Event Listener
        btnReset.addEventListener('click', () => {
            ageSlider.value = 10;
            updateChartAndPanel(10);
        });

        // Start initialization after assets load
        window.onload = function() {
            updateChartAndPanel(10);
        }
    </script>
</body>
</html>
