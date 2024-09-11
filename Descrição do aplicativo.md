# Descrição do Aplicativo

- ## O que é e o que faz?
	- O aplicativo Aura representará um lugar seguro e acolhedor àqueles que desejam realizar terapia, mas não podem ir ao consultório presencialmente, ou não têm psicólogos nas proximidades;
	- Além disso, disponibilizará a capacidade de buscar por profissionais especializados e diversas metodologias variadas;
	- Além disso, do lado do psicólogo, oferece a facilidade de organização das informações dos seus pacientes de forma digital dentro do aplicativo, além de um diário de emoções e notas que os pacientes podem usar, cujo psicólogo tem acesso;
	- Os pacientes entrarão em contato com um psicólogo pelo qual se interessam e, dentro do aplicativo, utilizarão uma chave para entrar na sala do psicólogo, se tornando um paciente dele, algo semelhante ao Google Classroom.
	<br>
- ## Por que o Flutter?
	- De um ponto de vista mais genérico, o Flutter tem uma curva de aprendizado menos acentuada do que outras tecnologias como ReactJS, além da estrutura low-code, ou seja, menos código, que o framework Flutter oferece. Sendo assim, o tempo de aprendizado da tecnologia e de desenvolvimento funcional é mais curto, e isso é essencial considerando o pouco tempo que temos para completar o trabalho de conclusão;
	- Além disso, vale mencionar que a estrutura do Flutter se assemelha muito a algo com o que já trabalhei brevemente; criadores de site dinâmicos. Estes geralmente são utilizados para criar documentação a partir de arquivos de notas individuais automaticamente a partir de um arquivo de configuração .yaml ou similar único, onde se define as diferentes áreas do site, quais páginas devem ser incluídas, quais idiomas, se deve ou não haver barra de navegação, entre vários outros, e a forma como se cria os elementos dentro de um site ou aplicativo em Flutter me lembra muito esse mesmo processo, o que facilita a aprendizagem.
	<br>
	- ### Multiplataforma
		- A forma como os frameworks cross-plataform geralmente funcionam é através da criação de uma camada de abstração sobre as bibliotecas UI Android ou iOS nativas, na tentativa de suavizar as inconsistências decorrentes das diferentes representações do mesmo aplicativo em cada plataforma. O código geralmente escrito em uma linguagem interpretada como JavaScript, que deve por sua vez interagir com as bibliotecas Android baseadas em Java ou iOS baseadas em Objective-C para exibir a interface gráfica. Tudo isso adiciona uma sobrecarga significativa, especialmente quando se tem muita interação da interface gráfica com a lógica do aplicativo.
		- O Flutter se difere por minimizar essas abstrações ultrapassando as bibliotecas de interface gráfica do sistema ao utilizar seu próprio conjunto de Widgets. O código Dart que "pinta" os gráficos do Flutter é compilado em código nativo, que usa o Skia (uma engine de gráficos escrita em C/C++) para renderização. Além disso o Flutter também incorpora uma cópia do Skia como parte da engine Flutter, o que permite que os desenvolvedores se mantenham sempre atualizados com os últimos aprimoramentos de performance, mesmo que o telefone não tenha sido atualizado com uma nova versão Android.
		<br>
	- ### Estrutura do Flutter
		- 
		<br>