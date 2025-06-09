| NAME         | TYPE                                 | ATTRIBUTES | INDEX |
| ------------ | ------------------------------------ | ---------- | ----- |
| id           | bigint                               |            |       |
| brand        | varchar(20)                          |            |       |
| Model        | varchar(20)                          |            |       |
| Plate        | char(7)                              |            |       |
| registration | year                                 |            |       |
| color        | varchar(20)                          |            |       |
| km           | int                                  |            |       |
| chassis      | int                                  |            |       |
| condition    | ENUM("km0","usato","N1","aziendali") |            |       |
| crashed      | boolean                              |            |       |
