BUILDING MY VUE APPLICATION
JS - user interactivity & reactivity

*User interactivity* - allowing a user to interact with an application through user 
 based actions(events) e.g. click , scroll, fill forms , zoom, focus,submit forms
*Reactivity* - JS automatically updating data e.g. add a product and JS updates a products table with that product
 

*static application* - no data changes
*dynamic application* - an application automatically updating based on data changes

data() -> a place to store values that Vue shows and updates on the screen
-> it returns an object containing values you want displayed in html
data -> UI (reactivity)

*v-model*
1.get input from the user
2. update your vue data automatically

input <-> data <-> ui

*two-way bidnding*  - typing updates data, data updates screen
*data modelling*
 -> data cant be a single value - its a structure

 *dynamic lists* - displaying data from an array using Vue 
  -> to do this we use v-for  
*v-for* 
is used to loop through data 

let items = ["mango","apple","banana"]

<li v-for="item in items" > {{items}}</li>

items - your array
item - each value inside the array

mango
apple
banana

*methods()* - actions that your app performs - (functions)
*created()* - 

aysnc & await

interpreted languages - Python , JS ,PHP ,Ruby - execute line by line
compiled languages  - C++ , java ,c#, c , Go,Rust - executes the program as a whole through an entry main

aysnc - used to handle operations that take time without blocking your program

synchronous vs asynchronous
what does aync solve: it lets your program start a task, continue doing other things and come back 
when the task is done

async - marks a function as asynchronous
      - it automatically returns a promise

await - pauses only that function until a reuslt is ready 
     -> DONT block the whole program

*promise* - represents a value that will be available later