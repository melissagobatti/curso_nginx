# curso_nginx
Alta Disponibilidade com Nginx

Nginx (lê-se "engine x") é um servidor leve de HTTP, proxy reverso, proxy de e-mail IMAP/POP3, feito por Igor Sysoev em 2005, sob licença BSD-like 2-clause.

O Nginx consome menos memória que o Apache, pois lida com requisições Web do tipo “event-based web server”; e o Apache é baseado no “process-based server”, podendo trabalhar juntos. É possível diminuir o consumo de memória do Apache, passando as requisições Web primeiro no Nginx, assim, o Apache não precisa servir arquivos estáticos, e pode depender do bom controle de cache feito pelo Nginx.[3]

O Wikipedia utiliza Nginx como um servidor de terminação SSL, o qual é responsável por receber requisições TLS, e repassar para outros servidores na rede, diminuído assim a carga sobre outros servidores.[4]

Desde a versão 5.2, o sistema operacional OpenBSD utiliza o Nginx como parte do sistema base, provendo uma alternativa ao fork do Apache 1.3 que o sistema utilizava, o qual o Nginx tinha como finalidade substituir[5], mas que acabou sendo subtituido por uma implementação própria de httpd
