
### 1.新建ceshi1目录文件夹,将c.box文件复制到ceshi1文件目录下
```markdown
D:\Linux_env\ceshi1
D:\Linux_env\ceshi1\c.box
```

### 2.cmd到`D:\Linux_env\ceshi1`目录下，运行如下命令后生成配置文件
```markdown
vagrant box add ceshi1 c.box

安装成功提示：
==> box: Adding box 'ceshi1' (v0) for provider:
    box: Downloading: file://D:/Linux_env/ceshi1/c.box
    box: Progress: 100% (Rate: 512M/s, Estimated time remaining: --:--:--)
==> box: Successfully added box 'ceshi1' (v0) for 'virtualbox'!
```

### 3.步骤2执行成功后，初始化配置文件
```markdown
vagrant init

成功提示：
A `Vagrantfile` has been placed in this directory. You are now
ready to `vagrant up` your first virtual environment! Please read
the comments in the Vagrantfile as well as documentation on
`vagrantup.com` for more information on using Vagrant.
```

### 4.更改生成后，Vagrantfile配置文件`vm.box名字为ceshi1`
```markdown
config.vm.box = "ceshi1"
```

### 5.启动ceshi1, `VirtualBox虚拟机`
*   重新打开一个新的cmd窗口，cd到：`D:\Linux_env\ceshi1`, 输入以下命令
```markdown
vagrant up
``` 
