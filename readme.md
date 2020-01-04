# Настройки моего рабочего окружения 
Для начала стоит скопировать данный репозиторий в домашнюю дирректорию
```
git clone https://github.com/bydigizu/myWorkSpace.git
```
## ZSH
Устанавливаем zsh:
```
sudo apt-get install -y zsh
```
Дополнительно рекомендуется установить oh-my-zsh:
```
h -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```
делаем симлинк для .zshrc
```
ln -s myWorkSpace/.zshrc ~/.zshrc
```
## TMUX
Устанавливаем tmux:
```
sudo apt-get install -y tmux
```
Дополнительно рекомендуется установить Oh My Tmux
```
cd
git clone https://github.com/gpakosz/.tmux.git
ln -s -f .tmux/.tmux.conf
cp .tmux/.tmux.conf.local .
```
делаем симлинк для .tmux.conf.local:
```
ln -s myWorkSpace/.tmux.conf.local
```
