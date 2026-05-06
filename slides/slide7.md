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
    <p class="box5">1. Primitive Data Types</p>
  </div>

  <div class="box6" >
    <JavaRunner
      :initialCode="helloCode"
    />
    <div  class="box7" >
````md magic-move [Main.java]
```java
class Main {
    public static void main(String[] args) {
        // your code
    }
}
```
```java
// datatype: byte 
// size: 8-bit 
// range:–128 to 127

class Main {
    public static void main(String[] args) {
        byte a = 1;
        System.out.print(a);
    }
}
```
```java
// datatype: short 
// size: 16-bit 
// range:–32,768 to 32,767

class Main {
    public static void main(String[] args) {
        short a = 130;
        System.out.print(a);
    }
}
```
``java
// datatype: int 
// size: 32-bit 
// range:–2,147,483,648 to 2,147,483,647

class Main {
    public static void main(String[] args) {
        int a = 50000;
        System.out.print(a);
    }
}
```
```java
// datatype: long 
// size: 64-bit 
// range:–9,223,372,036,854,775,808 to 
// 9,223,372,036,854,775,807

class Main {
    public static void main(String[] args) {
        long a = 5000000;
        System.out.print(a);
    }
}
```
``java
// datatype: float 
// size: 32-bit 
// range:–3.40282347E+38f to 
// 3.40282347E+38f

class Main {
    public static void main(String[] args) {
        float a = 12.345f;
        System.out.print(a);
    }
}
```
```java
// datatype: double 
// size: 64-bit 
// range:–1.7976931348623157E+308 to 
// 1.7976931348623157E+308

class Main {
    public static void main(String[] args) {
        double a = 12.345678;
        System.out.print(a);
    }
}
```
``java
// datatype: char 
// size: 16-bit 
// range:–128 to 127

class Main {
    public static void main(String[] args) {
        char a = 'A';
        System.out.print(a);
    }
}
```
```java
// datatype: boolean 
// size: 1-bit 
// range: true or false

class Main {
    public static void main(String[] args) {
        boolean a = true;
        System.out.print(a);
    }
}
```
````
    </div>
  </div>
</div>
