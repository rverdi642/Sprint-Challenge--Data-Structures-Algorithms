Add your answers to the Algorithms exercises here.


Exercise I

a) O(n)

b) O(n^3)

c) O(n)

Exercise II

probably a quick sort approach, partition the floors (fl),

 fl_base = math.ceil(fl_above/2)
 top = floors
 bottom = 1
 broken_eggs = 0

 flUp()
    bottom = fl_base
    floors above = top - bottom
 flDown()
        top = fl_base
        floor_below = top - bottom
        fl_base -= math.ceil(floor_below / 2)


 while fl_base
if broken egg call flDown

elif fl_base > fl
    broken_eggs = 0
    flUp
else
flDown
