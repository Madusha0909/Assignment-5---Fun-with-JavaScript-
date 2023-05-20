function bigger(){
    alert("Hello, world!");
    document.getElementById("txt").style.fontSize = "24pt";
}

function fancy(){
    var btn =  document.getElementById("fancy");
    var txt = document.getElementById("txt");
    if(btn.checked){
        txt.style.fontWeight = "bold";
        txt.style.color = "blue";
        txt.style.textDecoration = "underline";
    }
    else {
        txt.style.fontWeight = "normal";
        txt.style.color = "black";
        txt.style.textDecoration = "none";
    }
}

function moo(){
    var txt = document.getElementById("txt");
    txt.style.textTransform = "uppercase";
    var str = txt.value;
    var parts = str.split(".");
    str = parts.join("-Moo");
    txt.value = str;
}
