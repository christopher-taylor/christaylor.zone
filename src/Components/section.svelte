<script>
  export let heading;
</script>
<style>
    h3{
        margin-bottom: 5px;
    }
    hr {
        margin: 0px auto 10px auto;
    }
</style>
<div class="row">
  <div class="column">
    <h3>{heading}</h3>
    <hr/>
    <slot />
  </div>
</div>
