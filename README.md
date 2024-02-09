
> a1 = {'a','b','c','d'}
> a1
{'d', 'a', 'b', 'c'}
> a2 = {'a','b','e','f'}
> a2
{'b', 'a', 'f', 'e'}
> a1.update(a2)
> a1
{'d', 'b', 'f', 'e', 'a', 'c'}
> a1.difference_update(a2)
> a1
{'d', 'c'}
> a2.difference_update(a1)
> a2
{'b', 'a', 'f', 'e'}
> a1.symmetric_difference_update(a2)
> b1 = { 'g','h','i','j'}
> b1
{'j', 'g', 'i', 'h'}
> b2 = { 'g','h','k','l'}
> b2
{'k', 'g', 'l', 'h'}
> b1.symmetric_difference_update(b2)
> b1
{'k', 'i', 'l', 'j'}
> b1.intersection_update(b2)
> b1
{'k', 'l'}
> b2.intersection_update(b1)
> b2
{'k', 'l'}
> 
> 
