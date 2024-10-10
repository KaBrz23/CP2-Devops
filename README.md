# OrderAI

## Sum�rio
- [Integrantes;](#integrantes)
- [Arquitetura da API;](#arquitetura-da-api)
- [Instru��es para uso da aplica��o;](#instru��es-para-uso-da-aplica��o)
- [Observa��es importantes.](#observa��es-importantes)

## Integrantes
- Gabriel Augusto Fernandes - RM98986

- Kau� Fernandes Braz - RM97768

- Mariana Trentino Albano - RM551154

- Matheus Dantas de Sousa - RM98406

- Thomas N�colas de Melo Mendon�a - RM99832

## Arquitetura da API: Monol�tica vs Microservi�os

### Monol�tica vs Microservi�os

- **Arquitetura Monol�tica**: Em um sistema monol�tico, todas as funcionalidades da aplica��o s�o integradas em um �nico c�digo base. Isso significa que as diferentes partes, como a l�gica de neg�cios, a interface do usu�rio e a camada de acesso a dados, est�o todas no mesmo projeto, executadas como uma �nica unidade.

- **Arquitetura de Microservi�os**: Essa abordagem divide a aplica��o em v�rios servi�os menores e independentes que se comunicam entre si. Cada microservi�o � respons�vel por uma funcionalidade espec�fica e pode ser desenvolvido, implantado e escalado de forma independente.

---

### Defini��o de arquitetura

Optamos pela arquitetura monol�tica por alguns motivos-chave, considerando o est�gio atual do projeto e as necessidades espec�ficas da aplica��o:

1. **Simplicidade no Desenvolvimento**: 
   - A arquitetura monol�tica � mais simples de desenvolver e gerenciar no in�cio de um projeto. Com tudo em um �nico c�digo base, o time pode focar em entregar funcionalidades rapidamente sem a complexidade de orquestrar m�ltiplos servi�os.

2. **Facilidade de Implanta��o**: 
   - Com um mon�lito, h� apenas uma aplica��o para ser implantada e mantida, simplificando o processo de deployment. Isso � ideal quando a infraestrutura da aplica��o ainda � pequena e n�o exige solu��es complexas.

3. **Custo Inicial Menor**: 
   - Arquiteturas de microservi�os podem ser mais caras em termos de infraestrutura, j� que cada servi�o pode exigir sua pr�pria infraestrutura de execu��o, como cont�ineres ou m�quinas virtuais.

---

### Tecnologias utilizadas
- **`Linguagem de Programa��o`**: C#;
- **`Framework`**: .NET Core 8.0;
- **`Banco de Dados`**: Oracle Database;
- **`Design Pattern`**: Repository Pattern;

## Instru��es para Uso da Aplica��o

### Inicializa��o da Aplica��o
- Para iniciar a aplica��o, selecione a configura��o **`https`** e execute o projeto. Isso pode ser feito diretamente no Visual Studio (Ambiente de Desenvolvimento Integrado).

### Realiza��o de Requisi��es
- Ap�s iniciar a aplica��o, a documenta��o da API ser� aberta automaticamente no seu navegador padr�o.
- Na p�gina da documenta��o, voc� poder� visualizar todos os endpoints dispon�veis e suas descri��es.
- Para testar uma requisi��o, clique no endpoint desejado e, em seguida, no bot�o **`Try it out`**.
- Complete os campos necess�rios para a requisi��o e clique em **`Execute`** para enviar a solicita��o e ver a resposta da API.
