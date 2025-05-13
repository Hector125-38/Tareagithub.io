
#solucion del problema 
#martes 13 de mayo 2025

( ()=>{
const nombres: string[] = ['Hugo', 'Paco', 'Luis', 'Pedro', 'Hector'];
const edades: number[] = [35, 50, 40, 18, 30];

const indiceEdadMin = (): number => edades.indexOf(Math.min(...edades));
const indiceEdadMax = (): number => edades.indexOf(Math.max(...edades));

const nombreMenorEdad = (): string => nombres[indiceEdadMin()];
const nombreMayorEdad = (): string => nombres[indiceEdadMax()];

console.log(`${nombreMenorEdad()} es el menor con ${edades[indiceEdadMin()]} años.`);
console.log(`${nombreMayorEdad()} es el mayor con ${edades[indiceEdadMax()]} años.`);

}) ()





