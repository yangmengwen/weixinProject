<template>
    <div>
        <ul>
            <li v-for="(item,index) in list" :key="index">{{item.name}}</li>
        </ul>
    </div>
</template>
<script>
export default {
    props:['list']
}
</script>

