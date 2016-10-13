function add() {
    var a = document.getElementById("display").value;
    var b = document.getElementById("stack").value;
    document.getElementById("stack").value = parseFloat(a) + parseFloat(b);
}

function sub() {
    var a = document.getElementById("display").value;
    var b = document.getElementById("stack").value;
    document.getElementById("stack").value = parseFloat(b) - parseFloat(a);
}

function mul() {
    var a = document.getElementById("display").value;
    var b = document.getElementById("stack").value;
    document.getElementById("stack").value = parseFloat(b) * parseFloat(a);
}

function div() {
    var a = document.getElementById("display").value;
    var b = document.getElementById("stack").value;
    document.getElementById("stack").value = parseFloat(b) / parseFloat(a);
}