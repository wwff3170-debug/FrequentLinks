# FrequentLinks
常用链接导航网站

## profile
本网页旨在将常用的平 Web 平台链接进行归类，以便于快速查找、修改和导航的功能，可以理解为浏览器中的分类收藏夹。

## Usage
为促进知识传播，特编写以下用法说明，按操作执行即可复现属于自己的链接导航网页。

1.将本仓库 fork 至自己的个人仓库中

2.将 FrequentLinks.csv 文件清空（这个文件相当于数据库，保存各个 Web 平台的链接，可以自行修改）

3.生成外部访问的 API 令牌：点击个人的 Setting (非仓库的Settings) - Developer settings - Personal access tokens - Tokens(classic) , 点击 Generate new token - Generate new token(classic) , 验证通过后，输入 note(随便输入) , Expiration 选择 no expiration , Select scopes 勾选repo , 点击最下方Generate token ，保存好这个生成的 token 。

4.回到 FrequentLinks 仓库中，点击 Setting - Pages ，在这里面发布即可。发布后，这里会出现你的网页URL。

5.复制网站url，打开网页。点击 管理，输入第 3 步生成的 token ，即可进入管理员面板。以后在管理员面板中添加、编辑或删除数据即可，修改的结果会同步到 GitHub 仓库的 FrequentLinks.csv 文件中。

注：管理员面板中修改数据到网页更新通常会有几分钟的延迟，几分钟后重新刷新网页即可。
