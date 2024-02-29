
У цьому дослідженні було порівняно чотири алгоритми сортування: сортування злиттям, сортування вставками та Timsort (sort і sorted). Для цього були проведені емпіричні тести на трьох різних наборах даних: Small, Medium та Large.


## Висновки

1. **Timsort** виявився набагато ефективнішим за часом виконання порівняно з обома іншими алгоритмами на всіх розмірах наборів даних. Це підтверджується як на малих, так і на великих обсягах даних.

2. **Сортування злиттям** показує добрі результати на середніх розмірах даних, але стає менш ефективним на великих обсягах через свою складність O(n log n).

3. **Сортування вставками** є найповільнішим алгоритмом у всіх випадках, особливо на великих наборах даних, оскільки має складність O(n^2).

Отже, використання вбудованого алгоритму Timsort виявляється найбільш доцільним у більшості випадків, оскільки він комбінує в собі ефективність сортування злиттям і вставками.
