<template>
    <h1>Teacher Name is : {{name}}</h1>

</template>
<script>
export default {
    name: "teacherData",
    props:{
        name: String
    }
}
</script>