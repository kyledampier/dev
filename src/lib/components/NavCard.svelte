<script lang="ts">
    import Icon from "@iconify/svelte";

    export let title = "Title";
    export let icon = "mdi:question-mark-circle-outline";
</script>

<div class="w-full aspect-square bg-surface-700 rounded-lg shadow-xl overflow-hidden hover:bg-surface-600 hover:scale-105 hover:outline outline-slate-700 transition-all">
    <div class="flex flex-col justify-center items-center p-6 text-center h-full gap-4">
        <Icon icon={icon} class="w-full h-full aspect-square p-4" />
        <h2 class="h3 font-bold">{title}</h2>
    </div>
</div>