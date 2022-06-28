# Automação_start-stop_lambda

Aqui esta uma automação de Start/Stop para Servidores "EC2" AWS.

Add essa variavel Json em configurações adicionais da funcção no EventBridge da regra.


{   "instances": "i-0ee4790fd43e36a5e,i-049c810ea2733808d",   "action": "Start" } para Start

{   "instances": "i-0ee4790fd43e36a5e",   "action": "Stop" } Para Stop
