# Ansible-Instalacao-Promethus
Script Ansible para instalação automatizada de Prometheus em OS Debian ou derivados

### Executando o playbook

* Primeiro adicione o IP dos servidores no arquivos hosts

* Após adicionar o IP dos servidores no arquivos hosts basta executar o comando

* Ansible-playbook -i hosts playbook.yml -K


### Demais observações

* Arquivo hosts contem os IP'S dos servidores para execução do playbook
* Opção -K é para solicitar a senha de root dos servidores que serão acessados para configuração do node exporter

