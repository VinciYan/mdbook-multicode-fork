# mdbook-multicode-fork

> This project is a fork of [mdbook-multicode](https://github.com/trindadegm/mdbook-multicode.git) by trindadegm, this fork aims to continue its development and add new features.

Simple plugin to allow multiple language code listings, with a HTML select

## 配置

```
[preprocessor.multicode]
command = "mdbook-multicode"
renderer = ["html"]
```

## 使用

<pre><code>
```rust
fn id<X>(x: X) -> {
    x
}
```

```multicode
>>>>> rust
fn id<X>(x: X) -> {
    x
}
<<<<<
>>>>> cpp
X id<X>(X x) {
    return x;
}
<<<<<
```
</code></pre>

## 效果

移动端也同样支持

![](/screenshot/Snipaste_2024-09-09_15-37-21.png)
![](/screenshot/Snipaste_2024-09-09_15-37-54.png)
![](/screenshot/Snipaste_2024-09-09_15-37-58.png)