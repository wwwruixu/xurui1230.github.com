1.安装 zsh
yum install -y zsh
成功标志：/bin/zsh

2.切换shell由bash切换为zsh
chsh -s /bin/zsh

3.安装oh-my-zsh(需要安装git 可使用 yum install git)
wget https://github.com/robbyrussell/oh-my-zsh/raw/master/tools/install.sh -O - | sh


4.可以在～/.zshrc 中修改或添加配置 例如：主题、环境变量


5.可安装自动提示插件
wget http://mimosa-pudica.net/src/incr-0.2.zsh
mkdir ~/.oh-my-zsh/plugins/incr
mv incr-0.2.zsh ~/.oh-my-zsh/plugins/incr
echo 'source ~/.oh-my-zsh/plugins/incr/incr*.zsh' >> ~/.zshrc
source ~/.zshrc
