1. DH算法简介
   - 由Diffie和Hellen提出，是最早的公钥密码系统
   - 优点：需要时才生成，减少被攻击的机会；除了约定全局参数不需要约定其他的
   - 缺点：容易遭受中间人攻击
2. 算法过程  
   1. 选择一个大素数p,并计算出它的本元根a
   2. 用户A,B建立连接,用户A从1到p-1中选出Xa,用户B从1到p-1中选出Xb
   3. 用户A通过计算Ya=a^Xamodp得出Ya,并发给用户B
   4. 用户B通过计算Yb=a^Xbmodp得出Yb,并发给用户A
   5. 用户A计算K=Yb^Xamodp,用户B计算k=Ya^Xbmodp,得出共享秘钥K

3. 测试结果
   - 结果1
   - ![](fifthPictrue\DH1.png)
   - 结果2
   - ![](fifthPictrue\DH2.png)
