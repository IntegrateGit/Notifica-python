# Notifique-me-python
Usando o modulo de notificação por SMS e WhatsApp

# Instalando o modulo via pip
 > ` pip install notifiqueme`

1- Abrindo uma conexão e autenticando
```python
notification = modulo.Notification("ClienteId", "SecretKey")
```

2- Enviando uma notificação no WhatsApp
```python
notification.Send(5531900000000, "Sua mensagem", modulo.NotificationType.WHATSAPP)
```
 > ` Explicação: No metodo send, requer o numero do celular no tipo inteiro, texto para o destinatario no tipo string(str), e por fim o tipo de notificação`
 
 3- Enviando uma notificação via SMS
 ```python
notification.Send(5531900000000, "Sua mensagem", modulo.NotificationType.SMS)
```
 > ` Explicação: Neste exemplo para enviar um SMS basta colocar o tipo SMS`
 
 3- Enviando uma notificação via WhatsApp e SMS
 ```python
notification.Send(5531900000000, "Sua mensagem", modulo.NotificationType.WHATSAPP_SMS)
```
 > ` Explicação: Neste exemplo para enviar um SMS e uma mensagem no WhatsApp em apenas um envio basta colocar o tipo WHATSAPP_SMS`
 
 >
> ### Outras linguagens
>
> [C#, .net, SDK completo para instalar via nuget](https://github.com/Mrr66/Notifique.me)
> 
> [Python, modulo para instalar via pip](https://github.com/Mrr66/Notifique-me-python)
