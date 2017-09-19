# flask

## 使用了蓝图以后，注意url_for的函数
  如果蓝图模块是
  main = Blueprint('main', __name__) 
  那对于
  url_for(main.showlogin)  对于站点的url就是 蓝图指定的url前缀比如site/login
