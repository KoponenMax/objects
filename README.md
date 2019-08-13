# objects

1)У нас есть объект, в котором хранятся зарплаты нашей команды:

let salaries = {
  John: 100,
  Ann: 160,
  Pete: 130
}
Напишите код для суммирования всех зарплат и сохраните результат в переменной sum. Должно получиться 390.

Если объект salaries пуст, то результат должен быть 0.


let salaries = {
  John: 100,
  Ann: 160,
  Pete: 130
};

let sum = 0;
for (let key in salaries){
	 sum += salaries[key];
}

alert (sum);


2)Создайте функцию multiplyNumeric(obj), которая умножает все числовые свойства объекта obj на 2.

function multiplyNumeric(obj){
	for (let key in obj){
		if (typeof obj[key] === 'number'){
			 obj[key] *= 2;
		}
		else obj[key];
	}
}


3)Создайте функцию multiplyNumeric(obj), которая умножает все числовые свойства объекта obj на 2.

function multiplyNumeric(obj){
	for (let key in obj){
		if (typeof obj[key] === 'number'){
			 obj[key] *= 2;
		}
		else obj[key];
	}
}
