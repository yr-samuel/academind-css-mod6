### Criando uma barra de navegação fixa

* No seletor da header, colocamos as seguintes propriedades CSS:

        {
            position: fixed;
            top: 0;
            left: 0;
        }

* Foi definido o *top* e o *left*, pois caso algum elemento pai desse elemento aplique algum estilo não cause conflito com esse nosso elemento fixo.

* Nessa aula, aplicamos o position __fixed__, e vimos que tanto na página principal quanto na de pacotes de hospedagem, a imagem da principal e um pouco do card da de pacotes ficaram por de baixo do header, mas isso será resolvido em alguma próxima aula.