<template>
<li>
    <h1>{{bike.name}}</h1>
    <img :src="bike.bikeImg" alt="">
    <p>{{bike.price}}</p>
</li>
</template>

<script>
export default {
    name: 'Bike',
    props: {
        bike: Object
    }
    
}
</script>
