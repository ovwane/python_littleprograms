实现单例模式的方法
1.利用__new__静态方法，使他返回相同的对象
2.利用__dict__属性，让所有实例对象不同，但是具有相同的属性
3.利用元类
4.利用类装饰器装饰类，这种方法更优雅
