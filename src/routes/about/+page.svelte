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
			title: "Student first",
			description: "We solve real student problems—because we've lived them. Every feature starts with: 'Would this actually help me learn better under pressure?'"
		},
		{
			title: "Academic excellence",
			description: "We believe tools should match student potential, not hold it back. Good grades aren't magic—they're systems. We build those systems."
		},
		{
			title: "Innovation through youth",
			description: "StudyBuddy started with one frustrated 16-year-old who saw things differently. Youth isn't a limitation—it's our edge."
		}
	];
</script>

<SecondaryHero
	title="Transforming education with AI"
	subtitle="Founded by a 16-year-old genius to solve real student problems"
	imageSrc="/generated/image-a-professional-business-headshot-of-a-yo.webp"
/>

<!-- Story Section -->
<Story
	paragraphs={[
		"It started with a brilliant 16-year-old high school student named Osman who was drowning in dense lecture content. While his peers struggled with the same problem, Osman decided to build the solution.",
		"What began as solving his own learning challenges quickly evolved into something bigger. Osman realized that millions of college students at competitive universities faced the same information overload and ineffective study methods.",
		"Rather than accept the status quo of passive study materials, we're transforming them into active learning experiences. Our AI converts notes and recordings into interactive slides, then adapts based on where students struggle most.",
		"Founded by a genius who understands the problem firsthand, we're not just another ed-tech company. We're students building for students, creating the learning tools we wished existed when we needed them most."
	]}
/>

<!-- Our Culture Section -->
<Culture {values} />

<!-- StakeholderGrid Section -->
<StakeholderGrid
	stakeholderType="team"
	title="Meet our founder"
	subtitle="Building the future of active learning from a student's perspective"
	stakeholders={[
		{
			name: "Osman",
			position: "Founder & CEO, Age 16",
			bio: "A brilliant high school student who founded the company to solve his own learning challenges. At just 16, Osman is transforming how students engage with dense lecture content and creating the AI-powered study tools he wished existed.",
			image: "/generated/image-a-professional-business-headshot-of-a-yo.webp"
		}
	]}
/>

<!-- CTA Section -->
<CallToAction
	title="Join the students who study 10x faster"
	subtitle="Start for free today"
	description="We're already powering tens of thousands of sessions at top universities. Don't waste another night rewatching a 90-minute lecture you only half-remember."
	imageSrc="/generated/image-a-confident-college-student-with-a-subtl.webp"
/>
