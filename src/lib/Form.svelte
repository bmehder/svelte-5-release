<form>
	<div class="flow">
		<div class="form-group">
			<label for="first">First Name <span>*</span></label>
			<input
				type="text"
				name="first"
				id="first"
				placeholder="Enter first name..."
				required
			/>
		</div>

		<div class="form-group">
			<label for="last">Last Name <span>*</span></label>
			<input
				type="text"
				name="last"
				id="last"
				placeholder="Enter last name..."
				required
			/>
		</div>

		<div class="form-group">
			<label for="email">Email <span>*</span></label>
			<input
				type="email"
				name="email"
				id="email"
				placeholder="Enter email address..."
				required
			/>
		</div>

		<div class="form-group">
			<label for="tel">Phone (Optional)</label>
			<input
				type="tel"
				name="tel"
				id="tel"
				placeholder="Enter phone number..."
				required
			/>
		</div>

		<div class="form-group">
			<label for="message">Message <span>*</span></label>
			<textarea
				name="message"
				id="message"
				rows="10"
				placeholder="Enter message..."
				required
			>
			</textarea>
		</div>

		<button type="submit" class="bg-blue white">Send Message</button>
	</div>
</form>

<style>
	form {
		max-width: 32rem;
	}

	.form-group {
		display: grid;
		gap: 0.25rem;
	}

	label {
		font-weight: 600;
	}

	input,
	textarea {
		padding: 0.75rem;
	}

	button:hover {
		background-image: var(--gradient-pink);
	}
</style>
