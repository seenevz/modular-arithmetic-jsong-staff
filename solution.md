
# Modular Arithmetic

***Note***:
This does not have any test driven exercises. There is no Run Test button and the icon next to the title above has a book instead of a lab. There _are_ code cells below for you to practice concepts, but occassionally lessons won't have tests. On with the show...


### Modular Arithmetic Basics

If you don't remember Modular Arithmetic, it's this function in Python

```python
39 % 12
```

The result is 3 because that is the remainder after division (39 / 12 == 3 + 3/12).

Some people like to call it "wrap-around" math. If it helps, think of modular arithmetic like a clock:

![clock](http://latex.artofproblemsolving.com/f/4/d/f4daa2601de14fddf3d8441e16cc322a25e85354.png)

Think of taking the modulo as asking the question "what hour will it be 39 hours from now?"

If you're still confused, please take a look at [this](https://www.khanacademy.org/computing/computer-science/cryptography/modarithmetic/a/what-is-modular-arithmetic) article.


```python
print(39 % 12)
```

### Exercise

Find the modulo 19 of these numbers:

* 99
* \\(456 \cdot 444\\)
* \\(9^{77}\\)

(note python uses ** to do exponentiation)


```python
prime = 19
print(99 % prime)
print(456*444 % prime)
print(9**77 % prime)
```
