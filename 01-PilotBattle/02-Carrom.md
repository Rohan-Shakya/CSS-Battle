# 02 - Carrom

<img height="80px" src="https://cssbattle.dev/targets/2.png"/>

## Solutions

> Brute Force

```
<body bgcolor=#62374e style=margin:0>
<div a>
<div b>
<div c>
<div d>
<style>
    div{
        width:50;
        height:50;
        background:#fdc57b;
        position:fixed;
        top:50
    }
    div[a]{
        left:50
    }
    div[b]{
        right:50
    }
    div[c]{
        left:50;
        top:200
    }
    div[d]{
        right:50;
        top:200
```

> Optimal

```
<style>*{width:50;height:50;background:#fdc57b;margin:25 25;box-shadow:250px 0#fdc57b,250px 150px#fdc57b,0 150px#fdc57b,0 0 0 300px#62374e
```
