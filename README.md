# 1、Job
表示一个工作，要执行的具体内容。此接口中只有一个方法
void execute(JobExecutionContext context)
 
# 2、JobDetail
JobDetail表示一个具体的可执行的调度程序，Job是这个可执行程调度程序所要执行的内容，另外JobDetail还包含了这个任务调度的方案和策略。
 
# 3、Trigger
代表一个调度参数的配置，什么时候去调。
 
# 4、Scheduler
代表一个调度容器，一个调度容器中可以注册多个JobDetail和Trigger。当Trigger与JobDetail组合，就可以被Scheduler容器调度了。
