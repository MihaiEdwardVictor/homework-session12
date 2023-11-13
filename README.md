# homework-session12


Operatori aritmetici

1.Scrieți un program JavaScript care adună două numere și afișează rezultatul în consolă.

let number1 = Number(prompt('Introduceti primul numar: '));
let number2 = Number(prompt('Introduceti al doilea numar: '));
let suma = number1 + number2;
alert('Suma numerelor este: ' +suma);

2.Scrieți un program JavaScript care calculează media a trei numere și afișează rezultatul în consolă.

let number1 = Number(prompt('Introduceti primul numar: '));
let number2 = Number(prompt('Introduceti al doilea numar: '));
let number3 = Number(prompt('Introduceti al treilea numar: '));
let media = (number1 + number2 +number3)/3;

Varianta Smechera

let numberOfNumbers = Number(prompt('Introduceti cu cate numere vreti sa faceti media aritmetica: '));
let suma = 0;
let matrice = [];

for(let i=1;i<=numberOfNumbers;i++){
    let numere = Number(prompt('Introduceti numerele: '));
    matrice.push(numere);
}

for(let i=0;i<matrice.length;i++){
    suma += matrice[i];
}

let average = Number(suma/matrice.length);
alert('Media numerelor este: ' + average);

Operatori de atribuire

1.Scrieți un program JavaScript care adaugă 5 la o variabilă numită "x" și afișează rezultatul în consolă.

let x = 5;
alert(x);


2.Scrieți un program JavaScript care atribuie valoarea 10 variabilei "y" și apoi adaugă 2 la aceasta utilizând operatorul "+=".

let y = 10;
y+=2;
alert(y);

Operatori de comparare

1.Scrieți un program JavaScript care compară două numere și afișează "A este mai mare decât B" dacă primul număr este mai mare decât al doilea, sau "B este mai mare sau egal cu A" dacă al doilea număr este mai mare sau egal cu primul.

let a = Number(prompt('Introduceti primul numar (A) : '));
let b = Number(prompt('Introduceti al doilea numar (B): '));

if(a>b){
    alert("A este mai mare decat B");
}else if(a<=b){
    alert("B este mai mare sau egal cu A");
}

2.Scrieți un program JavaScript care verifică dacă o variabilă numită "varsta" este mai mare sau egală cu 18 și afișează un mesaj corespunzător în consolă, în funcție de rezultat.

let varsta = Number(prompt("Introduceti varsta: "));
if(varsta>=18){
    alert("Aveti cel putin 18 ani");
}else if (varsta<18){
    alert("Nu aveti cel putin 18 ani!");
}

Operatori logici

1.Scrieți un program JavaScript care verifică dacă două condiții sunt adevărate utilizând operatorul "&&" (și logic) și afișează un mesaj corespunzător în consolă, în funcție de rezultat.

let numar = Number(prompt('Introduceti numarul: '));
if (numar%2 == 0 && numar%5 == 0){
    alert("Numarul se imparte exact la 2 si la 5");
}else if(numar%2 == 0){
    alert("Numarul se imparte exact doar la 2");
}else if(numar%5 == 0){
    alert("Numarul se imparte exact doar la 5");
}else alert("Numarul nu se imparte nici la 2 nici la 5");

2.Scrieți un program JavaScript care verifică dacă o condiție este adevărată utilizând operatorul "!" (nu logic) și afișează un mesaj corespunzător în consolă, în funcție de rezultat.

let numar = Number(prompt('Introduceti numarul: '));
if(numar%2!=0){
    alert("Numarul este impar");
}else alert("Numarul este par");

