<script lang="ts">
    import NavCard from '$lib/components/NavCard.svelte';

    const MenuItems = [
        { title: 'Nail It', icon: 'mdi:nail' },
        { title: 'Fuse It', icon: 'mdi:shuffle' },
        { title: 'Stabilize It', icon: 'ic:round-close-fullscreen' },
        { title: 'Fix It', icon: 'mdi:hammer' },
        { title: 'Compass It', icon: 'mdi:compass-outline'},
        { title: 'Restore It', icon: 'mdi:restore' },
        { title: "Torque It", icon: 'mdi:wrench'}
    ];
</script>

<div class="flex flex-col w-64 p-6 gap-8">
    {#each MenuItems as { title, icon }}
        <NavCard {title} {icon} />
    {/each}
</div>