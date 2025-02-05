app.js
1letlistaAmigos=[];
2
3//adiciona nomes de amigos num array lista Amigos[] usando o botão adicionar
4functionadicionarAmigo(){
5letnomeDoAmigo=documento.querySelector('input').value;
6if(listaAmigos>0){
7alert(`Porfavor,insiraumnome.`);
8returnfalse;
9}else{
10limparlista();
11
12listaAmigos.push(nomeDoAmigo);
13letlista=documento.getElementById(listaAmigos');
14for(i=0;i<listaAmigos.length;++i){
15letli=documento.createElement('li');
16li.innerText=listaAmigos[i];
17lista.appendchild(li);
18}
19limparcampo();
20}
21}
22
23//SorteiaumdosamigosdoarraylistaAmigos[]se naoestivervazia
24functionsortearAmigos(){
25if(listaAmigos=="){
26alert(`Porfavor,insiraumnome.`);
27}else{
28letamigosecreto=lisaAmigos[Math.floor(Math.random()*listaAmigos.length)];
29letAmigo=documento.querySelector('resultado');
30.resultado.innerHTML=amigoSecreto;
31}
32limparLista();
33}
34
35//limpa campo do input após adicionar nome do amigo
36functionlimparCampo(){
37nomeDoAmigo=documento.querySelector('input');
38nomeDoAmigo.value=";
39}
40
41//limpa lista abaixo do campo input,para que não haja duplicação de listas
42functionlimparLista(){
43lista=documento.getElementById('listaAmigos');
44lista.innerHTML="";
45}
