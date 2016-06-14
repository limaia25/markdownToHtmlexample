![](https://github.com/SPMSSICC/Markdown/blob/master/logos%20SPMS/logo_SPMS2016.png)

#**[SICC](C://Users//User//Desktop//SICC//LOGIN.html "SICC") – Novos tipos de documentos: AF – Anulação de Faturas & Anulação de Receita**

``Os direitos de autor deste trabalho pertencem à SPMS e a informação nele contida é confidencial.``

> Este trabalho não pode ser reproduzido ou divulgado, na íntegra ou em parte, a terceiros nem utilizado para outros fins que não aqueles para que foi fornecido sem a autorização escrita prévia ou, se alguma parte do mesmo for fornecida por virtude de um contrato com terceiros, segundo autorização expressa de acordo com esse contrato. Todos os outros direitos e marcas são reconhecidos.

##1.	Introdução

Em conformidade com as recomendações da Autoridade Tributária e Aduaneira (AT), não é possível anular diretamente uma fatura. A anulação do movimento de uma fatura é feita através da emissão de uma nota de crédito.
Desta forma, no sistema SICC houve a necessidade de se criarem dois novos tipos de documentos:
- AF - Anulação de faturas (P2 + NC)
- AR - Anulação de receitas (FD + CC)
Sem reflexo para a contabilidade, o que se pretende com estes dois tipos de documentos é a regularização dos mesmos, de modo a que o seu impacto no final seja 0.

Assim, pretende-se com o seguinte manual mostrar a posição destes novos documentos no novo desenho de fluxograma, bem como explicar o respetivo procedimento de regularização.

##2. Criação de novo tipo de documento – Anulação de Faturas (AF)

No fluxograma do ciclo da despesa, irá surgir um novo tipo de documento designado de AF (anulação de faturas).

Este novo tipo de documento surgirá assim no fluxograma:

![fluxograma despesa.png](https://github.com/SPMSSICC/Markdown/blob/master/Novos%20tipos%20doc/fluxograma%20despesa.png "")

Proveniente exclusivamente do P2 ou da NC (exceto RAP), este novo tipo de documento obriga o Utilizador a selecionar pelo menos uma fatura e uma NC com o objetivo do resultado final ter valor “0” para proceder ao registo de anulação.


Desta forma, no menu:
![Anulação P2eNc.png](https://github.com/SPMSSICC/Markdown/blob/master/Novos%20tipos%20doc/Anula%C3%A7%C3%A3o%20P2eNc.png "")

Estes movimentos não são refletidos na contabilidade, sendo que o principal objetivo dos documentos selecionados (P2 e NC) seja a sua regularização, não necessitando de registos contabilísticos.
O número do documento pode ser atribuído pelo sistema.

![Anulação de faturas AF.png](https://github.com/SPMSSICC/Markdown/blob/master/Novos%20tipos%20doc/Anula%C3%A7%C3%A3o%20de%20faturas%20AF.png "")

##3.Criação de novo tipo de documento – Anulação de Receita (AR)

No fluxograma do ciclo da receita, irá surgir um novo tipo de documento designado de AR (anulação de Receitas).
Este novo tipo de documento surgirá assim no fluxograma:

![fluxograma receita.png](https://github.com/SPMSSICC/Markdown/blob/master/Novos%20tipos%20doc/fluxograma%20receita.png "")

Proveniente exclusivamente de, FD e CC (exceto RNAP), este novo tipo de documento obrigam o Utilizador a selecionar pelo menos uma FD e uma CC com o objetivo do resultado final ter valor “0” para proceder ao registo de anulação de receita.

Desta forma, no menu:

![anulação FD e CC.png](https://github.com/SPMSSICC/Markdown/blob/master/Novos%20tipos%20doc/anula%C3%A7%C3%A3o%20FD%20e%20CC.png "")

Estes movimentos não são refletidos na contabilidade, sendo que o principal objetivo dos documentos selecionados (FD e CC) seja a sua regularização, não necessitando de registos contabilísticos.
O número do documento pode ser atribuído pelo sistema.

![Anulação de Receitas AR.png](https://github.com/SPMSSICC/Markdown/blob/master/Novos%20tipos%20doc/Anula%C3%A7%C3%A3o%20de%20Receitas%20AR.png "")

**Nota**: Estes novos documentos devem aparecer no extrato de entidade.

Nas restantes listagens de gestão de terceiros o documento P2 e NC ficam como regularizados.











