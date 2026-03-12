# Firewall com iptables

Permitir SSH:

sudo iptables -A INPUT -p tcp --dport 22 -j ACCEPT

Listar regras:

sudo iptables -L
