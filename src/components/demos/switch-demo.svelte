<script lang="ts">
	import { Switch, Label } from "$lib/index.js";
</script>

<div class="flex items-center space-x-3">
	<Switch.Root
		id="marketing"
		class="peer inline-flex h-[36px] min-h-[36px] w-[60px] shrink-0 cursor-pointer items-center rounded-full px-[3px] transition-colors focus-visible:outline-none focus-visible:ring-2 focus-visible:ring-foreground focus-visible:ring-offset-2 focus-visible:ring-offset-background disabled:cursor-not-allowed disabled:opacity-50 data-[state=checked]:bg-foreground data-[state=unchecked]:bg-muted data-[state=unchecked]:shadow-mini-inset"
	>
		<Switch.Thumb
			class="pointer-events-none block size-[30px] shrink-0 rounded-full bg-background transition-transform data-[state=checked]:translate-x-6 data-[state=unchecked]:translate-x-0 data-[state=unchecked]:shadow-mini dark:border-background dark:shadow-mini dark:data-[state=unchecked]:border data-[state=unchecked]:dark:bg-background"
		/>
	</Switch.Root>
	<Label.Root for="marketing" class="text-sm font-medium">Do not disturb</Label.Root>
</div>
