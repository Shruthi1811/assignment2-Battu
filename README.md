# assignment2-Battu
# Shruthi battu
###### New York 
New York is divided into five boroughs  **Brooklyn**, Queens, Staten Island, the Bronx, and the best-known of all, Manhattan. This is where you will find most of the city’s top attractions, such as the Empire State Building, Central Park, Times Square, the Chrysler Building and more. And ferries to the Statue of Liberty on Liberty Island depart from Lower **Manhattan**. And for the best views of Manhattan go to the Top of the Rock at the Rockefeller Centre. As it is most happening place in the world, I like to visit that place.

---

# Directions from Maryville to Newyork
1. It covers a distance of 992.1 miles from Maryville to Newyork through railway transport. 
2. Catch a cab and go to kansas city railway station.
   1. first train is from kansas to columbus .
   2. After reaching columbus, change the platform to t3.
3. After changing the platform we have to travel from columbus to Newyork city.
   1. Catch a train from columbus to Pennsylvania.
   2. After changing the platform at Pennsylvania, catch a train to Newyork at t4 platform.
4. Finally we reach our destination city.

* I would like to carry: 
  * Accessories:
    * Camera
    * Goggles
    * Airpods
  * Drinks:
    * Maaza
    * Sprite
  * Snacks:
    * chips

**[AboutMe.md](AboutMe.md)**

---

# Foods i recommand someone to try

I am going to create a table with at least 4 food items that I would recommend someone try. The food items I would recommend are chicken biryani, pizza, burger, Dal rice.

|food item|location|cost|
|---|---|---|
|Biryani|Bawarchi|9$| 
|pizza|Dominoz|5$|
|Burger|Mcd|4$|
|Dal rice|Sri kanya|6$|

---

# Pithy Quotes

> “Be the change that you wish to see in the world.” ―*Mahatma Gandhi*<Br>
> “Everyone thinks of changing the world, but no one thinks of changing himself.” ―*Leo Tolstoy*

---

# Randomized Heap

> In computer science, a randomized meldable heap (also Meldable Heap or Randomized Meldable Priority Queue) is a priority queue based data structure in which the underlying structure is also a heap-ordered binary tree. However, there are no restrictions on the shape of the underlying binary tree.
   
[Click Here to Know more](https://en.wikipedia.org/wiki/Randomized_meldable_heap)

```
Tree* merge(Tree* t1, Tree* t2) {
    if (!t1 || !t2)
        return t1 ? t1 : t2;
    if (t2->value < t1->value)
        swap(t1, t2);
    if (rand() & 1)
        swap(t1->l, t1->r);
    t1->l = merge(t1->l, t2);
    return t1;
}
```
 
[Code Source](https://cp-algorithms.com/data_structures/randomized_heap.html)