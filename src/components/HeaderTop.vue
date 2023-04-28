<template>
    <div>
        <h1> {{bookName}} </h1>
        
    </div>
</template>
    
    <script>
    
    export default{
        name: 'HeaderTop',
        props:{
            bookName: String,
            authorName:String
        }
    }
    
    </script>
    
    <style scoped>
    
    div{
        text-align: center;
    }
    
    </style>