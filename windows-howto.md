1. Open cmd window: Start->Run->CMD, then cd to forward-proxy directory

2. Start export service: .\bin\node.exe .\bin\forward-proxy --key anywords --enable_export 

3. Start import service: .\bin\node.exe .\bin\forward-proxy --key anywords --http_port 51866 --socks_port 51888

4. Then, set web browser proxy settings point to import service's http proxy srever(127.0.0.1:51866) or socks proxy server(127.0.0.1:51888)
