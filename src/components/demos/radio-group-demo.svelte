<script lang="ts">
	import { RadioGroup, Label } from "$lib/index.js";
</script>

<RadioGroup.Root class="flex flex-col gap-4 text-sm font-medium">
	<div
		class="group flex cursor-pointer select-none items-center gap-3 text-foreground transition-all"
	>
		<RadioGroup.Item
			id="amazing"
			value="amazing"
			class="size-5 shrink-0 rounded-full border border-border-input bg-background transition-all duration-100 ease-in-out hover:border-dark-40 data-[state=checked]:border-6 data-[state=checked]:border-foreground"
		/>
		<Label.Root for="amazing">Amazing</Label.Root>
	</div>
	<div
		class="group flex cursor-pointer select-none items-center gap-3 text-foreground transition-all"
	>
		<RadioGroup.Item
			id="average"
			value="average"
			class="size-5 shrink-0 rounded-full border border-border-input bg-background transition-all duration-100 ease-in-out hover:border-dark-40 data-[state=checked]:border-6 data-[state=checked]:border-foreground"
		/>
		<Label.Root for="average">Average</Label.Root>
	</div>
	<div
		class="group flex cursor-pointer select-none items-center gap-3 text-foreground transition-all"
	>
		<RadioGroup.Item
			id="terrible"
			value="terrible"
			class="size-5 shrink-0 rounded-full border border-border-input bg-background transition-all duration-100 ease-in-out hover:border-dark-40 data-[state=checked]:border-6 data-[state=checked]:border-foreground"
		/>
		<Label.Root for="terrible">Terrible</Label.Root>
	</div>
</RadioGroup.Root>
