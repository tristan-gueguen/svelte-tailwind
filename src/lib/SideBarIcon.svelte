<script>
    import Icon from '@iconify/svelte';
    export let iconName;
    export const text = 'tooltip'

</script>
<div class="relative group">
    <Icon icon="{iconName}" class="sidebar-icon" />
    <span class="sidebar-tooltip group-hover:scale-100">{text}</span>
</div>