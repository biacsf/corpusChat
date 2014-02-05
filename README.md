corpusChat
==========

Corpus em português de chats com multiplos usuários.

Esse corpus contém 1936 mensagens anotadas de chats no Gtalk e no site e-democracia. 
Os nomes dos usuários foram alterados para garantir a sua privacidade.

As mensagens foram anotadas em arquivos xml no formato:

< discussao >
 < titulo >< /titulo >
	< data></ data>
	< mensagem>
		< numero></ numero>
		< texto></ texto>
		< usuario></ usuario>
		< referenciaTreinamento></ referenciaTreinamento>
	</ mensagem>

		
Aonde os atributos titulo e data são informações do diálogo. E a mensagem tem como informações o número(ordem no diálogo),
texto, nome do usuário que a enviou e referenciaTreinamento quando ela faz referencia a uma outra mensagem.
O site http://edemocracia.camara.gov.br/ é um portal da camâra dos deputados que tem o objetivo de favorecer 
a comunicação entre a população e os deputados. Assim, ele conta com diversas comunidades que discutem assuntos 
referentes a legislação brasileira. A maioria dessas comunidades tem uma área de bate-papo aonde a população pode 
conversar entre si durante uma assembléia pública, podem também, enviar perguntas aos deputados. Os logs desses 
bate-papos estão disponíveis em XML ou HTML podendo ser anotados facilmente.

