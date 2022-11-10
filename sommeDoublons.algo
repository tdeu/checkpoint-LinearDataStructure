// Somme des éléments distincts

let ensemble1 = [3, 1, 7, 9];
let ensemble2 = [2, 4, 1, 9, 3];
let sum = 0;
let etat = false;

function sommeElementsDistincts(tab1, tab2){    
    for(let i=0; i<tab1.length; i++){
        for(let j=0; j<tab2.length; j++){
            if(tab1[i]==tab2[j]){
                etat = true;
            }
        }
        if(!etat){
            sum = sum + tab1[i];
        }
        etat = false;
    }
    
    for(let j=0; j<tab2.length; j++){
        for(let i=0; i<tab1.length; i++){
            if(tab2[j]==tab1[i]){
                etat = true;
            }
        }
        if(!etat){
            sum = sum + tab2[j];
        }
        etat = false;
    }
    
    return sum;
}

let somme = sommeElementsDistincts(ensemble1, ensemble2);

console.log(somme);

// Somme des doublons

let ensemble3 = [12, 13, 6, 10];
let ensemble4 = [13, 10, 16, 15];
let sumRepeatElement = 0;

function sommeDoublons(tab1, tab2){    
    for(let i=0; i<tab1.length; i++){
        for(let j=0; j<tab2.length; j++){
            if(tab1[i]==tab2[j]){
                sumRepeatElement = sumRepeatElement + tab1[i] * 2;
            }
        }
    }
    
    return sumRepeatElement;
}

let sommeDouble = sommeDoublons(ensemble3, ensemble4);

console.log(sommeDouble);