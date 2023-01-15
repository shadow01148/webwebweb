<script lang="ts">
	import navlogo from '$lib/assets/img/logo.png';
	import srvicon from '$lib/assets/img/hero-img.png';
	import logo from '$lib/assets/img/apple-touch-icon.png';
</script>

<div class="navbar bg-base-300">
	<div class="flex-1">
		<a href="/" class="btn btn-ghostnormal-case text-xl"
			><img src={navlogo} width="250" height="300" alt="bg" /></a>
	</div>
</div>

<div class="card lg:card-side bg-base-100 shadow-xl">
	<figure class="animate-pulse"><img src={srvicon} alt="Background" /></figure>
	<div class="card-body">
		<h1 class="card-title font-bold text-3xl">Yeet Hosting</h1>
		<p class="text-xl">Cheap Servers, easy configuration</p>
		<div class="stats stats-vertical w-72 shadow">
			<div class="stat">
				<div class="stat-figure text-secondary">
					<svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" class="inline-block w-8 h-8 stroke-current"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z"></path></svg>
				</div>
			  <div class="stat-title">Uptime</div>
			  <div class="stat-value text-secondary">99.999*</div>
			</div>
			<div class="stat">
				<div class="stat-figure text-secondary">
					<svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" class="inline-block w-8 h-8 stroke-current"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4.318 6.318a4.5 4.5 0 000 6.364L12 20.364l7.682-7.682a4.5 4.5 0 00-6.364-6.364L12 7.636l-1.318-1.318a4.5 4.5 0 00-6.364 0z"></path></svg>
				</div>
				<div class="stat-title">Happy Clients</div>
				<div class="stat-value text-secondary">139</div>
			  </div>
			  <div class="stat">
				<div class="stat-figure text-secondary">
					<svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" class="inline-block w-8 h-8 stroke-current"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 16h-1v-4h-1m1-4h.01M21 12a9 9 0 11-18 0 9 9 0 0118 0z"></path></svg>
				</div>
				<div class="stat-title">Years of Experience</div>
				<div class="stat-value text-secondary">3</div>
			  </div>
		</div>
	<div class="card-actions justify-end">
		<a href="https://panel.mindustry.me/" class="btn bt">Get started!</a>
	</div>
</div>
</div>

<div class="card bg-base-100 shadow-xl">
	<div class="card-body">
	  <h2 class="card-title font-bold text-3xl">Features</h2>
	  <div class="card-actions justify-end">
	  </div>
	</div>
  </div>

<div id="about" class="card lg:card-side bg-base-200 shadow-xl">
	<div class="divider" />
	<figure><img src={logo} alt="About" /></figure>
	<div class="card-body">
		<article class="prose">
			<h1 class="card-title font-bold text-4xl text-center">About Us</h1>
			<div class="di vider" />
			At Yeet Hosting, we are dedicated to providing the best hosting solutions for businesses and individuals
			alike. We understand the importance of having a reliable and efficient application, and we are
			committed to making sure our customers have the resources they need to succeed online. Our team
			is composed of experienced professionals who have a deep understanding of the latest hosting technologies.
			We work closely with our customers to understand their unique needs and tailor our services to
			fit those needs.
			<br />
			<br />
			Whether you're looking to host a mindustry server or a complex discord bot, Yeet Hosting has the
			tools and expertise you need to succeed. We offer a wide range of hosting options, including shared
			hosting, VPS hosting, and dedicated servers, so you can choose the plan that best fits your needs.
			In addition to our hosting services, we also offer a variety of other tools and resources to help
			you build and manage your applications. From a easy to use control panel to a extensive knowledgebase,
			we have everything you need to get your application up and running in no time.
			<br />
			<br />
			<ul>
				<li>Danbot Hosting</li>
				<li>Quackhost.uk</li>
				<li>HostMC4Free</li>
			</ul>
		</article>
	</div>
</div>

<div id="services" class="card lg:card-side bg-base-100 shadow-xl">
	<div class="card-body">
		<h1 class="card-title font-bold text-3xl">Services</h1>
		<div class="divider" />
		<div class="flex flex-row flex-wrap justify-between">
			<!-- Mindustry Card -->
			<div class="card w-72 bg-base-100 hover:bg-base-300 shadow-xl image-full">
				<figure>
					<img
						src="https://mindustrygame.github.io/2.0d4f9a35.webp"
						width="400"
						height="225"
						alt="Mindustry"
					/>
				</figure>
				<div class="card-body">
					<h2 class="card-title">Mindustry Hosting</h2>
					<div class="divider" />
					<p>
						We are experts in doing this service, just ask us to set your server up after buying,
						its free.
					</p>
				</div>
			</div>
			<!-- Minecraft Card -->
			<div class="card w-72 bg-base-100 hover:bg-base-300 shadow-xl image-full">
				<figure>
					<img
						src="https://store-images.s-microsoft.com/image/apps.608.13510798885735219.cf55aeca-e690-41e0-a88b-41b0e517a3be.c94e1bfa-1b68-4cf5-9954-f967168480b4?q=90&w=400&h=225"
						alt="Minecraft"
					/>
				</figure>
				<div class="card-body">
					<h2 class="card-title">Minecraft Hosting</h2>
					<div class="divider" />
					<p>Minecraft Servers using Yeet Hosting can use up to 70 mods (depends).</p>
				</div>
			</div>
			<!-- Source Engine Card -->
			<div class="card w-72 bg-base-100 hover:bg-base-300 shadow-xl image-full">
				<figure>
					<img
						src="https://cdn.akamai.steamstatic.com/half-life.com/images/halflife2/halflife2_1.jpg"
						width="400"
						height="255"
						alt="Source Engine"
					/>
				</figure>
				<div class="card-body">
					<h2 class="card-title">Source Engine Hosting</h2>
					<div class="divider" />
					<p>Yeah! thats right, you can create a server on your favorite steam games!</p>
				</div>
			</div>
			<!-- ETC -->
			<div class="card w-72 bg-base-100 hover:bg-base-300 shadow-xl image-full">
				<figure><img src={logo} width="400" height="255" alt="ETC" /></figure>
				<div class="card-body">
					<h2 class="card-title">Discord Bot, Database, Voice Server Hosting</h2>
					<div class="badge badge-secondary">NEW</div>
					<div class="divider" />
					<p>For developers, we also offer a cheap plan to get started.</p>
				</div>
			</div>
		</div>
	</div>
</div>

<footer class="footer p-10 bg-base-200 text-base-content">
	<div>
		<img alt="Logo" width="100" height="100" src={logo} />
		<p>Yeet Hosting™.<br />The best in hosting.<br />team@mindustry.me<br />+1(702)552-2237</p>
	</div>
	<div>
		<span class="footer-title">Company</span>
		<a href="#about" class="link link-hover">About Us</a>
		<a href="#services" class="link link-hover">Our Services</a>
	</div>
</footer>
