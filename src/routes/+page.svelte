<script lang="ts">
	import sourceengine from '$lib/assets/img/halflife.jpg';
	import mindus from '$lib/assets/img/mindustry.webp';
	import mc from '$lib/assets/img/minecraft.jfif';
	import logo from '$lib/assets/img/apple-touch-icon.png';
</script>

<div class="card bg-base-100 h-96 shadow-xl">
	<div class="card-body">
		<h1 class="font-extrabold text-5xl sm:h-16 md:h-16 text-center">Secure, flexible and reliable</h1>
		<h1 class="font-extrabold sm:h-20 sm:w-18 md:h-26 text-transparent bg-clip-text md:text-6xl sm:text-4xl text-center bg-gradient-to-r from-green-200 via-green-300 to-blue-500">Yeet Hosting.</h1>
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
		<div class="flex flex-row flex-wrap sm:justify-evenly md:justify-between">
			<!-- Mindustry Card -->
			<div class="card w-72 bg-base-100 hover:bg-base-300 shadow-xl image-full">
				<figure>
					<img
						src={mindus}
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
			<br>
			<!-- Minecraft Card -->
			<div class="card w-72 bg-base-100 hover:bg-base-300 shadow-xl image-full">
				<figure>
					<img
						src={mc}
						alt="Minecraft"
					/>
				</figure>
				<div class="card-body">
					<h2 class="card-title">Minecraft Hosting</h2>
					<div class="divider" />
					<p>Minecraft Servers using Yeet Hosting can use up to 70 mods.</p>
				</div>
			</div>
			<br>
			<!-- Source Engine Card -->
			<div class="card w-72 bg-base-100 hover:bg-base-300 shadow-xl image-full">
				<figure>
					<img
						src={sourceengine}
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
			<br>
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
			<br>
		</div>
	</div>
</div>
