<template>
    <div class="submitted">
        <button class="submitted-button" @click="buttonClicked">Submitted Activity Proposal Form</button>
    </div>
</template>

<script>
export default {
    methods: {
        buttonClicked() {
            console.log('Submitted Activity Proposal Form button clicked');
        }
    }
}
</script>

<style scoped>
.submitted {
  
    text-align: center;
    color: white;
    padding: 10px;
    display: inline-block;
}

.submitted-button {
    background-color: #272F5C;
    color: #e5e7f0;
    border: none;
    border-radius: 5px;
    padding: 10px 20px;
    cursor: pointer;
    font-size: 16px;
}

</style>
