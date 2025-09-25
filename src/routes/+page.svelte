<script lang="ts">
	// Components
	import Summary from "$lib/components/layout/Summary.svelte";
	import Features from "$lib/components/layout/Features.svelte";
	import Testimonials from "$lib/components/layout/Testimonials.svelte";
	import CallToAction from "$lib/components/layout/CallToAction.svelte";
	import AboutTeaser from "$lib/components/layout/AboutTeaser.svelte";
	import LogoScroller from "$lib/components/layout/LogoScroller.svelte";
	import Hero from "$lib/components/layout/hero-sections/Hero.svelte";
</script>

<Hero
	title="Sleep-friendly ice cream"
	subtitle="Because parents deserve better nights."
	imageSrc="/generated/image-a-peaceful-parent-sleeping-deeply-in-a-c.webp"
	centered={false}
/>
<LogoScroller 
	label="Trusted by parents everywhere"
	logoUrls={[
		'https://cdn.brandfetch.io/target.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/jnj.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/pg.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/wholefoods.com/w/400/h/400/logo'
	]}
/>

<Summary
	title="Sleep better, one scoop at a time"
	text="The only ice cream designed to help you fall asleep—and stay asleep. We took everything parents love about ice cream and made it functional, blending proven sleep-inducing ingredients with rich, crave-worthy flavors.

No pills, no gimmicks—just better nights, by the spoonful."
/>

<Testimonials
	testimonials={[
		{
			name: "Isabella Martinez",
			position: "Mother of twins",
			company: "San Diego, CA",
			quote:
				"Finally sleeping through the night again! After 8 months of 3-hour sleep cycles with my twins, this ice cream helped me fall asleep 40% faster.\nSaved me from $200/month on sleep supplements and countless hours of tossing and turning.",
			image: "/generated/image-professional-headshot-of-a-confident-lat.webp"
		},
		{
			name: "Marcus Thompson",
			position: "Father of three",
			company: "Atlanta, GA",
			quote:
				"Game changer for our bedtime routine. My kids love the taste, and I love that it actually works - sleeping 2 extra hours per night now.\nNo more expensive melatonin gummies or late-night grocery runs for sleep aids.",
			image: "/generated/image-professional-headshot-of-a-tired-but-hop.webp"
		},
		{
			name: "Lily Chen",
			position: "New mom",
			company: "Seattle, WA",
			quote:
				"Cut my time to fall asleep from 45 minutes to just 15 minutes. As a first-time mom, those extra 30 minutes of sleep are precious.\nReplaced my $80/month sleep clinic visits with something that actually tastes amazing.",
			image: "/generated/image-professional-headshot-of-a-warm-asian-mo.webp"
		}
	]}
/>

<Features
	title="Why parents choose us"
	subtitle="Designed specifically for sleep-deprived parents who deserve both better sleep and incredible flavor."
	features={[
		{
			title: "Sleep-inducing ingredients",
			description: "Natural melatonin and chamomile work together to help you fall asleep faster and sleep deeper.",
			imageSrc: "/generated/image-a-close-up-arrangement-of-natural-herbs-.webp"
		},
		{
			title: "Peaceful nights guaranteed",
			description: "Wake up refreshed instead of exhausted with our carefully crafted blend designed for quality rest.",
			imageSrc: "/generated/image-a-parent-peacefully-sleeping-in-a-cozy-s.webp"
		},
		{
			title: "Better mornings ahead",
			description: "Start your day with energy and joy instead of dragging through another sleepless aftermath.",
			imageSrc: "/generated/image-a-happy-parent-enjoying-a-morning-coffee.webp"
		},
		{
			title: "Premium organic ingredients",
			description: "Every pint uses the finest organic milk and natural sweeteners because parents deserve the best.",
			imageSrc: "/generated/image-a-glass-of-organic-milk-on-a-wooden-tabl.webp"
		},
		{
			title: "Family-friendly routine",
			description: "Create a calming bedtime ritual that brings you closer to your children while caring for yourself.",
			imageSrc: "/generated/image-a-parent-and-child-bonding-over-a-bedtim.webp"
		},
		{
			title: "Science-backed formula",
			description: "Developed with sleep specialists to deliver real results without compromising on taste or safety.",
			imageSrc: "/generated/image-a-scientist-in-a-bright-laboratory-caref.webp"
		}
	]}
/>
<AboutTeaser generating />
<CallToAction generating />
