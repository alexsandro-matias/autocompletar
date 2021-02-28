# Libreoffice
Vamos supor que você seja um usuário do Microsoft Word e quando você digita, por exemplo, a palavra “distribuicao”.
O Word autocompleta para você deixando a palavra na forma de distribuição.

Se usássemos a palavra `distribuicao`, como faremos para que sejam autocompletada para a palavra `distribuição` automaticamente?
Para isso, abriremos o Libreoffice e iremos no menu `Ferramentas` &rarr; `Opções da autocorreção`. 

Na janela que será exibida, deixa-se com as seguintes configurações:

* Completar palavras – Marcado;
* Acrescentar espaço – Desmarcado – Às vezes, tenho um ponto final para ser digitado e dificulta a produtividade da elaboração do texto;
* Coletar palavras – Marcado – Mais palavras serão adicionadas na completação;
* Remover palavras coletadas do documento ao fechá-lo – Desmarcado – Eficácia ainda maior nos trabalhos, uma vez que mais palavras estão sendo incorporadas.
* Aceitar com: Enter
* Tamanho mínimo de palavras – Quanto menor melhor, por que quanto menor a quantidade caracteres, mais palavras serão reconhecidas no processo de completação.
* Número máximo de entradas – deixo o padrão.


# Microsoft
As entradas de AutoCorreção se aplicam a todos os programas do pacote Microsoft Office e são armazenadas em arquivos * .ACL no perfil de usuário do computador. Ao copiá-los, você os colocará no mesmo lugar, mas sob o perfil do outro usuário no computador.

* No computador, vá para: C: \ Usuários \ [nome_do_usuário] \ AppData \ Roaming \ Microsoft \ Office;
* Você verá um conjunto de arquivos ACL listados. Os números MSO em cada nome de arquivo indicam o idioma / localidade; por exemplo, MSO0127.acl = Matemática, MSO1033.acl = Inglês (EUA), MSO2057.acl = Inglês, (Reino Unido), MSO3081.acl = Inglês (Austrália). (Para obter uma lista completa de números de localidade, consulte:  http://support.microsoft.com/en-us/help/221435/list-of-supported-locale-identifiers-in-word .) Dica: Observe a data última modificação - os arquivos ACL com as datas mais recentes são provavelmente aqueles usados pela instalação do Office;
* Copie os arquivos ACL de que você precisa (ou copie-os todos se não tiver certeza e eles vão para um novo computador);
* No computador de destino, vá para: C: \ Usuários \ [nome_do_usuário_de_outra pessoa] \ AppData \ Roaming \ Microsoft \ Office;
* Cole os arquivos copiados nesta pasta, dizendo sim para sobrescrever os arquivos existentes.


# Fontes
[Canal SempreUpdate](https://sempreupdate.com.br/author/alexsandro/page/2/)
[CyberText Newsletter](https://cybertext.wordpress.com/2017/05/03/word-copy-autocorrect-entries-to-another-computer/)
