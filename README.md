# Click

let saniye = 2;

 

let secici = 'button:has(svg[name="chevron-right"])';

 

let clicker= setInterval(function() {

                let hedefElement = document.querySelector(secici);

 

                if (hedefElement) {

                               hedefElement.click();

                } else {}

}, saniye * 1000);
