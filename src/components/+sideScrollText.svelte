<script>
	import { gsap } from 'gsap';
	import { ScrollTrigger } from 'gsap/dist/ScrollTrigger';
	import { onMount } from 'svelte';
	onMount(() => {
		gsap.registerPlugin(ScrollTrigger);
		gsap.to('.sideScrollServices', {
			scrollTrigger: {
				trigger: '.sideScrollingTextWrapper',
				end: 'bottom start',
				scrub: 1
			},
			x: 1000,
			ease: 'none'
		});
	});
</script>

<section class="sideScrollingTextWrapper">
	<div class="sideScrollingText" id="sideScrollText">
		<h3 class="sideScrollServices">
			WEB TASARIM - GRAFİK TASARIM - SOSYAL MEDYA GÖNDERİ YÖNETİMİ - ARAMA MOTORU OPTİMİZASYONU -
			WEB TASARIM - GRAFİK TASARIM - SOSYAL MEDYA GÖNDERİ YÖNETİMİ - ARAMA MOTORU OPTİMİZASYONU -
			WEB TASARIM - GRAFİK TASARIM - SOSYAL MEDYA GÖNDERİ YÖNETİMİ - ARAMA MOTORU OPTİMİZASYONU -
			WEB TASARIM - GRAFİK TASARIM - SOSYAL MEDYA GÖNDERİ YÖNETİMİ - ARAMA MOTORU OPTİMİZASYONU -
			WEB TASARIM - GRAFİK TASARIM - SOSYAL MEDYA GÖNDERİ YÖNETİMİ - ARAMA MOTORU OPTİMİZASYONU
		</h3>
	</div>
</section>
