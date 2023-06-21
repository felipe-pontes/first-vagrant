Este repositório contém dois diretórios principais, cada um com um Vagrantfile, permitindo a fácil configuração de um ambiente de desenvolvimento local para hospedagem de um site via Apache HTTP Server (httpd) e um servidor do WordPress.

Diretório "Site HTTPd":
Neste diretório, você encontrará um Vagrantfile que provisiona uma máquina virtual com o Apache HTTP Server (httpd) instalado. Após a inicialização da máquina virtual, você poderá acessar o site através do seu navegador, utilizando o endereço IP fornecido pelo Vagrant. O diretório do site está mapeado para a pasta compartilhada no ambiente virtual, permitindo que você desenvolva seu site localmente e visualize as alterações instantaneamente.

Diretório "Servidor WordPress":
No diretório "Servidor WordPress", você encontrará outro Vagrantfile que provisiona uma máquina virtual contendo um servidor do WordPress. A configuração inclui a instalação do WordPress, banco de dados MySQL e todas as dependências necessárias. Após a inicialização da máquina virtual, você pode acessar a interface de administração do WordPress através do seu navegador, utilizando o endereço IP fornecido pelo Vagrant. Você pode personalizar o site WordPress e testar plugins e temas sem afetar um ambiente de produção.

Utilizando este repositório, você pode facilmente configurar ambientes de desenvolvimento local para um site HTTPd e um servidor do WordPress. Isso permite que você experimente e teste suas aplicações sem impactar o ambiente de produção. A utilização do Vagrant simplifica o processo de provisionamento de máquinas virtuais, tornando o desenvolvimento mais rápido e eficiente.

Sinta-se à vontade para clonar este repositório e personalizá-lo conforme suas necessidades.
