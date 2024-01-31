$(document).foundation()

const areacua = () => {
    const lado = parseFloat(prompt("digite lado:"));
    const area = lado * lado;
    console.log(area);
    alert("El area del Cuadrado es igual a:" + area);
}

const Pericua = () => {
    const lado = parseFloat(prompt("digite lado :"));
 const Perimetro = lado * 4 ;
    console.log(Perimetro);
    alert("El Perimetro del cuadrado es igual a:" + Perimetro);
}

const areacirc = () => {
    const diametro = parseFloat(prompt("digite diametro:"));
    const area = diametro / 2 * 3.14;
    console.log(area);
    alert("El area del Circulo es igual a:" + area);
}

const Pericir = () => {
    const diametro = parseFloat(prompt("digite diametro :"));
 const Perimetro = diametro * 3.14 ;
    console.log(Perimetro);
    alert("El Perimetro del Circulo es igual a:" + Perimetro);
}

const areatri = () => {
    const base = parseFloat(prompt("digite base:"));
    const altura = parseFloat(prompt("Digite altura"));
const area = base * altura / 2;
    console.log(area);
    alert("El area del triangulo es igual a:" + area);
}

const Peritri = () => {
    const lado1 = parseFloat(prompt("digite lado 1:"));
    const lado2 = parseFloat(prompt("Digite lado 2"));
    const lado3= parseFloat(prompt("Digite lado 3"));
const Perimetro = lado1 + lado2 + lado3;
    console.log(Perimetro);
    alert("El Perimetro del triangulo es igual a:" + Perimetro);
}

const arearec = () => {
    const base = parseFloat(prompt("digite base:"));
    const altura = parseFloat(prompt("Digite altura"));
const area = base * altura;
    console.log(area);
    alert("El area del Rectangulo es igual a:" + area);
}

const Perirec = () => {
    const base = parseFloat(prompt("digite base:"));
    const altura = parseFloat(prompt("Digite altura"));
    const Perimetro = base * 2 + altura * 2;
    console.log(Perimetro);
    alert("El Perimetro del Rectangulo es igual a:" + Perimetro);
}
