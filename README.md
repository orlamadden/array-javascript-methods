# Array methods in Javascript

.pop() - Removes the last element in an array and returns the removed element (it changes the array length)
```Javascript
const pokemon = ['pikachu', 'squirtle', 'charmander', 'ghastly', 'pidgey', 'growlithe'];
pokemon.pop(); // growlithe
console.log(pokemon); // now displays ['pikachu', 'squirtle', 'charmander', 'ghastly', 'pidgey']
```

.push() - Adds new item to the beginning of an array, returns the new length of array (it chnges the length of the array)
```Javascript
const pokemon = ['pikachu', 'squirtle', 'charmander', 'ghastly', 'pidgey', 'growlithe'];
pokemon.push('ditto');
console.log(pokemon); // now displays ['pikachu', 'squirtle', 'charmander', 'ghastly', 'pidgey']
```