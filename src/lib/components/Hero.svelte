<section class="flex flex-col gap-12 py-20">
	<div class="flex flex-col gap-5">
		<h1 class="text-4xl font-bold text-[#111827]">
			Zero-config environment sync for development teams
		</h1>
		<h5 class="text-lg">
			Keep your team's <span class="font-semibold text-[#0F766E]">.env</span> files securely in sync.
			No shared spreadsheets, no decrypted secrets in Slack, no friction.
		</h5>
	</div>
	<div class="rounded-xl border border-[#1E293B] bg-[#0F172A] font-mono">
		<div class="rounded-t-xl bg-[#1E293B] px-4 py-3 text-xs text-[#9CA3AF]">
			terminal — envy pull
		</div>

		<div class="flex flex-col gap-3 p-6 text-sm text-[#F8FAFC]">
			<p><span class="text-[#64748B]">$</span> <span class="text-[#38BDF8]">envy</span> pull</p>
			<p><span class="text-[#4ADE80]">✓</span> Connected to vault (project: env-prod)</p>
			<p><span class="text-[#4ADE80]">✓</span> Fetched 18 secure variables [0.3s]</p>
			<p><span class="text-[#4ADE80]">✓</span> Updated .env.local (3 changes applied)</p>
			<p class="pt-5">
				<span class="text-[#64748B]">$</span> <span class="text-[#38BDF8]">envy</span> diff
			</p>
			<p>
				<span class="text-[#4ADE80]">✓</span> Your local workspace is fully aligned with production environment.
			</p>
		</div>
	</div>
</section>
