<script>
    import Icon from '@iconify/svelte';
    export let iconName;
    export const text = 'tooltip'

</script>
<div class="relative">
    <Icon icon="{iconName}" class="sidebar-icon" />
    <span class="sidebar-tooltip">{text}</span>
</div>