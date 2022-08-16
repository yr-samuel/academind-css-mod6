### Indo a fundo em position: relative

* Position relativo não é removido do fluxo normal do documento.

* O contexto de posicionamento (vulgo a quem esse posicionamento fica relacionado, ex: fixed -> viewport) é o proprio elemento, logo as propriedades *top, right, bottom e left* são relativas a posição inicial do elemento no fluxo normal do documento.

* Quando posicionamos o elemento com top, left... por mais que ele saia do seu ponto inicial, os elementos adjacentes ainda veem como se o elemento estivesse ali.

* O position relative é muito usado em conjunto com um filho com position absolute, pois queremos que o filho tenha o contexto relacionado ao pai, porém não queremos que o elemento pai saia do fluxo normal do documento.