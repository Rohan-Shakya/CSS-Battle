# 19 - Cube

<img height="100px" src="https://cssbattle.dev/targets/19.png"/>

## Solutions

> Brute Force

```
<div class="b">
</div>
<div class="l s">
</div>
<div class="r s">
<style>
  *{background:#0B2429}
  div{
    position:absolute;
    width:100;
    height:100;
    background:#dd6b4d
  }
  .b{
    transform:rotate(45deg);
    background:#F3AC3C;
    left:150;
    bottom:65
  }
  .s{
    width:70;
    height:70;
    top:80
  }
  .r{
    transform:skewY(45deg);
    left:50%;
    background:#1A4341
  }
  .l{
    transform:skewY(-45deg);
    right:50%;
    background:#998235
```

> Optimal

```
<div class="b"></div><div class="l s"></div><div class="r s"><style>*{background: #0B2429}div{position:absolute;width:100;height:100;background:#dd6b4d}.b{transform:rotate(45deg);background:#F3AC3C;left:150;bottom:65}.s{width:70;height:70;top:80}.r{transform:skewY(45deg);left:50%;background:#1A4341}.l{transform:skewY(-45deg);right:50%;background:#998235
```
