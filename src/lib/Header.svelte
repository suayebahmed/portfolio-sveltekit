<header>
	<nav class="nav-bar">
		<!-- LOGO -->
		<div class="logo">Suayeb <span class="last-name">Ahmed</span></div>
		<!-- NAVIGATION MENU -->
		<ul class="nav-links">
			<!-- USING CHECKBOX HACK -->
			<!-- <input type="checkbox" id="checkbox_toggle" />
		  <label for="checkbox_toggle" class="hamburger">&#9776;</label> -->
			<!-- NAVIGATION MENUS -->
			<div class="menu">
				<li><a href="/">home</a></li>
				<li><a href="/about/">about</a></li>
			</div>
		</ul>
	</nav>
	<hr />
</header>

<style>
	* {
		margin: 0;
		padding: 0;
		box-sizing: border-box;
		/* background-color: beige; */
	}

	header {
		font-family: monospace;
		width: 95%;
		margin: auto;
	}

	a {
		text-decoration: none;
	}

	li {
		list-style: none;
	}

	.nav-bar {
		display: flex;
		align-items: center;
		justify-content: space-between;
		padding: 5%;
	}

	/* .logo {
        font-size: 32px;
    } */

	.menu {
		display: flex;
		gap: 1em;
	}

	.menu li {
		padding: 5px 14px;
		letter-spacing: 1px;
	}

	.menu li:hover {
		border-radius: 5px;
		transition: 0.3s ease;
	}

	.last-name {
		font-weight: bold;
	}
</style>
