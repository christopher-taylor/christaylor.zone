<script>
    export let title
    export let startDate
    export let endDate
</script>
<div>
    <b>{title}</b> - <i>{startDate}-{endDate}</i>
    <slot></slot>
</div>