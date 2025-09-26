<script lang="ts">
	// Components
	import CallToAction from "$lib/components/layout/CallToAction.svelte";

	// Icons
	import Story from "./Story.svelte";
	import SecondaryHero from "$lib/components/layout/hero-sections/SecondaryHero.svelte";
	import Culture from "$lib/components/layout/Culture.svelte";

	// Constants
	const values = [
		{
			title: "Science-backed wellness",
			description: "Every ingredient is researched and proven to support better sleep, blending effectiveness with indulgence."
		},
		{
			title: "Parent empathy",
			description: "We understand the exhaustion—because we've been there too. Every product is designed with tired parents in mind."
		},
		{
			title: "Premium quality",
			description: "No compromises on taste or effectiveness. We create ice cream that works as well as it tastes."
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
<Culture {values} />

<!-- CTA Section -->
<CallToAction
	title="Your best sleep starts tonight"
	subtitle="Finally, a bedtime treat that works"
	description="Stop counting sheep and start savoring sleep. Our scientifically-crafted ice cream transforms restless nights into peaceful rest. Join over a million parents who've discovered the sweet solution to better sleep."
	imageSrc="/generated/image-a-parent-relaxing-peacefully-in-a-cozy-b.webp"
/>
