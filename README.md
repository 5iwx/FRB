# 1 文件目录:

- example: 本地编译结果放在这, 命名为:'姓名-创建日期'

- include_picture: 插入的图片放在这, 注意命名

- include_tex: 插入的其他tex模块放这里

### 1.1 分支:

- scenario: 场景分支, by czh/yjw
- theory: 理论分支, by wcx/swt

    大版本再将场景和理论合并

***

# 2 用法:

> 首次使用:
> 
> 1. `git clone`把远程仓库下载到本地, 然后把模板(zip中全部文件)复制到仓库文件夹内, 命名重复的全部不替换
> 
> 2. 向仓库所有者提出"成为合作者"请求, 将自己的github用户名或邮箱发给他, 等他同意你成为合作者, 你就可以提交代码了.

1. **每次编辑前先`git pull`一下**, 有冲突就本地合并 (手动选择>>>>标识的冲突部分, 然后commit即可)

2. 创作内容...
   
   - 图片放在`./include_picture`
   
   - 本地编译结果pdf文件也要一并上传, 为别人作参考(检查自己对他人的tex编译结果是否正常) 放在`./example`中

3. `git push`

### 分支使用:

0. 查看远程分支 `git branch -r`
1. 首先在本地创建一个分支, 以scenario为例:`git checkout -b scenario origin/scenario`
    通过这种方式, 同时可以将scenario绑定在远程分支origin/scenario上
2. 修改分支
3. `git push origin scenario`

***

# 3 日志
- 2023-03-31, 5iwx, 更新了example, 主tex。理论部分推进1小节（s: RS编码）

- 2023-03-29, 5iwx，更新了example, include_picture, 主tex。理论部分进度：大约完成了5/12。

  分工：s: 诚实验证方前提的零知识证明，交互式谕示机证明；w: 单变量求和校验协议，低度检测和FRI，默克尔树

- 2023-03-29, 将理论部分和场景部分分为两个分支, 分开开发

- 2023-03-29, [usr_name], 这里写一些除了commit msg外还想交代的, 这里是栈, 新行添加在上方🚀
