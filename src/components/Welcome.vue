<template>
    <div class="hi">
        <h2>{{info}}</h2>
    </div>
</template>
<script>
import { component } from 'vue/types/umd'
export default {
    name:'Welcome',
    props:{
        info:String
        
    }
}
</script>



