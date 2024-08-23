<template>
    <div class="form-container">
        <table>
            <tr>
                <th colspan="1">Txn.no.</th>
                <th colspan="0">014</th>
                <th colspan="5">SEND COPIES TO:</th>
            </tr>
            <tr>
                <td colspan="2">Proponent</td>
                <td><input type="checkbox"></td>
                <td>Security</td>
                <td><input type="checkbox"></td>
                <td>Sound System</td>
                <td><input type="checkbox"></td>
            </tr>
            <tr>
                <td colspan="2">EAMO</td>
                <td><input type="checkbox"></td>
                <td>Janitorial</td>
                <td><input type="checkbox"></td>
                <td>Others</td>
                <td><input type="checkbox"></td>
            </tr>
            <tr>
                <td colspan="2">PhotoLab</td>
                <td><input type="checkbox"></td>
                <td>Sports</td>
                <td><input type="checkbox"></td>
                <td></td>
                <td></td>
            </tr>
            <tr>
                <td colspan="2">PPGS</td>
                <td><input type="checkbox"></td>
                <td>Hotel</td>
                <td><input type="checkbox"></td>
                <td></td>
                <td><button class="next-button">&gt;</button></td>
            </tr>
        </table>
    </div>
</template>

<script>
</script>

<style scoped>

body {
    font-family: Arial, sans-serif;
}

.form-container {
    width: 50%;
    margin: 0 auto;
    padding: 0px;
    border: 10px solid #000080;
    border-radius: 10px;
}
th[colspan="5"] {
    text-align: left;
    padding-right: 20px;
}

table {
    width: 100%;
    border-collapse: collapse;
    text-align: center;
}

th, td {
    padding: 20px;
    border: 4px solid #000080;;
}

th {
    background-color: transparent;
}

input[type="checkbox"] {
    appearance: none;
    -webkit-appearance: none;
    -moz-appearance: none;
    width: 20px;
    height: 20px;
    border: 2px solid #272F5C;
    border-radius: 50%;
    outline: none;
    cursor: pointer;
    position: relative;
}


input[type="checkbox"]:checked {
    background-color: #000080;
}

input[type="checkbox"]:checked::after {
    content: '';
    display: block;
    width: 10px;
    height: 10px;
    border-radius: 10%;
    position: absolute;
    top: 3px;
    left: 3px;
}

.next-button {
    background-color: transparent;
    color: black;
    border: none;
    padding: 10px 20px;
    border-radius: 5px;
    cursor: pointer;
    font-size: 30px;
}

.next-button:hover {
    background-color: transparent;
    
}




</style>
