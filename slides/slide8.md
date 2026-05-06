---
layout: default
title: "Program 1: Hello World"
---

<script setup>
const helloCode = `public class Main {
    public static void main(String[] args) {
        // Write your code here
    }
}`;
</script>

<style>
    .box1 {
        margin-top: -10px; 
        margin-left: -30px; 
        padding-bottom: 10px; 
        width: 107%; 
        max-height: 72vh; 
        color:#464646ff;
        background-color: #ffffffff; 
        font-size: .8rem; 
        font-weight: 400; 
        overflow-x: auto; 
        scrollbar-width: none; 
        overflow-y: auto;
    }

    .box2{
        display: flex; 
        flex-direction:row; 
        justify-content: space-between; 
        align-items:center; 
        gap: 0.75rem; 
        padding:0px 10px; 
        color: #ffffff; 
        margin-bottom: 4px; 
    }

    .box2 > img {
        height: 30px;
    }

    .box3{
        margin: 0; 
        font-size: 1.5rem; 
        font-weight: 700; 
        background-color: #ef5050ff; 
        color: #ffffffff; 
        width: 80%; 
        padding-left:10px; 
        margin-left:-10px
    }

    .box4{
        display: flex; 
        align-items: left; 
        gap: 0.75rem;
        border-radius: 4px; 
        padding:10px; 
        margin-top:10px;
        display: flex;
        flex-direction: column;
    }
    .box5{
        margin: 0; 
        font-size:1rem;
    }
    .box6{
        display: flex;
        flex-direction: row;
        padding: 10px 0px;
    }
    .box7{
        width:100%; 
        padding:0px 10px;
        margin-top: 10px;

        display: flex;
        flex-direction: row;
        gap: 10px;
        justify-content: center;
        align-items: center;
    }
    .box8{
        border: 1px solid #cbd5e1; border-radius: 4px; padding:2px 10px;
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        width: 160px;
        height: 100px;
    }
</style>

<div class="box1">
  <div class="box2">
    <h2 class="box3">Java Comments</h2>
    <img src="../assets/logo.png"/>
  </div>

  <div class="box4" style="margin-top:10px">
    <p v-click class="box5" style="padding-top: 10px;">Comments can be used to explain Java code, and to make it more readable. It can also be used to prevent execution when testing alternative code.</p>
    <div v-click class="box5" style="padding-top: 20px; color: #ef5050ff; font-weight: 700;">1. Single-line Comments</div>
    <div v-click class="box5" style="padding-top: 0px;">* Single-line comments start with <code style="weight:800">two forward slashes (//)</code>.</div>
    <div v-click class="box5" style="padding-top: 0px;">* Any text between // and the end of the line is ignored by Java (will not be executed).</div>
   <div v-click class="box7" >
````md magic-move [Example]
```java
class Main {
    public static void main(String[] args) {
        System.out.println("Hello World"); // Prints hello world to the console
    }
}
```
````
    </div>
    <div v-click class="box5" style="padding-top: 20px; color: #ef5050ff; font-weight: 700;">2. Java Multi-line Comments</div>
    <div v-click class="box5" style="padding-top: 0px;">* Multi-line comments <code style="weight:800">start with /* and ends with */</code>.</div>
    <div v-click class="box5" style="padding-top: 0px;">* Any text between /* and */ will be ignored by Java.</div>
    <div v-click class="box7" >
````md magic-move [Example]
```java
class Main {
    public static void main(String[] args) {
        /* The code below will print the words Hello World
            to the screen, and it is amazing */
        System.out.println("Hello World");
    }
}
```
````
    </div>
  </div>
</div>
