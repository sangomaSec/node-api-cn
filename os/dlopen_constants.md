
如果下面提到的常量在操作系统上是可用的,那么他们将被拓展到 `os.constants.dlopen`. 详细信息请参阅dlopen(3) 
<table>
  <tr>
    <th>常量</th>
    <th>描述</th>
  </tr>
  <tr>
    <td><code>RTLD_LAZY</code></td>
    <td>执行惰性绑定. Node.js将这个标识设置为缺省.</td>
  </tr>
  <tr>
    <td><code>RTLD_NOW</code></td>
    <td>在 dlopen(3) 返回之前在库中处理所有未声明的标识</td>
  </tr>
  <tr>
    <td><code>RTLD_GLOBAL</code></td>
    <td>在库中声明的标志将被用于随后加载的库的符号解析。</td>
  </tr>
  <tr>
    <td><code>RTLD_LOCAL</code></td>
    <td>与`RTLD_GLOBAL`相反。 如果没有标志被指定，那么它将是那个默认执行的。</td>
  </tr>
  <tr>
    <td><code>RTLD_DEEPBIND</code></td>
    <td>使一个独立的库优先使用它自己的符号，而不是先前加载的库。</td>
  </tr>
</table>

