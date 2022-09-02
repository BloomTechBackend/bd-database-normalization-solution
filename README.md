# Database Normalization

## Solution Tables

<p>

### Customer Table

| Customer Id | Name     |
|-------------|----------|
| 1           | Captain  |
| 2           | Duchess  |
| 3           | Lexi     |

### Product Table

| Product Id | Product   | Product Unit Price |
|------------|-----------|--------------------|
| 1          | Crunchies | 1.00               |
| 2          | Tuna      | 2.00               |
| 3          | Bedding   | 3.00               |
| 4          | Collar    | 5.00               |
| 5          | Cat Toy   | 4.00               |

### Order Table

| Order Id | Customer Id   | Order Number |
|----------|---------------|--------------|
| 1        | 1             | AAA          |
| 2        | 2             | BBB          |
| 3        | 1             | CCC          |

### Order Product Table

| Order Product Id | Order Id | Product Id | Quantity Ordered |
|------------------|----------|------------|------------------|
| 1                | 1        | 1          | 5                |
| 2                | 1        | 2          | 3                |
| 3                | 1        | 3          | 7                |
| 4                | 2        | 1          | 2                |
| 5                | 2        | 2          | 1                |
| 6                | 2        | 4          | 8                |
| 7                | 2        | 5          | 4                |
| 8                | 3        | 5          | 8                |
| 9                | 3        | 2          | 1                |

_Notice that in order 2, COLLAR was ordered twice. These items orders are combined here_

### Location Table

| Location Id | Customer | Location       |
|-------------|----------|----------------|
| 1           | 1        | Cat Tree       |
| 2           | 1        | Living Room    |
| 3           | 2        | Box Fort       |
| 4           | 2        | Kid's Room     |
| 5           | 3        | Cat Tree       |

</p>
