# ZQN的自动化测试

- config 配置文件
- -database 数据库配置
- driver 驱动配置(查询MySQL 和 Redis等方法)
- logs 日志目录
- package 用于存放自动化测试扩展包，例：HTMLTestRunner.py。
- public 公共文件
- report 测试报告（用于存放HTML测试报告，在其下面创建了image目录存放截图）
- testcase 测试用例代码
- testdata 测试数据
- utils 公共方法 （所有的支撑代码都在这里，包括读取config的类、写log的类、读取excel、xml的类、生成报告的类（如HTMLTestRunner）等类和方法，都在这里）
