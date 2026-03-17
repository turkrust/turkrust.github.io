% İlişkili Türler (Associated Types)

<small>Kitabın yeni bir sürümü mevcuttur, bu eski bir bağlantıdır.</small>

> İlişkili türler, bir tür yer tutucusunu (type placeholder) davranış yöntemi (trait method) tanımlarının bu yer tutucu türleri kendi imzalarında kullanabilecekleri şekilde iliştirme yoludur.

```rust
pub trait Iterator {
    type Item;
    fn next(&mut self) -> Option<Self::Item>;
}
```

---

Güncel haline bu bağlantıdan ulaşılabilir.
[here](ch20-02-advanced-traits.html#specifying-placeholder-types-in-trait-definitions-with-associated-types).
