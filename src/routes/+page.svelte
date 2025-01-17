<script lang="ts">
import Profile from './Profile.svelte';
import Product from './Product.svelte';
</script>

<div class="md my-4"></div>

<div class="container d-block text-center">
    <div class="row justify-content-md-center">
        <div class="col col-md-auto">
            <Product price="$170" name="Nike Air Max Pulse SE" src="https://static.nike.com/a/images/c_limit,w_592,f_auto/t_product_v1/1fcfa163-572e-4673-8c97-1a70923de817/NIKE+AIR+MAX+PULSE+SE.png"/>
        </div>
        <div class="col col-md-auto">
            <Product price="$180" name="Nike Dunk Low" src="https://static.nike.com/a/images/c_limit,w_592,f_auto/t_product_v1/b9c52ab5-ed2b-41e2-ba82-c395efcbd1e6/NIKE+DUNK+LOW+NN.png"/>
        </div>
        <div class="col col-md-auto">
            <Product price="$132.99" name="Nike Lunar Force 1" src="https://static.nike.com/a/images/c_limit,w_592,f_auto/t_product_v1/0ca943b5-2488-4aa4-b980-cd4179ae2d3f/LUNAR+FORCE+1+DUCKBOOT.png" />
        </div>
    </div>
    <div class="row my-4 justify-content-md-center">
        <div class="col col-md-auto">
            <Product price="$170" name="Nike Air Max Pulse SE" src="https://static.nike.com/a/images/c_limit,w_592,f_auto/t_product_v1/1fcfa163-572e-4673-8c97-1a70923de817/NIKE+AIR+MAX+PULSE+SE.png"/>
        </div>
        <div class="col col-md-auto">
            <Product price="$180" name="Nike Air Force 1<br>High By You" src="https://static.nike.com/a/images/t_PDP_864_v1/f_auto,b_rgb:f5f5f5/e1bdc567-2790-4db1-91be-ff34f1e6d880/custom-nike-air-force-1-high.png"/>
        </div>
        <div class="col col-md-auto">
            <Product price="$132.99" name="Nike Lunar Force 1" src="https://static.nike.com/a/images/c_limit,w_592,f_auto/t_product_v1/0ca943b5-2488-4aa4-b980-cd4179ae2d3f/LUNAR+FORCE+1+DUCKBOOT.png" />
        </div>
    </div>
</div>

<hr class="border opacity-50 my-5">

<div class="container d-block bg-white">
    <div class="text-center p-4 fs-2">Employees of the Month</div>
    <div class="mw-auto text-center">
        <Profile name="Jane Smith"/>
        <Profile name="John Doe"/>
        <Profile name="Jane Smith"/>
        <Profile name="John Doe"/>
        <Profile name="Mary Sue" position="Manager"/>
        <Profile name="Mary Sue" position="Manager"/>
    </div>
</div>
