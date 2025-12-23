<script lang="ts">
    import ProductCard from './ProductCard.svelte';

    const products = [
        {
            badge: "Flagship",
            code: "PC-01",
            title: "Postpartum Care Program",
            image: "/generated/image-healthcare-provider-consulting-with-new--1766523679287-1.webp", 
            price: "$299"
        },
        {
            badge: "Essential",
            code: "MH-01",
            title: "Mental Health Support",
            image: "/generated/image-therapist-in-compassionate-conversation--1766523681865-2.webp", 
            price: "$199"
        },
        {
            badge: "Premium",
            code: "DE-01",
            title: "Digital Education Platform",
            image: "/generated/image-mother-using-laptop-for-video-consultati-1766523684397-3.webp",
            price: "$99"
        },
        {
            badge: "Partnership",
            code: "CP-01",
            title: "Clinical Partnerships",
            image: "/generated/image-medical-team-of-diverse-healthcare-provi-1766523686924-4.webp",
            price: "Custom"
        }
    ];
</script>

<section class="bg-[#1A3026] py-24">
    <div class="container mx-auto px-6 md:px-12">
        <div class="flex flex-col md:flex-row justify-between items-end mb-16 text-white">
            <div class="max-w-xl">
                <h2 class="text-4xl md:text-[44px] leading-tight font-medium tracking-tight mb-6">Postpartum care that addresses your whole health.</h2>
                <p class="text-[17px] text-white/80 font-light max-w-md leading-relaxed">Comprehensive programs combining medical expertise, mental health support, and continuous screening to ensure optimal recovery.</p>
            </div>
            <a href="/" class="hidden md:inline-flex items-center text-[13px] font-bold border-b border-white/30 pb-0.5 hover:border-white transition-colors mt-6 md:mt-0 tracking-wide uppercase">
                View All Programs <span class="ml-2">→</span>
            </a>
        </div>

        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-4">
            {#each products as product}
                <ProductCard {...product} isDark={true} />
            {/each}
        </div>

        <div class="mt-12 text-center md:hidden">
            <a href="/" class="inline-flex items-center text-[13px] font-bold border-b border-white/30 pb-0.5 hover:border-white transition-colors text-white tracking-wide uppercase">
                View All Programs <span class="ml-2">→</span>
            </a>
        </div>
    </div>
</section>
