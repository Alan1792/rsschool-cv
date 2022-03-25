# Karim Sharafullin

### Contact information:

* __email:__<razor171992@gmail.com>
* [github:](https://github.com/Alan1792) 
* __diccord:__@Karim
* __telegram:__<https://t.me/dvsr>
* __vk:__<https://vk.com/alanbreak>

***
### About me:

Greetings. I am 29 years old, I work in a government agency. I decided to change the type of activity, because I think programming is a more interesting and developing profession. I chose the front-end for its interactive component. In my free time I like to read, I am a little fond of music, in the summer I ride a bike, and in the winter I skate.

***
### Skills and Proficiency: ###

* HTML, CSS
* Git, Github
* figma, avocode
* gulp
* basic javascript

### Code example: ###

Happy Tickets

```javascript
console.log(getLuckyTickets());

function getLuckyTickets() {
	let result = [];
	
	for (let i = 1001; i <= 999999; i++) {
		if (isLucky(i)) {
			result.push(i);
		}
	}
	
	return result;
}

function isLucky(num) {
	let str = normalizeNum(num);
	
	let sum1 = Number(str[0]) + Number(str[1]) + Number(str[2]);
	let sum2 = Number(str[3]) + Number(str[4]) + Number(str[5]);
	
	return sum1 == sum2;
}

function normalizeNum(num) {
	let str = String(num);
	
	if (str.length == 5) {
		str = '0' + str;
	}
	if (str.length == 4) {
		str = '00' + str;
	}
	
	return str;
}
```

***
### Languages: ###

* russian
* english - B1