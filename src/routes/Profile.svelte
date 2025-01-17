<script lang="ts">
    let {
        name = "John Doe",
        position = "Employee",
        contact = "(1300) 555 06"
    } = $props();
</script>

<div class="profile container m-2 rounded shadow-sm bg-light fs-4 d-inline-block">
    <div class="row align-items-end justify-content-between">
        <div class="col-9 text-start">
            <b>{name}</b>
            <br>
            {position}
        </div>
        <div class="col align-self-center">
            <i class="bi bi-person-circle" style="font-size: 3rem"></i>
        </div>
    </div>
</div>

<style>
    @import url("https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css");

    .profile {
        max-width: 300px;
    }
</style>
