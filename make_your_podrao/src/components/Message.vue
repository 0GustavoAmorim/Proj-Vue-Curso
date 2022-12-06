<template>
    <div class="message-container">
        <p>{{ msg }}</p>
    </div>
</template>


<script>
export default{
    name: "Message",
    props:  {
        msg: String
    }
}
</script>

<style scoped>
    .message-container {
        color: #000000;
        font-style: bold;
        background-color: #6be67b;
        border: 2px solid #505050;
        border-radius: 5px;
        padding: 10px;
        max-width: 400px;
        margin: 30px auto;
    }
</style>