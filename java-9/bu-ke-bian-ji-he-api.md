# 不可变集合API

在Java 9中List、Set、Map新增了一系列名为of的method，可以通过该方法快速创建不可变集合。

<figure><img src="../.gitbook/assets/image (7).png" alt=""><figcaption><p>快速创建不可变集合</p></figcaption></figure>

而在Java 9之前我们需要通过`Collections.unmodifiableXXX`方法将可变集合转换成不可变集合。

<figure><img src="../.gitbook/assets/image (10).png" alt=""><figcaption><p>Java 8创建不可变集合写法</p></figcaption></figure>
