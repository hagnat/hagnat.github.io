## Setup Registro.br Domain for GitHub Pages

Assuming you are setting up your Github Pages _johndoe.github.io_

* On your repository create a new file CNAME and put the domain.com in the file.

*  _registro.br_ > Login with your credentials > _Domínios_ > Select your domain > _DNS_ > _Configurar Zona DNS_.
  * you may need to enable _Modo Avançado_.

* If may need to remove previously defined _A_ and _CNAME_ entries related to the domain you are setting.

* Add a new entry (_Nova Entrada_), selec _A_ in the _Type_ (_Tipo_) dropbox.
  * in the "_Endereço Ipv4_" input, set it to _192.30.252.153_

* Add a new entry (_Nova Entrada_), select _CNAME_ in the _Type_ (_Tipo_) dropbox.
  * in the "_Nome_" input, set it to _www_
  * in the "_Nome do Servidor_" input, set it to _johndoe.github.io_

* Save the changes by pressing "_Salvar Alteraçoes_"
  * it may take some time for changes to be relected by _registro.br_ DNS servers.

Credits:
https://gist.github.com/Avelar/cf9629eb771f02c48366d848b71b58d9
