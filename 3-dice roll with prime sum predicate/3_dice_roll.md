# Comic book Grade <!-- omit in toc -->

- [Task](#task)
- [Scoring reference](#scoring-reference)
- [Score Recording](#score-recording)

## Task

determine the probability that the sum of a three-dice roll is prime:

```python
D = {1,2,3,4,5,6}

D3 = {(d1, d2, d3) for d1 in D for d2 in D for d3 in D}

def prime_sum(outcome): return is_prime(sum(outcome))

def is_prime(n): return ...  # implement is_prime()!

p(prime_sum, D3)
```

Go ahead, please implement is_prime(), a predicate function

## Scoring reference

|Requirement|Ratio|
|-|-|
Code submission|50 %
No late| 40%
Simple as professor's solution| 10%

## Score Recording

Name|NUID|Code submission|No late|Simple as professor's solution|Grade|
|-|-|-|-|-|-|
Anh Dao|001532403S|50|0 (overdue)|10 (copy from lecture)|60|
Xuejiao Dong|001569734S|50|40|10|100|
Hung-Chih Huang|001005756S|50|40|5|95|
Archil Lelashvili|001522269S|50|40|10|100|
Hongji Luo|001306756S|50|40|5|95|
Sumit Malbari|001526279S|50|40|8 (Same soluction but not in ```[... for ... in ...]``` format)|98|
Riya Moitra|001528940S|50|40|8 (Same soluction but not in ```[... for ... in ...]``` format)|98|
David Nallapu|001530978|50|40|8 (Same soluction but not in ```[... for ... in ...]``` format)|98|
Monali Patel|001044316S|50|40|8 (Same soluction but not in ```[... for ... in ...]``` format)|98|
Prerana Urs Praveen Kumar Urs|001553207S|50|40|5|95|
Shanzizhi Shang|001085151S|50|40|8 (Same soluction but not in ```[... for ... in ...]``` format)|98|
Hongyao Tao|001067209S|50|40|8 (Same soluction but not in ```[... for ... in ...]``` format)|98|
Cong Wang|001002178S|50|40|8 (Same soluction but not in ```[... for ... in ...]``` format)|98|
Jian Xiao|001901943S|50|40|8 (Same soluction but not in ```[... for ... in ...]``` format)|98|
Yuxuan Yang|001389098S|50|40|8 (Same soluction but not in ```[... for ... in ...]``` format)|98|
Zhi Yao|001520706S|50|40|8 (Same soluction but not in ```[... for ... in ...]``` format)|98|
Tianhui Zhang|001566190S|50|40|8 (Same soluction but not in ```[... for ... in ...]``` format)|98|
Qixiang Zhou|001822974S|50|40|8 (Same soluction but not in ```[... for ... in ...]``` format)|98|