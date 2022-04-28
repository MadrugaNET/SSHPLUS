# SSHPLUS

apt update -y && apt upgrade -y && wget https://raw.githubusercontent.com/MadrugaNET/SSHPLUS/main/Plus && chmod 777 Plus && ./Plus


#Acessa Root

wget https://raw.githubusercontent.com/MadrugaNET/SSHPLUS/main/senharoot.sh && chmod 777 senharoot.sh && ./senharoot.sh


#Comando para corrigir o MENU

cd /bin/ && rm menu && wget https://raw.githubusercontent.com/MadrugaNET/SSHPLUS/main/Modulos/menu && chmod 777 menu


#REMOVER SCRIPT

bash <(wget -qO- https://raw.githubusercontent.com/MadrugaNET/SSHPLUS/main/Modulos/delscript)
