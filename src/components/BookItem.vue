<template>

    <div :class="book.published ? 'green': 'red' ">
        <h2>Order Number : {{book.ordernumber}}</h2>
        <h4> Shipping : {{book.shipping}}</h4>
        <h4> Pickup/ Drop off : {{book.pickupordropoff}}</h4>
        <h4> Locker Number : {{book.locker}}</h4>
        <h4> Customer Support : {{book.customerservice}}</h4>
        <h4> Claims : {{book.claims}}</h4>
    </div>

</template>

<script>


export default{
    name: 'BookItem',
    props:{
        book: Array
    }
}


</script>

<style scoped>


h4{
    margin: 2px;
}

div{
    background-color: #ffb89e;
    color: black;
    padding: 1em;
    text-align: center;
}

.red{
background-color: orangered !important;

}
.green{
    color: white;
    background-color: green;
}


</style>