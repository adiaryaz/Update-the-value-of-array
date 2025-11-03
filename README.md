# Update the value of array

A program to modify a 1-dimensional array (list) of integers based on the index of each element.

## 📝 Description

This program takes a single 1-dimensional array of integers as input. It then iterates through the array, applying a specific modification rule to each element based on its position (index).

-----

## 🎯 Problem Statement

### Input:

  * A single 1-dimensional array (list) of integers.

### Output:

  * The modified array (list) after applying the rules.
  * "Cannot modify; the array is empty." if the input array is empty.

### Rules:

1.  The program must read an array of integers.
2.  If the array is empty (`[]`), the program must output the error message "Cannot modify; the array is empty."
3.  If the index of an element is **even** (0, 2, 4, ...), its value must be **doubled** (value = value \* 2).
4.  If the index of an element is **odd** (1, 3, 5, ...), its value must be **decremented by 1** (value = value - 1).
5.  The program must handle single-element arrays (which will only have an even index, 0).

-----

## 💡 Examples

### Example 1 (Sample 1)

**Input:**

```
[5, 8, 10, 3, 7]
```

**Output:**

```
[10, 7, 20, 2, 14]
```

**Explanation:**

  * Index 0 (even): `5 * 2 = 10`
  * Index 1 (odd): `8 - 1 = 7`
  * Index 2 (even): `10 * 2 = 20`
  * Index 3 (odd): `3 - 1 = 2`
  * Index 4 (even): `7 * 2 = 14`

### Example 2 (Sample 2)

**Input:**

```
[4, 9, 12, 15, 20]
```

**Output:**

```
[8, 8, 24, 14, 40]
```

**Explanation:**

  * Index 0 (even): `4 * 2 = 8`
  * Index 1 (odd): `9 - 1 = 8`
  * Index 2 (even): `12 * 2 = 24`
  * Index 3 (odd): `15 - 1 = 14`
  * Index 4 (even): `20 * 2 = 40`

### Example 3 (Sample 4 - Single Element)

**Input:**

```
[3]
```

**Output:**

```
[6]
```

**Explanation:** The only element is at index 0 (even), so `3 * 2 = 6`.

### Example 4 (Sample 6 - Empty Array)

**Input:**

```
[]
```

**Output:**

```
Cannot modify; the array is empty.
```

**Explanation:** The array is empty, so no modifications can be performed.

-----

## 🚀 How to Use

1.  **Clone this repository**

    ```bash
    git clone https://github.com/adiaryaz/array-index-update.git
    cd array-index-update
    ```

2.  **Run the program** (assuming the file is `main.py`):

    ```bash
    python main.py
    ```

    Enter the array in list format (e.g., `[5, 8, 10]`) when prompted to see the result.
