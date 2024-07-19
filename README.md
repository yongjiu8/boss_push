## Boss Push v1.2.4

## 忒星boss直聘批量简历投递+自动发送自定义消息

# 原作者：https://github.com/yangfeng20/boss_batch_push

### 使用步骤

1. 浏览器下载油猴：https://www.tampermonkey.net/index.php?ext=iikm
2. 添加新脚本，复制 【main.js】 中的代码，粘贴到油猴脚本中
或者点击 https://greasyfork.org/zh-CN/scripts?q=%E5%BF%92%E6%98%9Fboss%E7%9B%B4%E8%81%98%E6%89%B9%E9%87%8F%E7%AE%80%E5%8E%86%E6%8A%95%E9%80%92 安装脚本

### 使用说明

# 建议关闭boss自动打招呼语，发送突出自己特长的招呼语，以获得面试官青睐

![示例](/imgs/close.png)

![示例](/imgs/plane.png)

![示例](/imgs/message.png)

1. 批量投递：点击批量投递开始批量投简历，请先通过上方 Boss 的筛选功能筛选大致的范围，然后通过脚本的筛选进一步确认投递目 标。

2. 生成Job词云图：获取当前页面的所有job详情，并进行分词权重分析；生成岗位热点词汇词云图；帮助分析简历匹配度。

3. 保存配置：保持下方脚本筛选项，用于后续直接使用当前配置。

4. 过滤不活跃 Boss：打开后会自动过滤掉最近未活跃的 Boss 发布的工作。以免浪费每天的 100 次机会。

5. 发送自定义招呼语：因为boss不支持将自定义的招呼语设置为默认招呼语。开启表示发送boss默认的招呼语后还会发送自定义招呼语

6. 过滤猎头岗位：打开后会自动过滤掉猎头发布的工作。猎头的岗位要求一般都非常高，实际投此类岗位是无意义的，以免浪费每天的100次机会。

7. 可以在网站管理中打开通知权限,当停止时会自动发送桌面端通知提醒。

#### 脚本筛选项介绍：

1. 公司名包含：投递工作的公司名一定包含在当前集合中，模糊匹配，多个使用逗号分割。这个一般不用，如果使用了也就代表只投这 些公司的岗位。例子：【阿里,华为】

2. 排除公司名：投递工作的公司名一定不在当前集合中，也就是排除当前集合中的公司，模糊匹配，多个使用逗号分割。例子：【xxx 外包】

3. 排除工作内容：会自动检测上文(不是,不,无需等关键字),下文(系统,工具),例子：【外包,上门,销售,驾照】，如果写着是'不是外包''销售系统'那也不会被排除

4. Job 名包含：投递工作的名称一定包含在当前集合中，模糊匹配，多个使用逗号分割。例如：【软件,Java,后端,服务端,开发,后台】

5. 薪资范围：投递工作的薪资范围一定在当前区间中，一定是区间，使用-连接范围。例如：【12-20】

6. 公司规模范围：投递工作的公司人员范围一定在当前区间中，一定是区间，使用-连接范围。例如：【500-20000000】

7. 自定义招呼语：编辑自定义招呼语，当【发送自定义招呼语】打开时，投递后发送boss默认的招呼语后还会发送自定义招呼语；使用&lt;br&gt; \n 换行；例子：【你好\n我...】

8. 过滤猎头岗位：打开后会自动过滤掉猎头发布的工作。猎头的岗位要求一般都非常高，实际投此类岗位是无意义的，以免浪费每天的100次机会。

### 效果演示

![示例](/imgs/home.png)

### 更新内容

##### 2024-07-19/yongjiu8（忒星）

- 修复boss更新导致的投递失败

##### 2024-04-12/bai-xuan

- 新增HR是否在线功能

##### 2024-03-12/yongjiu8（忒星）

- 新增过滤猎头岗位
- ![示例](/imgs/headhunter.png)

##### 2023-12-1/yongjiu8（忒星）

- 修复发送自定义打招呼语大部分发送失败（还是会有几个发送失败)

##### 2023-11-29/yongjiu8（忒星）

- 修复发送自定义打招呼语

