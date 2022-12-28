# try语法升级

在Java 8中可以将需要需要被关闭的资源写在try关键字的括号内，在使用完毕后资源会被自动关闭。

<figure><img src="../.gitbook/assets/image (3).png" alt=""><figcaption><p>Java 8 自动关闭流图例</p></figcaption></figure>

但在Java 9后该语法进行了一些升级，自动关闭资源语句的写法将变的更容易，我们可以用`try包裹住已经被初始化过的资源，但限制该资源必须是**final**的。`

<figure><img src="../.gitbook/assets/image (4).png" alt=""><figcaption><p>Java 9 自动关闭流图例</p></figcaption></figure>
