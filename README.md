Para aplicar qualquer manual, aplique ele na pasta `/usr/share/man/pt_BR/`.

**man1** *vai na pasta* **/usr/share/man/pt_BR/man1**<br/>
**man2** *vai na pasta* **/usr/share/man/pt_BR/man2**<br/>
**man3** *vai na pasta* **/usr/share/man/pt_BR/man3**<br/>
**man4** *vai na pasta* **/usr/share/man/pt_BR/man4**<br/>
**man5** *vai na pasta* **/usr/share/man/pt_BR/man5**<br/>
**man6** *vai na pasta* **/usr/share/man/pt_BR/man6**<br/>
**man7** *vai na pasta* **/usr/share/man/pt_BR/man7**<br/>
**man8** *vai na pasta* **/usr/share/man/pt_BR/man8**<br/>

Para que você possa digitar o comando `man MANUAL` e funcione na tradução português, você deve ter o sistema configurado em português.

Você pode verificar a linguagem usando o comando `localectl`, `echo $LANG` ou 
`echo $LANGUAGE`, o que vai valer em primeiro lugar é a variável **LANG** (tem que estar **pt_BR** no mínimo).

Caso não esteja e mesmo assim você quer lêr os manuais em português digite `man -L pt_BR MANUAL`.

Lembrando que você deve ter o manual nas pastas em português, caso não tenha, será retornado o manual em inglês.
