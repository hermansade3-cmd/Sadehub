<!DOCTYPE html>
<html lang="sw">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Finance Tracker ya Mwaka</title>

<style>

body{
font-family:Arial;
background:#f4f6f9;
padding:20px;
}

h1{
text-align:center;
}

table{
width:100%;
border-collapse:collapse;
background:white;
}

th,td{
padding:8px;
border:1px solid #ccc;
text-align:center;
}

th{
background:#1565c0;
color:white;
}

input{
width:85px;
padding:4px;
}

.total{
background:#e3f2fd;
font-weight:bold;
}

button{
margin-top:15px;
padding:10px 20px;
background:#d32f2f;
color:white;
border:none;
cursor:pointer;
}

</style>
</head>

<body>

<h1>Mpangilio wa Fedha za Mwaka</h1>

<table>

<tr>
<th>Mwezi</th>
<th>Mshahara</th>
<th>Ration</th>
<th>Package</th>
<th>Mapato</th>
<th>Chakula</th>
<th>Matumizi</th>
<th>Deni</th>
<th>Akiba</th>
<th>Salio</th>
</tr>

<tbody id="tableBody"></tbody>

<tr class="total">
<td colspan="8">Jumla ya Akiba</td>
<td id="totalSavings">0</td>
<td></td>
</tr>

</table>

<button onclick="resetData()">Futa Data Zote</button>

<script>

const salary=516000
const ration=300000
const packageMoney=300000

const months=[
"Januari","Februari","Machi","Aprili","Mei","Juni",
"Julai","Agosti","Septemba","Oktoba","Novemba","Desemba"
]

const packageMonths=[2,5,8,11]

const tbody=document.getElementById("tableBody")

months.forEach((month,index)=>{

let packageValue=packageMonths.includes(index)?packageMoney:0
let income=salary+ration+packageValue

let row=`
<tr>

<td>${month}</td>

<td>${salary}</td>
<td>${ration}</td>
<td>${packageValue}</td>

<td class="income">${income}</td>

<td><input type="number" class="food" data-id="${index}-food"></td>

<td><input type="number" class="expense" data-id="${index}-expense"></td>

<td><input type="number" class="debt" data-id="${index}-debt"></td>

<td><input type="number" class="saving" data-id="${index}-saving"></td>

<td class="balance">${income}</td>

</tr>
`

tbody.innerHTML+=row

})

const inputs=document.querySelectorAll("input")

inputs.forEach(input=>{

let saved=localStorage.getItem(input.dataset.id)

if(saved){
input.value=saved
}

input.addEventListener("input",()=>{

localStorage.setItem(input.dataset.id,input.value)

calculate()

})

})

function calculate(){

let foods=document.querySelectorAll(".food")
let expenses=document.querySelectorAll(".expense")
let debts=document.querySelectorAll(".debt")
let savings=document.querySelectorAll(".saving")
let balances=document.querySelectorAll(".balance")
let incomes=document.querySelectorAll(".income")

let totalSavings=0

foods.forEach((food,i)=>{

let foodCost=Number(food.value)||0
let expense=Number(expenses[i].value)||0
let debt=Number(debts[i].value)||0
let saving=Number(savings[i].value)||0
let income=Number(incomes[i].innerText)

let balance=income-foodCost-expense-debt-saving

balances[i].innerText=balance

totalSavings+=saving

})

document.getElementById("totalSavings").innerText=totalSavings

}

calculate()

function resetData(){

localStorage.clear()

document.querySelectorAll("input").forEach(input=>input.value="")

calculate()

}

</script>

</body>
</html>
