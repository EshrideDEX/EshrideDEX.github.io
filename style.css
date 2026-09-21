:root {
	--background: #0b0b0d;
	--surface: #131316;
	--surface-hover: #19191d;
	--text: #f2f2f2;
	--muted: #9a9aa2;
	--border: #29292e;
	--accent: #ffffff;

	--content-width: 1180px;
	--section-spacing: 140px;
}


* {
	box-sizing: border-box;
	margin: 0;
	padding: 0;
}


html {
	scroll-behavior: smooth;
}


body {
	background: var(--background);
	color: var(--text);
	font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
	line-height: 1.6;
}


a {
	color: inherit;
	text-decoration: none;
}


.site-header {
	position: sticky;
	top: 0;
	z-index: 100;

	background: rgba(11, 11, 13, 0.85);
	backdrop-filter: blur(12px);

	border-bottom: 1px solid rgba(255, 255, 255, 0.06);
}


.navbar {
	max-width: var(--content-width);
	margin: 0 auto;

	display: flex;
	align-items: center;
	justify-content: space-between;

	padding: 22px 32px;
}


.logo {
	font-size: 1.25rem;
	font-weight: 700;
	letter-spacing: -0.03em;
}


.nav-links {
	display: flex;
	gap: 32px;
}


.nav-links a {
	color: var(--muted);
	font-size: 0.9rem;
	transition: color 0.2s ease;
}


.nav-links a:hover {
	color: var(--text);
}


.hero {
	max-width: var(--content-width);
	min-height: 720px;
	margin: 0 auto;

	display: flex;
	align-items: center;

	padding: 100px 32px;
}


.hero-content {
	max-width: 780px;
}


.eyebrow {
	margin-bottom: 18px;

	color: var(--muted);
	font-size: 0.75rem;
	font-weight: 700;
	letter-spacing: 0.14em;
}


.hero h1 {
	font-size: clamp(3.5rem, 8vw, 7rem);
	line-height: 0.95;
	letter-spacing: -0.065em;
	margin-bottom: 36px;
}


.hero-description {
	max-width: 620px;

	color: var(--muted);
	font-size: 1.15rem;
	line-height: 1.8;

	margin-bottom: 40px;
}


.button {
	display: inline-block;

	padding: 14px 22px;

	background: var(--accent);
	color: var(--background);

	border-radius: 6px;

	font-size: 0.9rem;
	font-weight: 700;

	transition:
		transform 0.2s ease,
		opacity 0.2s ease;
}


.button:hover {
	transform: translateY(-2px);
	opacity: 0.85;
}


.section {
	max-width: var(--content-width);
	margin: 0 auto;

	padding: var(--section-spacing) 32px;
}


.section-heading {
	margin-bottom: 60px;
}


.section-heading h2 {
	font-size: clamp(2.5rem, 5vw, 4rem);
	line-height: 1;
	letter-spacing: -0.05em;
}


.project-grid {
	display: grid;
	grid-template-columns: repeat(2, 1fr);
	gap: 24px;
}


.project-card {
	background: var(--surface);

	border: 1px solid var(--border);
	border-radius: 10px;

	overflow: hidden;

	transition:
		transform 0.25s ease,
		background 0.25s ease;
}


.project-card:hover {
	transform: translateY(-5px);
	background: var(--surface-hover);
}


.project-image {
	aspect-ratio: 16 / 9;

	display: flex;
	align-items: center;
	justify-content: center;

	background: #1a1a1f;

	font-size: 2rem;
	font-weight: 700;
	letter-spacing: -0.04em;
}


.project-image-animkit {
	background: #17171b;
}


.project-image-luminara {
	background: #1b1b20;
}


.project-image-unwoven {
	background: #151518;
}


.project-image-animation {
	background: #19191d;
}


.project-content {
	padding: 28px;
}


.project-type {
	margin-bottom: 10px;

	color: var(--muted);
	font-size: 0.7rem;
	font-weight: 700;
	letter-spacing: 0.12em;
}


.project-content h3 {
	margin-bottom: 12px;

	font-size: 1.7rem;
	letter-spacing: -0.035em;
}


.project-content p:not(.project-type) {
	color: var(--muted);
	margin-bottom: 24px;
}


.project-link {
	font-size: 0.9rem;
	font-weight: 700;
}


.project-link:hover {
	text-decoration: underline;
}


.about-section {
	display: grid;
	grid-template-columns: 1fr 1fr;
	gap: 80px;
	align-items: start;
}


.about-section .section-heading {
	margin-bottom: 0;
}


.about-content {
	max-width: 600px;
}


.about-content p {
	color: var(--muted);
	font-size: 1.1rem;
	line-height: 1.9;
	margin-bottom: 24px;
}


.contact-links {
	display: flex;
	flex-wrap: wrap;
	gap: 16px;
}


.contact-links a {
	padding: 12px 18px;

	border: 1px solid var(--border);
	border-radius: 6px;

	color: var(--muted);

	transition:
		color 0.2s ease,
		border-color 0.2s ease;
}


.contact-links a:hover {
	color: var(--text);
	border-color: #55555c;
}


.site-footer {
	max-width: var(--content-width);
	margin: 0 auto;

	padding: 40px 32px 60px;

	border-top: 1px solid var(--border);

	color: var(--muted);
	font-size: 0.8rem;
}


@media (max-width: 700px) {

	.navbar {
		padding: 18px 20px;
	}


	.nav-links {
		gap: 16px;
	}


	.hero {
		min-height: 620px;
		padding: 80px 20px;
	}


	.hero h1 {
		font-size: clamp(3rem, 15vw, 5rem);
	}


	.section {
		padding: 90px 20px;
	}


	.project-grid {
		grid-template-columns: 1fr;
	}


	.about-section {
		grid-template-columns: 1fr;
		gap: 40px;
	}


	.section-heading {
		margin-bottom: 40px;
	}

}
