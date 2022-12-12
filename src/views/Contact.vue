<template>
	<main>
        <!-- Contact Section Start -->
		<section id="contact" class="pt-16 pb-32">
			<div class="container">
				<div class="w-full px-4">
					<div class="max-w-xl mx-auto text-center mb-16">
					<h4 class="font-semibold text-lg text-emerald-400 mb-2">CONTACT</h4>
					<h2 class="font-bold text-dark text-3xl mb-4 sm:text-4xl lg:text-5xl">Contact Me</h2>
					</div>
				</div>


				<form name="milan-contact-form">
					<div class="w-full lg:mx-auto">

					<div class="w-full px-4 mb-8">
						<label for="name" class="text-base text-emerald-400 font-bold">Name</label>
						<input type="text" id="name" autocomplete="off" name="name"
						class="w-full bg-slate-200 text-dark p-3 rounded-md focus:outline-none focus:ring-emerald-400 focus:ring-1 focus:border-emerald-400">
					</div>

					<div class=" w-full px-4 mb-8">
						<label for="email" class="text-base text-emerald-400 font-bold">Email</label>
						<input type="email" id="email" name="email"
						class="w-full bg-slate-200 text-dark p-3 rounded-md focus:outline-none focus:ring-emerald-400 focus:ring-1 focus:border-emerald-400">
					</div>

					<div class="w-full px-4 mb-8">
						<label for="message" class="text-base text-emerald-400 font-bold">Message</label>
						<textarea type=" text" id="message" autocomplete="off" name="message"
						class="w-full bg-slate-200 text-dark p-3 rounded-md focus:outline-none focus:ring-emerald-400 focus:ring-1 focus:border-emerald-400 h-32"></textarea>
					</div>

					<div class="w-full px-4">
						<button type="submit"
						class="btn-send text-base font-semibold text-white bg-emerald-400 py-3 px-8 rounded-lg w-full hover:opacity-80 transition duration-300">
						Send
						</button>
					</div>

					</div>
				</form>
			</div>
		</section>
  		<!-- Contact Section End -->
	</main>
</template>