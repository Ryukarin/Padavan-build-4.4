# Padavan-build说明

### 步骤：

1. 点击右上角的【Fork】按钮，进入自己fork后的仓库。

2. 修改`/workflows/build-padavan.yml`里的插件与机型。修改***TNAME: K2P***中的**K2P**为需要编译的型号，注意名称要与`configs/templates/`目录下的名字
相同。修改后【commit changes】保存。

3. 点击页面上部的【Actions】按钮，点击【I understand my workflows，go ahead and enable them】绿色按钮启用action。

4. 点击右上角的【Star】星星按钮即可开始自动编译（自己点击才会编译）。修改配置后若需再次编译，先点击【Star】取消Star后，再点击【Star】即可重新编译。

编译完成后在Actions页面底部下载固件。
