<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CoLabs - Biotech Innovation Hub</title>
    
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    
    <!-- Google Fonts: Inter -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
    
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f8f8f8;
            color: #000000;
        }
        
        /* Smooth selection color */
        ::selection {
            background-color: #000000;
            color: #ffffff;
        }

        /* Utility class to hide scrollbars if needed on smaller screens */
        .no-scrollbar::-webkit-scrollbar {
            display: none;
        }
        .no-scrollbar {
            -ms-overflow-style: none;
            scrollbar-width: none;
        }
    </style>
</head>
<body class="min-h-screen p-4 md:p-6 lg:p-8 flex flex-col">

    <!-- HEADER -->
    <header class="flex flex-col md:flex-row justify-between items-start md:items-center mb-6 lg:mb-8 gap-4 relative z-10 w-full max-w-[1800px] mx-auto">
        
        <!-- Logo Area -->
        <div class="flex flex-col">
            <span class="text-[10px] md:text-xs font-medium tracking-wide text-gray-500 mb-0.5 ml-1 uppercase">Naarm/Melbourne</span>
            <div class="flex items-center gap-2">
                <!-- Custom 'C' Logo Icon -->
                <div class="w-8 h-8 md:w-10 md:h-10 bg-black rounded-full flex items-center justify-center relative">
                    <div class="w-3.5 h-3.5 md:w-4 md:h-4 bg-white rounded-full ml-2"></div>
                </div>
                <h1 class="text-3xl md:text-4xl font-bold tracking-tight">CoLabs</h1>
            </div>
        </div>

        <!-- Desktop Navigation Pill -->
        <nav class="hidden md:flex bg-[#EFE3CF] rounded-full px-6 py-3 items-center gap-6 shadow-sm">
            <!-- Dropdown Items -->
            <div class="flex items-center gap-1 cursor-pointer group">
                <span class="text-sm font-medium group-hover:opacity-70 transition-opacity">Services</span>
                <svg class="w-3.5 h-3.5 opacity-50 group-hover:opacity-100 transition-opacity" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><polyline points="6 9 12 15 18 9"></polyline></svg>
            </div>
            <div class="flex items-center gap-1 cursor-pointer group">
                <span class="text-sm font-medium group-hover:opacity-70 transition-opacity">Sites</span>
                <svg class="w-3.5 h-3.5 opacity-50 group-hover:opacity-100 transition-opacity" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><polyline points="6 9 12 15 18 9"></polyline></svg>
            </div>
            <div class="flex items-center gap-1 cursor-pointer group">
                <span class="text-sm font-medium group-hover:opacity-70 transition-opacity">About</span>
                <svg class="w-3.5 h-3.5 opacity-50 group-hover:opacity-100 transition-opacity" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><polyline points="6 9 12 15 18 9"></polyline></svg>
            </div>
            <div class="flex items-center gap-1 cursor-pointer group">
                <span class="text-sm font-medium group-hover:opacity-70 transition-opacity">Resources</span>
                <svg class="w-3.5 h-3.5 opacity-50 group-hover:opacity-100 transition-opacity" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><polyline points="6 9 12 15 18 9"></polyline></svg>
            </div>
            
            <!-- Standard Link -->
            <span class="text-sm font-medium cursor-pointer hover:opacity-70 transition-opacity ml-2">Contact</span>
            
            <!-- Social Icons -->
            <div class="flex items-center gap-4 ml-4 pl-4 border-l border-black/10">
                <svg class="w-4 h-4 cursor-pointer hover:opacity-70 transition-opacity" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><rect x="2" y="2" width="20" height="20" rx="5" ry="5"></rect><path d="M16 11.37A4 4 0 1 1 12.63 8 4 4 0 0 1 16 11.37z"></path><line x1="17.5" y1="6.5" x2="17.51" y2="6.5"></line></svg>
                <svg class="w-4 h-4 cursor-pointer hover:opacity-70 transition-opacity" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M18 2h-3a5 5 0 0 0-5 5v3H7v4h3v8h4v-8h3l1-4h-4V7a1 1 0 0 1 1-1h3z"></path></svg>
            </div>
        </nav>

        <!-- Search Icon -->
        <div class="w-12 h-12 bg-white rounded-full flex items-center justify-center shadow-sm cursor-pointer hover:bg-gray-50 transition-colors hidden md:flex shrink-0">
            <svg class="w-5 h-5" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><circle cx="11" cy="11" r="8"></circle><line x1="21" y1="21" x2="16.65" y2="16.65"></line></svg>
        </div>
    </header>


    <!-- MAIN GRID LAYOUT -->
    <main class="flex-grow grid grid-cols-1 lg:grid-cols-[1fr_360px] xl:grid-cols-[1fr_400px] gap-4 md:gap-6 max-w-[1800px] mx-auto w-full">
        
        <!-- ========================================== -->
        <!-- LEFT COLUMN: HERO SECTION                  -->
        <!-- ========================================== -->
        <div class="relative w-full h-[60vh] lg:h-auto min-h-[550px] rounded-[40px] overflow-hidden bg-white shadow-sm">
            
            <!-- Hero Background Image (Macro Anemone/Texture) -->
            <div 
                class="absolute inset-0 bg-cover bg-center"
                style="background-image: url('https://images.unsplash.com/photo-1618512496248-a07fe83aa8cb?auto=format&fit=crop&q=80&w=2400'); background-color: #EAB308;">
            </div>

            <!-- Hero Text Cutout Box (Bottom Left) -->
            <!-- 
                Using a solid background matching the page, and rounding the top-right corner.
                The inverted corner fills the gap to make it look like the image is seamlessly cut.
            -->
            <div class="absolute bottom-0 left-0 bg-[#f8f8f8] w-[90%] md:w-[75%] lg:w-[70%] max-w-[750px] pt-8 pr-8 md:pt-12 md:pr-12 rounded-tr-[40px]">
                
                <!-- CSS Inverted Corner Trick -->
                <div class="absolute bottom-full left-0 w-[40px] h-[40px] pointer-events-none" style="background-image: radial-gradient(circle at top right, transparent 40px, #f8f8f8 0);"></div>

                <div class="pr-4 md:pr-8 pb-4">
                    <h2 class="text-5xl md:text-6xl lg:text-[5rem] font-medium tracking-tight leading-[1.02] mb-10 text-[#000000]">
                        Making space for<br />
                        transformative<br />
                        innovation
                    </h2>
                    
                    <button class="w-14 h-14 md:w-16 md:h-16 rounded-full border border-gray-300 flex items-center justify-center hover:bg-white transition-colors group bg-transparent">
                        <svg class="w-6 h-6 group-hover:translate-y-1 transition-transform" stroke-width="1.5" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round"><line x1="12" y1="5" x2="12" y2="19"></line><polyline points="19 12 12 19 5 12"></polyline></svg>
                    </button>
                </div>
            </div>
        </div>

        <!-- ========================================== -->
        <!-- RIGHT COLUMN: SIDEBAR WIDGETS              -->
        <!-- ========================================== -->
        <div class="flex flex-col gap-4 md:gap-6 h-full">
            
            <!-- Widget 1: Stat Card (Perfect Circle) -->
            <div class="bg-[#e4cdad] w-full aspect-square rounded-[40px] lg:rounded-full flex flex-col items-center justify-center relative p-8 text-center shadow-sm shrink-0 mx-auto max-w-[400px]">
                <h3 class="text-[7rem] md:text-[8rem] font-bold leading-none tracking-tighter text-black mb-1">25</h3>
                <p class="text-[15px] font-medium leading-[1.2] max-w-[160px] text-black">
                    Impact<br />Scholarships<br />Awarded
                </p>
                
                <!-- Pagination Dots -->
                <div class="absolute bottom-10 flex gap-2">
                    <div class="w-2.5 h-2.5 rounded-full bg-black"></div>
                    <div class="w-2.5 h-2.5 rounded-full bg-black/20"></div>
                    <div class="w-2.5 h-2.5 rounded-full bg-black/20"></div>
                    <div class="w-2.5 h-2.5 rounded-full bg-black/20"></div>
                    <div class="w-2.5 h-2.5 rounded-full bg-black/20"></div>
                </div>
            </div>

            <!-- Widget 2: Call to Action (Blue Coral Background) -->
            <div class="relative rounded-[40px] overflow-hidden flex-1 min-h-[220px] shadow-sm group cursor-pointer max-w-[400px] mx-auto w-full">
                <!-- Background Image -->
                <div 
                    class="absolute inset-0 bg-cover bg-center transition-transform duration-700 group-hover:scale-105"
                    style="background-image: url('https://images.unsplash.com/photo-1546026423-cc46426ba649?auto=format&fit=crop&w=800&q=80'); background-color: #0EA5E9;">
                </div>
                
                <!-- Content -->
                <div class="relative z-10 p-6 md:p-8 h-full flex flex-col">
                    <h3 class="text-white text-2xl md:text-[28px] font-medium leading-[1.15] w-3/4 tracking-tight drop-shadow-md">
                        Want lab space?<br />Click here.
                    </h3>
                </div>

                <!-- Bottom Right Cutout for Button -->
                <div class="absolute bottom-0 right-0 w-[80px] h-[80px] bg-[#f8f8f8] rounded-tl-[36px] z-20">
                    <!-- Inverted Corners to blend into the main background -->
                    <div class="absolute bottom-full right-0 w-[24px] h-[24px] pointer-events-none" style="background-image: radial-gradient(circle at top left, transparent 24px, #f8f8f8 0);"></div>
                    <div class="absolute bottom-0 right-full w-[24px] h-[24px] pointer-events-none" style="background-image: radial-gradient(circle at top left, transparent 24px, #f8f8f8 0);"></div>
                    
                    <!-- Action Button -->
                    <button class="absolute bottom-2 right-2 w-[56px] h-[56px] bg-black rounded-full flex items-center justify-center hover:bg-gray-800 transition-colors">
                        <svg class="text-white w-6 h-6 -rotate-45 group-hover:rotate-0 transition-transform duration-300" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><line x1="5" y1="12" x2="19" y2="12"></line><polyline points="12 5 19 12 12 19"></polyline></svg>
                    </button>
                </div>
            </div>

            <!-- Widget 3: Newsletter (Solid Green) -->
            <div class="relative rounded-[40px] bg-[#3dd28d] p-6 md:p-8 flex-1 min-h-[240px] shadow-sm flex flex-col justify-between group cursor-pointer max-w-[400px] mx-auto w-full">
                <p class="text-black text-[19px] leading-[1.25] w-[85%] font-medium tracking-tight">
                    <span class="font-bold">Triskelion.</span> A monthly newsletter covering biotech news and articles from within the Co-
                </p>

                <!-- Pagination Dots / Dashes (Matching the reference exactly) -->
                <div class="flex gap-1.5 mt-auto mb-4 items-center">
                    <div class="h-2 w-5 rounded-full bg-black/30"></div>
                    <div class="h-2 w-2 rounded-full bg-black"></div>
                    <div class="h-2 w-5 rounded-full bg-black/10"></div>
                    <div class="h-2 w-5 rounded-full bg-black/10"></div>
                    <div class="h-2 w-5 rounded-full bg-black/10"></div>
                    <div class="h-2 w-5 rounded-full bg-black/10"></div>
                </div>

                <!-- Bottom Right Cutout for Button -->
                <div class="absolute bottom-0 right-0 w-[80px] h-[80px] bg-[#f8f8f8] rounded-tl-[36px] z-20">
                    <!-- Inverted Corners -->
                    <div class="absolute bottom-full right-0 w-[24px] h-[24px] pointer-events-none" style="background-image: radial-gradient(circle at top left, transparent 24px, #f8f8f8 0);"></div>
                    <div class="absolute bottom-0 right-full w-[24px] h-[24px] pointer-events-none" style="background-image: radial-gradient(circle at top left, transparent 24px, #f8f8f8 0);"></div>
                    
                    <!-- Action Button -->
                    <button class="absolute bottom-2 right-2 w-[56px] h-[56px] bg-black rounded-full flex items-center justify-center hover:bg-gray-800 transition-colors">
                        <svg class="text-white w-6 h-6 -rotate-45 group-hover:rotate-0 transition-transform duration-300" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><line x1="5" y1="12" x2="19" y2="12"></line><polyline points="12 5 19 12 12 19"></polyline></svg>
                    </button>
                </div>
            </div>

        </div>
    </main>
    
    <!-- Mobile Nav Overlay (Bottom Sticky) -->
    <div class="md:hidden fixed bottom-6 left-1/2 -translate-x-1/2 bg-black text-white px-6 py-3 rounded-full flex gap-6 z-50 shadow-xl items-center">
        <svg class="w-5 h-5" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><circle cx="11" cy="11" r="8"></circle><line x1="21" y1="21" x2="16.65" y2="16.65"></line></svg>
        <div class="w-px h-5 bg-white/30"></div>
        <span class="text-sm font-medium">Menu</span>
    </div>

</body>
</html>
