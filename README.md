# Ansible-Instalacao-Promethus
Script Ansible para instalação automatizada de Prometheus em OS Debian ou derivados

### Executando o playbook

* Primeiro passo será adicionar os IP's dos servidores qual vamos instalar o Prometheus no arquivos hosts

* Após adicionar os IP's dos servidores no arquivos hosts basta executar o comando abaixo

* Ansible-playbook -i hosts playbook.yml -K


### Demais observações

* Arquivo hosts contem os IP'S dos servidores para execução do playbook
* Opção -K é para solicitar a senha de root dos servidores que serão acessados para configuração do node exporter

