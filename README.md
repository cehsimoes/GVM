# **GVM e o Video-Mapa**
## **Resumo: O GVM foi criado para monitorar e inventariar placas de sinalização vertical viária de trânsito.**
### **História do Legado:**
<p>O protótipo do Sistema **GVM** foi criado para monitorar e inventariar placas de sinalização vertical viária de trânsito. </p>
<p>Este sistema foi desenvolvido e financiado  pela FAPESP, com Bolsa TT5, Processo 2013/14956-9, no período de 01/09/2013 a 30/06/2014,  durante parte do meu doutorado no laboratório LTG do Departamento de Transportes da Escola Politécnica da USP. </p>
<p>Todo esse experimento pode ser lido no capitulo 7 de minha a tese que  pode ser acessada em  https://teses.usp.br/teses/disponiveis/3/3138/tde-16062016-114254/publico/CarlosEnriqueCorrigida.pdf onde diversas duvidas podem ser sanadas.</p>
<p>Este sistema utilizou uma interface de usuário por mim desenvolvida e denominada de **Video-Mapa**. </p>
<p>O Video-Mapa que pode ser utilizada como a interface de um Sistema de Mapeamento Móvel de baixo custo e as diversas versões podem reutilizadas em outros projetos caso exista o interesse dado que é Open-Source. </p>
<p>O Video-Mapa foi criado  em 2009 utilizando  MXML, ActionScript, Servidor de Video da Adobe e Google Maps API para ActionScript no projeto GeoRTA. </p>
<p>O Video-Mapa, vem sendo refatorado e versionado desde então. </p>
<p>Foi depois atualizado para HTML5, CSS3, JavaScript, Jquery, Google Maps API. </p>
<p>Depois para ficar Open-Source atualizei o código e utilizei Leaflet, substituindo o Google Maps API, e passei a utilizar as camadas OSM e Imagens da Esri disponibilizada gratuitamente. </p>
<p>**A grande motivação e desafio nessa época dos pesquisadores nessa época era desenvolver uma navegação não linear.** Veja-se Harrower e Fabrikant. (2008) https://onlinelibrary.wiley.com/doi/10.1002/9780470987643.ch4 . </p>
<p>Desenvolvi então em 2009, utilizando programação orientada a eventos, um algoritmo para sincronizar mapa com video e video com mapa. </p>
<p>O avanço ou retrocesso do vídeo pode ser feito tanto no dial do vídeo como capturando e arrastando o ícone de localização do sistema móvel (carro) na rota do mapa. </p>
<p>Recentemente, 2025, no VizLab da Unisinos, utilizei nesta ultima versão uma base criada e treinada de placas de trânsito brasileiras por pesquisador da UFU, disponibilizada no site da Roboflow. </p>
<p>Usei em visão computacional, a técnica de rede neural convolucional, especificamente o Yolo8, para reconhecer e identificar automaticamente as placas de trânsito seguindo o padrão CONTRAN. </p>
<p>Esta era uma funcionalidade importante que faltava. </p>
<p>Com isso pode-se obter todos os dados necessários para o monitoramento e inventario placas de sinalização vertical viária de trânsito está automatizado. </p>
<p>Basta fazer o levantamento em campo, com os sensores apropriados e processar no escritório, atualizar em uma base de dados de tempos em tempos. </p>
<p>Com certeza, concessionárias e departamentos de trânsito devem ter interesse em uma aplicação desse tipo, por segurança viária significa mitigação de acidentes e mortes no trânsito.</p>





