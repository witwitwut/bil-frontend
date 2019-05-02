<template>
    <section class="bikeSection">
        <ul>
            <Bike :bike="bike" v-bind:key="bike.name" v-for="bike in bikes" />
        </ul>
    </section>
    
</template>


<script>
import Bike from "./Bike"

export default {
    name: 'Bikes',
    components: {Bike},
    props: {
        bikes: Array,
    } 
}
</script>
