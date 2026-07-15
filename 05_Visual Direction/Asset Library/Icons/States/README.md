# States

Bu klasör yalnızca gerçekten ihtiyaç duyulan icon state varyantları için kullanılır.

Örnek:

```text
bookmark → default
bookmark-filled → selected

bell → default
bell-filled → active
```

## Kural

- Filled icon sistemi bağımsız bir ikinci icon kütüphanesi değildir.
- Yalnızca selected / active state için üretilir.
- Base geometry korunur.
- State farkı yalnızca renkle verilmez.
