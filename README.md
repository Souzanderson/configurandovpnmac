# Instruções de Configuração para conexão com VPN IKVE EAP–MSCHAPv2 no MacOS

* Após diversas tentativas, muita pesquisa e dificuldade, descobri uma forma simples e definitiva pra configurar uma conexão com a VPN do tipo IKVE com autenticação EAP-MSCHAPv2:

# Iniciando a configuração da VPN:

* Basta abrir as configurações, Rede, clicar nos três pontos, adicionar configuração de VPN, IKVE2:

<img src="/public/image1.png" />

* Para que a rede faça a autenticação corretamente, basta deixar o campo ID Remoto vazio, pra isso você deve dar um espaço no campo, pois é requerido para salvar a conexão:

<img src="/public/image2.png" />

* Com isso a VPN vai conseguir autenticar sem problemas, lembrando que, se no seu servidor este ID estiver configurado, será neessária a inserção dele.