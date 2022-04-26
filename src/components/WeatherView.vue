<template>
    <div class="WeatherView">
    <h1>Weather</h1>
    {{weather}}

    </div>
</template>

<script>
export default {
    name: 'WeatherView',
    data(){
        return{
            weather: "sun",
        }
    }

}
</script>

<style>


</style>

