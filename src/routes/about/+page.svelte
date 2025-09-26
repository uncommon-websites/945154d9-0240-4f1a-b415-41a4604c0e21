<script lang="ts">
	// Components
	import CallToAction from "$lib/components/layout/CallToAction.svelte";

	// Icons
	import StakeholderGrid from "$lib/components/layout/StakeholderGrid.svelte";
	import Story from "./Story.svelte";
	import SecondaryHero from "$lib/components/layout/hero-sections/SecondaryHero.svelte";
	import Culture from "$lib/components/layout/Culture.svelte";

	// Constants
	const values = [
		{
			title: "Innovation",
			description: "Constantly challenging the status quo to create better solutions."
		},
		{
			title: "Integrity",
			description: "Building trust through transparent actions and honest communication."
		},
		{
			title: "Impact",
			description: "Measuring our success by the positive change we create for our clients."
		}
	];
</script>

<SecondaryHero
	title="Good sleep tastes good"
	subtitle="Ice cream that helps parents rest"
	imageSrc="/generated/image-a-group-of-diverse-professionals-collabo.webp"
/>

<!-- Story Section -->
<Story
	paragraphs={[
		"Sleep-deprived? We've been there too. The idea for Company was born in the quiet chaos of a sleepless night—rocking a crying baby, exhausted, and desperate for rest. Like so many parents, we craved something to help us unwind, but everything felt either sterile, sugary, or ineffective. So we created what we couldn't find: a bedtime ritual that works—a rich, dreamy ice cream made to help you actually sleep.",
		"We collaborated with food scientists, sleep specialists, and nutritionists to design a formula that blends function and flavor. Each pint is infused with ingredients like L-theanine, magnesium, and tart cherry—natural compounds backed by research and trusted by experts. The result? A sleep-supporting dessert that doesn't taste like a supplement. More than a million pints later, tired parents have found a sweet spot between science and indulgence.",
		"At Company, we're on a mission to turn end-of-day exhaustion into a moment of calm. Starting with parents, we're reimagining what sleep routines can feel like: comforting, satisfying, and genuinely effective. Because when you sleep well, everything else feels lighter—from morning tantrums to the 3pm meeting. Better nights make better parents. And everyone deserves both."
	]}
/>

<!-- Our Culture Section -->
<Culture {values} generating />

<!-- StakeholderGrid Section -->
<StakeholderGrid
	generating
	stakeholderType="team"
	title="Our team."
	subtitle="Your partners in innovation."
	stakeholders={[
		{
			name: "Alex Morgan",
			position: "Founder & CEO",
			bio: "Started the company with a vision to transform the industry through innovative solutions.",
			image: "https://www.unc.mn/image-placeholder.svg"
		},
		{
			name: "Jamie Chen",
			position: "Chief Design Officer",
			bio: "Award-winning designer with a passion for creating intuitive and beautiful experiences.",
			image: "https://www.unc.mn/image-placeholder.svg"
		},
		{
			name: "Taylor Wright",
			position: "Head of Engineering",
			bio: "Technology enthusiast focused on building scalable systems that make a difference.",
			image: "https://www.unc.mn/image-placeholder.svg"
		}
	]}
/>

<StakeholderGrid
	generating
	stakeholderType="investor"
	title="Backed by the best."
	subtitle="Point Nine, TSIC and others"
	stakeholders={[
		{
			name: "Point Nine Capital",
			image: "https://cdn.brandfetch.io/pointnine.com/w/400/h/400/logo?c=1id_elLz2Bd5Ej-dWo7"
		},
		{
			name: "TSIC Ventures",
			image: "https://cdn.brandfetch.io/tiny.vc/w/400/h/400/logo?c=1a2b3c4d5e"
		},
		{
			name: "Sequoia Capital",
			image: "https://cdn.brandfetch.io/sequoiacap.com/w/400/h/400/logo"
		}
	]}
/>

<!-- CTA Section -->
<CallToAction
	generating
	title="Ready to collaborate?"
	subtitle="Let's create something amazing"
	description="Join the companies already leveraging our expertise to transform their digital presence and achieve their business goals."
/>
