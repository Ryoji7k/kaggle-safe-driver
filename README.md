## 環境構築
- apt update
- apt install git emacs build-essential tmux htop
- wget https://repo.anaconda.com/archive/Anaconda3-2019.10-Linux-x86_64.sh
- sh Anaconda3-2019.10-Linux-x86_64.sh
- source .bashrc

## その他
- 処理時間が掛かるものについては `tmux` でsession管理すること
- Emacs（spacemacs）設定
    - package install
        - company
        - yasnippet
    - .spacemacsの下記に設定を書き込む
        - dotspacemacs-additional-packages
        - defun dotspacemacs/user-config
