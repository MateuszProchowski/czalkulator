# czalkulator
body{
    text-align: center;
    justify-content: center;
    align-items: center;
    display: flex;
}

function calculator(num) {
    let inp = document.getElementsByClassName('inp')[0].value
    inp+=num
    document.getElementsByClassName('inp')[0].value = inp
}

function getSum() {
    let inp = document.getElementsByClassName('inp')[0].value
    document.getElementsByClassName('inp')[0].value = eval(inp)
}
