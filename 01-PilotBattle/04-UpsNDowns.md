# 04 - Ups n Downs

<img height="80px" src="https://cssbattle.dev/targets/4.png"/>

## Solutions

> Brute Force

```
<body bgcolor=#62306D>
<div>
  <p a>
  <p b>
  <p c>
<style>p{
  position:fixed;
  top:100;
  left:50%;
  transform:translate(-50%,-50%);
  width:100;
  height:100;
  background:#F7EC7D;
  border-top-left-radius:50%;
  border-top-right-radius:50%}
  p[a],p[c]{
    border-radius:0;
    border-bottom-left-radius:50%;
    border-bottom-right-radius:50%;
    margin-top:100;
    left:calc(50% - 100px)
  }
  p[c]{
    left:calc(50% + 100px)
  }
  p[b]{
    top:28%
```

> Optimal

```
<p><p i><style>*{background:#62306D;}p{width:100;height:100;background:#F7EC7D;margin:50 142;border-radius:50px 50px 0 0}[i]{margin:-50 242;transform:rotate(180deg);box-shadow:200px 0#F7EC7D
```
