<div>
    <h1 style="text-align: center">Bonish-JS</h1>
</div>
<hr>

### Usage

##### Step 1:
Make sure Node.js and Npm is installed. If not [visit here.](https://nodejs.org/en/download)
To verify:
```
node --version
npm --version
```

##### Step 2:
Install the package `bonish-js`
```bash
npm install -g bonish-js
```

##### Step 3:
START BONISHING...
```bash
bonish path-to-your-file.js
```

###### Use the following for an example:
Create a file named `factorial.js` and add following content.
```js
function calculateFactorial(n) {
    if (n === 0) {
        return 1;
    }
    return n * calculateFactorial(n - 1);
}

const number = 5;
const result = calculateFactorial(number);
console.log(`The factorial of ${number} is ${result}`);
```

And now in your terminal,
```bash
bonish ./factorial.js
```

> <strong>YES:</strong> That's IT...