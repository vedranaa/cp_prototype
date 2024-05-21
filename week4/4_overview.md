---
layout: default
---

# Week 4


{%- capture code -%}
print("Hello World!") 

for i in range(5):
    print('hello', i)

while i < 30:
    print(i)
    i = 1.2 * i 

print(f"Oh, no, now I'm {i}")
{%- endcapture %}

{% include tryit.html code=code%}