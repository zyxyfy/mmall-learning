
**慕课网 《Java大牛 带你从0到上线开发企业级电商项目》 学习**

功能如下：    
    1.用户模块
    
        登录
            login.do
            根据用户名和密码登录，如果登陆成功，存入Session，失败返回登录界面，返回错误信息
        用户名验证
            int checkUsername(String username);
            验证用户名是否存在，
            登录情况下，用户名存在，进行登录
            注册情况下，用户名存在，注册失败
        注册
            register.do
            设置角色，密码MD5加密
        忘记密码
            
        提交问题答案
        重置密码
        获取用户信息
        更新用户信息
        退出登录
            logout.do
            从session中删除登录存入的用户，返回登录界面
        