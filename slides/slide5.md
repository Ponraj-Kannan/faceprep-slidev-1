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
        width: 107%; max-height: 
        72vh; 
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
        font-size: 1.3rem; 
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
        background-color: #f8fafc;
        border: 1px solid #cbd5e1; 
        border-radius: 4px; 
        padding:10px; 
        margin-top:10px
    }
    .box5{
        margin: 0; 
        font-size:.8rem;
    }
    .box6{
        display: flex;
        flex-direction: row;
        padding: 10px 0px;
    }
    .box7{
        width:40%; 
        padding:0px 10px;

    }
    .box8{
      font-size: 0.7rem;
      border: 1px solid #cbd5e1; border-radius: 4px; padding:2px 10px;
      display: flex; 
      flex-direction:row;
    }
</style>

<div class="box1">
  <div class="box2">
    <h2 class="box3">Java playground</h2>
    <img src="../assets/logo.png"/>
  </div>

  <div class="box4" >
    <p class="box5">What are the different ways to print "Hello World" in Java?</p>
  </div>

  <div class="box6" >
    <JavaRunner/>
    <div  class="box7" >
````md magic-move {duration:500}
```java
System.out.println("Hello World");
```
```java
System.out.print("Hello World");
```
```java
System.out.printf("Hello World");
```
````
    </div>
  </div>
</div>
