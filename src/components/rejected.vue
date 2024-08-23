<template>
    <div class="display">
 <div class="box">
<p>Transaction Number</p>
</div>
<div class="box">
    <p>Activity Title</p>
</div>
<div class="box">
    <p>Date</p>
</div>
</div>

<div class="display">

    <div class="box1"></div>
    <div class="box1"></div>
    <div class="box1"></div>

</div>
<div class="display">

<div class="box1"></div>
<div class="box1"></div>
<div class="box1"></div>

</div>
<div class="display">

<div class="box1"></div>
<div class="box1"></div>
<div class="box1"></div>

</div>
<div class="display">

<div class="box1"></div>
<div class="box1"></div>
<div class="box1"></div>

</div>
<div class="display">

<div class="box1"></div>
<div class="box1"></div>
<div class="box1"></div>

</div>
</template>

<style>
.display {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
   
}

.box {
    background-color: #272F5C;
    color: #e5e7f0;
    border: none;
    padding: 10px 110px;
    cursor: pointer;
    font-size: 16px;
    margin: 60px auto;
    text-align: center;
    width: 260px;
    align-items: center;
    justify-content: space-around;
    flex-direction: row;
    

}

.box1 {
    background-color: #D9D9D9;
    color: #e5e7f0;
    border: none;
    padding: 30px 110px;
    cursor: pointer;
    font-size: 16px;
    margin: 60px auto;
    text-align: center;
    margin-top: -50px;
    width: 260px;
    align-items: center;
    justify-content: space-around;
    flex-direction: row;

}
</style> 