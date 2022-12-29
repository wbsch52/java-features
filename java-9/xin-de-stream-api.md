# 新的Stream API

在Java 9中Stream新增了以下几个API：

*   **takeWhile**

    该方法接受一个Predicate对象用于过滤Stream中的元素，与filter不同的是，takeWhile在迭代过程中当遇到第一个false时会立即中断。

<figure><img src="../.gitbook/assets/image (3).png" alt=""><figcaption><p>takeWhile代码示例</p></figcaption></figure>

*   **dropWhile**

    与takeWhile相反，dropWhile会丢弃所有符合条件的元素，但当遇到第一个false时也会立马中断，并包含当前元素及其之后的所有元素。

<figure><img src="../.gitbook/assets/image (6).png" alt=""><figcaption><p>dropWhile代码示例</p></figcaption></figure>

*   **ofNullable**

    该方法允许我们创建一个可能为null的单一Stream流。

<figure><img src="../.gitbook/assets/image (8).png" alt=""><figcaption><p>ofNullable代码示例</p></figcaption></figure>

*   **iterate**

    这是一个重载方法，方法签名为：

    * T seed
    * Predicate hasNext
    * UnaryOperator next

    允许我们通过Predicate控制什么时候结束迭代。

<figure><img src="../.gitbook/assets/image (5).png" alt=""><figcaption><p>iterate代码示例</p></figcaption></figure>
