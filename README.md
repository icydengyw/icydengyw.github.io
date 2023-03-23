# 极简版主页，去除了花里胡哨的东西，直接修改就行
# 使用方法
## 一. fork到自己的github中
### 1.注册一个 GitHub 帐户并确认您的电子邮件（必需！），注册时最好设置GitHub username都为小写
### 2.单击右上角的“fork”按钮
### 3.转到存储库的设置，修改名字为[your GitHub username].github.io", 这也将是您网站的网址（URL）,名字必须与GitHub username名字一至，包括大小写一致，实际上名字只能都是小写，如果不行就改下GitHub username名字


# 修改方法
## 一、修改主页内容
### 1. 主页中的文字内容在`_pages`文件夹中的`about.md`中编辑
### 2. 修改导航菜单需要修改`_data`文件夹中的`navigation.yml`文件
### 3. 修改左侧内容方法
1. 修改照片，照片名字与`_config.yml`文件中84行`avatar`后的图片名字一样，图片需为正方形存放在`images`文件夹下
2. 修改根目录根目录中的`_config.yml`文件，直接在对应的位置写入链接
3. 如果没有需要的名称  
a. 在`_includes`文件夹中的`author-profile.html`文件内添加对应的行，网页中显示的图标、名称均在这里修改   
b. 图标存放到`images`文件夹下，名字与之对应  
c. 修改根目录根目录中的`_config.yml`文件，写下名称和链接

## 二、修改其它页
修改`_pages`文件夹中的`education.md`、`publications.md`、`programs.md`、`honors.md`、`practice.md`、`techinical.md`对应文件。

## 三、修改脚注
### 1. 修改更新时间
修改`_includes\footer`文件夹中的`custom.html`中的update时间。

# 欢迎访问我的主页： <a href="https://icydengyw.github.io/">https://icydengyw.github.io/</a>

