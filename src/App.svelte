<script>
	import { t } from "svelte-i18n";
	import { Router } from "@roxi/routify";
  import { routes } from "../.routify/routes";
</script>

<style global lang="scss">
	@import './app.scss';
</style>

<nav class="nav">
	<a href='/'>Home</a>
	<a href='/about'>{$t('about.title')}</a>
</nav>
<Router {routes} />