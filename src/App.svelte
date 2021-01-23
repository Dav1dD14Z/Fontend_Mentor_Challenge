<script>
	import Header from './Components/Header.svelte'
	import Feature from './Components/Feature.svelte'
	import Card from './Components/Card.svelte'
	import Message from './Components/Message.svelte'
	import Footer from './Components/Footer.svelte'

</script>

<style>

:global(body) {
	transition: background 0.8s linear 0.2s;
}

:global(body.dark-mode) {
	background-color: #1d3040;
	color: white;
	transition: background 0.8s linear 0.2s;
}

main {
	margin: 0px;
	padding: 0px;
}

</style>

<main>
	<Header />
	<Feature />
	<Card
	 title = 'Grow Together'
	 info = 'Generate meaningful discussions with your audience and build a strong, loyal community. Think of the insightful conversations you miss out on with a feedback form'
	 image ='https://huddle-challenge-git-main.david1012.vercel.app/images/illustration-grow-together.svg'
	/>
	<Card
	 title = 'Flowing Conversations'
	 info = "You wouldn't paginate a conversation in real life, so why do it online? Our threads have just-in-time loading for a more natural flow."
	 image ='https://huddle-challenge-git-main.david1012.vercel.app/images/illustration-flowing-conversation.svg'
	 position_1 = 'right: 0'
	 position_2 = 'left: 0'
	 text_align = 'text-align: right'
	/>
	<Card
	 title = 'Your Users'
	 info = "It takes no time at all to integrate Huddle with your app's authentication solution. This means, once signed in to your app, your users can start chatting immediately."
	 image ='https://huddle-challenge-git-main.david1012.vercel.app/images/illustration-your-users.svg'
	/>
	<Message />
	<Footer />
</main>
