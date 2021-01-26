<template>
    <div>
        <ul>
            <li v-for="(item, index) in numbers" :key="index" v-text="item"/>
        </ul>
    </div>
</template>

<script>
export default {
    data: () => ({
        numbers: [1,2,34,5,6]
    })
}
</script>