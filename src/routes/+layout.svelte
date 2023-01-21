<script lang='ts'>
	/** @type {import('./$types').LayoutData} */
	import '../app.css';
	import navlogo from '$lib/assets/img/logo.png';
	import logo from '$lib/assets/img/apple-touch-icon.png';
</script>

<html data-theme="night" class="scroll-smooth" lang="en">

  <div class="navbar bg-base-300">
	<div class="navbar-start">
		<img class="object-cover" src={navlogo} width="250" height="300" alt="bg" />	
	  <div class="dropdown">
		<!-- svelte-ignore a11y-no-noninteractive-tabindex -->
		<!-- svelte-ignore a11y-label-has-associated-control -->
		<label tabindex="0" class="btn btn-ghost lg:hidden">
		  <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h8m-8 6h16" /></svg>
		</label>
		<!-- svelte-ignore a11y-no-noninteractive-tabindex -->
		<ul tabindex="0" class="menu menu-compact dropdown-content mt-3 p-2 shadow bg-base-100 rounded-box w-52">
		  <li><a href="/#about">About</a></li>
		  <li><a href="/#services">Services</a></li>
		</ul>
	  </div>	</div>
	<div class="navbar-center hidden md:visible lg:visible lg:flex">
		<!-- svelte-ignore a11y-no-noninteractive-tabindex -->
		<ul tabindex="0" class="menu menu-horizontal px-1 space-x-1">
			<li><a href="/#about" class="btn bt">About</a></li>
			<li><a href="/#services" class="btn bt">Services</a></li>
		  </ul>
	</div>
	<div class="navbar-end">
	  <a href="https://discord.gg/89Pc5BrgSd" class="btn">Get started</a>
	</div>
  </div>

<slot />

<footer class="footer p-10 bg-base-200 text-base-content">
	<div>
		<img alt="Logo" width="100" height="100" src={logo} />
		<p>Yeet Hosting™.<br />The best in hosting.<br />team@mindustry.me<br />+1(702)552-2237</p>
	</div>
	<div>
		<span class="footer-title">Company</span>
		<a href="/#about" class="link link-hover">About Us</a>
		<a href="/#services" class="link link-hover">Our Services</a>
	</div>
	<div>
		<span class="footer-title">Legal</span>
		<a href="/policy" class="link link-hover">Privacy Policy</a>
		<a href="/terms" class="link link-hover">Terms and Conditions of Use</a>
	</div>
</footer>
</html>	
