# Objetos

São

## O que pode colocar num objeto

```javascript
let user = {
  name: "Bryan",
  age: 30,
  gender: "male",
  hobbies: ["jogging", "gaming", "cycling"],
  favoriteBook: {
    title: "1984",
    gender: "fiction"
  },
  print: function(what) {
    return `I want um ${what}`
  }
}

console.log(user.name)
// Bryan

console.log(user.print("refri"))
// I want um refri
```

## Acessando chaves do objeto

## Acessando valores do objeto

```javascript
let user = {
  name: "Bryan",
  age: 30,
  gender: "male",
  hobbies: ["jogging", "gaming", "cycling"],
  favoriteBook: {
    title: "1984",
    gender: "fiction"
  },
  print: function(what) {
    console.log(`I want um ${what}`)
  }
}

console.log(user.name)
// Bryan

console.log(user.favoriteBook.title)
// 1984

console.log(user["age"])
// 30

let key = "hobbies"
console.log(user[key])
// ["jogging", "gaming", "cycling"]
```
