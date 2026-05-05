# Exemplo de uso do MQTT com ESP-IDF

Este exemplo é baseado no [exemplo da espressif](https://github.com/espressif/esp-mqtt/tree/2c3e1e0942afcc5b3cea2710ffe220fe699da02a/examples/tcp) e na configuração de rede no formato "Wi-Fi Portal" do [exemplo de Wi-Fi](https://github.com/armandokeller/portal-wifi).

Para testes rápidos, acessar [https://www.hivemq.com/demos/websocket-client/](https://www.hivemq.com/demos/websocket-client/) para monitorar as mensagens MQTT.

## Configuração do projeto

Conforme a [documentação do componente esp-mqtt](https://docs.espressif.com/projects/esp-idf/en/stable/esp32/api-reference/protocols/mqtt.html), é necessário adicionar a dependencia do componente com o comando `idf.py add-dependency espressif/mqtt`.

Caso o comando acima não funcione no vscode, executar o comando na paleta de comandos (ctrl+shift+p): `ESP-IDF: Run idf.py reconfigure Task`
