<template>
    <div v-if="products.length6">
        <div v-for="item in products" :key="item">
            <div class="m-3">
                <div class="">
                    <div class="card text-bg-dark">
                        <div class="card-body">
                            <h4 class="card-title">Name: {{item.name}}</h4>
                            <h5 class="card-title">Category: {{item.category}}</h5>
                            <p class="card-text">Value: R{{item.value}}</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <div v-else>
        <Spinners></Spinners>
    </div>
</template>
<script>
import Spinners from '@/components/Spinner.vue'
export default {
    name: 'product',
    data() {
        return {
            products: [
//     {
//         id: 1,
//         name: "Carrot",
//         category: "Veg",
//         value: 1020,
//     },
//     {
//         id: 2,
//         name: "Pumpkin",
//         category: "Veg",
//         value: 1500,
//     },
//     {
//         id: 3,
//         name: "Egg Plant",
//         category: "Veg",
//         value: 1350,
//     },
//    {
//         id: 4,
//         name: "Cabbage",
//         category: "Veg",
//         value: 600,
//     },{
//         id: 5,
//         name: "Broccoli",
//         category: "Veg",
//         value: 100,
//     },
//     {
//         id: 6,
//         name: "Onions",
//         category: "Veg",
//         value: 470,
//     }
]}},
    components:{
        Spinners
    }
}
</script>
<style>
    
</style>