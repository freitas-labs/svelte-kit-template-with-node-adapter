<script>
	import { CardNoImage, CardWithImage, Heading, RedBall } from '@components';
	import { LL } from '@i18n';
</script>

<Heading value="svelte-kit-template-with-node-adapter" />
<div class="flex flex-row justify-evenly">
	<CardNoImage />
	<CardWithImage />
</div>
<div class="flex flex-col justify-center">
	<RedBall />
	<p class="text-center">{$LL.greetings()}</p>
</div>
