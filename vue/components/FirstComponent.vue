<template>
<div>
The year is {{year}}
</div>
</template>

<script>
export default{
    data(){
        return{
            year: new Date().getFullYear()
        }
    }
}
</script>