<template>
    <div>
         <div>
            hi {{name}}
        </div>
        <div>
            <list/>
        </div>
    </div>
</template>

<script>
import List from './component/List.vue'
export default {
    components: { List },
    data: () => ({
        name: 'John'
    })
}
</script>
