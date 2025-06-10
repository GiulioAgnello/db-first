| NAME         | TYPE                                  | ATTRIBUTES                         | INDEX       |
| ------------ | ------------------------------------- | ---------------------------------- | ----------- |
| id           | BIGINT                                | NOT NULL, A.I, UNSIGNED            | PRIMARY_KEY |
| brand        | VARCHAR(20)                           | NOT NULL, DEFAULT("brand")         | INDEX       |
| Model        | VARCHAR(20)                           | NOT NULL, DEFAULT("model")         | INDEX       |
| Plate        | CHAR(7)                               | NOT NULL, DEFAULT(XX000XX), UNIQUE | INDEX       |
| registration | YEAR                                  | NOT NULL                           | INDEX       |
| color        | ENUM("gray","black","white","silver") | NOT NULL                           |             |
| km           | int                                   | NULL, UNSIGNED                     |             |
| chassis      | int                                   | NOT NULL, UNSIGNED                 | INDEX       |
| used tyoe    | ENUM("km0","usato","N1","aziendali")  | NOT NULL                           | INDEX       |
| crashed      | boolean                               | NULL                               |             |
| price        | FLOAT(9, 3)                           | NOT NULL                           | INDEX       |
