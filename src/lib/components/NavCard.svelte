<script lang="ts">
	import { Hammer } from "lucide-svelte";

    export let title = "Title";
    export let size = 64;
</script>

<div class="w-full aspect-square bg-surface-700 rounded-lg shadow-lg overflow-hidden">
    <div class="aspect-content">
        <div class="flex flex-col justify-center items-center p-4 text-center">
            <Hammer size={size} />
            <h2 class="h3 font-bold">{title}</h2>
        </div>
    </div>
</div>