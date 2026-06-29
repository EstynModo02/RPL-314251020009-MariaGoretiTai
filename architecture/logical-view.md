# Logical View

## Diagram Logical View

```text
               +-------------+
               | Pelanggan   |
               +-------------+
                     |
                     v
               +-----------+
               |   Login   |
               +-----------+
                     |
                     v
             +----------------+
             |   Dashboard    |
             +----------------+
        /-----------|------------\
       /            |             \
      v             v              v
Data Pelanggan Penerimaan Laundry Pembayaran
       |             |              |
       |             v              |
       |      Status Laundry        |
       |             |              |
       \-------------|--------------/
                     |
                     v
                 Database
```

## Penjelasan

Setelah login, admin atau kasir dapat mengelola data pelanggan, menerima cucian, memperbarui status laundry, melakukan pembayaran, dan seluruh data disimpan ke dalam database.
