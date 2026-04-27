* git clone https://github.com/ahmetb/kubectx.git ~/.kubectx
* COMPDIR=$(pkg-config --variable=completionsdir bash-completion)
* ln -sf ~/.kubectx/completion/kubens.bash $COMPDIR/kubens
* ln -sf ~/.kubectx/completion/kubectx.bash $COMPDIR/kubectx
* cat << EOF >> ~/.bashrc


#kubectx and kubens
* export PATH=~/.kubectx:$PATH
* EOF

* curl -sS https://webinstall.dev/k9s | bash   #imp
* enter l -> to check logs
* esc -> to come to back
* Shift+: -> to serach for something