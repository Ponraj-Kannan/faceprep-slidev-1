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
    <h2 class="box3">Declaring (Creating) Variables</h2>
    <img src="../assets/logo.png"/>
  </div>

  <div class="box4" style="margin-top:10px">
    <div v-click class="box5" style="padding-top: 0px;">To declare a variable in Java, follow these steps:</div>
    <div v-click class="box5" style="padding-top: 0px;">* Select an appropriate data type (such as int or String)</div>
    <div v-click class="box5" style="padding-top: 0px;">* Provide a meaningful name for the variable (for example: x, age, or name)</div>
    <div v-click class="box5" style="padding-top: 0px;">* Use the assignment operator (<code style="weight:800">=</code>) to give the variable a value. This is also called initializing a variable.</div>
    <div v-click class="box5" style="color:#ef5050ff; font-weight:700"><code>type variableName = value;</code></div>
<div class="box6" >
    <JavaRunner v-click
      :initialCode="helloCode"
    />
    <div v-click class="box7" style="margin-top:-180px">
```java
class Main {
    public static void main(String[] args) {
        String company = "FacePrep";
        System.out.println(company);
    }
}
```
</div>
    </div>
  </div>
</div>
