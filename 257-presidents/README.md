# Solution

```elixir
iex(1)> Pres.run("data.csv")
[{1824, 18}, {1834, 18}, {1831, 18}, {1844, 18}, {1839, 18},
 {1826, 18}, {1837, 18}, {1838, 18}, {1841, 18}, {1835, 18},
 {1845, 18}, {1843, 18}, {1840, 18}, {1822, 18}, {1825, 18},
 {1836, 18}, {1823, 18}, {1833, 18}, {1829, 17}, {1830, 17},
 {1859, 17}, {1846, 17}, {1832, 17}, {1862, 17}, {1842, 17},
 {1847, 17}, {1861, 17}, {1848, 17}, {1858, 17}, {1860, 17},
 {1821, 16}, {1816, 16}, {1809, 16}, {1865, 16}, {1817, 16},
 {1811, 16}, {1849, 16}, {1815, 16}, {1827, 16}, {1818, 16},
 {1813, 16}, {1812, 16}, {1810, 16}, {1820, 16}, {1814, 16},
 {1857, 16}, {1828, 16}, {1819, 16}, {1867, ...}, {...}, ...]
```

## Answer

Results are the format: {"year", "count"}.
Various years each had 18 living presidents.

```
{1824, 18}, {1834, 18}, {1831, 18}, {1844, 18}, {1839, 18},
{1826, 18}, {1837, 18}, {1838, 18}, {1841, 18}, {1835, 18},
{1845, 18}, {1843, 18}, {1840, 18}, {1822, 18}, {1825, 18},
{1836, 18}, {1823, 18}, {1833, 18}
 ```