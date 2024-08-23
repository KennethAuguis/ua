<template>
    <div class="display">
 <div class="box">
<p>Transaction Number</p>
</div>
<div class="box">
    <p>Date</p>
</div>
<div class="box2">
    <p>Activity Proposal Form</p>
</div>
<div class="box3">
    <p>Status</p>
</div>
</div>

<div class="display">
    

    <div class="box1"></div>
    <div class="box1"></div>
    <div class="box5"></div>
    <div class="box4">
    <div class="dropdown">
    <button class="dropdown-btn"></button>
    <div class="dropdown-content">
        <a href="#">Approved</a>
        <a href="#">Disapproved</a>
        <a href="#">Revised</a>
    </div>
</div>
</div>

</div>
<div class="display">

<div class="box1"></div>
<div class="box1"></div>
<div class="box5"></div>
<div class="box4"></div>

</div>
<div class="display">

<div class="box1"></div>
<div class="box1"></div>
<div class="box5"></div>
<div class="box4"></div>

</div>
<div class="display">

<div class="box1"></div>
<div class="box1"></div>
<div class="box5"></div>
<div class="box4"></div>

</div>
<div class="display">

<div class="box1"></div>
<div class="box1"></div>
<div class="box5"></div>
<div class="box4"></div>

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
    width: 130px;
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
    width: 130px;
    align-items: center;
    justify-content: space-around;
    flex-direction: row;

}
.box2 {
    background-color: #272F5C;
    color: #e5e7f0;
    border: none;
    padding: 10px 110px;
    cursor: pointer;
    font-size: 16px;
    margin: 60px auto;
    text-align: center;
    width: 180px;
    align-items: center;
    justify-content: space-around;
    flex-direction: row;
    

}
.box3 {
    background-color: #272F5C;
    color: #e5e7f0;
    border: none;
    padding: 10px 110px;
    cursor: pointer;
    font-size: 16px;
    margin: 60px auto;
    text-align: center;
    width: 20px;
    align-items: center;
    justify-content: space-around;
    flex-direction: row;
    

}
.box4 {
    background-color: #D9D9D9;
    color: #e5e7f0;
    border: none;
    padding: 30px 110px;
    cursor: pointer;
    font-size: 16px;
    margin: 60px auto;
    text-align: center;
    margin-top: -50px;
    width: 20px;
    align-items: center;
    justify-content: space-around;
    flex-direction: row;

}
.box5 {
    background-color: #D9D9D9;
    color: #e5e7f0;
    border: none;
    padding: 30px 110px;
    cursor: pointer;
    font-size: 16px;
    margin: 60px auto;
    text-align: center;
    margin-top: -50px;
    width: 180px;
    align-items: center;
    justify-content: space-around;
    flex-direction: row;

}

.dropdown {
            margin-top: -40px;
            margin-left: 50px;
            
        }

        .dropdown-content {
            display: none;
            position: absolute;
            background-color: #272F5C;
            box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
            z-index: 1;
            min-width: 160px;
        }

        .dropdown-content a {
            color: white;
            padding: 12px 16px;
            text-decoration: none;
            display: block;
        }

        .dropdown-content a:hover {
            background-color: #01030f;
        }

        .dropdown:hover .dropdown-content {
            display: block;
        }

        .dropdown-btn {
            background-color: transparent;
            color: #272F5C;
            padding: 10px;
            font-size: 16px;
            border: none;
            cursor: pointer;
        }

        .dropdown-btn:after {
            content: ' ▼';
            font-size: 20px;
        }

        .dropdown-btn:hover {
            background-color: transparent;
        }
</style> 