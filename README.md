## **JavaScript Day 2 Assignment – Answers**


## **1. Welcome Program**

```js
let name = prompt("Enter your name:");
alert("Hi, Welcome to JavaScript Training");
console.log("Hi, Welcome to JavaScript Training");
```

---

## **2. Console Methods Practice**

```js
console.log("This is a log message");
console.warn("This is a warning message");
console.error("This is an error message");
console.clear();
```

---

## **3. Data Type Identification**

```js
let str = "JavaScript";
let num = 100;
let bool = true;
let undef;
let nul = null;

console.log(str, typeof str);
console.log(num, typeof num);
console.log(bool, typeof bool);
console.log(undef, typeof undef);
console.log(nul, typeof nul);
```

---

## **4. Arithmetic Operations**

```js
let a = 20;
let b = 5;

console.log(a + b); 
console.log(a - b); 
console.log(a * b); 
console.log(a / b); 
console.log(a % b);
```

---

## **5. Increment & Decrement**

```js
let x = 10;

console.log(++x); // pre-increment
console.log(x++); // post-increment
console.log(--x); // pre-decrement
console.log(x--); // post-decrement
```

---

## **6. Assignment Operators**

```js
let num = 10;

num += 5;
console.log(num);

num -= 3;
console.log(num);

num *= 2;
console.log(num);

num /= 4;
console.log(num);

num %= 3;
console.log(num);
```

---

## **7. Array Access**

```js
let subjects = ["HTML", "CSS", "JavaScript", "React"];

console.log(subjects[0]); 
console.log(subjects[1]); 
console.log(subjects[subjects.length - 1]); 
console.log(subjects.length);
```

---

## **8. Modify Array**

```js
let subjects = ["HTML", "CSS", "JavaScript", "React"];

subjects.push("NodeJS");
subjects.pop();

console.log(subjects);
```

---

## **9. Student Object**

```js
let student = {
  name: "Rahul",
  age: 21,
  course: "JavaScript",
  city: "Mumbai"
};

console.log(student.name);
console.log(student.age);
console.log(student.course);
console.log(student.city);
```

---

## **10. Nested Object Practice**

```js
let company = {
  name: "Tech Solutions",
  trainer: {
    name: "Amit",
    subject: "JavaScript"
  }
};

console.log(company.name);
console.log(company.trainer.name);
console.log(company.trainer.subject);
```

---

