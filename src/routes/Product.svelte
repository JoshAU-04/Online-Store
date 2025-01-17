<script lang="ts">
let {
    name = "Some Product",
    price = "$79.20",
    stocked = true,  /* Sold out? */
    src
} = $props();

function getStock() { return stocked ? "In stock" : "Sold Out" }

</script>

<div class="card" style="width: 18rem">
    <div class="card-header fs-5"> {getStock()} </div>
    <div class="card-body" style="background-color: #f6f6f6">
        <img {src} class="card-img-top" alt="A shoe">
    </div>
    <div class="card-body">
        <div style="padding: 0px; margin: 0px" class="fs-4 card-title">{@html name}</div>
    </div>
    <div class="text-body-secondary mx-3 pb-4">
        $69.99
    </div>
</div>

<style>
@import url("https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css");
</style>
