<script lang="ts">
</script>

<section class="relative h-screen min-h-[800px] w-full overflow-hidden bg-[#8C8C84]">
    <!-- Background Image -->
    <div class="absolute inset-0 w-full h-full">
        <img 
            src="https://images.unsplash.com/photo-1518531933037-91b2f5f229cc?q=80&w=2000&auto=format&fit=crop" 
            alt="Nature background" 
            class="w-full h-full object-cover opacity-90"
        />
        <div class="absolute inset-0 bg-black/10"></div>
    </div>

    <!-- Content -->
    <div class="relative z-10 h-full container mx-auto px-6 md:px-12 flex items-center">
        <div class="w-full grid grid-cols-1 lg:grid-cols-2 gap-12 items-center">
            <!-- Left Text -->
            <div class="text-white max-w-xl">
                <span class="inline-block text-[10px] font-bold tracking-widest uppercase mb-6 opacity-80">
                    ● Evidence-Based Care
                </span>
                
                <h2 class="text-4xl md:text-[56px] leading-[1.1] font-medium tracking-tight mb-12">
                    Continuous screening catches what others miss.
                </h2>
                
                <div class="flex items-center gap-6 bg-white/10 backdrop-blur-md p-6 rounded-lg max-w-md border border-white/10">
                    <div class="flex flex-col">
                        <span class="text-[10px] uppercase tracking-widest opacity-70 mb-1">Mental Health Risks</span>
                        <span class="text-sm font-medium">detected early through</span>
                    </div>
                    <div class="text-4xl font-light tracking-tighter">
                        Regular<br/>Screening
                    </div>
                </div>
                
                <p class="mt-8 text-[13px] opacity-80 max-w-md leading-relaxed">
                    Our evidence-backed protocols and continuous monitoring ensure no warning signs are overlooked during your postpartum journey.
                </p>
            </div>

            <!-- Right Care Journey Visualization -->
            <div class="relative h-[600px] flex items-center justify-center">
                <!-- Care Journey Steps -->
                <div class="relative w-full max-w-md">
                    <!-- Step 1 -->
                    <div class="mb-8 flex items-start gap-4 bg-white/10 backdrop-blur-md p-6 rounded-lg border border-white/20">
                        <div class="w-12 h-12 rounded-full bg-primary-400 flex items-center justify-center text-white font-bold flex-shrink-0">1</div>
                        <div>
                            <h4 class="text-white font-semibold mb-1">Initial Assessment</h4>
                            <p class="text-white/70 text-sm">Comprehensive health screening and care plan development</p>
                        </div>
                    </div>
                    
                    <!-- Step 2 -->
                    <div class="mb-8 flex items-start gap-4 bg-white/10 backdrop-blur-md p-6 rounded-lg border border-white/20">
                        <div class="w-12 h-12 rounded-full bg-primary-400 flex items-center justify-center text-white font-bold flex-shrink-0">2</div>
                        <div>
                            <h4 class="text-white font-semibold mb-1">Continuous Monitoring</h4>
                            <p class="text-white/70 text-sm">Regular check-ins and mental health screenings</p>
                        </div>
                    </div>
                    
                    <!-- Step 3 -->
                    <div class="flex items-start gap-4 bg-white/10 backdrop-blur-md p-6 rounded-lg border border-white/20">
                        <div class="w-12 h-12 rounded-full bg-primary-400 flex items-center justify-center text-white font-bold flex-shrink-0">3</div>
                        <div>
                            <h4 class="text-white font-semibold mb-1">Coordinated Care</h4>
                            <p class="text-white/70 text-sm">Multidisciplinary team collaboration for optimal outcomes</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</section>
