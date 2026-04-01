# Math Tools

A self-contained math utility app — 28 tools, zero dependencies, no backend.

## Quick start

### Docker Compose (recommended)
```bash
docker compose up -d
```
Open http://localhost:8080

### Docker (manual)
```bash
docker build -t mathtools .
docker run -d -p 8080:80 --name mathtools mathtools
```
Open http://localhost:8080

### No Docker — just open the file
```bash
open index.html   # macOS
xdg-open index.html  # Linux
```
Works in any modern browser directly from disk.

## Tools included

**Numbers**
- Is it prime? (with neighborhood visualization)
- Base converter (bin / oct / dec / hex)
- Prime factorization + Sieve of Eratosthenes
- Number properties (12 checks: perfect, Armstrong, palindrome…)
- Roman numeral converter
- Scientific / engineering notation
- GCD / LCM
- Modulo + modular exponentiation
- Fibonacci / Lucas / custom sequences

**Math**
- Combinatorics (P, C, n!)
- Fraction calculator (simplify + arithmetic)
- Logarithm & roots (any base, nth root, powers)
- Statistics (mean, median, std dev, IQR…)
- Trigonometry (6 functions + inverses)
- Quadratic equation solver
- 2×2 Matrix (det, inverse, transpose, eigenvalues)

**Geometry**
- Shape calculator (circle, rectangle, triangle, sphere, cylinder, cone…)
- Pythagorean theorem

**Finance**
- Compound interest (with growth chart)
- Tip & bill splitter

**Logic**
- Truth table generator (AND / OR / NOT / XOR / XNOR, up to 4 vars)
- Set operations (union, intersection, difference, symmetric difference)

**Statistics+**
- Normal distribution (bell curve, z-score, CDF)
- Linear regression (scatter plot, R²)

**Fun / Visual**
- Pascal's triangle (with pattern highlights)
- Collatz conjecture (bar chart visualization)

**Conversions**
- Percentage calculator
- Unit converter (length, mass, temp, area, speed, time, digital)
- Random generator (integers, floats, dice, list picker)
