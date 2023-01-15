<script lang="ts">
	import navlogo from '$lib/assets/img/logo.png';
	import logo from '$lib/assets/img/apple-touch-icon.png';

	function switchMode() {
		const element = document.getElementById("mood") as HTMLInputElement;
		const input = document.getElementById("fordata");

		if (element.checked) {
			input?.setAttribute('data-theme', 'cupcake');
			window.localStorage.setItem('theme', 'cupcake');
		} else {
			input?.setAttribute('data-theme', 'night');		
			window.localStorage.setItem('theme', 'night');
		}
	}
	const theme = typeof window !== 'undefined' ? localStorage.theme : null;
</script>

{@html '<!-- theme variable to be used in the future -->'}
<html id="fordata" data-theme="" class="scroll-smooth" lang="en">

<div class="navbar bg-base-300">
	<div class="navbar-start">
		<div class="flex-1">
			<a href="/" class="btn btn-ghostnormal-case transition-all text-xl"
				><img src={navlogo} width="250" height="300" alt="bg" /></a>
		</div>	
	</div>
	<div class="navbar-center hidden lg:flex">
	  <ul class="menu menu-horizontal px-1">
		<li><a href="#about">About</a></li>
		<li><a href="https://uptime.mindustry.me/">Status</a></li>
	  </ul>
	</div>
	<div class="navbar-end">
		<label class="swap swap-rotate">
			<input id="mood" type="checkbox" on:click={() => switchMode()} />
			<svg class="swap-off fill-current w-14 h-10" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path d="M5.64,17l-.71.71a1,1,0,0,0,0,1.41,1,1,0,0,0,1.41,0l.71-.71A1,1,0,0,0,5.64,17ZM5,12a1,1,0,0,0-1-1H3a1,1,0,0,0,0,2H4A1,1,0,0,0,5,12Zm7-7a1,1,0,0,0,1-1V3a1,1,0,0,0-2,0V4A1,1,0,0,0,12,5ZM5.64,7.05a1,1,0,0,0,.7.29,1,1,0,0,0,.71-.29,1,1,0,0,0,0-1.41l-.71-.71A1,1,0,0,0,4.93,6.34Zm12,.29a1,1,0,0,0,.7-.29l.71-.71a1,1,0,1,0-1.41-1.41L17,5.64a1,1,0,0,0,0,1.41A1,1,0,0,0,17.66,7.34ZM21,11H20a1,1,0,0,0,0,2h1a1,1,0,0,0,0-2Zm-9,8a1,1,0,0,0-1,1v1a1,1,0,0,0,2,0V20A1,1,0,0,0,12,19ZM18.36,17A1,1,0,0,0,17,18.36l.71.71a1,1,0,0,0,1.41,0,1,1,0,0,0,0-1.41ZM12,6.5A5.5,5.5,0,1,0,17.5,12,5.51,5.51,0,0,0,12,6.5Zm0,9A3.5,3.5,0,1,1,15.5,12,3.5,3.5,0,0,1,12,15.5Z"/></svg>
			<svg class="swap-on fill-current w-14 h-10" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path d="M21.64,13a1,1,0,0,0-1.05-.14,8.05,8.05,0,0,1-3.37.73A8.15,8.15,0,0,1,9.08,5.49a8.59,8.59,0,0,1,.25-2A1,1,0,0,0,8,2.36,10.14,10.14,0,1,0,22,14.05,1,1,0,0,0,21.64,13Zm-9.5,6.69A8.14,8.14,0,0,1,7.08,5.22v.27A10.15,10.15,0,0,0,17.22,15.63a9.79,9.79,0,0,0,2.1-.22A8.11,8.11,0,0,1,12.14,19.73Z"/></svg>	
		  </label>
	</div>
  </div>

<div class="card bg-base-100 h-96 shadow-xl">
	<div class="card-body">
		<h1 class="font-extrabold text-5xl h-18 text-center">Secure, flexible and reliable</h1><h1  class="font-extrabold text-transparent bg-clip-text text-5xl h-16 text-center bg-gradient-to-r from-green-200 via-green-300 to-blue-500">Yeet Hosting.</h1>
		<p class="text-3xl text-center">lol explanation here</p>
</div>
</div>

<div id="about" class="card lg:card-side h-1/4 bg-base-200 shadow-xl">
	<div class="divider" />
	<figure><img src={logo} alt="About" /></figure>
	<div class="card-body">
		<article class="prose">
			<h1 class="card-title font-bold text-4xl text-center">About Us</h1>
			<div class="divider" />
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
					<p>Minecraft Servers using Yeet Hosting can use up to 70 mods.</p>
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
</html>